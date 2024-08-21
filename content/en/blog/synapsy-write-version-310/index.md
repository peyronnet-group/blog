---
author: "Léo Peyronnet"
title: "Synapsy Write v3.1.0 Changelog"
date: 2024-08-21
description: "We added a new login system."
tags: ["changelog", "synapsy"]
thumbnail: /blog/synapsy-write-version-310/banner.png
images:
  - /blog/synapsy-write-version-310/banner.png
---

A new version of Synapsy Write is now available and it is the version 3.1.0. This version includes a new login system and several fixes and improvements.

## New login system

The latest update to Synapsy Write, version 3.1.0, introduces a revamped login system designed to enhance user experience and security. This update replaces the old account management system with a new, streamlined Sign In page and account forms, offering a more intuitive and efficient process for accessing the platform. The integration of Supabase SSR ensures secure authentication, while localized support for the Sign In page caters to a global user base. Additionally, users will benefit from clear toaster notifications, guiding them through the login process with ease. This overhaul not only improves accessibility but also aligns with the platform's commitment to providing a seamless and secure user experience.

## Changelog

### New

- Added new Metadata object (closes #849)
- Removed legacy API routes
- Added Supabase Utils
- Added Stripe Utils
- Added Helpers
- Added Auth Helpers
- Added Auth Forms
- Added Account Forms
- Added Auth Routes
- Added new Sign In page
- Removed old Account system
- Added locales for Sign In page
- Added links to Peyronnet Account
- Added new Account page
- Disabled Account edition
- Added toaster notifications

### Fixed

- Cleaned importations
- Removed unecessary margins (fixes #848)

### Updated

- Made navbar sticky (#848)
- Updated types
- Updated webhooks
- _Updated dependencies_

## Launch

[Click here](https://write.peyronnet.group) to launch the app.
