# It Figures — original published website

Recovered from https://itfigures.lovable.app on 29 September 2026.

Includes the original Home, Collections, Custom Atelier, About, and Visit pages, original CSS, compiled client-side JavaScript, and five original photographs. No redesign was performed. Lovable branding is preserved. The Lovable-only analytics injection was removed because its hosting endpoint does not exist on Vercel. The Google Maps embed and badge font remain external as in the original.

## Deploy
Upload all contents of this folder to the ROOT of a new GitHub repository (not the ZIP itself), then import that repository into Vercel. Use Other as the framework, no Build Command, and . as Output Directory. vercel.json supplies static hosting configuration and page rewrites. Do not use the settings from a React/Vite source project with this compiled static package.

This is a deployable copy of the published site, not the original editable React/TypeScript source project. For future source-level editing, export the original project from Lovable to GitHub.

To preview locally, run python3 -m http.server 8000 from this directory and open http://localhost:8000. Do not double-click index.html: the original assets use root-relative URLs and JavaScript modules.

Publishing and the custom domain are not yet configured.
