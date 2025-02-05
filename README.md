# supabase_sample

Install `supabase`:

```sh
npm install supabase --save-dev
```

Initialize `supabase`:

```sh
npx supabase init
```

Start `supabase`:

```sh
npx supabase start
```

Generate `schema.sql`:

```sh
pg_dump --schema-only --file=schema.sql postgresql://postgres:postgres@127.0.0.1:54322/postgres
```
