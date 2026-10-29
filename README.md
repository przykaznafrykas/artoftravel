# Poland Art of Travel

English-language website for Tomasz Kujawski, prepared for artoftravel.pl.

## Deployment

Connect this repository to Netlify. Production branch: `main`.
The publish directory is `dist`; no build command or package installation is needed.
Netlify reads these settings from `netlify.toml`.

Edit files in `dist/`, then commit and push to trigger deployment.
Configure artoftravel.pl and www.artoftravel.pl in Netlify Domain management;
apply the DNS values provided by Netlify in Hostido.

The contact form currently opens a draft email in the visitor's email application.
It does not submit or store messages on the server.
