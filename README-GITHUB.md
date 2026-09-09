# RIHLA — GitHub Pages Ready

## Structure

```text
index.html              # Public RIHLA site (passenger + driver)
robots.txt              # Prevents search engines from indexing admin path
.nojekyll               # Keeps GitHub Pages from applying Jekyll processing
012012/index.html       # Private admin entry page
supabase/schema.sql     # Database schema for the future production backend
```

## GitHub Pages upload

Upload the **contents of this folder** to the root of your repository. Do not upload the outer folder itself.

The repository root must contain `index.html` directly.

Admin URL after deployment:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/012012/`

Admin PIN: `2852003`

> Note: the hidden URL + client-side PIN is not real security. For production, admin authorization should be enforced by Supabase Auth/RLS or a server-side backend.
