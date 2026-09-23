# Norven - coming soon page

A one-page holding site for Cloudflare Pages while the full site is finished.
No JavaScript, no cookies, no forms, no analytics - so no cookie banner or
privacy policy is needed for it.

## Deploy

Workers & Pages > Create > **Pages** > Upload assets > drag in this whole
folder (or push it to a GitHub repo and connect it). Framework preset None,
no build command, output directory `/`.

## Before you go live

- **Contact button:** there's no email address yet. In `index.html`, find the
  `CONTACT:` comment, swap in your address and remove the `<!--` and `-->`.
- **Domain:** canonical and social tags use `https://www.norven.co.uk`.
- **Always Use HTTPS:** turn it on under SSL/TLS > Edge Certificates once the
  custom domain is added.

## When the full site is ready

Deploy the full site to the **same** Pages project (push it to the same repo,
or upload it over this one). It replaces this page, and the custom domain and
HTTPS settings carry over.
