# Meridian — live interview starter

This is the standard WorkOS SE interview, version `se-interview-v1`. Read [LIVE.md](LIVE.md) ahead of time if you like, but **do not implement it before the session**.

## Before the call: at most 15 minutes

1. Use Node.js 22 LTS and this package's lockfile. If setup or changing Node versions becomes a distraction, contact your interviewer rather than troubleshooting for hours.
2. Run `npm ci` in this folder.
3. Copy `.env.local.example` to `.env.local`. Populate it privately from the interviewer-supplied candidate credential item:
   - `client_id` → `WORKOS_CLIENT_ID`
   - `api_key` → `WORKOS_API_KEY`
   - `cookie_secret` → `WORKOS_COOKIE_PASSWORD`
   - `callback_uri` → `NEXT_PUBLIC_WORKOS_REDIRECT_URI`
4. Run `npm run dev`, open `http://localhost:3000`, and try the supplied demo login.
5. If anything fails, stop and contact the interviewer. Setup failures are not scored; we can restore access or reschedule.

Keep the app and credentials private. Never commit `.env.local`, put keys in browser code, or paste secrets into AI prompts. You do not need Platform credentials. Use only the demo accounts and designated invitation inbox supplied by the interviewer.

## What happens

- Discovery: 45 minutes.
- Collaborative live technical session: **75 minutes**. Documentation, search and AI are welcome; no paid AI subscription is required. Bring your editor and tell recruiting if you need tool access or accommodations.
- After an explicit pass: a separate extension, **90 minutes maximum including submission**, within a flexible one-week window. You may use your live app or an optional continuation starter supplied equally to passing candidates. No unpaid catch-up is required.
- Panel: 60 minutes; recruiting supplies the brief, with no more than 30 minutes of preparation expected.
- Recruiting confirms any remaining conversations and scheduling.

We assess customer understanding, organization-scoped authorization, technical ownership, verification and communication—not UI polish, typing speed or continuous narration. The extension cap is honor-based; overtime is neither penalized nor rewarded. Partial work with an honest explanation is acceptable.

Only the initial live prompt is included here. Recruiting will send extension instructions and the submission template after the pass decision. Keep this working copy private and use the agreed private submission channel. Custom sign-out routing, deployment, external IdP trials, videos and slides are not required for this interview.
