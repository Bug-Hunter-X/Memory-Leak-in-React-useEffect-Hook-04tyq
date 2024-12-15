# React useEffect Hook Memory Leak

This repository demonstrates a common error in React applications: a memory leak caused by improper use of the `useEffect` hook.  The `setInterval` function, without a cleanup function, leads to multiple intervals running concurrently, consuming memory resources and causing potential performance issues.

The `bug.js` file showcases the flawed code, while `bugSolution.js` provides the corrected version.  This example is designed to help developers better understand how to avoid memory leaks using the `useEffect` cleanup function.