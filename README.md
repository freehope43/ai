# AI Drama Stream — Vercel Deploy v2

Clean Next.js deployment foundation for AI Drama Stream.

## Environment variables

NEXT_PUBLIC_SUPABASE_URL=https://spmpfoufmdlcmfdqvvzy.supabase.co
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=YOUR_SUPABASE_PUBLISHABLE_KEY
NEXT_PUBLIC_APP_URL=https://YOUR-VERCEL-DOMAIN.vercel.app

## Deployment
1. Replace the files in your GitHub `aidrama` repository with this package.
2. Commit and push to `main`.
3. In Vercel, redeploy the latest commit.
4. Add the three environment variables above to Vercel Production.

## Security
Do not commit `.env.local`, Supabase service-role keys, Paystack secret keys, or Cloudflare tokens.

Next.js is pinned to 15.5.27, the current 15.x Maintenance LTS security-patched release.
