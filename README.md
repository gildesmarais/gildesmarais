# Moin, I'm Gil 👋

**Builder in Berlin. I take products from a fuzzy problem to shipped, then run them and own the result. Agents are part of how I ship.**

> 🟢 **Open to new roles:** Senior/Staff IC with direct ownership of outcomes. [Résumé](https://gil.desmarais.de/resume) · [Get in touch](https://gil.desmarais.de/contact)

At work I lead platform engineering for a health-tech product. That includes Rails, React Native, Go, infrastructure and compliance (ISO 27001, C5, GDPR), and the work cut platform-related customer complaints by about 80%. Below is what I build in the open.

![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-D30001?style=flat-square&logo=rubyonrails&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WASM-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-191919?style=flat-square&logo=anthropic&logoColor=white)

## Start here

- 📰 **[html2rss](https://github.com/html2rss)** — Turns any website into RSS or JSON Feed. It started as a Ruby gem and grew into an org: a [web app](https://github.com/html2rss/html2rss-web), a [config library](https://github.com/html2rss/html2rss-configs), a [CLI generator](https://github.com/html2rss/generator), a [headless scrape bridge](https://github.com/html2rss/botasaurus-scrape-api) and a [docs site](https://html2rss.github.io/). I run it in production for myself.
  ![gem stars](https://img.shields.io/github/stars/html2rss/html2rss?style=flat-square&label=gem) ![web stars](https://img.shields.io/github/stars/html2rss/html2rss-web?style=flat-square&label=web)
- 🎨 **[moodbar.rs](https://github.com/gildesmarais/moodbar.rs)** — Music visualisation in Rust from one core: CLI, WASM on npm, and native iOS/Android bindings. [Live demo →](https://gildesmarais.github.io/moodbar.rs/)
- 🤖 **[omnifocus-mcp](https://github.com/gildesmarais/omnifocus-mcp)** — An MCP server in Go that lets AI assistants read and edit OmniFocus. It's a single binary that runs locally and needs no account or API key.
- 🧰 **[dotfiles](https://github.com/gildesmarais/dotfiles)** — My macOS setup and the agent skills I use every day with Claude Code and Codex. They cover reviews, PRs, architecture and tickets.

🔒 Currently building a DJ-prep app: SwiftUI on a Rust core, with BPM and key detection, spectral features, and playlists that follow energy arcs. It's closed source.

## Upstream

I fix things where I find them:

- **ruby/ruby** — two fixes to the core `Set` class in C: [`Set#^` no longer mutates its argument](https://github.com/ruby/ruby/commit/b5604833a3) and [`compare_by_identity` is preserved across Set operations](https://github.com/ruby/ruby/commit/f069efc3f6) ([all commits](https://github.com/ruby/ruby/commits/master/set.c?author=gildesmarais))
- **whitequark/parser** — [accept UTF-8 string literals with non-UTF-8 byte escapes](https://github.com/whitequark/parser/pull/1097) (open)
- **yotarok/flacenc-rs** — [fixed-block encoding with a non-multiple tail frame](https://github.com/yotarok/flacenc-rs/pull/255) (merged), plus decode and deinterleave perf work ([#257](https://github.com/yotarok/flacenc-rs/pull/257), [#258](https://github.com/yotarok/flacenc-rs/pull/258), open)
- **kungfusheep/hue** (Philips Hue MCP server) — [sRGB gamma fix](https://github.com/kungfusheep/hue/pull/1) and [error surfacing](https://github.com/kungfusheep/hue/pull/2) (open). My [fork](https://github.com/gildesmarais/hue) has more.
- **navidrome/navidrome** — [respect `prefers-reduced-motion`](https://github.com/navidrome/navidrome/pull/2090) (merged)
- **fedy2/yahoo-weather-java-api** — [`java.net.Proxy` support](https://github.com/fedy2/yahoo-weather-java-api/pull/6) (merged, 2013 😄)

## Also built

**Ruby**
- [jekyll-loading-lazy](https://github.com/gildesmarais/jekyll-loading-lazy) — adds `loading="lazy"` with no JavaScript ![stars](https://img.shields.io/github/stars/gildesmarais/jekyll-loading-lazy?style=flat-square&label=%E2%98%85) *(legacy)*

**Early web culture**
- [The Shrine](https://github.com/svenpanel/the-shrine-ng) — a cult retro soundboard from the Adobe Flash era, brought back as a PWA so it survives Flash's end. [theshrine.pw →](https://theshrine.pw) ![stars](https://img.shields.io/github/stars/svenpanel/the-shrine-ng?style=flat-square&label=%E2%98%85)

**Infra**
- [ansible-5-minutes-server](https://github.com/gildesmarais/ansible-5-minutes-server) — a hardened Ubuntu server in five minutes *(legacy)*

**Small tools**
- [awesome-stars](https://github.com/gildesmarais/awesome-stars) — an auto-updated list of what I star
- [discogs-bulk-comment-field-userscript](https://github.com/gildesmarais/discogs-bulk-comment-field-userscript) — bulk-edits listing comments on Discogs *(legacy)*

## How I build

- **Outcomes are the scoreboard.** I measure work by the numbers it moves, not by tickets closed.
- **End to end.** Backend, mobile, infra, CI and on-call, all as one system.
- **Agents as leverage.** I write skills, rules and MCP servers so that agent-written code passes the same gates as mine.
- **Judgement over language.** I pick the stack that fits the problem: Ruby, Rust, Go, TypeScript or Swift.

## Elsewhere

[![Website](https://img.shields.io/badge/gil.desmarais.de-000?style=flat-square&logo=astro&logoColor=white)](https://gil.desmarais.de)
[![Blog](https://img.shields.io/badge/blog-555?style=flat-square)](https://gil.desmarais.de/blog)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gildesmarais/)
[![SoundCloud](https://img.shields.io/badge/SoundCloud-FF5500?style=flat-square&logo=soundcloud&logoColor=white)](https://soundcloud.com/gildesmarais)

Off-screen: music, film, movement. Cheers!

<img src="https://github-gil.goatcounter.com/count?p=/" alt="" width="1" height="1">
