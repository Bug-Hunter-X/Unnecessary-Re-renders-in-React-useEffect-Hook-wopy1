# Unnecessary Re-renders in React useEffect Hook

This repository demonstrates a common React bug involving unnecessary re-renders caused by a missing dependency array in the `useEffect` hook.  The `useEffect` hook, without a dependency array, runs after every render, leading to performance issues and potential unexpected behavior.  The solution showcases how to fix this by providing the correct dependency array.