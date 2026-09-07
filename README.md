Hi, I'm Hannan

Backend engineering, currently deep in FastAPI + PostgreSQL. CS student at CUI Lahore.

Featured Work
Widget & Lead-Capture Platform

FlyRank Backend AI Engineering internship capstone. Multi-tenant backend for embeddable signup widgets — hardened public submission pipeline with validation, rate limiting, geo-enrichment with provider fallback, idempotent storage, and background jobs for side effects. Design rationale and evidence documented in the repo.

AI Interview Coach

Team project — a full-stack mock-interview platform with live speech analysis, webcam-based body language tracking, and LLM-generated coaching. My part: backend (FastAPI, service layer) and the LLM integration — question generation and scoring via a Groq/Grok fallback chain with a rule-based backstop if both are unavailable.

FlyRank Backend AI Engineering Internship

Certificate: verify here

flyrank-capstone-widget-platform — capstone, see above.

CRUD-API — task API + auth + scraper + LLM enrichment Task CRUD API extended with Supabase Auth, a polite web scraper (books.toscrape.com), and an /enrich endpoint that sends scraped data to an LLM with retry/repair logic — scored against an 8-case eval suite.

Background-Job — background jobs with Inngest Report-generation API where slow work happens off the request path: instant 202 response, status polling, cron jobs, durability across process restarts.

pdf-report-generator — SQL → HTML → PDF pipeline Aggregates a catalogue via SQL, renders through an HTML template, prints to PDF with headless Chromium. Idempotent — a repeated request returns the existing report instead of duplicating it.
