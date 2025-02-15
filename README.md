# React 19 useEffect Performance Issue

This repository demonstrates a common performance issue in React 19 related to the `useEffect` hook and provides a solution.  The initial implementation shows `useEffect` running after every render, causing unnecessary re-renders and potential performance degradation. The solution shows how to optimize this using the dependency array.