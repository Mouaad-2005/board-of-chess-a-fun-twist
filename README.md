# ♟️ Board of Chess – A Fun Twist

> A lightweight, interactive JavaScript chessboard component.

---

## Overview

**Board of Chess** is a simple JavaScript chessboard component that lets you display positions, allow users to move pieces, and integrate it with your own chess logic or game rules.

> **Requires:** jQuery v3.4.1 or higher

---

## Features

- ♟️ Display chess positions easily
- 🖱️ Drag and drop pieces on the board
- 🎨 Fully customizable styles
- 🔌 Compatible with any chess engine or logic library

---

## Limitations

This library only handles the **board and piece movement**. It does **not**:

- Enforce chess rules
- Track turns automatically
- Detect check or checkmate

You can pair it with a separate chess logic library to handle these rules.

---

## Installation

Install via npm:

```bash
npm install @chrisoakman/chessboardjs
```

Then include it in your project and create a board:

```js
var board = Chessboard('board', {
  position: 'start'
});
```

---

## Development

Build the library:

```bash
npm run build
```

Rebuild the demo site:

```bash
npm run website
```

---

## Examples

- Set up a board and display any position
- Let users move pieces interactively
- Combine with your own chess logic for full games
