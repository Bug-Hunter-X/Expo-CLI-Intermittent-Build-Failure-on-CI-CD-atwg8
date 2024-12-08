# Expo CLI Intermittent Build Failure on CI/CD

This repository demonstrates an uncommon bug encountered with the Expo CLI during the build process within a CI/CD environment. The issue manifests as an intermittent build failure, with vague error messages, despite successful local builds. 

The `bug.js` file showcases a simplified representation of the codebase where the problem occurred. The `bugSolution.js` file offers a potential solution or workaround.  Note that the exact cause and solution might vary depending on your specific project setup and dependencies.  Further investigation might require analyzing build logs and environment variables.

## Reproduction

To reproduce the problem (results may vary):
1. Clone this repository.
2. Install dependencies using `npm install` or `yarn install`.
3. Attempt to build the project using Expo CLI. (Observe inconsistent success/failure)

## Solution

The proposed solution, detailed in `bugSolution.js`, addresses potential causes such as conflicting dependencies or environment inconsistencies. It is crucial to check for and address any discrepancies between your local development environment and CI/CD setup.