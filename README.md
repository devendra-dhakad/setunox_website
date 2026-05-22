# Setunox VPN Website

Static GitHub Pages site for Setunox VPN.

## Pages

- `/` - public Setunox VPN home page
- `/privacy/` - privacy policy URL for Google Play
- `/account/delete/` - public account deletion URL for Google Play

## GitHub Pages Hosting

1. Create a GitHub repository for the website.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings > Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`.
6. Save.

For Play Console, use the final published URLs, preferably on a custom domain:

```text
https://setunox.com/privacy/
https://setunox.com/account/delete/
```

Before Play submission, confirm the policy matches the real production backend,
Google sign-in configuration, crash reporting, subscription handling, and
retention behavior.
