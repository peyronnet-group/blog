---
author: "Léo Peyronnet"
title: "Synapsy Write v3.2.0 Changelog"
date: 2024-08-29
description: "Introducing Mistral AI Providers and other improvements."
tags: ["changelog", "synapsy"]
thumbnail: /blog/synapsy-write-version-320/banner.png
images:
  - /blog/synapsy-write-version-320/banner.png
---

A new version of Synapsy Write is now available and it is the version 3.2.0. This version introduces our new AI providers system along with many other new features.

## Introducing the Mistral AI Models

The most anticipated feature in this release is the integration of Mistral AI models. Mistral models are known for their efficiency and precision in generating high-quality text, making them a valuable addition to Synapsy Write. Here’s what you can expect:

- **Model Selector Component**: The newly added Model Selector component on the Create page allows users to easily switch between available models. With the inclusion of Mistral models, you can now choose the best AI provider for your specific needs.

- **Mistral Names and Options**: Synapsy Write has also introduced the ability to see and select different Mistral model options by name. This means you can experiment with various configurations to find the optimal model for your tasks.

## New and Improved Features

Alongside the introduction of Mistral, Synapsy Write v3.2.0 brings several other enhancements designed to improve your overall experience:

- **Language Support Expansion**: Spanish language support has been added, allowing for broader international use and catering to a diverse user base.
- **Unified Prompt System**: A new prompt creation system unifies the way prompts are managed, making it easier to generate consistent and tailored responses. The addition of system and user prompts objects helps in creating more structured and nuanced prompts.

- **User Interface Upgrades**: The introduction of a Tabs component and placeholder in Chat, along with a new logo and footer, not only enhances the aesthetic appeal but also improves the usability of the platform.

## Why Mistral Models Matter

The inclusion of Mistral models in Synapsy Write is a game-changer for users who require advanced text generation capabilities. Mistral models are particularly effective in generating long-form content with greater coherence and context retention, making them ideal for complex document creation. By offering Mistral as an AI provider, Synapsy Write empowers users to choose models that best fit their content needs, whether they’re working on creative writing, technical documentation, or multilingual projects.

## Changelog

### New

- Added Language type
- Added system prompts object
- Added user prompts object
- Added new Prompt Creator system
- Unified Prompt system
- Added Spanish language
- Added new AI SDK chat system
- Added placeholder in Chat
- Added Tabs component
- Added model selector component
- Added Model Selector to Create page
- Added new AI SDK Completions system
- Added GPT-4o Mini (08/2024)
- Added the possibility to get Mistral models
- Added the possibility to see available Mistral Models
- Added Mistral option in Model Selector
- Added the possibility to use Mistral as AI Provider
- Added Mistral Names
- Added new logo
- Added new footer
- Improved alignment with footer

### Fixed

- Fixed typo

### Updated

- Replaced legacy type
- Updated Model Section
- Refactored `getModelString` function to use a dictionary
- Updated Model API
- Updated PWA icons
- _Updated dependencies_

## Launch

[Click here](https://write.peyronnet.group) to launch the app.
