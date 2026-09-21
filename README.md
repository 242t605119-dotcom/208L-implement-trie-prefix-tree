# LeetCode 208 - Implement Trie (Prefix Tree)

## Problem Description

A Trie, also called a Prefix Tree, is a tree-like data structure used to store strings.

In this problem, we need to implement three operations:

- `insert()` - Add a word to the Trie.
- `search()` - Check whether a complete word exists.
- `startsWith()` - Check whether any word starts with a given prefix.

## Example

Operations:

```text
insert("apple")
search("apple")
search("app")
startsWith("app")
insert("app")
search("app")
