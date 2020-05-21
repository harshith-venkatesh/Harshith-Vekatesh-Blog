---
title: My First React Project
date: "2020-05-14T22:12:03.284Z"
description: "Welocome to Harshith Venkatesh Blog"
---

This is my first post on react project, I am really excited to share my thoughts with you guys on how I struggled to create my first react project. I was motivated by Tanay to explore more on React JS and after going through his course, one thing I noticed is his explanation behind mentioning the mistake and rectifying the same, the actually made me think of explaining my small journey of going through the course of Shaun Wassell on Building Modern Project with React (I will mention the reason behind choosing his course in the next paragraph) and doting down the mistakes that I have encountered while trying the project on my own and how I rectified the same. It is way easier to just copy and paste the project from the course exercise file but when it comes to writing the code we realize how some silly mistakes can create a big issue on the project.

The course introduced by Shaun Wassell is really amazing and his explanatory skills are top-notch, what I really found exciting about his course was the detail behind why a particular package is chosen, how we can build the project without using <strong>npx create-react-app my-app</strong>. He started with initiating package.json and kept on adding the required package and explaining the reason behind the same which cleared more thoughts and gave ideas to explore more on the same. This thought actually motivated me to go on with the project.

In this project, I got the opportunity to learn more on <strong>react, redux, explore more on Redux Developer Tools, express.js, how to define redux reducer, creating server resource to host</strong> etc.,
You can check the codebase in my GitHub repo and please feel free to point out the improvements, fork it and add the features :)

My first encounter of error in React: An Error is a nightmare for the developer, We spend hours to days sometimes to rectify the error and the worst part would be the error would be a small mistake would be a character or word or and line of code which would break an entire project and I observed the nightmare below

Uncaught TypeError: dispatch is not a function
at onCreatePressed (NewToDoForm.js:63)
at onClick (NewToDoForm.js:47)
at HTMLUnknownElement.callCallback (react-dom.development.js:70)
at Object.invokeGuardedCallbackDev (react-dom.development.js:90)
at invokeGuardedCallback (react-dom.development.js:105)
at invokeGuardedCallbackAndCatchFirstError (react-dom.development.js:114)
at executeDispatch (react-dom.development.js:122)
at executeDispatchesInOrder (react-dom.development.js:125)
at executeDispatchesAndRelease (react-dom.development.js:697)
at executeDispatchesAndReleaseTopLevel (react-dom.development.js:697)

This took me hours as I have described the function and its actions to be performed when called and have defined the right parameters still it was specifying the same error over and over again.
I cross-checked my entire function rewritten the code emphasizing line to line but all in vain. My biggest mistake was <strong> Not checking how I called the function</strong>. All the time I wasted on defining the function but I was actually sending the parameters in the wrong way, Whether I was lazy or took advantage of Ctrl+ space of VSCode but I learnt a good lesson.
