# Introduction

Provides basic functionality used by other Rhythm libraries.

Include some string extension methods and some collection extension methods.

Refer to the [generated documentation](docs/generated.md) for more details.

# Installation

Install with NuGet. Search for "Rhythm.Core".

# Overview

Collection extension methods:

* **MakeSafe** Returns a non-null version of the collection.
* **Repeat** Creates a collection of the specified size with each element containing the same item.
* **WithoutNulls** Returns the collection without null items.

String extension methods:

* **SplitBy** Splits a string by the specified delimiters.
* **ToSnakeCase** Converts a camel case string to snake case.
* **SanitizeForCss** Converts a string for use as a CSS class.

# Maintainers

To create a new release to NuGet, see the [NuGet documentation](docs/nuget.md).