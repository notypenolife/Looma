# Looma

A personalised boarding-school companion with original animated Loomas, a calm student assistant and practical staff tools.

## [Open the live demo →](https://notypenolife.github.io/Looma/)

The demo runs on GitHub Pages. You can open it from any device without keeping a laptop or localhost server running.

### Explore

- **Student life:** daily schedules, uniform and notices, simulated chat, homework and personal goals.
- **Companions:** original SVG characters, individual first-person messages, articulated jumping, eating, reading and sleeping, colours and fitted accessories.
- **Rewards:** Dewdrops, streaks, shop collections, eight earned-chest tiers, five-tap upgrades and rewards that jump out of the chest.
- **Staff tools:** room inspections, follow-up notes, duties, assignment receipts, reward missions and fictional detention administration.
- **Settings:** reset the demo account and choose a starter again.

### Demo boundaries

All names and school records are fictional. Progress stays in each visitor’s browser and does not sync across devices. Nothing is sent to teachers, no real money is used, and live AI, authentication and databases are not enabled. The role switcher is demonstration navigation, not real staff access.

### Source and publishing

[Looma-source.zip](Looma-source.zip) contains the complete portable application source, configuration, 39 domain tests and the verified static build in `out/`. Download and extract it to work on the code.

Built with Next.js App Router, React, TypeScript, Tailwind CSS, Radix Dialog, Lucide and original SVG/CSS artwork.

```sh
npm ci
npm run dev
```

Open `http://localhost:3000/Looma/`. Run `npm test`, `npm run typecheck` and `npm run build` for checks. The build exports the site to `out/`, with `/Looma` as the GitHub Pages base path.

The repository’s Pages workflow uses a read-only checkout to publish the reviewed static build from the archive. It cannot push source changes or alter the repository. Updating the reviewed archive or running the workflow manually republishes the demo.

Before handling real student data, add authenticated school memberships, database access policies, server-authorised rewards and audited staff permissions. Live AI requires server-side validation, rate limiting, cost controls and school-approved safeguards. Never put secret keys in browser code.

Original Looma characters and branding remain all rights reserved unless the owner adds a license.
