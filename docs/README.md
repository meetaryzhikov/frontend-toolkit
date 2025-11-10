# My Frontend Toolkit — Documentation

## Table of contents
- [Introduction](#introduction)
- [Quickstart: component-library](#quickstart-component-library)
- [How to contribute](#how-to-contribute)
- [Roadmap](#roadmap)
- [Contact](#contact)

## Introduction
This repository contains pragmatic frontend utilities, architecture guides and demo apps.

## Quickstart: component-library

Clone repository:

```bash
git clone https://github.com/meetaryzhikov/frontend-toolkit.git
cd frontend-toolkit/packages/component-library
npm install
npm run storybook
```
### Usage example (copy-paste)

```jsx
import React from "react";
import { Button } from "component-library";

export const App = () => (
  <div>
    <Button variant="primary">Hello</Button>
  </div>
);
```

## How to contribute

* See CONTRIBUTING.md in repo root.
* Pick issues labeled good first issue or help wanted.

## Roadmap

See ROADMAP.md (root).

## Contact

For maintainers: [meet.aryzhikov@gmail.com]