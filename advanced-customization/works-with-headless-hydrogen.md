---
description: >-
  This doc guides you on how to integrate BOGOS with your headless/Hydrogen
  store.
---

# Works with Headless/Hydrogen

### Overview

BOGOS offers two integration approaches for headless stores, each designed for different use cases and technical requirements. This guide breaks down both methods so you can choose the one that fits your setup:

[Option 1: API Integration (Maximum Flexibility)](works-with-headless-hydrogen.md#option-1-api-integration-maximum-flexibility)

[Option 2: JS/SDK Integration (Faster Implementation)](works-with-headless-hydrogen.md#option-2-js-sdk-integration-faster-implementation)

### Option 1: API Integration (Maximum Flexibility)

**Documentation:** [https://bogos-api-integration.gitbook.io/bogos-api-integration/integration-steps/gift-offer](https://bogos-api-integration.gitbook.io/bogos-api-integration/integration-steps/gift-offer)

**Best for:** Developers who need complete control and are building for any platform (web, mobile app, or third-party integrations)

**What offers is supported**

The API integration supports **all BOGOS offer types**, including gift offers, bundles, upsells, discount offers, and boosters. This approach gives you direct access to BOGOS's core functionality through API endpoints.

**Advantages**

* **Complete customization** - Build exactly what you need
* **Platform agnostic** - Works with web apps, mobile apps, and third-party integrations
* **Full control** - Implement the logic exactly how you want it

**Technical Requirements**

Your development team needs solid expertise in:

* Shopify platform architecture
* Storefront API implementation
* BOGOS app features and offer mechanics

This isn't a plug-and-play solution. You're building the integration from the ground up, which means your developers need to understand both the Shopify ecosystem and how BOGOS promotions work under the hood.

***

### Option 2: JS/SDK Integration (Faster Implementation)

**Documentation:** [https://bogos-api-integration.gitbook.io/bogos-api-integration/bogos-js-sdk](https://bogos-api-integration.gitbook.io/bogos-api-integration/bogos-js-sdk)

**Best for:** Web applications where speed of implementation matters and you want working code examples

**What offers is supported**

The JS/SDK supports all BOGOS offer types, giving you full coverage of BOGOS features with less implementation work.

**Advantages**

* **Faster development** - Pre-built SDK handles the heavy lifting
* **Concrete examples** - Demo code gets you started quickly
* **Less detailed knowledge required** - Still need Shopify & storefront API expertise, but don't need to know every detail of BOGOS internals

**Limitations**

* **Web apps only** - Not compatible with native mobile applications

***

### Getting Started

**Step 1:** Review your technical requirements

* What platforms do you need to support?
* What types of offers will you run during BFCM?
* What's your development timeline?

**Step 2:** Assess your team's expertise

* How familiar are they with Shopify's architecture?
* Do they have bandwidth to build from scratch (API) or need faster implementation (SDK)?

**Step 3:** Choose your Integration Method

* **API approach:** Start with the API integration guide for your chosen offer type.
* **SDK approach:** Review the JS/SDK documentation and demo code.

**Step 4:** Check the Docs and ask BOGOS Support Team for your **bogos api-key**

**Step 5:** Build using the instructions from your chosen method.
