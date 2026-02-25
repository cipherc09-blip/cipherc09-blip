<div align="center">

<img src="https://thredly.dev/logo/logo.svg" alt="thredly" width="80" />

# Hi, I'm Cipher

**Building [thredly.dev](https://thredly.dev) — Threads & Instagram data infrastructure at scale**

[![Website](https://img.shields.io/badge/thredly.dev-B9FF66?style=for-the-badge&logo=cloudflare&logoColor=191A23)](https://thredly.dev)
[![Twitter Follow](https://img.shields.io/twitter/follow/Cipher37953?style=for-the-badge&logo=x&logoColor=white&color=191A23)](https://x.com/Cipher37953)
[![GitHub followers](https://img.shields.io/github/followers/cipherc09-blip?style=for-the-badge&logo=github)](https://github.com/cipherc09-blip)

</div>

## What I'm Building

**[thredly](https://thredly.dev)** — a professional-grade Threads & Instagram data API built for researchers, analysts, and developers who need reliable social data at scale.

- Auto session management with zero-maintenance cookie rotation
- 15+ endpoints covering users, posts, search, and analytics
- TypeScript SDK for easy integration
- Deployed globally on Cloudflare Workers — sub-500ms P95 latency

## Quick Look

```typescript
import { ThredlyClient } from 'threads-api-client';

const client = new ThredlyClient({ apiKey: 'your-api-key' });

// Get a user profile
const user = await client.users.getInfo('zuck');

// Fetch their posts (paginated)
const posts = await client.users.getPosts(user.userId, { limit: 20 });

// Search Threads
const results = await client.search.top('AI research');
```

**[Get started at thredly.dev →](https://thredly.dev)**

## Tech Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

</div>

## GitHub Stats

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=cipherc09-blip&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cipherc09-blip&layout=compact&langs_count=6&theme=tokyonight"/>

</div>

---

<div align="center">

**[thredly.dev](https://thredly.dev) · [@Cipher37953](https://x.com/Cipher37953)**

</div>
