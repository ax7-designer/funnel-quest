# Funnel Quest - Public Hostinger Package

This folder contains only the public static files intended for Hostinger.

GitHub repository:

`https://github.com/ax7-designer/funnel-quest`

Upload the contents of this folder to a safe public subfolder, recommended:

`public_html/funnel-quest/`

Avoid uploading directly to `public_html/` if the domain already has an active website.

Included:

- `index.html`
- `site.webmanifest`
- `sw.js`
- `icon.svg`
- `.htaccess`
- `data/schema.json`
- `data/default-content.json`

Do not upload internal research folders, Instagram scripts, screenshots, backups, or handoff notes to the public website.

After upload:

1. Open `https://your-domain.com/funnel-quest/` on mobile.
2. Confirm the dashboard loads.
3. Test `Backup JSON`.
4. Test `Importar progreso`.
5. If migrating from the local file version, import a previously exported backup JSON.

Hostinger options:

- hPanel Git deployment: Websites -> Dashboard -> Advanced -> Git, then connect GitHub and choose this repository.
- hPanel File Manager: upload `hostinger_upload.zip` and extract it into `public_html/funnel-quest/`.
- SFTP: upload these files into `/home/<user>/domains/<domain>/public_html/funnel-quest`.
