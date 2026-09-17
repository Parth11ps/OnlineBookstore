# OnlineBookstore

A Java starter repository for a future online bookstore project.

> **Status:** Initial scaffold. The current application prints `Hello, World!`; bookstore functionality has not yet been implemented in the checked-in source.

## Current contents

| Path | Purpose |
| --- | --- |
| `src/App.java` | Java entry point containing `main` |
| `bin/App.class` | Previously committed compiled output |
| `.gitignore` | Rules for local build output and system files |

The project has no external dependencies or Maven/Gradle configuration.

## Build and run

Install a Java Development Kit (JDK) with `javac` and `java` available in your terminal, then run from the repository root:

```bash
javac -d bin src/App.java
java -cp bin App
```

Expected output:

```text
Hello, World!
```

These commands follow the source layout; a supported JDK version and automated build verification have not yet been established.

## Proposed development plan

The following are possible next steps, not existing features:

1. Define a `Book` model with an identifier, title, author, price, and stock quantity.
2. Add a catalogue with search and filtering.
3. Implement a shopping cart with quantities and totals.
4. Persist catalogue and order data.
5. Add tests for stock validation and price calculations.
6. Choose a console or web interface as the application grows.

## Repository notes

Compiled classes and macOS metadata should remain local. The ignore rules prevent new untracked files of these types from being added accidentally; they do not remove files already tracked in Git.

This repository documents the starting point rather than a completed storefront.
