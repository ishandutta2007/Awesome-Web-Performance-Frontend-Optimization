# Awesome-Web-Performance-Frontend-Optimization

# Top Web Performance & Frontend Optimization Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Edge Caching, Asset Optimization, Core Web Vitals Monitoring, Bundle Compression & AI Frontend Craft Auditing*  
**Last updated: November 2026**

This repository (`Awesome-Web-Performance-Frontend-Optimization`) tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Web Performance & Frontend Optimization** — Top Web Performance Frontend Optimization (Opensource) 🌟 Star if you like it! 🌟. These tools accelerate page loads via edge CDNs, automate HTML/CSS/JS/image optimization, monitor Core Web Vitals (LCP, INP, CLS), enforce CI/CD performance budgets, and audit frontend UI craft and runtime efficiency.

**Examples** include Cloudflare, Fastly, Akamai Ion, Google PageSpeed Insights / Service, SpeedCurve, Calibre, GTmetrix, DebugBear, Vercel Speed Insights, NitroPack, and `pbakaus/impeccable` (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for frontend build/bundle optimization, next-gen image/CSS/JS minification, self-hosted synthetic speed testing, Core Web Vitals RUM telemetry, and AI coding-agent frontend design/performance auditing — ideal for frontend engineers, performance architects, DevOps teams, and web developers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Cloudflare](https://cloudflare.com)**  
  Global anycast CDN and edge performance suite offering Argo Smart Routing, Polish image optimization, Early Hints, Zaraz third-party script offloading, and HTTP/3 acceleration.

- **[Fastly](https://fastly.com)**  
  Programmable edge cloud platform delivering instant cache purging, real-time log streaming, Image Optimizer, and low-latency VCL/Compute edge caching.

- **[Akamai Ion](https://akamai.com)**  
  Adaptive web performance acceleration suite automating device-aware image compression, route optimization, and proactive third-party script management.

- **[Google PageSpeed Insights](https://web.dev)**  
  Official Google web performance analysis platform combining lab Lighthouse diagnostics with real-world Chrome User Experience Report (CrUX) Core Web Vitals telemetry (successor to Google PageSpeed Service).

- **[NitroPack](https://nitropack.io)**  
  All-in-one cloud web performance optimization service automating full-page caching, critical CSS generation, lazy loading, and WebP/AVIF conversion.

- **[SpeedCurve](https://speedcurve.com)**  
  Continuous synthetic speed monitoring and Real User Monitoring (RUM) platform tracking Core Web Vitals, JavaScript long tasks, and competitive benchmarks.

- **[Calibre](https://calibreapp.com)**  
  Automated frontend performance monitoring platform providing pull-request performance budgets, device/network emulation, and third-party script audits.

- **[GTmetrix](https://gtmetrix.com)**  
  Cloud website speed testing and waterfall diagnostic platform powered by Lighthouse metrics, multi-region test nodes, and historical performance alerts.

- **[DebugBear](https://debugbear.com)**  
  Synthetic testing and Real User Monitoring platform specializing in deep LCP, INP, and CLS root-cause debugging and CrUX field data tracking.

- **[Vercel Speed Insights](https://vercel.com)**  
  Managed Real User Monitoring service tracking real-visitor Core Web Vitals broken down by route, device tier, and geographic region.

- **[Cloudinary](https://cloudinary.com)**  
  Cloud media optimization and delivery platform automatically transforming images and videos into optimal AVIF/WebP/MP4 formats with responsive breakpoints.

## Open-Source GitHub Projects

- **[Impeccable (pbakaus/impeccable)](https://github.com/pbakaus/impeccable)**  
  Open-source design vocabulary, quality layer, and automated detector skill for AI coding agents (Claude Code, Cursor, Gemini CLI, Codex) that audits frontend craft, accessibility, responsiveness, and performance while eliminating generic AI slop.

- **[Google Lighthouse (GoogleChrome/lighthouse)](https://github.com)**  
  Industry-standard open-source automated auditing engine measuring web page performance, Core Web Vitals, accessibility, SEO, and progressive web app best practices.

- **[Lighthouse CI (GoogleChrome/lighthouse-ci)](https://github.com-ci)**  
  Open-source CLI and self-hosted server for running Lighthouse on every pull request, asserting strict performance budgets, and tracking score regressions over time.

- **[Sitespeed.io (sitespeedio/sitespeed.io)](https://github.com)**  
  Complete open-source web performance testing suite combining Browsertime, Lighthouse, WebPageTest, and Grafana dashboards for continuous synthetic optimization.

- **[WebPageTest (Catchpoint/WebPageTest)](https://github.com)**  
  Open-source engine behind the premier synthetic web performance testing platform supporting multi-step browser scripting, filmstrip views, and packet-level throttling.

- **[web-vitals (GoogleChrome/web-vitals)](https://github.com)**  
  Modular, ultra-lightweight (~2 KB) open-source JavaScript library from Google for measuring real-world LCP, INP, CLS, FCP, and TTFB metrics in production.

- **[Unlighthouse (harlan-zw/unlighthouse)](https://github.com)**  
  Fast open-source CLI and web dashboard that crawls and audits an entire website with Google Lighthouse concurrently in minutes.

- **[Partytown (BuilderIO/partytown)](https://github.com)**  
  Open-source library that relocates resource-heavy third-party analytics and tag manager scripts off the main thread into a Web Worker to drastically improve Interaction to Next Paint (INP).

- **[Quicklink (GoogleChromeLabs/quicklink)](https://github.com)**  
  Lightweight open-source drop-in library accelerating subsequent navigations by prefetching and prerendering visible viewport links during browser idle time.

- **[Speculation Rules / Instant.page (instantpage/instant.page)](https://github.com)**  
  Tiny open-source JavaScript library using just-in-time hover/touch preloading to make multi-page site navigations feel instantaneous.

- **[Vite (vitejs/vite)](https://github.com)**  
  Next-generation open-source frontend build tool leveraging native ES modules and Rollup/Rolldown bundling for instant dev startup and highly optimized production assets.

- **[Rolldown (rolldown/rolldown)](https://github.com)**  
  Fast open-source Rust-based JavaScript/TypeScript bundler with Rollup-compatible APIs designed for high-speed production code-splitting and tree-shaking.

- **[esbuild (evanw/esbuild)](https://github.com)**  
  Extremely fast open-source JavaScript and CSS bundler and minifier written in Go, accelerating frontend build and compression pipelines by orders of magnitude.

- **[SWC (swc-project/swc)](https://github.com)**  
  Super-fast open-source Rust platform for compiling, minifying, and bundling modern JavaScript and TypeScript for production web delivery.

- **[Lightning CSS (parcel-bundler/lightningcss)](https://github.com)**  
  Blazingly fast open-source CSS parser, transformer, bundler, and minifier written in Rust that compiles modern CSS syntax and strips unused vendor prefixes.

- **[PurgeCSS (FullHuman/purgecss)](https://github.com)**  
  Open-source static analysis utility that scans HTML and JavaScript components to remove unused CSS selectors and shrink stylesheet payloads.

- **[Beasties (formerly Critters) (danielroe/beasties)](https://github.com)**  
  Open-source build plugin that extracts and inlines critical above-the-fold CSS directly into HTML while asynchronously loading the remaining stylesheets.

- **[Sharp (lovell/sharp)](https://github.com)**  
  High-performance open-source Node.js image processing library powered by `libvips` for resizing and converting web images into modern AVIF and WebP formats.

- **[imgproxy (imgproxy/imgproxy)](https://github.com)**  
  Fast, secure, self-hosted open-source image processing server written in Go for on-the-fly resizing, cropping, and AVIF/WebP optimization at the edge.

- **[Squoosh CLI / libavif (AOMediaCodec/libavif)](https://github.com)**  
  Reference open-source AV1 Image File Format (AVIF) encoder and decoder delivering superior perceptual compression over JPEG and WebP.

- **[Brotli (google/brotli)](https://github.com)**  
  Official Google open-source lossless compression library providing smaller HTML, CSS, and JavaScript transfer sizes over HTTPS than Gzip.

- **[Size Limit (ai/size-limit)](https://github.com)**  
  Open-source CI performance budget tool that calculates real JavaScript bundle download and main-thread execution time on simulated low-end hardware.

- **[million.js (aidenybai/million)](https://github.com)**  
  Open-source optimizing virtual DOM compiler for React that accelerates component rendering and reduces main-thread CPU overhead.

- **[Varnish Cache (varnishcache/varnish-cache)](https://github.com)**  
  High-performance open-source HTTP reverse proxy and edge caching accelerator serving cached web pages in microseconds.

- **[Workbox (GoogleChrome/workbox)](https://github.com)**
