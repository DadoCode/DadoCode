# AI-Assisted Property Content Workflow

**AI automation prototype · Python, Anthropic API, Pillow**

## The problem

Generating repeated marketing content for a multi-property portfolio can lead to duplication, inconsistent tone and unsupported claims about individual properties.

## Prototype capabilities

I developed a pipeline that organises property facts, content history and available media to prepare weekly plans and content assets:

1. Plan topics and formats while accounting for recent content
2. Generate draft copy with an AI model
3. Validate property-specific claims against structured facts
4. Select suitable images and formats
5. Prepare visual assets and captions for review

The workflow includes deterministic fallback behaviour and automated checks. AI-generated suggestions are not accepted unconditionally.

## Important design principle

**Generative AI proposes; structured rules validate.**

This is especially important for factual property claims: a model should not invent amenities, capacity or location details simply to improve marketing copy.

## Current status

Active prototype. Not a public subscription product, not an autonomous publishing service, and not presented as a completed client-ready platform.

## Disclosure

This case study intentionally describes behaviour and architecture without publishing the private implementation, production media, credentials or business-specific details. Synthetic examples can be added as a visual demo after ownership and asset rights are checked.
