# Smoking Map Alert

喫煙所・喫煙可店舗の新規/閉鎖通知

## Repository

Recommended repository name: `smoking-map-alert`

## Domain candidates

First candidate: `smokingmap.jp`

Other candidates:

- `smokingmap.jp`
- `kitsuenmap.jp`
- `smokealert.jp`
- `smokecafe.jp`

## Concept

喫煙所の新設、閉鎖、喫煙可飲食店を通知し、飲食店送客、掲載課金、マップ広告へつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 飲食店送客
- 掲載課金
- マップ広告
- クーポン
- スポンサー

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
