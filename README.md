````markdown name=README.md
# TypeScript Interpreters – Guide to Interpreters Series

This repository accompanies the [Guide to Interpreters Series](https://www.youtube.com/playlist?list=PL_2VhOvlMk4UHGqYCLWc6GO8FaPl8fQTh), a YouTube series focused on building interpreters and a custom language in TypeScript. Each episode in the series corresponds to a separate folder in this repository and introduces new concepts with incremental code.

## Table of Contents

- [Overview](#overview)
- [Series Structure](#series-structure)
- [Getting Started](#getting-started)
- [Episode Breakdown](#episode-breakdown)
- [Contributing](#contributing)
- [Community](#community)
- [License](#license)
- [Links](#links)

---

## Overview

This project is designed to help you learn how interpreters work by building one from scratch in TypeScript. The repository is organized by episodes, with each directory containing the code and examples for a specific stage in the interpreter-building process.

## Series Structure

- **Episode Folders:**  
  - `ep01-lexer`: Tokenization (lexical analysis)
  - `ep02-ast-types`: Abstract Syntax Tree (AST) types
  - `ep03-parser`: Parser implementation
  - *(Further episodes will be added as the series progresses)*

- **Each episode folder** contains all necessary code, typically including TypeScript source files, configuration, and examples.

## Getting Started

### Prerequisites

- [Deno](https://deno.land/) (recommended, as the series uses Deno for TypeScript execution)
- Basic knowledge of TypeScript

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AnujaGajaweera/typescript-interpreters.git
   cd typescript-interpreters
   ```

2. **Navigate to the episode you want to explore:**
   ```bash
   cd ep01-lexer
   ```

3. **Run the code using Deno:**
   ```bash
   deno run --allow-read lexer.ts
   ```

   *(Adjust the file name as needed for each episode.)*

## Episode Breakdown

### Episode 1 – Lexer

- **Path:** `ep01-lexer/`
- **Description:** Introduction to lexical analysis; converting raw source code into tokens.
- **Key Files:** [`lexer.ts`](./ep01-lexer/lexer.ts)

### Episode 2 – AST Types

- **Path:** `ep02-ast-types/`
- **Description:** Defining the Abstract Syntax Tree (AST) types used for parsing and evaluation.
- **Key Files:** [`ast.ts`](./ep02-ast-types/ast.ts)

### Episode 3 – Parser

- **Path:** `ep03-parser/`
- **Description:** Building a parser that converts tokens into an AST.
- **Key Files:** *(To be implemented in the series)*

*(More episodes will be added as the series continues.)*

## Contributing

Contributions are welcome! Please open issues or submit pull requests to improve code, documentation, or examples.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Create a Pull Request

## Community

- **YouTube Playlist:** [Guide to Interpreters Series](https://www.youtube.com/playlist?list=PL_2VhOvlMk4UHGqYCLWc6GO8FaPl8fQTh)
- **Channel:** [JSimplified](https://www.youtube.com/c/JSimplified)
- **Discord:** [Join our Discord server!](https://discord.gg/KEfHqZ3zn7)

## License

This project is licensed under the [MIT License](LICENSE).

## Links

- [Deno Documentation](https://deno.land/manual)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Original Series Inspiration](https://github.com/tlaceby/guide-to-interpreters-series)

---

*Happy coding and enjoy learning how interpreters work!*
````
