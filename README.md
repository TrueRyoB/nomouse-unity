# nomouse-unity
A powerful command-line interface designed to streamline file generation, execution, and bundling for Unity development.

![nomouse logo](./assets/nms-logo.png)

## Overview

This project is the official successor to [nomouse-cli](https://github.com/TrueRyoB/nomouse-cli), aiming to integrate and evolve all its core features for a modern development workflow.

* **Status**: Quickly display internal milestones and the current state of your project.

## Enhanced Features

We have significantly extended existing concepts to offer more flexibility and control.

* **Gen**: Supports dynamic parameters for a high-speed, template-driven experience.
* **Set**: Pass implicit or explicit arguments directly to your template files.
* **Run**: Execute the entire program or run a specific test file with a single command.
* **Export**: Consolidate file-related configurations into a single, portable file.

## New Features

* **Query**: Seamlessly interact with any LLM while maintaining context effortlessly within the CLI.
* **Doc**: Quick access to target documentation, param updates for edits, or creating new docs on the fly.
* **Task Queue (Emplace / Top / Pop)**: Manage temporary notes and tasks via an internal priority queue.
* **Rename**: Synchronously rename both the file and its internal class name (when they match) to ensure consistency.
* **Resolve**: A specialized workflow that handles `git add` + `commit` while automatically cleaning up unused namespaces.

## Deprecated / Potential Removal

The following features are under review and may be removed due to low usage or design shifts:

* **Wind**: Automatic concatenation of dependent files into a single output.
* **Pause / Resume**: Timer-related features.

## License

MIT License
