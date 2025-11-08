# PostHog Frontend - Vercel Deployment

This repository contains a simplified Vercel deployment of the PostHog frontend interface.

## ⚠️ Important Notice

**This is a demonstration deployment only.** The full PostHog application requires:

- Django REST API backend
- PostgreSQL database
- ClickHouse analytics database
- Redis cache
- Kafka event streaming

This Vercel deployment serves the frontend UI as a static site for reference purposes.

## Deployment

This site is deployed on Vercel at: [Your Vercel URL will appear here after deployment]

### Deploy Your Own

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/PostHog/posthog)

Or using Vercel CLI:

```bash
npm install -g vercel
vercel login
vercel
```

## Full PostHog Deployment

For a complete, functional PostHog installation:

### Option 1: PostHog Cloud (Recommended)
Visit [posthog.com/signup](https://posthog.com/signup)

### Option 2: Self-Hosted
See the [official self-hosting guide](https://posthog.com/docs/self-host)

### Option 3: Docker (Local Development)
```bash
docker run -d --name posthog -p 8000:8000 posthog/posthog:latest
```

## Resources

- [PostHog Documentation](https://posthog.com/docs)
- [GitHub Repository](https://github.com/PostHog/posthog)
- [Self-Hosting Guide](https://posthog.com/docs/self-host)
- [Community Slack](https://posthog.com/slack)

## License

MIT - See [LICENSE](https://github.com/PostHog/posthog/blob/master/LICENSE)
