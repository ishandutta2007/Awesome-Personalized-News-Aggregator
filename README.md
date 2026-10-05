# Awesome-Personalized-News-Aggregator

## Top Personalized News Aggregator Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Algorithmic Curation, RSS Reading & Self-Hosted Feed Management*  

**Last updated: October 2026**



This repository tracks notable **commercial news aggregators** and **open-source projects** that personalize news consumption — from algorithmic feeds and AI summaries to self-hosted RSS readers with full user control over sources and ranking.



**Examples** include Microsoft Start, Google News, Apple News, Flipboard, SmartNews, Pocket, Feedly, NewsBreak, Inoreader, and Artifact (the category leaders).



**Open-source emphasis**: Personalized news aggregation is a strong open-source domain. **FreshRSS**, **Miniflux**, **CommaFeed**, and **Tiny Tiny RSS** provide mature self-hosted readers with full source control. **RSSHub** generates feeds for sites that don't offer them. **Feedly alternatives** like **Fever** and **NewsBlur** offer API-compatible self-hosting. AI-powered curation is emerging with **HackerNews AI** and **Brief** summarizing feeds. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

**Market Size & Sector Structure**: The global news aggregator market is estimated at **~$14.8 Billion to $15.0 Billion (2025/2026)** and is projected to reach **~$29.8 Billion by 2033** (CAGR ~9.1%). The sector is **moderately to highly fragmented**: mass-consumer news portals are dominated by big-tech giants, while niche content curation, power-user RSS reading, and AI feed summarization are distributed across specialized commercial platforms and self-hosted open-source tools.

| Product / Platform | Description & Key Features | Pricing (Starting Paid Tier) | Free Tier Limit | Company Size / Valuation / Revenue |
| :--- | :--- | :--- | :--- | :--- |
| **[Apple News](https://www.apple.com/apple-news/)** | Curated news combining human editors and algorithmic personalization. Apple News+ adds digital magazines and premium audio stories. | **$12.99/month** (Apple News+ standard individual subscription) | Free app with select article previews; 1-month free trial for Apple News+ (3 months with eligible new Apple device) | **~$3.84 Trillion - $4.98 Trillion** Market Cap *(Apple Inc.)* |
| **[Microsoft Start](https://www.msn.com/)** | Windows, Edge, and MSN-integrated content aggregator delivering personalized news, weather, and trending topics. | **Free** (Ad-supported, no paid premium tier) | Unlimited ad-supported web/mobile feed access (no custom RSS feed imports) | **~$3.84 Trillion** Market Cap *(Microsoft Corp.)* |
| **[Google News](https://news.google.com/)** | Algorithmic AI-powered news clustering, topic following, and local coverage spanning news publishers across 125+ countries. | **Free** (Ad-supported, no paid premium tier) | Unlimited ad-supported personalized feed access and search (no ad-free plan or feed import) | **~$2.10 Trillion - $2.50 Trillion** Market Cap *(Alphabet Inc.)* |
| **[SmartNews](https://www.smartnews.com/)** | Machine-learning news discovery platform focused on quality journalism, "Smart" channels, and local news delivery. | **Free** (Ad-supported, no paid premium tier) | Unlimited ad-supported article reading and offline channel browsing | **$2.0 Billion** Valuation (~$104.5M Annual Revenue; ~500 employees) |
| **[Flipboard](https://flipboard.com/)** | Magazine-style aggregation platform allowing users to curate custom digital "Magazines" from any Web/RSS source. | **Free** (Ad-supported, creator referral ad revenue sharing) | Unlimited magazine creation, curation, and reading with no reader paywalls | **$1.3 Billion** Valuation (~$34M - $71M Annual Revenue; ~150 employees) |
| **[NewsBreak](https://www.newsbreak.com/)** | AI-driven hyperlocal news aggregator connecting local content creators and publishers with U.S. community readers. | **Free** (Ad-supported, no paid premium tier) | Unlimited hyper-local news feed access and community contributor posts | **$1.0 Billion** Valuation (~$100M Annual Revenue; ~350 employees) |
| **[Pocket](https://getpocket.com/)** | Save-for-later article reader and discovery service (*Service officially shut down by Mozilla on July 8, 2025*). | **Discontinued** ($4.99/month or $44.99/year prior to July 2025 shutdown) | Service Shutdown (Export-only window concluded Nov 12, 2025; historically unlimited article saving) | **~$600 Million** Annual Revenue *(Mozilla Corp parent; acquired Pocket for ~$30M)* |
| **[Feedly](https://feedly.com/)** | Leading commercial RSS reader featuring AI assistant ("Leo") for feed deduplication, keyword filtering, and team boards. | **$6.00/month** (Billed annually at $72/yr for Pro tier; Pro+ with AI at $12.99/mo) | Up to 100 RSS sources across 3 folders max (no AI filtering, power search, or integrations) | **~$7 Million - $10 Million** ARR (Bootstrapped private company; ~60 employees) |
| **[Inoreader](https://www.inoreader.com/)** | Power-user RSS reader featuring automation rules, keyword monitoring, newsletter feeds, and WebSub push updates. | **$7.50/month** (Billed annually at $90/yr for Pro tier; $9.99/mo monthly) | Up to 150 RSS subscriptions, 20 newsletter feeds, and 20 web feeds (ad-supported) | **~$1 Million - $2 Million** ARR (Bootstrapped Innologica Ltd; ~10 employees) |




## Open-Source GitHub Projects



- **[FreshRSS](https://github.com/FreshRSS/FreshRSS)**  

  **The leading self-hosted RSS aggregator**, AGPL-3.0 licensed with **8,000+ GitHub stars** . **Supports WebSub, XPath scraping for sites without feeds, OPML import/export, and multi-user with per-user feed management** . **Docker deployment** and extensive themes/plugins . **The most widely adopted open-source Google Reader replacement** — mature, actively maintained, and feature-complete . **Best for self-hosted news aggregation with full control** .



- **[Miniflux](https://github.com/miniflux/v2)**  

  **Minimalist, opinionated RSS reader**, Apache-2.0 licensed with **7,000+ GitHub stars** . **Go-based single binary with PostgreSQL** . **Deliberately minimal** — focused on reading, not features . **Supports Fever and Google Reader APIs for mobile app compatibility** (Reeder, Unread) . **The fastest, simplest self-hosted reader** . **Best for users wanting speed over feature breadth** .



- **[CommaFeed](https://github.com/Athou/commafeed)**  

  **Self-hosted Google Reader-inspired RSS reader**, Apache-2.0 licensed . **Java backend with Angular frontend** . **Lightweight and simple** — closer to original Google Reader than FreshRSS . **Docker deployment** . **Best for users wanting a familiar Google Reader experience** .



- **[Tiny Tiny RSS](https://git.tt-rss.org/fox/tt-rss)**  

  **Veteran self-hosted RSS reader** (since 2005), GPL-3.0 licensed . **Plugin architecture, filters, and mobile apps** . **Highly extensible** — custom scoring, filters, and integrations . **Best for power users wanting deep customization** .



- **[RSSHub](https://github.com/DIYgod/RSSHub)**  

  **The most important open-source feed generator**, MIT licensed with **39,000+ GitHub stars** . **Generates RSS feeds for websites that don't offer them** — Weibo, Bilibili, YouTube, Twitter/X, Telegram, and **1,000+ sources** . **Self-hostable or use public instances** . **The essential companion to any self-hosted reader** . **Best for following modern sites without RSS** .



- **[RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge)**  

  **Companion to RSSHub** — PHP bridges for sites without RSS . **200+ bridges** . **Best for additional feed generation** .



- **[NewsBlur](https://github.com/samuelclay/NewsBlur)**  

  **Open-source RSS reader with commercial hosting**, MIT licensed . **Intelligence filtering, story training, and social sharing** . **The most feature-complete open-source reader with a hosted option** . **Best for users wanting a polished commercial-grade open-source reader** .



- **[Feedbin](https://github.com/feedbin/feedbin)**  

  **Open-source RSS reader powering the commercial Feedbin service**, MIT licensed . **Advanced filtering, save-for-later, and newsletter support** . **Best for users wanting a modern RSS reader with a hosted option** .



- **[Fever](https://github.com/k976/fever)**  

  **Self-hosted RSS reader with API compatibility**, MIT licensed . **The original API-compatible reader** — many mobile apps support Fever . **Best for mobile app compatibility with self-hosted backend** .



- **[Yarr](https://github.com/nkanaev/yarr)**  

  **Simple, minimal RSS reader in Go**, MIT licensed . **Single binary with embedded SQLite** . **Extremely lightweight** — starts instantly . **Best for Raspberry Pi and low-resource environments** .



- **[Selfoss](https://github.com/fossar/selfoss)**  

  **Multi-purpose RSS reader, live stream, and mashup aggregator**, GPL-3.0 licensed . **PHP-based with multiple feed types** (RSS, Atom, JSON, HTML scraping) . **Docker deployment** . **Best for aggregating heterogeneous sources** .



- **[Kriss Feed](https://github.com/tontof/kriss_feed)**  

  **Simple, lightweight PHP RSS reader**, GPL-3.0 licensed . **Minimalist and fast** — MySQL/SQLite . **Best for low-resource servers** .



- **[Leed](https://github.com/ldleman/Leed)**  

  **Self-hosted RSS aggregator with mobile-friendly interface**, GPL-3.0 licensed . **French-origin with clean UI and notification support** . **Best for users wanting a modern PHP reader** .



### AI-Powered Personalization (Emerging)



- **[HackerNews AI](https://github.com/hackernews-ai/hackernews-ai)**  

  **AI-powered Hacker News summarizer and personalizer**, open-source . **Summarizes stories and comments with LLMs** . **Best for tech news personalization** .



- **[Brief](https://github.com/brief-app/brief)**  

  **AI-powered RSS summarizer**, open-source . **Summarizes feeds with LLMs** . **Best for reducing information overload** .



- **[Feedly AI (Leo) alternatives](https://github.com/topics/feedly-alternative)**  

  Various open-source projects exploring AI-powered feed prioritization .



### Additional Strong Open-Source Options



- **Tiny Tiny RSS** — Veteran self-hosted reader with plugins .

- **Fever** — API-compatible reader for mobile apps .

- **NewsBlur** — Open-source reader with commercial hosting .

- **Feedbin** — Open-source reader with commercial hosting .

- **Yarr** — Minimal Go-based reader .

- **Selfoss** — Multi-source aggregator .

- **Kriss Feed** — Lightweight PHP reader .

- **Leed** — French-origin reader .

- **Stringer** — Self-hosted RSS reader (Ruby) .

- **Goeland** — CLI RSS to email/digest tool .



**Frameworks for building custom news aggregation solutions**: Combine **FreshRSS** for a full-featured self-hosted reader with plugin ecosystem . Use **Miniflux** for minimal, fast reading with API compatibility . Deploy **RSSHub** for generating feeds from sites without RSS . Choose **NewsBlur** or **Feedbin** for open-source readers with commercial hosting options . Use **Yarr** for lightweight, low-resource deployments . Integrate **HackerNews AI** or **Brief** for AI-powered summarization . Note that true commercial personalized news with algorithmic curation, cross-device sync, and editorial content (Google News, Apple News) remains primarily commercial territory; open-source stacks provide strong RSS aggregation, feed generation, and self-hosted reading foundations that require configuration for complete personalized news workflows.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- News aggregators may filter, rank, or editorialize content. **Self-hosted readers provide full user control** over sources and reading order — the primary reason to choose them over algorithmic portals .

- **RSSHub public instances may rate-limit or restrict access** — self-host for reliability .

- **Google Reader's shutdown in 2013** remains the canonical cautionary tale for relying on proprietary feed readers. Open-source self-hosted readers are immune to this risk .

- **AI summarization may introduce inaccuracies** — verify critical information from primary sources .

- The open-source ecosystem provides strong RSS aggregation, feed generation, and self-hosted reading foundations, but **algorithmic curation, cross-device sync, and editorial content** remain primarily commercial offerings.



---



**Made for RSS enthusiasts, privacy-conscious readers, and self-hosting advocates.**  

Let's make personalized news aggregation more open, transparent, and user-controlled.
