# NovaPay Wallet

A Railway-hosted digital wallet interface based on the supplied visual reference.

- Railway: hosting
- Supabase: authentication + PostgreSQL + RLS
- Google OAuth: Supabase Auth
- Internal transfers: atomic Postgres RPC with idempotency protection

Required Railway variables: SUPABASE_URL and SUPABASE_PUBLISHABLE_KEY.

This is a wallet application, not a licensed bank. External bank transfers, cards and regulated payment rails must be connected through an appropriately licensed provider before moving real-world fiat.