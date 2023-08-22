---
title: "Proposing Changes to NeoForge"
date: 2023-07-31T20:15:00+02:00
draft: true
categories:
- News
author: orion
summary:
description:
---
# Proposing Changes to NeoForge

With our transition away from Minecraft Forge starting, a lot of new ideas and interests are bubbling up in the community.
To not have that momentum die out, the proposed ideas need to be turned into actual Pull Requests, and this blog post describes the general concept.

## The NeoForge Change Process
From a simple idea to a merged feature, several steps are taken to ensure that each idea reflects the communities needs:

### Step 1: [#brainstorming](https://discord.com/channels/313125603924639766/1105595318197825557) on Discord

The first step in the process involves sparking ideas and initiating discussions in the designated Discord channel, [#brainstorming](https://discord.com/channels/313125603924639766/1105595318197825557). Here, community members can freely propose and deliberate the general concepts of changes they wish to see in NeoForge. This open forum allows diverse perspectives to emerge and encourages a healthy exchange of ideas.

### Step 2: Targeted Discussion Threads

Once an idea gains traction in [#brainstorming](https://discord.com/channels/313125603924639766/1105595318197825557), moderators take the initiative to create targeted discussion threads. These threads are designed to guide and focus the community's efforts, helping to solidify and concretize the proposed ideas. Both maintainers and moderators participate in these threads in their personal capacity, providing valuable insights and guidance where necessary. However, their existence expresses no guarantee that an idea will be adopted. And the opinions expressed in those threads is of the people involved in their personal capacity as a modder, not as a NeoForged Organisation member, or even a maintainer. 

### Step 3: Developing Proofs of Concepts

The community's creative energy is unleashed in step three, where individuals or groups involved in the idea collaborate to create one or more proofs of concepts (PoCs). These PoCs serve as tangible demonstrations of how the suggested changes could be implemented in NeoForge. The PoCs showcase different approaches, fostering an environment of experimentation and innovation.

### Step 4: Publishing PoCs on GitHub

Once the PoCs are ready, they are published as Pull Requests (PRs) on our GitHub page. This step ensures that the proposed changes are transparent and accessible to all community members. By making these PRs public, we encourage further feedback and contributions from the wider NeoForged community.

### Step 5: Rigorous PR Review Process

The heart of our proposal process lies in step five, where the PRs undergo a thorough review. Our team of maintainers evaluates each PR on several criteria, including:

- Merit: How impactful and valuable the proposed change is to the overall NeoForge project.
- Contents: How well the PR addresses the identified issue and aligns with the project's goals.
- Implementation: The technical quality and feasibility of the proposed changes.
- Maintainability: Whether the changes adhere to NeoForge's coding standards and are easy to maintain in the long term.
- Fulfillment of Requirements: How well the PR meets the outlined requirements.

### Step 6: Consensus Building

To accept a change, consensus among maintainers is required. This ensures that decisions are reached collectively and are in the best interest of the NeoForged community as a whole. It may involve discussions, revisions, and constructive debates until a single Pull Request implementation is agreed upon. However, a unanimous decision is not need.


## Building a Solid Foundation: Key Insights into our Community-Driven Change Process
### Role of Maintainers:

Throughout the idea drive change process, it is essential to understand the distinct roles that maintainers play. In their capacity as modders and users of NeoForge, maintainers actively participate in the earlier steps of the process, including discussions and the creation of targeted discussion threads. Their involvement at this stage is as valuable community members who contribute ideas and insights.

However, from Step 5 onwards, maintainers transition into their role as stewards of the project's codebase. At this point, they take on the responsibility of reviewing and evaluating the proposed Pull Requests (PRs) based on merit, implementation, maintainability, and fulfillment of requirements.

### Encouraging Thoughtful Consideration:

The NeoForged community places great emphasis on ensuring the longevity and stability of NeoForge. As such, we strongly encourage all community members to consider the implications of their proposed changes, especially during the Pull Request phase.

**Maintainability**: Proposed changes should be designed and implemented in a way that promotes maintainability. This involves adhering to coding standards, writing clean and well-documented code, and considering the long-term impact on the project's codebase.

**Backwards Compatibility**: While we do not mandate API/ABI backwards compatibility, we highly value backwards feature and functional compatibility. Pull Requests that risk breaking existing features or functionalities face a significant challenge in being merged into NeoForge. The community acknowledges that maintaining compatibility is vital to the satisfaction and trust of our user base.