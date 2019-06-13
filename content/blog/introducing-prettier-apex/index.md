---
title: Introducing Prettier Apex
date: "2019-06-15T20:40:32.169-04:00"
description: Introducing Prettier Apex - An opinionated code formatter for the Apex programming language.
---

Salesforce is well known for its low code advantages, allowing
enterprises and businesses to move fast without having to engage
in the full development lifecycle. However, as the platform gets
more and more popular as a development framework, the need for
development teams to invest in their Apex code bases is an all time high.

One of the most important thing a development team can do is to standardize the development process across teams,
chief among them the need to have a common style guide.

Prettier Apex is a unique solution to this important issue.

## What is Prettier Apex?

Prettier is an open source implementation of a famous algorithm
by Philip Wadler, one of the designers for the Haskell programming
language. It is an opinionated formatter for many modern programming
languages, including but not limited to Javascript/CSS/HTML/Typescript.
Adopting Prettier means stopping all debates within a development team about styles.

Ever since its first release in 2017,
Prettier has been a trend setter in the Javascript community -
it has been adopted almost unanimously across the industry as
a must have tool in a modern development team.
Its philosophy has influenced many other formatting tools for other languages, such as `gofmt` for Go or `black` for Python.

Prettier Apex is developed as a Prettier plugin, specifically
for the Apex language. As a plugin, it inherits the same intuitive
and elegant design from Prettier, and allows teams to invest in
the same tool across their entire Salesforce development workflow -
from now on teams can format Aura components/Lightning Web Components/Apex classes all using Prettier.

## How to use Prettier Apex?

Both Prettier and Prettier Apex are NodeJS CLI applications,
distributed via NPM and can be installed very easily by doing:

```
npm install prettier prettier-plugin-apex
```

This makes Prettier Apex a perfect companion for SFDX projects,
which are often automated via the command line.

Since every SFDX project is unique in its own way,
there can be multiple ways to integrate Prettier Apex.
You can find more complete installation instructions at the project home page: https://github.com/dangmai/prettier-plugin-apex

## What can I do with Prettier Apex?

There are many ways that you can utilize Prettier Apex, a few ideas are:

- Auto format Apex classes and triggers on save in VSCode,
  before they are deployed by SFDX to your scratch org/sandbox.
- Git hooks to automatically format Apex code before they are committed to the repository.
- Use it as part of your linting process in Continuous Integration,
  to make sure that all codes in your repository follows the same standard.

The sky is the limit, and I can't wait to hear about how your team
uses Prettier Apex!

## Where can I find more information?

- Project Home page: https://github.com/dangmai/prettier-plugin-apex
- Prettier's documentation: https://prettier.io/
- My blog: https://blog.dangmai.net
