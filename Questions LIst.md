## Chapter - 1: Arrays and Strings

1.1 Is Unique: Implement an algorithm to determine if a string has all unique characters. What if you cannot use additional data structures ?

1.2 Check permutation: Given two strings, write a method to check if one is a permutation of the other.

1.3 URLify: Write a method to replace all spaces in a string with '%20'. You may assume that the string has sufficient space at the end to hold the additional characters, and that you are given the "true" length of the string. (Note: If implementing in Java, please use a character array so that you can perform this operation in place)
Example:
Input: "Mr John Smith ", 13
Output: "Mr%20John%20Smith"

1.4 Pallindrome Permutation: Given a string, write a function to check if it is a permutation of a pallindrome. A palindrom is a word or phrase that is the same forwards and backwards. A permutation is a rearrangement of letters. The palindrome does not need to be limited to just dictionary words.
Example:
Input: Tact Coa
Output: True (permutation: "taco cat", "atco cta", etc)

1.5 One Away: There are three types of edits that can be performed on strings: insert a character, remove a character, or replace a character. Given two strings, write a function to check if they are one edit (or zero edits) away.
Example:
pale, ple -> true
pales, pale -> true
pale, bale -> true
pale, bake -> false
