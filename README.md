# Guacamole Finback Partners — guacamole finback partners llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `guacamolefinbackpartnersllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/guacamolefinbackpartnersllc.mjs`).
> To change the content, edit that file and run `node build.mjs guacamolefinbackpartnersllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@guacamolefinbackpartnersllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Quote) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Guacamole Finback Partners LLC is a privately held Florida limited liability company that holds and operates interests in hospitality and real estate for its own account. Its activities include holding ownership interests in affiliated operating businesses, acquiring and holding real property, providing administrative and management support to the businesses it owns, and evaluating opportunities alongside existing partners. The company is privately held, manages only its own and its partners' capital, offers no security or investment to the public, and provides no investment, legal or tax advice to third parties. Site: guacamolefinbackpartnersllc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
