---
published: true
title: Frontend Development with Umi, Dva, and Ant Design
layout: post
categories: Dev Log
author: Lucas Reed
---

![](/assets/blog-img0002.png)

### The Umi, Dva & Ant Design Stack

After being away from Ant Design for over a year, I recently dove back in and discovered they've wrapped their development toolkit into something called Umi. After spending half a day exploring it, I found that Umi is essentially an abstraction and simplification layer built on top of the original Ant Design Pro.

Here's a quick guide to setting up the environment and some gotchas to watch out for.

### Why This Stack?

The Umi + Dva + Ant Design combination offers:

- **Convention over configuration** — Less boilerplate, more building
- **Built-in routing** — File-based routing that just works
- **State management** — Dva provides a clean Redux wrapper
- **UI components** — Ant Design's comprehensive component library

### Getting Started

The setup is straightforward once you understand the ecosystem. The key is leveraging the built-in scaffolding tools rather than trying to wire everything together manually.

For most React projects targeting enterprise applications, this stack provides an excellent foundation with sensible defaults that can be customized as needed.
