# Querying-a-document
A dictionary(m) with ingredients as indexes is made.
using regex article words are matched with the substrings of ingredients, for each match of an ingredient, the dictionary element with its index as the ingredient gets incremented by 2(to take into account higher relevance).
ingredients are made into groups; these groups are searched with certain keywords. The ingredients in these groups are incremented by 1(lesser relevance).
the dictionary is sorted based on the values of the indexes, then the indexes are printed in reverse, i.e., most relevant ingredient at the top and least at the bottom

