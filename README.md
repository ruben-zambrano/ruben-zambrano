<h1 align="center">Hi, I'm Rubén 👋</h1>

<p align="center">
  <b>Software Engineer</b> from Madrid · 9+ years building for the web<br/>
  I build fast, accessible and memorable products — from the database to the last pixel,<br/>with AI agents as part of my daily workflow.
</p>

<p align="center">
  <a href="https://rubenzambrano.com"><img src="https://img.shields.io/badge/rubenzambrano.com-0a0a0b?style=for-the-badge&logo=googlechrome&logoColor=white" height="25" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/ruben-zambrano-casas"><img src="https://img.shields.io/badge/linkedin-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" height="25" alt="LinkedIn"/></a>
  <a href="mailto:ruzamca@gmail.com"><img src="https://img.shields.io/badge/gmail-E4405F?style=for-the-badge&logo=gmail&logoColor=white" height="25" alt="Email"/></a>
  <a href="https://twitter.com/_ruben_zambrano"><img src="https://img.shields.io/badge/x-000000?style=for-the-badge&logo=x&logoColor=white" height="25" alt="X"/></a>
</p>

```typescript
export class WhoAmI {
  readonly name = "Rubén Zambrano";
  readonly location = "Madrid, Spain";
  readonly languages = ["Spanish (native)", "English"];

  currentRole() {
    return { title: "Frontend Software Engineer", company: "eDreams ODIGEO", since: 2023 };
  }

  previously() {
    return ["Tech Lead @ Decathlon Digital (~20 engineers)", "Software Engineer @ Decathlon Digital"];
  }

  sideProjects() {
    return ["Jugueo", "Guildeo", "Lulivo", "Peña Ortigal", "a self-hosted homelab"];
  }

  workflow() {
    return "AI-native: I design the system, agents help me build it, I own every line";
  }

  hobbies() {
    return ["Sports", "Gaming", "Series"];
  }
}
```

## 🚀 What I'm building

| Project | What it is | Stack |
| --- | --- | --- |
| [**Jugueo**](https://jugueo.com) | 50 group games to play from a single phone. Mobile-first, no sign-up, self-hosted on my homelab. | Next.js · TypeScript · PostgreSQL · next-intl |
| [**Guildeo**](https://guildeo.app) | Multi-tenant SaaS for associations, gyms and academies: members, fees, payments and events. Tenant isolation with Postgres Row-Level Security. | Next.js · Drizzle · PostgreSQL · Stripe · Turborepo |
| [**Lulivo**](https://lulivo.app) | A baby's digital diary for parents: sleep, feeding, growth and stats. iOS + Android, in beta. | Flutter · Dart · Next.js · Prisma · Firebase |
| [**Peña Ortigal**](https://www.acpenaortigal.es) | Website and backoffice for a cultural association, plus a Flutter app for members with NFC access control. | Next.js · MongoDB · Flutter · NFC |
| [**rubenzambrano.com**](https://rubenzambrano.com) | My portfolio, with 3D and scroll-driven animation. | Next.js · Three.js · GSAP · Framer Motion |

## 🤖 How I work with AI

AI isn't a side tool for me: it's part of how I design, build and ship every day. I treat it
as leverage, not autopilot. I own the architecture and the judgment calls, and I review
everything that reaches production.

- **Agent-ready repos.** Every project ships with a `CLAUDE.md` / `AGENTS.md` that sets out
  its conventions, architecture and guardrails, so agents work like another engineer on the team.
- **Custom skills and workflows.** I write reusable skills (Git conventions, release
  process, design rules) and share them across repositories.
- **Decisions first.** ADRs and design docs come before the code, so humans and agents
  build on the same context.
- **Agents with real tools.** MCP servers (Playwright for browser checks, docs, Drive),
  parallel agents on isolated worktrees, and AI-assisted code review before every merge.
- **Solo, at team speed.** That's how I ship several full products in parallel, from mobile
  apps to multi-tenant SaaS and my own infrastructure, without cutting corners on tests or quality.

<img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" height="25" alt="Claude Code"/> <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" height="25" alt="Model Context Protocol"/> <img src="https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white" height="25" alt="GitHub Copilot"/> <img src="https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white" height="25" alt="Cursor"/>

## 🛠️ Tech stack

**Languages**

<a href="#"><img src="https://skillicons.dev/icons?i=ts,js,dart,html,css,sass,less,bash,python&perline=12" alt="Languages"/></a>

**Frontend**

<a href="#"><img src="https://skillicons.dev/icons?i=react,nextjs,vue,svelte,astro,threejs,graphql,tailwind&perline=12" alt="Frontend"/></a>

<img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white" alt="Framer Motion"/> <img src="https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black" alt="GSAP"/> <img src="https://img.shields.io/badge/HeroUI-000000?style=flat-square&logo=heroui&logoColor=white" alt="HeroUI"/> <img src="https://img.shields.io/badge/next--intl-26A69A?style=flat-square&logo=i18next&logoColor=white" alt="next-intl"/> <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod"/>

**Mobile**

<a href="#"><img src="https://skillicons.dev/icons?i=flutter,dart,apple,androidstudio&perline=12" alt="Mobile"/></a>

**Backend & data**

<a href="#"><img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mongodb,redis,kafka,prisma,firebase&perline=12" alt="Backend and data"/></a>

<img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black" alt="Drizzle ORM"/> <img src="https://img.shields.io/badge/Neon-00E599?style=flat-square&logo=neon&logoColor=black" alt="Neon"/> <img src="https://img.shields.io/badge/Upstash-00E9A3?style=flat-square&logo=upstash&logoColor=black" alt="Upstash"/> <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" alt="Stripe"/> <img src="https://img.shields.io/badge/Resend-000000?style=flat-square&logo=resend&logoColor=white" alt="Resend"/> <img src="https://img.shields.io/badge/Auth.js-5B21B6?style=flat-square" alt="Auth.js"/> <img src="https://img.shields.io/badge/Inngest-1E1E1E?style=flat-square" alt="Inngest"/>

**Testing & code quality**

<a href="#"><img src="https://skillicons.dev/icons?i=vitest,jest,cypress&perline=12" alt="Testing"/></a>

<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square" alt="Playwright"/> <img src="https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white" alt="Testing Library"/> <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white" alt="Storybook"/> <img src="https://img.shields.io/badge/Chromatic-FC521F?style=flat-square&logo=chromatic&logoColor=white" alt="Chromatic"/> <img src="https://img.shields.io/badge/SonarQube-126ED3?style=flat-square&logo=sonar&logoColor=white" alt="SonarQube"/> <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white" alt="ESLint"/> <img src="https://img.shields.io/badge/Prettier-1A2B34?style=flat-square&logo=prettier&logoColor=F7B93E" alt="Prettier"/>

**Cloud, DevOps & self-hosting**

<a href="#"><img src="https://skillicons.dev/icons?i=docker,githubactions,git,github,vercel,gcp,cloudflare,nginx,linux,debian&perline=12" alt="Cloud and DevOps"/></a>

<img src="https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white" alt="Turborepo"/> <img src="https://img.shields.io/badge/release--please-494949?style=flat-square&logo=semanticrelease&logoColor=white" alt="release-please"/> <img src="https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white" alt="Tailscale"/> <img src="https://img.shields.io/badge/Home_Assistant-18BCF2?style=flat-square&logo=homeassistant&logoColor=white" alt="Home Assistant"/> <img src="https://img.shields.io/badge/Backblaze_B2-E21E29?style=flat-square&logo=backblaze&logoColor=white" alt="Backblaze B2"/>

## 🏠 Homelab

My side projects run on a self-hosted **Debian NAS** (Intel N100, 16 GB): one Docker Compose
stack per service, a shared **PostgreSQL 18**, private access over **Tailscale** and public
entry through **Cloudflare Tunnel**, with zero open ports on the router. Apps ship from GitHub
Actions with release-please to a self-hosted runner; backups go to Backblaze B2 with
`restic`, and uptime alerts land on my phone.

---

<p align="center"><i>Simple code, fast iteration, and shipping over talking.</i></p>
