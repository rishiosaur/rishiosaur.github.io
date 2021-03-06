---
layout: project
title: Hoot
description: An assignment tracker.
logo: /assets/hootlogo.png
screenshot: /assets/hootscreen.png
theme: 'saddlebrown'
catchphrase: AM for tech-savvy students.
repo: hoot-cli
info1: A powerful assignment tracker.
info2: Built using Node.
---

# Hoot-cli

The assignment tracking system for tech-savvy students.

[![npm version](https://img.shields.io/npm/v/hoot-cli/latest?style=flat-square)](https://npmjs.org/package/hoot-cli "View this project on npm")

[![Dependencies](https://img.shields.io/david/rishiosaur/hoot-cli?style=flat-square)](https://npmjs.org/package/hoot-cli "View this project on npm")

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/894a4dd7f89943e0899eb85dd1a8284a)](https://www.codacy.com/manual/rishiosaur/hoot-cli?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rishiosaur/hoot-cli&amp;utm_campaign=Badge_Grade)


## Usage

How to use `Hoot`

### Installation

Hoot is available on the npm registry, so installation is a breeze:

`npm i -g hoot-cli`

### Setup

Run:

`hoot setup`

and answer the questions to the best of your abilities.

### Subjects

Hoot runs on this folder directory:

`School / Term <number> / <Subject> / <Unit> / <Assignments|Finished|Notes|Homework>`

To generate a subject directory with `hoot.json`, run:

`hoot new subject <title>`

Where `<title>` is the name of the subject.

Use the `hoot new <item> <name>` command for creation of subjects, units, assignments, or notes!

### Assignments

Assignment generation is done using the `hoot assignment <title>` command, and templating is done by copying an assignment template in the `templates/` folder.
