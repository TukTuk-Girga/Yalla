# RIHLA HTML Website

## Public
Open `index.html`. The public site exposes only passenger and driver entry points.

## Private admin
The admin panel is intentionally removed from the public navigation and lives at `/012012/` when deployed to GitHub Pages. It asks for a PIN before showing the control center.

**Important:** this is still a static HTML app. A hidden URL + client-side PIN is obscurity, not real security. Anyone with access to the source can inspect the JavaScript. For production, move admin authentication and authorization to Supabase Auth/RLS or a server-side backend.
