# 100 Websites, Forums, and Blogs Every IT Engineer Should Follow

[中文](README.zh-CN.md) | English

> Also published on my blog: [100 Websites, Forums, and Blogs Every IT Engineer Should Follow (General Edition)](https://leekairos.com/en/p/100-websites-it-engineers-should-follow/)

An engineer's technical horizon is half decided by what they read every day.

Building a personal knowledge system usually has three stages: input, processing, output.

If you think of a knowledge system as a production line, input is the raw material at the source. The quality of what flows into your view every day sets the ceiling on your later thinking and the sharpness of your technical judgment. This list won't talk about complicated note-taking methods or output-driven input — it focuses on the most basic and most important first layer: where should your daily technical information come from?

To save you the time of sifting through the sand, I distilled a general list of 100 core sources from several hundred candidate tech sites.

#### What makes this list different?

- **Broad coverage, no blind spots**: it spans frontend, backend, mobile, data, cloud-native, security, and AI. It isn't limited to one specialty — whatever your stack, you can pick your own core sources from it. (I also put together a personal edition of 71 sources filtered along a single stack — I'll share it later for reference.)

- **Strict inclusion criteria**: every site had to pass all four of these tests, no exceptions — no matter how famous:

1. **Stays updated**: active, not a dead site.

2. **Genuinely deep content**: no clickbait or reposts.

3. **Covers a mainstream stack**: broadly useful in real engineering practice.

4. **Free to read**: no paywall in the way of daily reading.

#### How to use this list?

To avoid information overload, I split the 100 sources into three tiers by reading frequency and use:

- **S tier · Must follow (25)** : the high signal-to-noise core. Read them on a fixed schedule, daily or weekly.

- **A tier · Main sources (59)** : the deep waters of each field. Subscribe by your current direction.

- **B tier · Search-only (16)** : mostly references and deep dives. Don't subscribe or scroll — search them when debugging, choosing tools, or researching.

#### Language and subscriptions

- **Language**: first-hand tech news is still mostly in English, so the list has about **79 English sources**, **19 Chinese sources**, and **2 bilingual ones**.

- **Subscriptions**: the links below are all official homepages. Most natively support RSS — grab them with whatever reader you use (Feedly, Inoreader, Follow, and so on); feed addresses aren't listed one by one here.

Next, let's walk through the list tier by tier, direction by direction.

---

## How to use it (matters more than the list)

The list itself doesn't matter. What matters is how it flows into your knowledge system. My approach is to treat these 100 as the intake, managed in three tiers:

1. **Daily, ≤15 minutes**: only the daily reads in S tier — Hacker News top stories, Solidot, daily.dev, Ruan Yifeng's Weekly (weekly), SRE Weekly / Postgres Weekly / DB Weekly (on arrival day). Open no more than 3 articles.
2. **Weekend, 30 minutes**: sweep A tier by your direction — cover your main direction fully, skim the titles of the rest. Save good articles to read later; don't deep-read on the spot.
3. **B tier is search-only, forever**: the right way to use Stack Overflow / Server Fault / CSDN / Zhihu is to search them with "the exact error message + site name". Scrolling their homepages is a waste of time.
4. **Forum red lines**: V2EX, LinuxDo, Reddit — read titles and hot posts only, never join the flame wars; Zhihu — search only, never subscribe to the feed.
5. **Clean up every three months**: anything in S/A you haven't opened in three months gets demoted or deleted. Subscriptions only shrink, never grow.
6. **English sources are the primary source**: English sources like HN, SRE Weekly, and Simon Willison update weeks before Chinese translations appear — reading the English original is the fastest way.

---

## S tier · Start with these 25 (if you're short on time, read only this section)

This is the daily input layer: 25 sources, checked daily or weekly. When you're short on time, this section alone is enough.

|#|Name|Language / Type|URL|Why it's essential|
| ----| ------------------------------| -------------------------------| -----------------------------------------------------------| ---------------------------------------------------------------------------------------------------------------------|
|1|Hacker News|English · Forum / News|https://news.ycombinator.com|The global programmer weather vane, source of AI/open-source/startup topics; huge volume — scan top stories only|
|2|Stack Overflow|English · Q&A Forum|https://stackoverflow.com|First stop for debugging — search here first for any error|
|3|GitHub Blog + Trending|English · Official / Ranking|https://github.blog / https://github.com/trending|Platform news (Copilot/Actions/security) + the open-source trending list — where to find tools and building blocks|
|4|Reddit (tech subreddits)|English · Forum|https://www.reddit.com|Subscribe to subreddits only: r/programming, r/devops, r/sysadmin, r/webdev, r/learnprogramming|
|5|Lobsters|English · Forum|https://lobste.rs|More hardcore than HN — a higher share of deep systems/database/language pieces|
|6|daily.dev|English · Aggregator|https://daily.dev|A developer news aggregator homepage, a replacement for checking many sites|
|7|Dev.to|English · Community|https://dev.to|English developer writing community, many tutorials and career posts|
|8|Ruan Yifeng's Weekly|Chinese · Blog / Weekly|https://www.ruanyifeng.com/blog/|The steadiest weekly in the Chinese tech world — one issue beats a day of scrolling Weibo|
|9|Solidot|Chinese · News|https://www.solidot.org|Long-running Chinese tech news site, mostly open source/science/security — scannable in 30 seconds|
|10|SSPAI|Chinese · News|https://sspai.com|The first stop in Chinese for productivity tools, gadgets, and workflows|
|11|Juejin|Chinese · Forum / Library|https://juejin.cn|A library of Chinese frontend and AI engineering articles — use it as a library, don't scroll the feed|
|12|InfoQ (Chinese / English)|Chinese + English · News|https://www.infoq.cn / https://www.infoq.com|Architecture and AI engineering media — the two editions complement each other|
|13|Ars Technica|English · News|https://arstechnica.com|Solid English tech reporting — policy, security, and science|
|14|freeCodeCamp|English · Tutorials|https://www.freecodecamp.org|Full programming courses, free — one course, one complete system|
|15|MDN Web Docs|English · Official Docs|https://developer.mozilla.org|The authoritative reference for web standards and best practices|
|16|roadmap.sh|English · Learning Roadmaps|https://roadmap.sh|Roadmaps for every direction — frontend, backend, DevOps, AI — one chart shows what to learn|
|17|Kubernetes Blog|English · Official Blog|https://kubernetes.io/blog/|The official word on K8s releases, KEPs, and case studies|
|18|CNCF Blog|English · Official Blog|https://www.cncf.io/blog/|The full cloud-native picture: a radar for Prometheus/Argo/Backstage choices|
|19|Docker Blog|English · Official Blog|https://www.docker.com/blog|Container and image best practices — cloud-native basics|
|20|OpenAI News + Anthropic News|English · Official Blogs|https://openai.com/news/ / https://www.anthropic.com/news|Releases and API changes from the two model makers — the upstream change log for AI apps|
|21|Hugging Face Blog|English · Official Blog|https://huggingface.co/blog|The open-model ecosystem: new models, datasets, and deployment practice|
|22|Simon Willison|English · Personal Blog|https://simonwillison.net|The most subscribable personal blog on applied LLM engineering — extremely high practical density|
|23|Julia Evans (jvns)|English · Personal Blog|https://jvns.ca|Explains Linux, networking, and debugging better than anyone|
|24|Martin Fowler|English · Personal Blog|https://martinfowler.com|The living dictionary of software architecture and refactoring|
|25|LWN.net|English · News / Weekly|https://lwn.net|The most authoritative weekly on the Linux kernel and open-source ecosystem|

---

## 1. General news & trends (10 beyond S tier)

|Name|Language / Type|Tier|URL|Use|
| ---------------------| ---------------------------------| ------| -----------------------------| -------------------------------------------------------------------------------------------------|
|BestBlogs|Chinese + English · Aggregator|A|https://www.bestblogs.dev|A curated pick of quality blogs in Chinese and English — one source stands in for twenty blogs|
|TechCrunch|English · News|A|https://techcrunch.com|Tech startups and funding news — read the industry's direction|
|DZone|English · Community / News|A|https://dzone.com|A broad developer article aggregator — a practical library|
|The New Stack|English · News|A|https://thenewstack.io|Cloud-native and engineering-culture news, architecture-leaning|
|Stack Overflow Blog|English · Official Blog|A|https://stackoverflow.blog|The platform's own blog: developer surveys, engineering culture, and AI topics|
|Product Hunt|English · Ranking|B|https://www.producthunt.com|The daily ranking of new products worldwide — product trends and ideas|
|The Verge|English · News|B|https://www.theverge.com|Consumer tech and product coverage — scan the headlines|
|iFanr|Chinese · News|B|https://www.ifanr.com|Consumer tech and product observation — complements SSPAI|
|36Kr|Chinese · News|B|https://36kr.com|Chinese tech-business news — funding and industry moves|
|IT Home|Chinese · News|B|https://www.ithome.com|Chinese tech flash news — new hardware, software, and industry news|

## 2. Forums / Q&A / Communities (10 beyond S tier)

|Name|Language / Type|Tier|URL|Use|
| ---------------------| ----------------------| ------| -------------------------------| ------------------------------------------------------------------------------------------------------------------------------------------|
|V2EX|Chinese · Forum|A|https://www.v2ex.com|A Chinese developer community — a folk thermometer for indie dev and market conditions|
|LinuxDo|Chinese · Forum|A|https://linux.do|A Chinese developer / AI-tools community, dense with resource posts — search, don't scroll|
|Server Fault|English · Q&A|A|https://serverfault.com|The Stack Overflow for ops: Linux/network/server debugging|
|DBA Stack Exchange|English · Q&A|A|https://dba.stackexchange.com|The dedicated database Q&A site|
|Hashnode|English · Community|A|https://hashnode.com|A developer writing and blogging community, many English tech articles|
|SegmentFault|Chinese · Q&A|B|https://segmentfault.com|A supplementary Chinese tech Q&A source — uneven quality, cross-check|
|CSDN|Chinese · Library|B|https://www.csdn.net|Use it only as a legacy library to search (old errors and old-version material are all there) — don't scroll, don't trust a single post|
|Zhihu (tech topics)|Chinese · Community|B|https://www.zhihu.com|Search only, don't subscribe: long answers on system design and career choices have lasting value|
|OSChina|Chinese · Community|B|https://www.oschina.net|Chinese open-source project news — scan the titles|
|Super User|English · Q&A|B|https://superuser.com|General computing Q&A: system, software, and hardware puzzles|

## 3. Databases (8 beyond S tier)

|Name|Language / Type|Tier|URL|Use|
| -----------------------------| ----------------------------| ------| ---------------------------------------------------| -------------------------------------------------------------------------------------------|
|Planet PostgreSQL|English · Blog Aggregator|A|https://planet.postgresql.org|The official PostgreSQL community aggregator|
|Percona Blog|English · Blog|A|https://www.percona.com/blog/|Open-source database practice: MongoDB/MySQL/PostgreSQL tuning and incident write-ups|
|Postgres Weekly + DB Weekly|English · Newsletters|A|https://postgresweekly.com / https://dbweekly.com|Two newsletters cover a week of PostgreSQL and the whole database world|
|Planet MySQL|English · Blog Aggregator|A|https://planet.mysql.com|The official MySQL ecosystem aggregator|
|MongoDB Blog|English · Official Blog|A|https://www.mongodb.com/blog|MongoDB official: new features, performance, and architecture cases|
|ClickHouse Blog|English · Official Blog|A|https://clickhouse.com/blog|Columnar database features and performance tips|
|Modb.pro|Chinese · Community|A|https://www.modb.pro|A Chinese database community: domestic databases, Oracle, and PostgreSQL articles and Q&A|
|DB-Engines Ranking|English · Ranking|B|https://db-engines.com|Database popularity rankings — check trends when choosing a database|

## 4. Cloud, DevOps & SRE (12 beyond S tier)

|Name|Language / Type|Tier|URL|Use|
| -------------------------------------| ---------------------------| ------| -------------------------------------------------------------------------| ----------------------------------------------------------------------------------------------------------|
|SRE Weekly|English · Newsletter|A|https://sreweekly.com|The global SRE weekly: incident write-ups, observability, on-call culture|
|AWS News Blog + Architecture Blog|English · Official Blogs|A|https://aws.amazon.com/blogs/aws/|AWS service launches + architecture practice|
|Azure Blog + Google Cloud Blog|English · Official Blogs|A|https://azure.microsoft.com/en-us/blog/ / https://cloud.google.com/blog|New services and architecture cases from the other two big clouds|
|Last Week in AWS|English · Newsletter|A|https://www.lastweekinaws.com|The snarky AWS weekly — filters a week of launches down to what matters|
|HashiCorp Blog|English · Official Blog|A|https://www.hashicorp.com/blog/|Terraform/Vault official — IaC best practices|
|Cloudflare Blog|English · Official Blog|A|https://blog.cloudflare.com|Deep posts on networking, edge, and security engineering|
|Netflix Tech Blog|English · Official Blog|A|https://netflixtechblog.com|The reliability/chaos-engineering benchmark — interview story material|
|Meta Engineering + Uber Engineering|English · Official Blogs|A|https://engineering.fb.com / https://www.uber.com/blog/engineering/|Engineering write-ups from two big tech companies: scale, performance, and org|
|Charity Majors|English · Personal Blog|A|https://charity.wtf|The observability evangelist (Honeycomb CTO) — the source of high-frequency SRE concepts|
|Grafana Labs Blog|English · Official Blog|A|https://grafana.com/blog/|Observability practice: monitoring, logs, and alerting|
|DevOps Weekly|English · Newsletter|A|https://www.devopsweekly.com|The DevOps weekly: tools, culture, and practice|
|Dan Luu|English · Personal Blog|B|https://danluu.com|Hardcore long reads on hardware, performance, and debugging — infrequent, high quality, weekend reading|

## 5. Backend & programming languages (12 beyond S tier)

|Name|Language / Type|Tier|URL|Use|
| ----------------------------------| -----------------------------------| ------| ----------------------------------------------------------------| -----------------------------------------------------------------------------------------------------------------|
|Go Blog + Golang Weekly|English · Official / Newsletter|A|https://go.dev/blog/ / https://golangweekly.com|Go's official evolution + the ecosystem's weekly picks|
|Real Python + Python Weekly|English · Tutorials / Newsletter|A|https://realpython.com / https://pythonweekly.com|The benchmark for leveling up Python engineering (testing, packaging, typing)|
|Rust Blog|English · Official Blog|A|https://blog.rust-lang.org|Rust language evolution and ecosystem news|
|Baeldung (Java/Spring)|English · Tutorials|A|https://www.baeldung.com|A hands-on tutorial library for Java and Spring — searchable and readable|
|TypeScript Blog|English · Official Blog|A|https://devblogs.microsoft.com/typescript|TypeScript releases and language features|
|Node.js Blog|English · Official Blog|A|https://nodejs.org/en/blog|Node.js releases and security notices|
|JavaScript Weekly|English · Newsletter|A|https://javascriptweekly.com|The week's picks from the JS/TS ecosystem|
|High Scalability|English · Blog|A|https://highscalability.com|The classic site dissecting big-tech system architecture — a living question bank for system design interviews|
|ByteByteGo|English · Newsletter / Blog|A|https://blog.bytebytego.com|Illustrated system design — a shortcut for system design interview prep|
|Baoyu's Blog|Chinese · Blog|A|https://baoyu.io|Curated Chinese editions of long overseas AI/engineering pieces|
|Coding Horror / Joel on Software|English · Personal Blogs|B|https://blog.codinghorror.com / https://www.joelonsoftware.com|Classics of software engineering culture — infrequent, every piece worth reading|
|CoolShell|Chinese · Personal Blog|B|https://coolshell.cn|Classic programming and career essays — read the archive, no longer updated|

## 6. Frontend & mobile (10 beyond S tier)

|Name|Language / Type|Tier|URL|Use|
| -------------------------| --------------------------| ------| -------------------------------------------| --------------------------------------------------------------------------------|
|web.dev|English · Official Docs|A|https://web.dev|Google's web development guide: performance, accessibility, and best practices|
|CSS-Tricks|English · Blog|A|https://css-tricks.com|The long-running CSS and frontend tricks site — search it often|
|Smashing Magazine|English · Blog|A|https://www.smashingmagazine.com|Deep frontend and design long reads, steady quality|
|Frontend Focus|English · Newsletter|A|https://frontendfoc.us|The week's frontend picks: articles, tools, and new libraries|
|React Blog|English · Official Blog|A|https://react.dev/blog|React releases and new features|
|Vue.js Blog|English · Official Blog|A|https://blog.vuejs.org|Vue's official news and release notes|
|Android Developers Blog|English · Official Blog|A|https://android-developers.googleblog.com|Android official: new APIs, tools, and best practices|
|iOS Dev Weekly|English · Newsletter|A|https://iosdevweekly.com|The week's iOS development picks|
|React Native Blog|English · Official Blog|A|https://reactnative.dev/blog|React Native releases and architecture evolution|
|Can I Use|English · Tool|B|https://caniuse.com|Check browser compatibility — the reference book every frontend dev needs|

## 7. AI & data (8 beyond S tier)

|Name|Language / Type|Tier|URL|Use|
| ----------------------------| ---------------------------------| ------| ------------------------------------| ----------------------------------------------------------------------------------------------|
|Google AI Blog|English · Official Blog|A|https://blog.google/technology/ai/|Google's AI research and product news|
|Latent Space|English · Podcast / Newsletter|A|https://www.latent.space|The top newsletter in the AI engineer circle — the highest concentration of AI infra topics|
|Lilian Weng|English · Personal Blog|A|https://lilianweng.github.io|Survey masterpieces on agents, RL, and LLMs — textbook-grade pieces|
|Chip Huyen|English · Personal Blog|A|https://huyenchip.com|ML/LLM system design — on point for AI job interviews|
|Import AI (Jack Clark)|English · Newsletter|A|https://importai.substack.com|The AI policy and research weekly — the big picture and regulatory winds|
|Towards Data Science|English · Community|A|https://towardsdatascience.com|A library of data science and machine learning articles|
|Jiqizhixin (Machine Heart)|Chinese · News|A|https://www.jiqizhixin.com|Chinese AI research and industry media — steady paper coverage|
|QbitAI|Chinese · News|B|https://www.qbitai.com|Chinese AI industry flash news — scan headlines to track domestic models|

## 8. Security (5)

|Name|Language / Type|Tier|URL|Use|
| ---------------------------------| -----------------------------| ------| -------------------------------------------------------| --------------------------------------------------------------------------------------|
|Krebs on Security|English · Blog|A|https://krebsonsecurity.com|The ceiling of security news investigation|
|Schneier on Security|English · Personal Blog|A|https://www.schneier.com|The doyen of cryptography and security policy — mostly short posts|
|Troy Hunt / Have I Been Pwned|English · Blog / Tool|A|https://www.troyhunt.com / https://haveibeenpwned.com|Data breach tracking + check whether your own email was leaked|
|The Hacker News (security news)|English · News|A|https://thehackernews.com|Fast updates on vulnerabilities and attacks (different from YC's Hacker News)|
|FreeBuf|Chinese · News / Community|A|https://www.freebuf.com|The home ground of Chinese security media — vulnerabilities and attack/defense news|

---

## Sorted again by "what to do" (the wall version)

- **Open daily (≤15 minutes)** : Hacker News top stories, Solidot, daily.dev, Ruan Yifeng's Weekly (weekly), SRE Weekly / Postgres Weekly / DB Weekly (on arrival day)
- **Open weekly (30 minutes on the weekend)** : pick 5–8 fixed reads from A tier by your main direction — e.g., backend reads the Go/Python weeklies, frontend reads Frontend Focus, cloud-native reads CNCF/Docker, AI reads Latent Space
- **Search-only, forever**: Stack Overflow, Server Fault, DBA SE, SegmentFault, CSDN, Zhihu, Super User, Can I Use, DB-Engines
- **Open only when something happens**: Krebs, The Hacker News, FreeBuf, Have I Been Pwned (check the facts when there's a leak, a vulnerability, or a security incident)

## How to filter your own core layer from this list

- Start with the 25 in S tier. After two weeks, keep the ones you actually open and demote the rest.
- Then pick 3–5 from A tier per direction — frontend, backend, data, cloud-native, AI — take what you need, don't subscribe to everything.
- B tier needs no subscription. Search it when you need it.
- Review every three months: anything unopened for three months gets demoted or deleted. Subscriptions only shrink.
- Your main direction is different, so your S tier will be different too — use this tiering method to draw a core layer from your own collection. That's more useful than copying these 100.

---

## Closing: A list is only a starting point — judgment is the destination

That covers all 100 sources, spanning frontend, backend, mobile, data, cloud-native, security, and AI.

One last personal thought: **a list is only ever a starting point, never the destination.**

If our daily technical input and engineering output are a river, information sources are the upstream. The quality of the water upstream largely decides what kind of code, architecture, and thinking comes out downstream. In an age of information overload, actively filtering your sources is essentially building a firewall for your own technical horizon.

But at the same time, no ready-made list can replace your own judgment. With information exploding everywhere, saved-but-never-read collections are the norm — what actually sets people apart is rarely how many sources they subscribe to, but how well they digest and apply what they read.

To me, the test for a good source is actually very simple — just one question: after reading it, are the things you write, the incidents you fix, and the choices you make actually any better?

If yes, keep it and keep following it. If not, drop it without hesitation — no matter how famous it is or how many people recommend it.

I hope this list becomes a stepping stone for building your own technical information flow. And feel free to share your own hidden-gem sources via Issues or Pull Requests — let's keep adding to it and iterating together, so the water upstream stays clear.

---

## Contributing

Found a better source, or a dead link? You are welcome to:

- Open an [Issue](../../issues) to recommend a high-quality source you use
- Send a [Pull Request](../../pulls) to add or fix an entry

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and share.

Last updated: 2026-11-21
