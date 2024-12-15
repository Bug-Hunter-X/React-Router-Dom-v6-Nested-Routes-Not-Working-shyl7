# React Router Dom v6 Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6.  The problem arises when trying to render a nested component within a parent route.  The solution provided addresses this issue by correctly defining the nested routes.

## Problem

The provided `bug.js` file contains a React component using React Router Dom v6 to define nested routes. When navigating to the nested route ('/contact/form'), the nested component (`ContactForm`) fails to render, leading to an unexpected behavior or a blank page. 

## Solution

The solution (`bugSolution.js`) correctly structures the nested routes using the `useParams` hook and demonstrates the proper usage of nested routes within React Router Dom v6.