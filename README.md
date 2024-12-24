# React Router v6 Catch-all Route Problem

This repository demonstrates a common issue encountered when using catch-all routes ('/*') in React Router v6. The catch-all route unintentionally overrides other, more specific routes.

## Problem Description

The provided `App.js` demonstrates a scenario where a catch-all route (`/*`) is added to handle 404 errors. However, this route is triggered even when other, specific routes could match.  This effectively renders other routes useless. The solution provides a proper fix using the `useLocation` hook in order to handle the error case.

## Solution

The `AppSolution.js` file shows the correct implementation, using a proper error handler component.