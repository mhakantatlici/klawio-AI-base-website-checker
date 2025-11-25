# Website Score Checker — Showcase Project
A lightweight website auditing tool for checking SEO, technical performance, and page quality. Part of Klawio Web Agency’s toolset. This repository contains a safe, demo-friendly showcase version (no credentials or production code).

A lightweight website auditing tool that analyzes key technical, SEO, and performance metrics.

📌 Overview

The Website Score Checker is a web-based auditing tool that performs quick, automated scans of a website and generates a simple, easy-to-read report.

It was built for Klawio Web Agency to help small businesses understand their website’s technical condition and improvement opportunities.

This version is the safe showcase (no backend secrets, no real API keys, no private code).

🚀 Key Features
✔ 1. On-Page SEO Checks

Page title length

Meta description presence

Header (H1/H2) structure

Image alt tags

Robots/Sitemap detection

✔ 2. Technical Performance

Page loading time

Compression checks (GZIP/Brotli)

Mobile viewport support

HTTPS / SSL verification

Core Web Vitals (LCP/FID/CLS basics)

✔ 3. Content Quality Analysis

Word count

Keyword visibility (basic)

Duplicate text indicators

✔ 4. External Resource Review

Broken links detection

External script count

CDN usage

✔ 5. Email Report Sender (Optional)

If enabled, the system can send a website audit report to the user’s email.

(Safe for GitHub: no SMTP credentials are included in the showcase.)

🧰 Tech Stack

Frontend: HTML5, CSS3, JavaScript

Backend: PHP (API endpoint)

Data Fetching: cURL, DOM parsing

Email: SMTP (configurable)

Deployment: WordPress child theme / Klawio custom PHP module

🖼️ How It Works (Architecture)
[User] → enters URL & email  
  ↓
[Frontend UI] → form validation  
  ↓
[Backend API] → fetch URL → analyze HTML → collect metrics  
  ↓
Score calculation  
  ↓
(Optional) Email result to user  
  ↓
Display results on screen
