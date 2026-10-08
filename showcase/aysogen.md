# Aysogen — AI SaaS Platform

> **Laravel 13 · Livewire 4 · AI integrations · Queues · Subscription & credit billing**

[← Back to GitHub profile](../README.md)

## The product
Aysogen is a self-hosted AI services platform for conversational AI, image generation and video generation, backed by subscription and credit-based usage. Its administration layer covers AI provider configuration, billing, affiliates, email campaigns and branding.

## Engineering highlights
- **Multi-capability AI workflow:** text, image and video features built around configurable AI providers.
- **Asynchronous execution:** Laravel queue workers process generation tasks outside the request lifecycle; scheduled tasks support campaigns, affiliate commission processing and job recovery.
- **Business infrastructure:** subscriptions / credits, payment configuration, affiliate capabilities and administrative controls.
- **Deployment-oriented build:** installer and documentation for web server, database, worker and scheduler setup.

## Technology
PHP · Laravel 13 · Livewire 4 · MySQL · Laravel Queues · Scheduler · Nginx / Apache

## What this demonstrates
Integration-heavy SaaS design, long-running background workloads, reusable administrative tools and operational thinking beyond basic CRUD.

**Code availability:** The production/source repository is private. This public engineering summary intentionally excludes implementation details, secrets, and paid product source code.
