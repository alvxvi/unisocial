<div align="center">
    <h1>🌿<br>School Network</h1>
    <strong>Open source Social media app 💕</strong>
</div>
<div align="center">
    <a href="https://discord.gg/"><b>Discord</b></a>
    •
    <a href="https://github.com/alvxvi/schoolnetwork"><b>Issues</b></a>
</div>

## 🌿 Technology Stack

### Frontend

The frontend is built with [NextJS](https://nextjs.org) and uses [HeadlessUI](https://headlessui.com) with utility classes from [TailwindCSS](https://tailwindcss.com).

### Backend

The backend is based on [NestJS](https://nestjs.com) using [PostgreSQL](https://www.postgresql.org) as a database together with [Typeorm](https://typeorm.io) and [Redis](https://redis.io) for caching.

## 🤝 Contributing

We encourage you to contribute to this project! Please check out below for guidelines about how to proceed.

Anyone can be a contributor. Either you found a typo, or you have an awesome feature request you could implement, we encourage you to create a Merge Request.

### Submitting a Merge Request

- Merge Requests should be raised for any change and it will be approved by a maintainer before merging.
- The latest changes are always in `main` branch, so please create your branch from `main`.
- If you’ve fixed a bug or added code that should be tested, add the tests and then link the corresponding issue in either your commit or your PR.
- Run `npm lint` before committing to make resolving conflicts easier (VSCode users, check out this extension to fix lint issues in development)
- We encourage you to test your changes, and if you have the opportunity, please make those tests part of the Merge Request.
- If you add new functionality, please provide the corresponding documentation as well and make it part of the Merge Request.
- The Merge Request should be raised against main branch.

## ✅ Community

For a place to have open discussions on features, voice your ideas, or get help with general questions please visit our community at [Discord](https://discord.gg/).

## ⚙️ Setup

### Using Local Environment

```sh
cd web
cp .env.example .env
npm install
npm run dev
```
