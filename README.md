# Node Palindrome

Enter your word and check if it's a palindrome.

**Live Demo:** <a href="https://node-palindrome-jenna-nguyen.netlify.app/">Demo</a><i> for display only</i>

<img width="911" alt="Palindrome" src="https://user-images.githubusercontent.com/88993361/141169140-7dff6db3-12b7-4b95-8489-32a64c6cacc0.png">

## How It's Made

The application uses the fs and http modules, but more specifically the http creates the server and fs reads the html file. The user enters in a word, then the client sends a  fetch request to the server to check if the word is a palindrome, using logic stored in the backend.

## What I Learned

This was one of my first applications using Node.js so one of the first things I noticed was how it provided new ways to organize my code. Being able to create my own API allowed for me to now store logic within the backend rather than keeping it within my fetch requests, which I would do when using public APIs.
