# Better Component Isolation With React, GraphQL, and Relay

Slides for a talk on using GraphQL and Relay to improve the isolation of your React components.

## Talk Description

React has reframed how we think about UI. Instead of controllers, we now think in components. It's like we have a crate full of Legos we can use to assemble our app.

We've moved our styles into our components. We're breaking our components into the appropriate sizes. But there's one last problem that keeps us from full component isolation: interaction with a data source. Which components should load the data? How do we keep parent components from managing too much API state? What happens when a component suddenly needs the same data as its sibling? The boundaries of our components become blurry. Our API-based state management requires a lot of planning and management, and it still feels like we get it wrong.

In this talk, I'll show how you can use GraphQL and Relay to better isolate your React components. Imagine explicitly declaring which data a component needs. Imagine using a tool to combine and optimize all the data requests from your app. Imagine that tool automatically injecting the right data into the right places. It's not all sunshine and rainbows, but GraphQL and Relay can help you build better components.

## Guts

This talk is built on [my reveal starter kit](https://github.com/pepopowitz/my-reveal-starter-kit). See docs there for details how to create/edit slides.

## Running locally

`yarn start`

## Building

`yarn build`

The built assets can be found in a folder named `_site`.
