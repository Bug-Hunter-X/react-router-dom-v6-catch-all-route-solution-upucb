# React Router Dom v6 Catch All Route Issue

This repository demonstrates a common issue encountered when using the catch-all route ("*" path) in React Router Dom v6.  The catch-all route is intended to render a 404 Not Found component when navigating to an invalid URL path, but in this case, it does not behave as expected.

## Problem

The provided code uses React Router Dom v6.  Despite having a catch-all route defined, the application does not render the NotFound component when navigating to a non-existent route.  The problem stems from the route order in the Routes component, or from potential conflicts with other routes.