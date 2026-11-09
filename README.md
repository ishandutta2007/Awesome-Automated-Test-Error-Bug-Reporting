# Awesome-Automated-Test-Error-Bug-Reporting

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **several entries in your list have no usable pricing**, and **BrowserStack Error Reporting is a bug-capture extension, not an error monitoring platform**.



## The data problems



**BrowserStack "Error Reporting" is not a Sentry competitor.** The Chrome extension is **BrowserStack Bug Capture**—it records screen and console logs to create bug reports, integrating with Jira . It does not aggregate production errors, group stack traces, or track error trends. **Do not list it alongside Sentry or Rollbar.**



**Sentry's pricing is well-documented.** Developer free (5K errors/month, 1 user); Team **$29/mo** or **$26/mo annual** (50K errors); Business **$89/mo** or **$80/mo annual** . Overages are tiered by volume—1M errors/month on Team costs roughly **$187.50/mo** total .



**Rollbar publishes machine-readable pricing.** Free (5K occurrences, unlimited users); Essentials **from $9/mo** (10K) to **$6,499/mo** (50M); Advanced **from $13/mo** (10K) to **$12,049/mo** (50M) . **Never charges per seat** .



**Airbrake publishes tiered pricing.** Free Developer plan; paid **from $19/mo** (25K errors) through **$799/mo** (5M errors); annual saves 10% .



**TrackJS publishes traffic-based pricing.** Starter **$49/mo** (unlimited users, 800K+ errors); Professional **$99/mo**; Business **$199/mo** .



**Honeybadger publishes starting prices.** Team **$26/mo** base; free for individual developers .



**Raygun's pricing is from a provenance-stamped YAML file.** Crash Reporting Basic **$40/mo annual** or **$60/mo monthly** (100K errors); Team **$80/mo annual** or **$120/mo monthly**; Business **$400/mo annual** or **$600/mo monthly** . Software Advice lists **$40/mo** starting .



**Bugsnag's pricing is from Vendr benchmarks, not vendor-published.** Free **7,500 events/mo**; entry-level **~$99/mo** (25K events); discounts **15–30%** for annual/multi-year . **Bugsnag was acquired by SmartBear** .



**LogRocket's pricing page returned no dollar figures**—only "starting at" with a slider and plan descriptions . Do not fabricate.



**Crashlytics is free with Firebase.** It is a no-cost Firebase product with **64kB custom logging limit**; Spark plan allows production use at no cost .



## Open-source: what actually exists



**Ohbug** surfaced in the GitHub topics listing as **self-hosted application monitoring** for production errors . No star count was surfaced. **Do not invent one.**



The other results are **SDKs and notifiers** (raygun4net, bugsnag-php, rollbar-java, etc.) , not self-hosted platforms. Do not present an SDK as a platform replacement.



## What I recommend



**Split into three honest categories:**



**1. Error Monitoring Platforms** (proprietary):

- **Sentry** — Free 5K; Team $26/mo annual; Business $80/mo 

- **Rollbar** — Free 5K; Essentials from $9/mo; no per-seat fees 

- **Airbrake** — from $19/mo 

- **TrackJS** — from $49/mo 

- **Honeybadger** — from $26/mo 

- **Raygun** — from $40/mo annual 

- **Bugsnag** — from ~$99/mo (Vendr) 

- **LogRocket** — pricing not surfaced 



**2. Free with Platform:**

- **Crashlytics** — free with Firebase 



**3. Bug Reporting Tool (not error monitoring):**

- **BrowserStack Bug Capture** — Chrome extension for screen/console capture 



**4. Open-Source:**

- **Ohbug** — self-hosted application monitoring ; no star count surfaced



**Flag the metering difference explicitly:** Sentry meters errors + spans + replays ; Rollbar meters occurrences + session replays ; TrackJS meters traffic ; Raygun meters errors . A reader comparing costs needs that context.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not list BrowserStack Bug Capture as an error monitoring platform, fabricate LogRocket pricing, or present SDKs as self-hosted platforms.
