# alingse 作品集合

一个开发者，一个喜欢上网的人

**Live**: https://aeio.dev

## Deployment

This project is deployed on Cloudflare Workers with static assets.

### Deploy

```bash
npx wrangler deploy
```

### Configuration

- `wrangler.toml` - Worker configuration with assets binding
- `.wranglerignore` - Files to exclude from upload
- `not_found_handling = "single-page-application"` - All paths return `index.html` for client-side routing 
