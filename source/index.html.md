---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - scala

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

Welcome to Hiram's API! You can use our API to access service API endpoints, through which you can interact with a Lodge.

We have language bindings in Scala, but we may add hints in Ruby, JavaScript, Python, and others if they are requested! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.

This example API documentation page was created with [Slate](https://github.com/lord/slate).

# Authentication

> To authorize, use this code:

```scala
import hiram

val request =
  sttp
    .post(uri"https://api.project-hiram.com/auth/login")
    .body() // see https://sttp.readthedocs.io/en/latest/requests/body.html for information on request body serializers

```
