# yan-he-site existing-users-only magic link package

Required Netlify environment variables:
- SUPABASE_URL
- SUPABASE_ANON_KEY
- SUPABASE_BUCKET=photos

Important:
- Magic Link uses shouldCreateUser: false
- Only pre-created Supabase Auth users can sign in
- Public visitors can still view public content
