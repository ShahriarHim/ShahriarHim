<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e2d3d,100:2563eb&height=200&section=header&text=Shahriar%20Him&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20Systems%20and%20Infrastructure&descAlignY=58&descSize=18&descColor=a8c5f0" width="100%" />

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=shahriarhim&label=Profile%20views&color=2563eb&style=flat" alt="profile views" />
  <img src="https://img.shields.io/badge/Open%20to%20Work-2563eb?style=flat&logo=circle&logoColor=white" />
</p>

<br>

<p align="center">
  Building production systems end-to-end — API design, RBAC, Redis caching, queue workers, and VM deployment.<br>
  BRACU CSE. Currently deepening into distributed systems, message brokers, and cloud infrastructure.
</p>

---

## 📈 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=shahriarhim&theme=nord&hide_border=true&bg_color=1e2d3d&color=4299e1&line=2563eb&point=ffffff&area=true" width="100%" />
</p>

---

## 🚀 What I've Shipped

### Hometex Bangladesh — Multi-project production system

Three codebases. One Laravel API. Built and deployed to a live VPS.

| Project | What it is | Stack |
|---|---|---|
| [hometex-api](https://github.com/ShahriarHim/hometex-api) | REST API shared by both frontends — 244 routes, 49 models, Spatie RBAC, R2 object storage | Laravel 10 · Sanctum · Redis · Cloudflare R2 |
| [hometex-ims](https://github.com/ShahriarHim/hometex-ims) | Admin dashboard — inventory, POS, orders, staff management, 19 modules, 53 permissions | React 18 · Vite · TanStack Query |
| [hometex-ecom](https://github.com/ShahriarHim/hometex-ecom) | Customer storefront — bilingual (EN/BN), cart, checkout, Steadfast courier | Next.js 16 · TypeScript · next-intl |

**Things I'm proud of in this system:**
- Unified user table with Spatie RBAC — 7 roles, 53 permissions, enforced on every route and reflected live in the frontend without logout
- Cache versioning in Redis — version counters instead of tag flushes; cache-aside across all read-heavy endpoints
- Stock ledger as signed-quantity audit table — current stock is always a `SUM()`, no running totals that can drift
- Two-phase R2 upload — storage write first, DB write second; rollback deletes the orphaned key
- Steadfast courier wrapped in `Throwable` catch — courier failure never blocks order placement

---

## 📡 What I'm Building Toward

| Area | What I'm doing |
|---|---|
| **Caching** | Redis, cache invalidation strategies, TTL vs. version-counter patterns |
| **Queues & Workers** | Laravel Horizon, Supervisor, async job processing |
| **Message Brokers** | RabbitMQ / Kafka patterns, event-driven architecture |
| **Cloud Infra** | Linux VM admin, Nginx, Supervisor, Ubuntu server provisioning |
| **Observability** | Sentry, UptimeRobot, health endpoints, structured logging |

---

## 🛠 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=laravel,php,react,nextjs,ts,js,mysql,redis&theme=dark&perline=8" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,python,mongodb,linux,nginx,figma,postman,git&theme=dark&perline=8" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shahriarhim&show_icons=true&hide_border=true&count_private=true&theme=nord&bg_color=1e2d3d&title_color=4299e1&icon_color=4299e1&text_color=cdd6f4" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=shahriarhim&layout=donut&hide_border=true&theme=nord&bg_color=1e2d3d&title_color=4299e1&text_color=cdd6f4" height="165" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=shahriarhim&theme=nord&hide_border=true&background=1e2d3d&ring=4299e1&fire=4299e1&currStreakLabel=4299e1" height="150" />
</p>

---

## 🔗 Connect

<p align="center">
  <a href="https://linkedin.com/in/shahriar-him" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://twitter.com/shahriarhim" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
  <a href="https://instagram.com/living__spirit" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
  <a href="https://fb.com/shahriarhim.froz3nf1re" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  </a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:1e2d3d&height=100&section=footer&animation=fadeIn" width="100%" />
