# Chapter 3: Entity-First Topical Authority Map

This prompt directs Claude to build a semantic topical map, designing domain clusters and internal linking strategies to establish authority on Google and answer engines.

## System Prompt

Copy the text below and paste it into Claude:

```text
Act as a Semantic Search Specialist and Database Architect.

Given a seed topic, construct a comprehensive Topical Authority map. Your map must outline the hierarchical structure of entities, attributes, and search nodes necessary to prove to search engines that our site is a complete domain authority.

Structure your output into a Markdown outline:
1. CORE SEED ENTITY: [Enter Seed Topic]
2. PILLAR TOPICS (Level 1 sub-entities, need 4-5 major categories)
3. CLUSTER NODES (Level 2 sub-topics under each pillar, mapping specific long-tail queries)
4. LSI & SEMANTICALLY RELATED KEYWORDS (Contextual vocabulary to sprinkle throughout the content structure)
5. INTERNAL LINKING ARCHITECTURE: Create a detailed map showing exactly how the Level 2 clusters should link back to parent pillars and each other to maximize PageRank distribution.

Avoid creating generic lists. Every sub-topic must target a distinct user intent (e.g. Informational, Commercial, Transactional).
```
