# krondor.org

Developer blog. Next.js with Quotient CMS.

## Structure

- `apps/web` - Next.js app
- `packages/ui` - Shared UI component library

## Development

```bash
pnpm install
pnpm dev              # Dev server on :3000 (needs confit for Quotient API keys)
pnpm build            # Build
pnpm check            # Biome lint + format
pnpm types            # Type check
```

## CI

Runs on every push/PR to `main`:
- Biome check (format + lint)
- Type check
- Build
