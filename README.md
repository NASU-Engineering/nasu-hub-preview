# NASU Freshmen Hub — public UX preview (mock build)

Preview of `NASU-Engineering/nasu_web` branch `feature/hub-platform-redesign` at commit
`4761409`, built in **mock mode**:

- No backend connection: the Supabase URL and key are blank in this build, so no
  request can reach the real Hub backend.
- No real accounts or student data. "Continue with NASU Microsoft Account" signs
  in a fake demo account without contacting Microsoft. All people and content are
  sample data, kept only in your browser tab.
- English and Arabic (RTL), five themes: the gear icon in the top bar.
- Quizzes, Activities, XP and Leaderboards run on sample data here; in the real
  Hub they show "not live yet" until their backend is approved and built.
- The demo account holds every role, so you land in the Admin Control Center.
  Use the workspace switcher (top right) for Student Hub, Content Studio and
  Review Desk, and Admin → Role simulator to view each role exactly as it sees
  the Hub.

Each build lives in its own folder (`b/<commit>/`) so browsers never mix a new page
with cached scripts from an older build.

Production (https://nasu-engineering.github.io/nasu_web/) is not affected by
this repository.
