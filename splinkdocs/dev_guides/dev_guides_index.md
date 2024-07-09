---
hide:
  - toc
---

# Contributing to Splink

We encourage contributions from all users. Whether it be adding a feature, fixing a bug or fixing typos in our documentation we are extremely appreciative of the input of external contributors. Splink would not be as good without it!


## Developer Guides

The set of guides in this section are intended for users who are making changes to Splink. 

### Making Changes to Splink

When making changes to Splink, there are a number of common operations that developers need to perform. The guides in this section lay out some of these common operations, and provides scripts to automate these processes. These include:

* [Building a Virtual Environment](./changing_splink/building_env_locally.md) - to replicate the conditions when Splink is installed by users.
* [Linting and Formatting](./changing_splink/lint_and_format.md) - to ensure consistent code style and to reformat code, where possible.
* [Testing](./changing_splink/testing.md) - to ensure all of the codebase is performing as intended.
* [Building the Documentation locally](./changing_splink/build_docs_locally.md) - to test any changes to the docs site render correctly.
* [Releasing a new package version](./changing_splink/releases.md) - to walk-through the release process for new versions of Splink. This generally happens every 2 weeks, or in the case of an urgent bug fix.

### How Splink works

Splink is quite a large, complex codebase. The guides in this section lay out some of the key structures and key areas within the Splink codebase. These include:

* [Understanding and Debugging Splink](./debug_modes.md) - demonstrates several ways of understanding how Splink code is running under the hood. This includes Splink's debug mode and logging.
* [Transpilation using sqlglot](./transpilation.md) - demonstrates how Splink translates SQL in order to be compatible with multiple SQL engines using the sqlglot package.
* [Performance and caching](./caching.md) - demonstrates how pipelining and caching is used to make Splink run more efficiently.
* [Comparison and Comparison Level Libraries](./comparisons/new_library_comparisons_and_levels.md) - demonstrates how `Comparison` Library and `ComparisonLevel` Library functions are structured within Splink, including how to add new functions and edit existing functions.
* [User-Defined Functions](./udfs.md) - demonstrates how User Defined Functions (UDFs) are used to provide functionality within Splink that is not native to a given SQL backend.

