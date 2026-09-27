### Hi, I'm Rhett 👋

I'm a Computer Science and Cyber Security student at the University of North
Dakota, looking for a **software engineering or security internship**. I build
full-stack mobile apps on my own, from the database and security rules to the
algorithms and the App Store release.

**Portfolio:** [lindellrhett-gif.github.io](https://lindellrhett-gif.github.io/) ·
**Email:** [lindellrhett@gmail.com](mailto:lindellrhett@gmail.com)

---

#### 🏋️ [Rust Strength](https://lindellrhett-gif.github.io/rust-strength.html): submitted to the App Store

An iPhone workout tracker that suggests the weight for your next set.

- **Recommendation algorithm:** estimates a one-rep max from each set, smooths
  it over recent sets, and learns the conversion between differently labeled
  gym machines.
- **Offline-first:** sets logged with no signal are queued and synced later.
- **Social features:** a friends feed and leaderboards, secured with PostgreSQL
  Row Level Security and permission-checked SQL functions.
- **Tested and shipped:** 519 unit tests, released through TestFlight to App
  Store review.

`TypeScript` `React Native` `Expo` `Supabase` `PostgreSQL` `TanStack Query` `Jest`

[Source](https://github.com/lindellrhett-gif/rust-strength-app) ·
[Project page](https://lindellrhett-gif.github.io/rust-strength.html)

#### 🥫 [Shelfsmith](https://lindellrhett-gif.github.io/shelfsmith.html): in development

A shared-pantry app that shows what you can cook with what you already have.

- **Receipt scanning:** the Claude API reads receipts through a server-side
  Edge Function, and the user reviews every line.
- **Recipe matching:** a single SQL query matches recipes against the
  household's pantry.
- **Live household sync** with Supabase Realtime.
- **Subscriptions** through a RevenueCat webhook.
- **Database tests** that run the real migrations in PGlite.

`TypeScript` `React Native` `Supabase Edge Functions` `Realtime` `Claude API` `RevenueCat`

[Source](https://github.com/lindellrhett-gif/cooking-app) ·
[Project page](https://lindellrhett-gif.github.io/shelfsmith.html)

---

#### 🧰 Tools I use

- **Languages:** TypeScript, JavaScript, SQL (PostgreSQL, PL/pgSQL), HTML, CSS
- **Mobile:** React Native, React, Expo, Expo Router, TanStack Query
- **Backend and security:** Supabase, PostgreSQL, Row Level Security, Auth,
  Edge Functions, Realtime, webhooks
- **Testing and shipping:** Jest, PGlite, ESLint, Git, EAS Build, TestFlight,
  App Store Connect
