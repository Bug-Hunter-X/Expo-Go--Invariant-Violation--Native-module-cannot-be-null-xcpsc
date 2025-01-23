# Expo Go: Invariant Violation: Native module cannot be null

This repository demonstrates a common error encountered when developing Expo apps that utilize native modules and testing with Expo Go.  The error, "Invariant Violation: Native module cannot be null," arises because Expo Go doesn't include all native modules. This example showcases the problem and its solution.

## Problem

When a native module is required in your app and then tested using Expo Go, the absence of that module within the Expo Go environment will result in the specified error.  This makes debugging and testing difficult.

## Solution

The primary solution is to avoid relying on native modules during development and testing with Expo Go.  Alternatives include using a simulator or physical device for testing, focusing on JavaScript-only functionalities during Expo Go testing, or using mocked native modules for testing purposes only.
