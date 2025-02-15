# Nextjs 15

# What is Nextjs?

- A react framework for building production-ready full-stack web applications.
- It uses react for building user interfaces.

# Why learn Nextjs?

- It simplifies the process of building production-ready web applications.
- You don't need to install additional packages.
- Provides additional features that enable you to build production-ready
  applications, such as:
  - Routing
    - provides file based routing, you create a file then by default route is generated.
  - API routes
    - enables you to build Frontend react components and Backend APIs in one application, allowing seamless integration.
  - Rendering
    - supports both server-side and client-side rendering, improving performance and better search engine optimization.
  - Data fetching
    - provides build-in async await support in react components, making data fetching efficient.
  - Styling
    - supports CSS modules, Tailwind CSS, to merge CSS preferences.
  - Optimization
    - provides optimization for fonts, images and scripts, enhancing overall user experience.
  - Development and production build system
    - provides optimized development and production system.

n.b Folders within app folder are routes by default, that's one of the benefits of Nextjs.

# Installation:

```bash
npx create-next-app@latest
```

# Prerequisite:

- Nodejs (v18+).
- Text Editor (any of your choice).

# Overview

### Home route

```bash
src/app/page.tsx //this is treated as the home route when visiting localhost:300.
```

-The localhost:300 is gonna look for the page.tsx in app folder and render the component in the layout.tsx then the details of the component is displayed.

## Single Routes:

### About route

```bash
src/app/about/page.tsx //this is the about route.
```

### Contact route

```bash
src/app/contact/page.tsx //this is the contact route.
```

## Nested Routes:

### Blog routes

```bash
src/app/blog/page.tsx //this is the main blog route.

src/app/blog/first/page.tsx //this is the first blog route which is the sub-folder of the main.

src/app/blog/second/page.tsx //this is the second blog route which is the sub-folder of the main.
```
