# Next.js 15 App Directory Bug: Unexpected Behavior with Server Components and Dynamic Routes

This repository demonstrates a bug encountered when using server components with dynamic routes in Next.js 15's App directory. The issue involves unexpected behavior and potential runtime errors, specifically when routes are dynamically generated and server components are involved in rendering those routes. This bug report details the issue, provides a minimal reproducible example, and outlines possible solutions.

## Bug Description

The bug manifests as unexpected behavior or runtime errors when a dynamic route includes a server component.  The exact behavior varies depending on the specific scenario, but commonly involves incorrect data fetching, component rendering issues, or complete application failure. This behavior is inconsistent with the expected functionality of server components in dynamic routes.

## Reproducible Example

The `bug.js` file contains a minimal example showcasing the bug.  The example includes a dynamic route and a server component which attempts to access route parameters.  The route parameters either are unavailable or cause errors.

## Solution

The `bugSolution.js` file offers a possible workaround, mitigating the unexpected behavior.  The solution may involve changes to the data fetching strategy, route handling, or component structure.  However, more investigation is needed to determine the root cause and a definitive fix within Next.js framework itself.