# NetPulse

A dark, responsive network diagnostic workbench for exploring HTTP waterfall timings, DNS/TLS fixture records and synthetic latency profiles.

## Features
- Interactive HTTP/TLS waterfall with expandable request and response headers
- Local DNS record and TLS posture fixture inspector
- Network profile simulator with RTT/jitter visualization
- Synthetic health probe action and HAR 1.2 export
- Responsive React + TypeScript + Vite interface styled with Tailwind CSS v4

## Quick start

```bash
npm install
npm run dev
npm run build
```

## Important data note
NetPulse currently runs in **demo/simulation mode**. DNS records, DNSSEC status, certificate details, latency profiles, and captured requests are illustrative local fixtures. The synthetic probe does not contact external hosts, alter operating-system network settings, or measure the actual network. HAR export contains the visible fixture data.

## Deploy to Vercel
Import this repository in Vercel. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
