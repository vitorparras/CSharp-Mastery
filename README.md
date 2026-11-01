# C# Mastery

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/vitorparras/CSharp-Mastery/badge)](https://scorecard.dev/viewer/?uri=github.com/vitorparras/CSharp-Mastery)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A study guide for the C# language in question-and-answer format, from the
fundamentals to advanced topics, written in English and Brazilian Portuguese.

> **Status:** active. The material grows over time; new topics are added as
> they are written. See the [roadmap](#roadmap).

## Table of contents

- [What you will find](#what-you-will-find)
- [How to use it](#how-to-use-it)
- [Repository layout](#repository-layout)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Security](#security)
- [Code of conduct](#code-of-conduct)
- [License](#license)

## What you will find

Each document is a numbered list of questions. Every question has a direct
answer and, when it helps, a short code sample. Both languages cover the same
questions.

| Topic | English | Português (BR) |
|---|---|---|
| **C# programming foundations**: compiled, typed and managed code, CLR and IL, .NET and .NET Standard, SDK and runtime, versioning, types, memory, and the core language constructs | [C# Programming Foundations](<US - English Version/C# Programming Foundations.md>) | [Fundamentos da linguagem C#](<BR - Versão em Portugues Brasileiro/Fundamentos da linguagem C#.md>) |

The foundations document currently has 145 questions.

## How to use it

1. Pick a document in the language you prefer.
2. Read the question and answer it yourself, out loud or on paper, before
   expanding the answer.
3. Compare your answer with the one given. If something is unclear or wrong,
   [open a correction](https://github.com/vitorparras/CSharp-Mastery/issues/new?template=content_error.yml).
4. To work offline:

   ```bash
   git clone https://github.com/vitorparras/CSharp-Mastery.git
   ```

The questions work well for interview preparation, for reviewing before an
exam, or as a checklist of what to study next.

## Repository layout

```text
CSharp-Mastery/
├── US - English Version/                 # English documents
│   └── C# Programming Foundations.md
├── BR - Versão em Portugues Brasileiro/  # Brazilian Portuguese documents
│   └── Fundamentos da linguagem C#.md
├── .github/                              # Issue and PR templates, workflows, Dependabot
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
└── LICENSE
```

One document per topic, with the same file in both language folders.

## Roadmap

Planned topics, in no particular order. Open a
[suggestion](https://github.com/vitorparras/CSharp-Mastery/issues/new?template=content_suggestion.yml)
to propose another one or to volunteer for one of these.

- Object-oriented programming: classes, records, interfaces, inheritance,
  polymorphism
- Collections, generics and LINQ
- Asynchronous programming: `async`/`await`, `Task`, channels, cancellation
- Memory and performance: value vs. reference types, `Span<T>`, garbage
  collection
- Exceptions, logging and diagnostics
- ASP.NET Core and dependency injection
- Testing: xUnit, mocking, test design

## Contributing

Corrections, new questions and translations are welcome. Please read
[CONTRIBUTING.md](CONTRIBUTING.md) first: it explains the content guidelines
and the pull request workflow. The `main` branch is protected and only receives
changes through reviewed pull requests.

## Security

Found something that could lead a reader to an insecure practice, or a problem
in this repository's configuration? Follow [SECURITY.md](SECURITY.md) and report
it privately.

## Code of conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md). By
participating you agree to uphold it.

## License

Licensed under the [MIT License](LICENSE). Copyright © Vitor Hugo Parras.
