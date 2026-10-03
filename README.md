# Book Tattoo

This repository contains the Book Tattoo static website and is ready to deploy to Netlify.

## Deploy to Netlify
1. Log in to your Netlify account.
2. Click Add new site > Import from Git.
3. Select this repository.
4. Keep the build settings as-is for a static site.
5. Deploy the site.

## Enable admin access
1. In the Netlify dashboard, open the site.
2. Go to Site settings > Identity.
3. Enable Identity.
4. Enable Git Gateway if prompted.
5. In Identity > Invite users, add your admin email, such as `padgettjesse7@gmail.com`.
6. The user receives an email to create a password.

## Admin panel
Once Identity is enabled, the site's `/admin/` page can be used to edit CMS content through the configured Netlify CMS dashboard.
