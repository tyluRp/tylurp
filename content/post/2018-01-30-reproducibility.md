---
title: Reproducibility
author: ~
date: '2018-01-30'
slug: reproducibility
categories: ['rstats']
tags: ['rstats', 'stackoverflow', 'social programming']
description: ''
---

> _Welcome to SO. In order to answer your question, please provide a minimal, complete, and verifiable example._

If you've ever asked a question on [Stack Overflow](https://stackoverflow.com) (SO), you may recognize the quote above. This is because reproducibility is incredibly important when asking programming questions and it's often overlooked. To be brief, a great reproducible example should be:

1. **Minimal** -- Provide the least amount of code needed to reproduce the problem.
2. **Complete** -- Provide everything needed to reproduce the problem (packages, data, functions, etc.).
3. **Verifiable** -- Test your code and confirm that it reproduces the problem.

See [this SO post](https://stackoverflow.com/help/mcve) for a comprehensive defintion of what constitutes a minimal, complete, and verifiable example. For discussion on reproducibility in R, see [this SO post](https://stackoverflow.com/questions/5963269/how-to-make-a-great-r-reproducible-example).

Additionally, here's a list of some other things I think are important:

1. Load the packages you need. Don't ask/answer questions with `library(tidyverse)` when the user only needs `dplyr`. 
2. Avoid text heavy questions. Questions are often easier to answer with just a few sentences, data, and the desired output.
3. Ask one question at a time. If you have another, post a different question rather than modifying the original.
4. Use `dput` to copy/paste data and `reprex` for rendering your code.
5. Avoid fragile and destructive code like `setwd()` or `rm(list = ls())`.
