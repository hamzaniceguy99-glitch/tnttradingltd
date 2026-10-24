# TN & T — tn & t trading ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `tnttradingltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/tnttradingltd.mjs`).
> To change the content, edit that file and run `node build.mjs tnttradingltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@tnttradingltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per cut / $Per visit / $Per service) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
TN & T Trading Ltd, a private limited company registered in England and Wales (company number 12049201), is a barbershop and hairdresser in Hackney: cuts, fades and restyles with a consultation before the clippers come out, textured and Afro hair cut dry and shaped to the growth pattern, beard work and traditional hot towel shaves using single-use blades, and colour carried out only after a patch test at least 48 hours beforehand. Tools are cleaned and disinfected between every client. Appointments and walk-ins are both taken. Site: tnttradingltd.shop
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
