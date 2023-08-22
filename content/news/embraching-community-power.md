---
title: "Proposing Changes to NeoForge"
date: 2023-07-31T20:15:00+02:00
draft: true
categories:
- News
author: orion
summary: This post describes the process in which changes can be suggested to NeoForge
description: This post describes the process in which changes can be suggested to NeoForge
---
# Proposing Changes to NeoForge
If you are interested in making or suggesting changes to NeoForge, we suggest the following process:

## The NeoForge Change Process
1) [#brainstorming](https://discord.com/channels/313125603924639766/1105595318197825557) on Discord, generally this involves a thread dedicated to the idea.
2) Make Proofs of Concepts
3) Publishing PoCs on GitHub
4) Rigorous PR Review Process
Our team of maintainers evaluates each PR on several criteria, including:

   - Merit: How impactful and valuable the proposed change is to the overall NeoForge project.
   - Contents: How well the PR addresses the identified issue and aligns with the project's goals.
   - Implementation: The technical quality and feasibility of the proposed changes.
   - Maintainability: Whether the changes adhere to NeoForge's coding standards and are easy to maintain in the long term.
   - Fulfillment of Requirements: How well the PR meets the outlined requirements.

5) Consensus Building
To accept a change, consensus among maintainers is required. It may involve discussions, revisions, and discussions until a single Pull Request implementation is agreed upon. However, a unanimous decision is not need.

## Role of Maintainers:
Throughout the change process, it is essential to understand the distinct roles that maintainers play. In their capacity as modders and users of NeoForge, maintainers actively participate in the earlier steps of the process, including discussions and the creation of targeted discussion threads. Their involvement at this stage is as valuable community members who contribute ideas and insights.

## Considerations for PoCs:
When you are discussing your idea, please keep a keen eye on the following concepts:

**Maintainability**: Proposed changes should be designed and implemented in a way that promotes maintainability. This involves adhering to coding standards, writing clean and well-documented code, and considering the long-term impact on the project's codebase.
**Backwards Compatibility**: While we do not mandate API/ABI backwards compatibility, we highly value backwards feature and functional compatibility. Pull Requests that risk breaking existing features or functionalities face a significant challenge in being merged into NeoForge. The community acknowledges that maintaining compatibility is vital to the satisfaction and trust of our user base.