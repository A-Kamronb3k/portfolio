# Kamronbek Allanazarov — Portfolio

Personal portfolio site of an aspiring **Cloud Engineer** — built with **Astro** (zero-JS static output), deployed on **Cloudflare Pages** with automatic deploys from `main`.

**🔗 Live:** [https://YOUR-PORTFOLIO-URL.pages.dev](https://portfolio.kamronb3k03.workers.dev/) <!-- TODO: replace with your real Cloudflare Pages URL -->

## What's on it

Timeline (IT Park Uzbekistan cloud program, 29-day portfolio sprint), skills grouped by depth, and cards for the live projects:

| Project | Live demo | Code |
|---|---|---|
| Serverless Notes App (Terraform, Lambda, DynamoDB, Cognito) | [demo](https://d2k6mpvowrmd9f.cloudfront.net) | [repo](https://github.com/A-Kamronb3k/serverless-notes-terraform) |
| AWS Static Site + CDN + CI/CD (S3, CloudFront OAC, OIDC) | [demo](https://dtx8c9l8wd3k9.cloudfront.net) | [repo](https://github.com/A-Kamronb3k/aws-static-site-cicd) |
| Dockerized Feedback API (multi-stage, Trivy, GHCR) | [demo](https://dockerized-feedback-api-latest.onrender.com) | [repo](https://github.com/A-Kamronb3k/dockerized-feedback-api) |

## Stack

- **Astro** — static output, no client-side framework, fast by default
- Semantic HTML, responsive CSS (mobile-first), accessible markup
- **Cloudflare Pages** — free hosting, auto-deploy on every push to `main`

## Running locally

```bash
npm install
npm run dev        # http://localhost:4321
npm run build      # outputs to dist/
```

## License

MIT — see [LICENSE](./LICENSE).
