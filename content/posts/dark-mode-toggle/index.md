---
title: Dark Mode Toggle
description: Dark mode without the flash of default theme
date: 2021-04-21
draft: false
slug: /pensieve/dark-mode-toggle
tags:
  - Theming
  - Dark Mode
---

Dark mode toggle without the flash of default theme. Important bits:

- CSS variables for color theming
- Put `data-theme` attribute on `<html>`, not `<body>`, so we can run the JS before the DOM finishes rendering
- Run local storage check in the `<head>`
- JS for toggle button click handler can come after render
