# Firebase: Handling Non-Existent Documents and Collections
This repository demonstrates a common issue in Firebase development: unexpected behavior when accessing non-existent documents or collections.  The `bug.js` file showcases the problem, while `bugSolution.js` provides a robust solution.

The problem stems from the asynchronous nature of Firebase operations.  If you attempt to access data that doesn't exist, the result might not immediately throw an error, leading to runtime failures or incorrect application behavior.  The solution emphasizes using conditional checks to ensure data existence before processing it.

## Running the Code
1.  Clone this repository.
2.  Initialize a Firebase project.
3.  Install the Firebase SDK: `npm install firebase`
4.  Configure your Firebase credentials in the code.
5.  Run `node bug.js` to observe the error.
6.  Run `node bugSolution.js` to see the corrected behavior.