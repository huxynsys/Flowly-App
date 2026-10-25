# DNotifier Guard security report
*schedular project · 10/24/2026, 10:21:45 PM · 9 files scanned*

**Security score: 0/100** — 3 critical, 2 high, 5 medium, 2 low

## Dependencies (12)
- **[CRITICAL] next@16.3.5: Next.js: Unauthenticated Remote Code Execution in Image Optimization API when SVG files are used** — `flowlly-app/package.json:15`
  - GHSA-2464-fhr4-w9xw affects the locked version (16.3.5).
  - Fix: Upgrade next to 15.5.28 or later.
- **[CRITICAL] next@16.3.5: Next.js: Unauthenticated Remote Code Execution in `use cache` functions returning typed arrays** — `flowlly-app/package.json:15`
  - GHSA-673q-mjm6-r5xr affects the locked version (16.3.5).
  - Fix: Upgrade next to 16.4.1 or later.
- **[CRITICAL] next@16.3.5: Next.js: Remote Code Execution in next/og ImageResponse** — `flowlly-app/package.json:15`
  - GHSA-vcvr-r3jv-pc5j affects the locked version (16.3.5).
  - Fix: Upgrade next to 16.3.6 or later.
- **[HIGH] next@16.3.5: Next.js has Server-Side Request Forgery in Image Optimization** — `flowlly-app/package.json:15`
  - GHSA-cjq9-62q9-8jv4 (CVE-2026-94483) affects the locked version (16.3.5).
  - Fix: Upgrade next to 16.3.8 or later.
- **[HIGH] next@16.3.5: Next.js: Denial of Service in App Router using Server Actions** — `flowlly-app/package.json:15`
  - GHSA-p3m5-59mp-jv5r (CVE-2026-94482) affects the locked version (16.3.5).
  - Fix: Upgrade next to 15.5.28 or later.
- **[MEDIUM] next@16.3.5: Next.js: Pending `use cache` fill can leak Draft Mode content into regular responses and persisted pages** — `flowlly-app/package.json:15`
  - GHSA-3w37-wq28-93x7 (CVE-2026-94544) affects the locked version (16.3.5).
  - Fix: Upgrade next to 16.3.8 or later.
- **[MEDIUM] next@16.3.5: Next.js has cache poisoning of SSG and ISR pages in self-hosted applications** — `flowlly-app/package.json:15`
  - GHSA-4jqv-mc3x-m676 (CVE-2026-94543) affects the locked version (16.3.5).
  - Fix: Upgrade next to 15.5.27 or later.
- **[MEDIUM] next@16.3.5: Next.js has information disclosure in App Router metadata image routes via dynamicParams bypass** — `flowlly-app/package.json:15`
  - GHSA-f87g-xv8r-7p7x (CVE-2026-94485) affects the locked version (16.3.5).
  - Fix: Upgrade next to 16.3.8 or later.
- **[MEDIUM] next@16.3.5: next.js cache leak across root param values in nested 'use cache' functions** — `flowlly-app/package.json:15`
  - GHSA-h694-7cp9-m8p3 (CVE-2026-103004) affects the locked version (16.3.5).
  - Fix: Upgrade next to 16.3.8 or later.
- **[MEDIUM] next@16.3.5: Next.js has cache poisoning in SSG/ISR rendering that leads to cross-user content substitution and persistent denial of service** — `flowlly-app/package.json:15`
  - GHSA-mcj8-r9mp-w47p (CVE-2026-94484) affects the locked version (16.3.5).
  - Fix: Upgrade next to 15.5.27 or later.
- **[LOW] next@16.3.5: Next.js has information disclosure in development server's Model Context Protocol endpoint** — `flowlly-app/package.json:15`
  - GHSA-39w2-rjm5-chcv (CVE-2026-94486) affects the locked version (16.3.5).
  - Fix: Upgrade next to 16.3.8 or later.
- **[LOW] eslint@9.39.5 is deprecated** — `flowlly-app/package.json:24`
  - Maintainer notice: This version is no longer supported. Please see https://eslint.org/version-support for other options.
  - Fix: Migrate to the recommended replacement.
