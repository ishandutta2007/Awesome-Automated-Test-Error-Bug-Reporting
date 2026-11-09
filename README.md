# Awesome Automated Test, Error & Bug Reporting

A curated list of automated error monitoring, exception tracking, crash reporting, and bug capture tools.

## Sector Overview & Market Dynamics

The global error monitoring, crash reporting, and automated bug tracking market is valued at approximately **$1.5B to $2B+** (intersecting with the broader $5B+ Application Performance Monitoring and issue tracking ecosystem) and is expanding at a CAGR of ~11%–13%. 

The sector is **moderately fragmented**: high-volume mobile crash reporting and cloud-native capture are heavily influenced by platform-native giants (such as Google Firebase Crashlytics), while the core developer-first error tracking niche remains competitive across independent leaders (Sentry, Rollbar, LogRocket) and quality-suite consolidators (SmartBear/Bugsnag, Sauce Labs/Backtrace, LogicMonitor/Airbrake).

---

## SaaS Products

The table below covers prominent SaaS platforms in automated error monitoring, crash reporting, and bug capture. Products are ordered descending by company valuation / scale.

| Product | Company / Scale (Valuation / Revenue) | Category | Starting Price | Free Tier Limit / Free Trial | Notes & Metering Basis |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Firebase Crashlytics](https://firebase.google.com/products/crashlytics)** | **Alphabet / Google** (~$2.2T+ Market Cap, $350B+ Rev) | Mobile & Cross-Platform Crash Reporting | Free included with Firebase (Spark plan) | Free forever (Unlimited crashes; 64 KB custom logging limit per session) | Monetized via downstream GCP/Firebase backend service usage (Firestore, BigQuery exports). |
| **[BrowserStack Bug Capture](https://www.browserstack.com/bug-capture)** | **BrowserStack** (~$4.0B Valuation, ~$230M ARR) | Bug Capture & Manual/Automated Reporting | $25/user/month (Testing Toolkit Essentials) | Free forever plan available (Includes unlimited bug capture in standard Testing Toolkit); 14-day free trial on paid plans | Screen, network, and console capture extension integrating directly with Jira/GitHub. |
| **[Sentry](https://sentry.io/)** | **Functional Software (Sentry)** (~$3.0B Valuation, ~$130M ARR) | Error Tracking & Performance Monitoring | $26/month (billed annually) or $29/month | Free forever Developer plan (5,000 errors/mo, 10,000 performance units/mo, 50 session replays/mo, 1 user) | Meters errors, performance spans, and session replays. Team tier scales on volume. |
| **[Bugsnag](https://www.bugsnag.com/)** | **SmartBear** (~$2.0B Valuation, ~$150M+ ARR) | Application Stability & Error Monitoring | ~$99/month (starting tier via Vendr benchmark) | Free forever plan (7,500 events/month, 1 project, 1 user); 14-day free trial on full features | Acquired by SmartBear. Focuses on stability scoring and release tracking. |
| **[LogRocket](https://logrocket.com/)** | **LogRocket** (~$250M–$300M Est. Valuation, ~$110M Est. ARR) | Frontend Monitoring & Session Replay | $69/month (Core tier, billed annually) | Free forever plan (1,000 recorded sessions/month, 30-day retention); 14-day free trial on paid tiers | Error and log events are unlimited; billing scales primarily on monthly recorded sessions. |
| **[Raygun](https://raygun.com/)** | **Raygun (Mindscape)** (~$10M–$14.5M Est. ARR, Private) | Crash Reporting & Real User Monitoring | $40/month (Crash Reporting Basic, billed annually) or $60/month | 14-day free trial (Unlimited error monitoring, no credit card required) | Crash reporting metered by error occurrences (Basic includes 100,000 events/mo). |
| **[Rollbar](https://rollbar.com/)** | **Rollbar** (~$7M–$10M Est. ARR, Private) | Automated Error & Exception Tracking | $9/month (Essentials tier) | Free forever plan (5,000 error occurrences/month, 30-day retention, unlimited team seats); 30-day free trial | Never charges per seat; pricing is metered strictly on monthly error occurrences. |
| **[Airbrake](https://airbrake.io/)** | **LogicMonitor (Airbrake)** (~$5M Est. Segment ARR, Private) | Error Monitoring & Performance Tracking | $19/month (Essential tier, annual discount available) | Free Developer plan (7,500 errors/month, 1 user); 30-day free trial with unlimited error tracking | Acquired by LogicMonitor / Elsewhere Partners. Offers usage-capping alerts. |
| **[TrackJS](https://trackjs.com/)** | **TrackJS LLC** (~$5M Est. ARR, Bootstrapped) | JavaScript Error Monitoring | $49/month (Starter tier) | 14-day free trial (Full access to all features, no credit card required) | Structured around monthly page views (100K page views, ~800K errors/mo capped at 20 errors/min). |
| **[Honeybadger](https://www.honeybadger.io/)** | **Honeybadger Industries** (~$3.2M ARR, Bootstrapped) | Exception, Uptime & Cron Monitoring | $26/month (Team tier base) | Free forever plan (Developer plan: 1 user, core error tracking & uptime monitoring); 30-day free trial on paid tiers | Independent developer-centric exception tracking, uptime alerts, and check-in monitoring. |

---

## Open-Source Alternatives

For self-hosted error tracking and crash reporting environments:

| Tool | Focus | Tech Stack | Notes |
| :--- | :--- | :--- | :--- |
| **[Sentry (Self-Hosted)](https://github.com/getsentry/self-hosted)** | Full Error Monitoring & Tracing | Python / TypeScript / Kafka / ClickHouse | Fully featured self-hosted Docker Compose deployment of Sentry. |
| **[Ohbug](https://github.com/ohbug)** | Web & Application Monitoring | TypeScript / Node.js | Lightweight open-source monitoring platform for capturing runtime JavaScript exceptions. |
| **[GlitchTip](https://glitchtip.com/)** | Sentry-compatible Error Tracking | Python / Django / Postgres | Open-source alternative to Sentry using the standard Sentry SDKs. |
| **[Errbit](https://github.com/errbit/errbit)** | Airbrake-compatible Error Catcher | Ruby / MongoDB | Open-source, self-hosted error catcher that is API-compatible with Airbrake client libraries. |
