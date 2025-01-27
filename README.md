# React Native FlatList: Missing Unique Keys

This repository demonstrates a common error in React Native's FlatList component: failure to provide unique keys for each item in the data array.

## Problem

The `BuggyFlatList.js` file shows an example of a FlatList without unique keys.  This leads to unexpected rendering behavior, including incorrect item order, missing items, or extra items.

## Solution

The `FixedFlatList.js` file demonstrates the solution: providing unique keys for each item in the data array.  Using unique identifiers ensures that React Native can correctly update the list when data changes.