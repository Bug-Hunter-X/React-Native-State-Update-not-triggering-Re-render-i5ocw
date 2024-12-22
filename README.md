# React Native State Update Re-render Issue

This repository demonstrates a common issue in React Native where a state update fails to trigger a re-render of the component.  The `MyComponent` attempts to increment a counter, but the UI does not reflect the change.

## Bug

The `bug.js` file contains the buggy component. The counter button doesn't work as expected.

## Solution

The `bugSolution.js` file provides a corrected version of the component.  The solution addresses the re-rendering problem.

## How to Reproduce

1. Clone this repository.
2. Run `npx react-native run-android` or `npx react-native run-ios`
3. Observe that clicking the button does not update the displayed counter.
4. Examine the solution file to see the correction. 