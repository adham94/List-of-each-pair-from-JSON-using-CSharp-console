# List-of-each-pair-from-JSON-using-CSharp-console
List of each pair from JSON using C# console

The included json file contains a list of records with a name, id, and an array of tags.

produces a list of each pair of names which have 2 or more tags in common, in the format "name1, name2|name1, name2|..."

For example:

	Jana Stevenson and Sylvia Norman have the following tags respectively:

	campaign, shopping, buyer
	shopping, buyer, clicker
	      
	Because they both have a  buyer and shopping tag, Jana Stevenson,Sylvia Norman should be added to the list.

	Pearson Marquez and Fern Wise have the following tags respectively

	shopping, non-clicker
	promo, clicker, non-clicker

	Because they only share one tag "non-clicker" the pair "Pearson Marquez, Fern Wise" should not appear on the list.
