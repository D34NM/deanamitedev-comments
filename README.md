# Comments Repository for deanamite.dev

This is a public repository used to handle comments for the GitHub Pages blog at [deanamaite.dev](https://deanamite.dev).

## Purpose

This repository serves as a comment system backend for the blog using [Utterances](https://utteranc.es/), allowing readers to engage with blog posts through GitHub issues. Comments are managed through GitHub's native features, providing a simple and effective way to handle reader interactions without requiring a separate comment management system.

## How it works

- The blog uses **Utterances** to enable comments on each post
- When readers comment on a blog post, Utterances automatically creates a GitHub issue in this repository
- Comments are displayed on the blog posts in real-time using GitHub's API
- Each blog post maps to a unique GitHub issue based on the post's pathname, URL, title, or other identifier
- All comment moderation and management is handled through GitHub's issue interface

## Note

This repository contains no source code for the blog itself - it exists solely for comment management purposes. The actual blog source code and content are managed separately.
