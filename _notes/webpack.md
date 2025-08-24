# Webpack

Webpack is a static module bundler for modern JavaScript applications. When webpack processes your application, it internally builds a dependency graph which maps every module your project needs and generates one or more bundles.

## Core Concepts

- **Entry:** The starting point of the dependency graph.
- **Output:** Where to emit the bundles it creates.
- **Loaders:** Allow webpack to process other types of files (e.g., CSS, images) and convert them into valid modules.
- **Plugins:** Can be used to perform a wider range of tasks like bundle optimization, asset management, and injection of environment variables.

Webpack is often used with [[babel]] to transpile modern JavaScript for older browsers. It is a key tool in many [[react]] projects.
