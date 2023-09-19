# Königsberg

![Project Euler Badge](https://projecteuler.net/profile/bergren2.png)

Solutions to various problems on the Internet, including:

- [Project Euler](https://projecteuler.net/)
- [Advent of Code](http://adventofcode.com/)
- [r/dailyprogrammer](https://www.reddit.com/r/dailyprogrammer/)
- [Wolfram Challenges](https://challenges.wolfram.com)
- [dev.to Daily Challenge](https://dev.to/thepracticaldev/daily-challenge-1-string-peeler-4nep)
- [LeetCode](https://leetcode.com/problemset/all/)

## Languages

| Language | Build Status | Code Quality | Test Coverage |
|:---------|:-------------|:-------------|:--------------|
| [C#](https://github.com/bergren2/konigsberg-csharp) | ![Build Status](https://github.com/bergren2/konigsberg-csharp/workflows/build/badge.svg) | [![Maintainability](https://api.codeclimate.com/v1/badges/e29c49dcdc02208f384e/maintainability)](https://codeclimate.com/github/bergren2/konigsberg-csharp/maintainability) | [![Test Coverage](https://api.codeclimate.com/v1/badges/e29c49dcdc02208f384e/test_coverage)](https://codeclimate.com/github/bergren2/konigsberg-csharp/test_coverage) |
| [C++](https://github.com/bergren2/konigsberg-cpp) | | | |
| [Kotlin](https://github.com/bergren2/konigsberg-kotlin) | [![Build Status](https://github.com/bergren2/konigsberg-kotlin/actions/workflows/build.yml/badge.svg)](https://github.com/bergren2/konigsberg-kotlin/actions/workflows/build.yml) | [![Maintainability](https://api.codeclimate.com/v1/badges/5cfd4c2f74c44d0303c1/maintainability)](https://codeclimate.com/github/bergren2/konigsberg-kotlin/maintainability) | [![Test Coverage](https://api.codeclimate.com/v1/badges/5cfd4c2f74c44d0303c1/test_coverage)](https://codeclimate.com/github/bergren2/konigsberg-kotlin/test_coverage) |
| [Lua](https://github.com/bergren2/konigsberg-lua) | ![Build Status](https://github.com/bergren2/konigsberg-lua/workflows/build/badge.svg) || [![Coverage Status](https://coveralls.io/repos/github/bergren2/konigsberg-lua/badge.svg?branch=master)](https://coveralls.io/github/bergren2/konigsberg-lua?branch=master) |
| [Python](https://github.com/bergren2/konigsberg-python) | ![Build Status](https://github.com/bergren2/konigsberg-python/workflows/build/badge.svg) | [![Maintainability](https://api.codeclimate.com/v1/badges/776d6d4cc92c0915434c/maintainability)](https://codeclimate.com/github/bergren2/konigsberg-python/maintainability) | [![Test Coverage](https://api.codeclimate.com/v1/badges/776d6d4cc92c0915434c/test_coverage)](https://codeclimate.com/github/bergren2/konigsberg-python/test_coverage) |
| [Ruby](https://github.com/bergren2/konigsberg-ruby) | ![Build Status](https://github.com/bergren2/konigsberg-ruby/workflows/build/badge.svg) | [![Maintainability](https://api.codeclimate.com/v1/badges/599410792e9ca585f432/maintainability)](https://codeclimate.com/github/bergren2/konigsberg-ruby/maintainability) | [![Test Coverage](https://api.codeclimate.com/v1/badges/599410792e9ca585f432/test_coverage)](https://codeclimate.com/github/bergren2/konigsberg-ruby/test_coverage) |
| [Scala](https://github.com/bergren2/konigsberg-scala) | [![Build Status](https://github.com/bergren2/konigsberg-scala/actions/workflows/build.yml/badge.svg)](https://github.com/bergren2/konigsberg-scala/actions/workflows/build.yml) | [![Maintainability](https://api.codeclimate.com/v1/badges/139abd9599a72dcebbc6/maintainability)](https://codeclimate.com/github/bergren2/konigsberg-scala/maintainability) | [![Test Coverage](https://api.codeclimate.com/v1/badges/139abd9599a72dcebbc6/test_coverage)](https://codeclimate.com/github/bergren2/konigsberg-scala/test_coverage) |

## What is this?

I use this repository to track solutions I have come up with for various
programming puzzle sites. Solutions are sorted into different directories based
on language, and then further separated by site and problem.  If I've solved
several problems with a particular language, there will usually be advanced
features such as test suites and libraries.

> [!WARNING]
> I know this goes without saying, but **these are solutions**. You should really
> take a stab at the problems themselves before looking at this code.

## Why multiple languages?

I originally intended to use Project Euler as a way to learn new languages.
After sitting on that strategy for some time and seeing how it worked as the
problems became more difficult, I realized I'm better off using one language
_really, really_ well and learnings its ins-and-outs -- hence, most of the
solutions here are first implemented in Ruby.

Now that I have a few more problems under my belt, I have started writing
solutions in other languages. Most of the time this starts out as a straight
translation from one language to another, but it often means I can become
familiar with a new language without needing to first understand the math, and
it also can sometimes lead to using a particular language's feature to solve a
problem in a different way.
