# CompText Language Guide

## Overview

CompText DSL enables efficient LLM communication through structured commands.

## Core Concepts

### Commands
Reusable patterns stored in the codex.

```comptext
use:docker-setup-v1
```

### Modules
Grouped collections of related commands.

```comptext
module:development
```

### Composition
Combine multiple commands.

```comptext
use:project-init
use:git-workflow
```

## Full Specification

See [CompText DSL Repo](https://github.com/ProfRandom92/comptext-dsl) for complete spec.
