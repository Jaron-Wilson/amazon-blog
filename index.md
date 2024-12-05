---
title: Welcome to my blog site!
---

# Featured Links

This page displays a list of featured links with video content and an option to view them on Amazon.

## Components:

- **Container**: A wrapper for the content.
- **Typography**: Displays the main heading and content text.
- **Grid**: Displays items in a responsive grid layout.
- **Card**: Represents each item with a video and Amazon URL.

## Video Embed Logic:

- The `embedVideo` function detects if a URL is from YouTube and extracts the video ID to create an embedded iframe.

## Features:

- Displays a list of items with:
  - Title
  - Embedded YouTube video (if applicable)
  - Amazon URL link to view the product.
