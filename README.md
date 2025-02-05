# ActionScript 3 NullPointerException Example

This repository demonstrates a common error in ActionScript 3: `NullPointerException` when attempting to access properties of objects that might be null.  The example shows both the problematic code and improved solutions using the null-safe operator (if available) and a conditional operator.

## Problem

Attempting to access a property of an object before checking if it's null can result in a runtime `NullPointerException`. 

## Solution

The best approach is to use the null-safe operator (`?.`) to gracefully handle null values, or use a conditional operator to provide a default value when the object is null. 