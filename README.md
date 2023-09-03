# Semantic Versioning and Conventional Commits Guide

This repository is a resource for understanding Semantic Versioning (SemVer) and Conventional Commits. Semantic Versioning is a versioning scheme for software that helps developers and users understand the changes made in each release. Conventional Commits is a commit message convention that makes it easier to automate versioning and generate changelogs.

## Table of Contents

1. [Semantic Versioning](#semantic-versioning)

   - [What is Semantic Versioning?](#what-is-semantic-versioning)
   - [Semantic Versioning Format](#semantic-versioning-format)
   - [How to Use Semantic Versioning](#how-to-use-semantic-versioning)

2. [Conventional Commits](#conventional-commits)
   - [What are Conventional Commits?](#what-are-conventional-commits)
   - [Conventional Commit Format](#conventional-commit-format)
   - [Benefits of Conventional Commits](#benefits-of-conventional-commits)

## Semantic Versioning

### What is Semantic Versioning?

Semantic Versioning (SemVer) is a versioning scheme for software that standardizes the format of version numbers to communicate the nature of changes in a release. It consists of three parts: `MAJOR`, `MINOR`, and `PATCH`. SemVer also allows for pre-release and build metadata.

### Semantic Versioning Format

SemVer is in the form of:

<span style="color:blue">Major</span>
<span>.</span>
<span style="color:yellow">Minor</span>
<span>.</span>
<span style="color:orange">Patch</span>
<span>-</span>
<span style="color:green">PreRelease</span>
<span>+</span>
<span style="color:aqua">metadata</span>

### How to Use Semantic Versioning

## Major - Incompatible API changes

Increased by one, you must reset both minor version and patch version to zero.

### Example

2.6.8 -> 3.0.0

## Minor - Add functionality (backwards-compatible)

Increased by one, you must reset the patch version to zero

### Example

2.6.9 -> 2.7.0

## Patch - Bug fixes (backwards-compatible)

Increase the value of patch version when fixing bugs (No limit to this number)

### Example

2.6.9 -> 2.6.10
