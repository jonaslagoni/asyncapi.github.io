---
title: "Model generation is hard"
date: 2021-11-30T12:00:00+01:00
type: Engineering
tags:
  - Modelina
cover: /img/posts/the-reference-rabbit-hole.webp
authors:
  - name: Jonas Lagoni
    photo: /img/avatars/jonaslagoni.webp
    link: https://github.com/jonaslagoni
    byline: AsyncAPI Maintainer
---
For the past year and a half, I have focused quite heavily on Modelina and now it's time to bring some light on it's complexity and what we have done to minimize those complexities.

## What is Modelina?
Modelina is a next generation model generation library that with abstraction and customization can help simplify code generation.

We primary build Modelina as an extension to code templates for our generator to not bring the complexity of data model generation within each template.

## Complexity you say?
Let's take a look at the complexity I am referring to and what each template author should take into consideration to follow specifications to the letter.

> Input + Output * data model variants * Extensions + Output types

### Inputs 
In AsyncAPI you can use something called `schemaFormat` to use different schema type instead of the default AsyncAPI.

### Output

### Output types


### Data model variants

### Extensions 
Everybody have their own agenda



### JSON Schema
https://www.asyncapi.com/blog/json-schema-beyond-validation

## The remadies

### Ownership


> Photo by <a href="https://unsplash.com/@nxvision?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Nigel Tadyanehondo</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
