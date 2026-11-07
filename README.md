# Le Bouquet Floral Boutique

Static preview site, served with GitHub Pages from the `main` branch root.

## Custom domain

The site is set up for `www.lebouquetfloralboutique.com` (the `CNAME` file). The bare domain redirects to `www`.

DNS records to add at the registrar:

| Type | Host | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | rajapate-coder.github.io |

Then in GitHub: Settings > Pages > Custom domain should show `www.lebouquetfloralboutique.com`. Once the DNS check passes, tick "Enforce HTTPS".
