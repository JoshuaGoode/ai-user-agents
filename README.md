# ai-user-agents
Collection of AI User Agents used for dataset curation, training, browsing, and general crawling.

## Purpose

The objective is twofold: For one, this type of resource could serve as a valuable tool for monitoring and collecting data on how frequently your content is being accessed for AI training. Secondly, it can also aid in the implementation of restrictions or blocks to prevent your content from being scraped for such purposes.

For instance, OpenAI uses a user-agent identified as `GPTBot` for its web crawling. Likewise, the Common Crawl project uses `CCBot`. Knowing these identifiers could be used for stats, rate limiting, directory limiting, and blocking.

## Goals
1. Curate plaintext categorized lists of user agents related to various AI tasks.
2. Offer scripts and examples for automating list generation, updates, and integrations with applications. E.g., firewalls.
