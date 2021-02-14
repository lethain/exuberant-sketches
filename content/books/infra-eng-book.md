---
title: "Infrastructure Engineering Book"
date: 2021-02-11T19:16:28-08:00
draft: false
---

## How to operate and scale technical infrastructure and the infrastructure organizations that behind it

*   Overview
    *   Properties
    *   Not technology focused
*   Properties -- for each property expand on the work to support it, how to measure it, etc
    *   Efficiency: nudges, leaderboards, budgets, goals, etc
        *   QoS and cost post from a few years ago
    *   Reliability: incident program, metrics, 
    *   Productivity: docs (search, structured), bootcamp, mentoring, build, test, deploy, avoiding approval gates (process impact, [quality views](https://blog.colinbreck.com/reflections-on-using-quality-views/) help here!), refactoring over writing, static languages, org structure, code structure, compliance overhead, package hosting, code hosting
    *   Performance: instrumentation, nudges, budgets, tail at scale, latency and cost
    *   Security: hmm, don’t think I know enough here
*   Workflows, Interfaces & Platforms -- what are the things your users want to do?
    *   Making changes
        *   Deploys
        *   Feature flags too
        *   Infrastructure
        *   Infra configuration
    *   Networking
        *   [Routing: config (txt, gossip, …), Load Balancing (envoy, …), Points of pressence](https://docs.google.com/document/d/1LUyPYblS9YSSNy3zdn547X_H9yd9iYiZJcVYJ51-vCo/edit)
    *   Persistence
        *   Storage: replication, sharding, bad queries and proxies to controlk, audit, ACLs, isolation, …
*   Organization -- how to structure your organization from zero to hundreds
*   Special topics
    *   Product infrastructure vs infrastructure