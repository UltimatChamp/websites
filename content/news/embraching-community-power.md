---
title: "Proposing Changes to NeoForge"
date: 2023-07-31T20:15:00+02:00
draft: true
categories:
- News
author: orion
summary: This post describes the process we will follow in managing community driven changes to NeoForge and associated projects
description: This post describes the process we will follow in managing community driven changes to NeoForge and associated projects
---
## Introduction
NeoForge and it's associated projects are a large community driven effort. This document outlines our process for managing the influx of ideas and suggestions for changes and enhancements.

## The NeoForge Change Process
1) [#brainstorming](https://discord.com/channels/313125603924639766/1105595318197825557) on Discord, generally this involves a thread dedicated to the idea.
2) Develop Proofs of Concept demonstrating key ideas
3) Publishing Proofs of Concept on GitHub and generating a more formal proposal around the idea
4) Rigorous proposal and PR Review Process

    Our team of maintainers evaluates each PR on several criteria, including:

   - Merit: How impactful and valuable the proposed change is to the overall NeoForge project
   - Contents: How well the PR addresses the identified issue and aligns with the project's goals
   - Implementation: The technical quality and feasibility of the proposed changes
   - Maintainability: Whether the changes adhere to NeoForge's coding standards and are easy to maintain in the long term
   - Fulfillment of Requirements: How well the PR meets the outlined requirements of the associated proposal

5) Consensus Building
   
    To accept a change, consensus among maintainers is required. It may involve discussions, revisions, and discussions until a single Pull Request implementation is agreed upon. However, a unanimous decision is not necessary. Contentious changes may require a steering council resolution on the matter, however.

## Role of Maintainers
Throughout the change process, it is essential to understand the distinct roles that maintainers play. In their capacity as modders and users of NeoForge, maintainers actively participate in the earlier steps of the process, including discussions and the creation of targeted discussion threads. Their involvement at this stage is as valuable community members who contribute ideas and insights.

## Considerations for PoCs
When you are discussing your idea, please keep a keen eye on the following concepts

**Maintainability**: Proposed changes should be designed and implemented in a way that promotes maintainability. This involves adhering to coding standards, writing clean and well-documented code, and considering the long-term impact on the project's codebase.

**Backwards Compatibility**: While we do not mandate API/ABI backwards compatibility, we highly value backwards feature and functional compatibility. Pull Requests that risk breaking existing features or functionalities should have associated justifications for such a break before being merged into NeoForge. The community acknowledges that maintaining compatibility is vital to the satisfaction and trust of our user base.
