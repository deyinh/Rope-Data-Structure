# Rope-Data-Structure

## Project Overview
This Python project implements the Rope data structure, which is capable of efficiently manipulating strings by extracting a substring and reinserting it into a different position. This implementation is able to handle a series of queries that modify the string and can output the final result after all modifications.

## Problem Statement
The Rope data structure is designed to store a string and efficiently cut a part (a substring) of that string and insert it into a different position. This capability makes the Rope data structure an excellent choice for text editors that need to handle persistent versions of text.

## Input Format
- The first line contains the initial string `S`.
- The second line contains the number of queries `q`.
- The next `q` lines contain triples of integers `i`, `j`, `k`.

## Output Format
The script will output the string after all queries have been processed.

## Constraints
- `S` contains only lowercase English letters.
- `1 ≤ |S| ≤ 30000`
- `1 ≤ q ≤ 100000`
- `0 ≤ i ≤ j ≤ n - 1`
- `0 ≤ k ≤ n - (j - i + 1)`
