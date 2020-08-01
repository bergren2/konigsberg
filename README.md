# Königsberg

![Project Euler Badge](https://projecteuler.net/profile/bergren2.png)

Solutions to various problems on the Internet, including:

- [Project Euler](https://projecteuler.net/)
- [Advent of Code](http://adventofcode.com/)
- [r/dailyprogrammer](https://www.reddit.com/r/dailyprogrammer/)
- [Wolfram Challenges](https://challenges.wolfram.com)
- [dev.to Daily Challenge](https://dev.to/thepracticaldev/daily-challenge-1-string-peeler-4nep)

## Languages

| Language | Build Status | Code Quality | Test Coverage |
|:---------|:-------------|:-------------|:--------------|
| [C#](https://github.com/bergren2/konigsberg-csharp) | ![build](https://github.com/bergren2/konigsberg-csharp/workflows/build/badge.svg) | [![Maintainability](https://api.codeclimate.com/v1/badges/e29c49dcdc02208f384e/maintainability)](https://codeclimate.com/github/bergren2/konigsberg-csharp/maintainability) ||
| [Lua](https://github.com/bergren2/konigsberg-lua) | [![Build Status](https://travis-ci.com/bergren2/konigsberg-lua.svg?branch=master)](https://travis-ci.com/bergren2/konigsberg-lua) || [![Coverage Status](https://coveralls.io/repos/github/bergren2/konigsberg-lua/badge.svg?branch=master)](https://coveralls.io/github/bergren2/konigsberg-lua?branch=master) |
| [Python](https://github.com/bergren2/konigsberg-python) ||||
| [Ruby](https://github.com/bergren2/konigsberg-ruby) | ![Build Status](https://github.com/bergren2/konigsberg-ruby/workflows/build/badge.svg) | [![Maintainability](https://api.codeclimate.com/v1/badges/599410792e9ca585f432/maintainability)](https://codeclimate.com/github/bergren2/konigsberg-ruby/maintainability) | [![Test Coverage](https://api.codeclimate.com/v1/badges/599410792e9ca585f432/test_coverage)](https://codeclimate.com/github/bergren2/konigsberg-ruby/test_coverage) |
| [Scala](https://github.com/bergren2/konigsberg-scala) | [![Build Status](https://travis-ci.com/bergren2/konigsberg-scala.svg?branch=master)](https://travis-ci.com/bergren2/konigsberg-scala) | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=bergren2_konigsberg-scala&metric=alert_status)](https://sonarcloud.io/dashboard?id=bergren2_konigsberg-scala) | [![Coverage Status](https://coveralls.io/repos/github/bergren2/konigsberg-scala/badge.svg?branch=master)](https://coveralls.io/github/bergren2/konigsberg-scala?branch=master) |

## What is this?

I use this repository to track solutions I have come up with for various
programming puzzle sites. Solutions are sorted into different directories based
on language, and then further separated by site and problem.  If I've solved
several problems with a particular language, there will usually be advanced
features such as test suites and libraries.

I know this goes without saying, but **these are solutions**. You should really
take a stab at the problems themselves before looking at this code.

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
