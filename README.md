# React Router Dom v6 Catch-all Route Issue

This repository demonstrates a problem with the catch-all route ('*') in React Router Dom v6.  The catch-all route is intended to handle any unmatched routes, but in this case, it's unexpectedly rendering even when a valid route exists. The issue is related to the order of routes and how React Router matches paths.