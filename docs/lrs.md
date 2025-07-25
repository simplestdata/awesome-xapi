# 🧱 Learning Record Stores (LRS) — Open-Source & Commercial

> A curated, non-exhaustive catalog of Learning Record Stores you can use with xAPI.  
> **Tip:** Always verify **current xAPI (1.0.3 / 2.0 IEEE 9274.1.1)** conformance on the **ADL xAPI Adopter Registry** before you buy or deploy.

---

## ✅ Quick “How to Choose” (at a glance)

- **I want OSS + full control:** Learning Locker CE, Yet Analytics **lrsql**, TRAX LRS, ADL LRS, OpenLRW.  
- **I want analytics & dashboards out of the box:** Watershed, Veracity, Learning Locker Enterprise, GrassBlade (with WordPress stack), SCORM Cloud (basic), RISC VTA.  
- **I need embedded/white-label in my product:** Rustici Engine LRS, Yet Analytics lrsql, Learning Locker EE, OpenLRW.  
- **I need to test cmi5 quickly:** SCORM Cloud LRS, Veracity LRS (Try LRS), ADL LRS sandbox (if available), TRAX one-click deploys.  
- **I’m in DoD/TLA worlds:** ADL LRS (reference), Veracity, Rustici (Engine / Cloud), Watershed, Learning Locker EE, Yet Analytics (plus their open TLA-aligned tooling).

---

## 🟩 Open-Source LRS (Self-host)

### 1) **Learning Locker® Community Edition**
- **Type:** Open source (GPL) + Enterprise (commercial)
- **Stack:** Node.js, MongoDB
- **Highlights:** Most widely adopted OSS LRS; UI for querying & dashboards; mature ecosystem.
- **Demo / Try:** Learning Pool offers cloud trials for EE; CE can be self-hosted quickly with Docker.
- **Repo / Docs:** https://github.com/LearningLocker/learninglocker  
- **Conformance:** Historically conformant; **verify current status on ADL Registry**.

---

### 2) **Yet Analytics – lrsql (aka SQL LRS)**
- **Type:** Open source (Apache 2.0)
- **Stack:** Clojure + SQL (Postgres, etc.)
- **Highlights:** Cloud-native, lightweight, easy to deploy many LRS instances; great for pipelines & edge “noisy” LRS use.
- **Demo / Try:** Docker images & quick-start guides.
- **Repo / Docs:** https://github.com/yetanalytics/lrsql  
- **Conformance:** Check ADL Registry.

---

### 3) **TRAX LRS (trax2)**
- **Type:** Open source (Starter) + commercial support
- **Stack:** PHP (Laravel), Vue.js; MySQL/MariaDB/Postgres/MongoDB
- **Highlights:** Straightforward to deploy; DigitalOcean one-click image; friendly UI.
- **Demo / Try:** Project docs provide quick setup and ADL test instructions.
- **Repo / Docs:** https://github.com/trax-project  
- **Conformance:** Check ADL Registry.

---

### 4) **ADL LRS (Reference Implementation / “Serenity”)**
- **Type:** Open source reference implementation
- **Stack:** Varies by generation (Node / Java)
- **Highlights:** Spec-aligned reference; great for learning & testing; often used with ADL’s test suites.
- **Demo / Try:** ADL sometimes hosts a public sandbox; otherwise self-host from source.
- **Repo / Docs:** https://github.com/adlnet  
- **Conformance:** Usually aligned to current spec drafts; **verify** if you need production-grade conformance.

---

### 5) **OpenLRW (Apereo Learning Record Warehouse)**
- **Type:** Open source (institutional analytics focus)
- **Stack:** Java, MongoDB / Postgres (varies)
- **Highlights:** **Multi-standard**: supports **xAPI, IMS Caliper, OneRoster**; built for higher-ed analytics hubs.
- **Demo / Try:** Run from source / Docker.
- **Repo / Docs:** https://github.com/Apereo-Learning-Analytics-Initiative/OpenLRW  
- **Conformance:** Check ADL Registry (it’s more of a warehouse than a strict xAPI LRS).

---

## 🟦 Commercial / SaaS LRS (or Enterprise Editions)

### 6) **Veracity Learning LRS (lrs.io)**
- **Type:** Commercial SaaS / on-prem
- **Highlights:** Early **xAPI 2.0 (IEEE)** conformance; rich admin UI; profile validation; attachments & signatures.
- **Demo / Try:** **“Try LRS”** (public sandbox).
- **Docs:** https://lrs.io / https://veracity.it  
- **Conformance:** Widely cited as 2.0-conformant — still **verify on ADL Registry**.

---

### 7) **Watershed LRS**
- **Type:** Commercial SaaS
- **Highlights:** Full analytics, dashboards, data blending & ROI stories; strong enterprise focus; deep case studies (AT&T, Caterpillar).
- **Demo / Try:** By request.
- **Docs:** https://www.watershedlrs.com  
- **Conformance:** Historically conformant; **verify**.

---

### 8) **Learning Locker® Enterprise (Learning Pool)**
- **Type:** Commercial SaaS / supported on-prem
- **Highlights:** Same core as LL CE + enterprise features (HA, pipelines, support, connectors, governance, SSO).
- **Demo / Try:** By request.
- **Docs:** https://learningpool.com/learning-locker/  
- **Conformance:** **Verify** on ADL Registry.

---

### 9) **GrassBlade LRS (Next Software Solutions)**
- **Type:** Commercial SaaS / on-prem
- **Highlights:** Deep **WordPress** ecosystem integrations (with GrassBlade xAPI Companion), LearnDash, LifterLMS, H5P, etc.; cmi5 support.
- **Demo / Try:** Public demo instances available.
- **Docs:** https://www.nextsoftwaresolutions.com/grassblade-lrs/  
- **Conformance:** **Verify** on ADL Registry.

---

### 10) **SCORM Cloud LRS (Rustici Software)**
- **Type:** Commercial SaaS (free tier available)
- **Highlights:** Easiest **“first LRS”** to test; cmi5 & xAPI launch; built-in statement viewer; great for developers.
- **Demo / Try:** **Free developer account**.
- **Docs:** https://scorm.com/scorm-solved/scorm-cloud/  
- **Conformance:** Historically conformant; **verify**.

---

### 11) **Rustici Engine (with LRS)**
- **Type:** Commercial embeddable component
- **Highlights:** OEM engine for LMS/LXPs supporting SCORM, xAPI, cmi5, AICC; includes an LRS component and launch services.
- **Demo / Try:** By request.
- **Docs:** https://rusticisoftware.com/products/engine/  
- **Conformance:** **Verify** (LRS component within Engine).

---

### 12) **RISC VTA / RISC LRS**
- **Type:** Commercial SaaS / on-prem (often paired with VTA LMS)
- **Highlights:** Long-time xAPI advocates; strong corporate compliance reporting; xAPI + cmi5 support.
- **Demo / Try:** By request.
- **Docs:** https://risc-inc.com  
- **Conformance:** **Verify**.

---

### 13) **Moodle Workplace (Built-in LRS)**
- **Type:** Commercial distribution of Moodle
- **Highlights:** Offers **embedded LRS**; pairs nicely with Moodle’s xAPI plugins for event streaming.
- **Demo / Try:** Through Moodle Partners.
- **Docs:** https://moodle.com/workplace/  
- **Conformance:** **Verify** (it’s an embedded LRS).

---

### 14) **Cornerstone, Meridian, Docebo, D2L (Embedded / Partnered LRS)**
- **Type:** Commercial LMS/LXPs with LRS inside or via partner (e.g., Rustici, Watershed, Learning Locker)
- **Highlights:** “Check the box” xAPI capture + enterprise analytics (often with partner LRS behind the scenes).
- **Demo / Try:** Vendor-specific.
- **Conformance:** **Verify** per vendor/partner.

---

### 15) **Learning Pool Stream (Data Cloud)**
- **Type:** Commercial data platform
- **Highlights:** LRS-backed data lake/warehouse patterns; tightly integrated with Learning Locker.
- **Demo / Try:** By request.
- **Docs:** https://learningpool.com

---

### 16) **Yet Analytics (Commercial Platform)**
- **Type:** Commercial analytics & data platform (in addition to OSS tools)
- **Highlights:** High-scale analytics, profile validation, TLA-aligned tooling, open-source + enterprise support.
- **Demo / Try:** By request.
- **Docs:** https://www.yetanalytics.com  
- **Conformance:** **Verify** if using their hosted/enterprise LRS.

---

## 🧪 Reference / Test Suites / Utilities

### 17) **ADL LRS Test Suite**
- **What it is:** The official open-source conformance test runner for LRSs.
- **Use it:** To verify your LRS meets the xAPI spec (1.0.3 & beyond) — also check for IEEE 9274 compatibility.
- **Repo / Docs:** https://github.com/adlnet

---

### 18) **ADL xAPI Adopter Registry**
- **What it is:** The canonical list of **conformant** tools (LRS, content, tools).
- **Use it:** To verify **actual conformance** claims made by vendors or OSS projects.
- **URL:** https://adopters.adlnet.gov (or current ADL site)

---

### 19) **Postman Collections & Statement Validators**
- **What it is:** Developer utilities to test xAPI endpoints & validate JSON statement structure.
- **Use it:** Faster dev cycles, repeatable smoke tests, documentation.

---

### 20) **DATASIM (Synthetic xAPI Data Generator)**
- **What it is:** Open-source simulator for massive xAPI data sets.
- **Use it:** Load-testing LRSs, prototyping analytics models, testing profile constraints at scale.
- **Repo / Docs:** https://github.com/yetanalytics/datasim

---
