# The Shipping Dude — UI Prototype

A full-featured shipping platform prototype built as a single HTML file. Covers all user-facing screens and a complete admin panel.

## Quick start

Open `shipping_dude.html` in any browser — no build step or server required.

## Screens

### User-facing
| # | Screen | Description |
|---|--------|-------------|
| 01 | Landing | Marketing page with hero, pricing, testimonials |
| 02 | Sign Up | Account creation with Google OAuth option |
| 03 | Login | Sign in screen |
| 04 | Dashboard | Overview, quick rate quote, recent shipments |
| 05 | Ship To | Step 1 — recipient address entry |
| 06 | Package | Step 2 — dimensions, weight, insurance |
| 06 | Rates | Step 3 — carrier rate comparison |
| 07 | Confirm | Purchase confirmation modal |
| 08 | Label | Label ready — download, print, track |
| 09 | Wallet | Balance, top-up, transaction history |
| 10 | Rate Quote | Instant rate lookup (no purchase) |
| 11 | Settings | Profile, return address, label defaults, password |
| 12 | History | Label history with search, filters, expand rows |
| 13 | Upgrade | Free vs Pro plan comparison |
| 14 | Batch | CSV upload → review → purchase → done |
| 15 | Support | Help center, FAQ, contact form, ticket tracker |

### Admin panel
| Screen | Description |
|--------|-------------|
| Dashboard | Stats, recent labels, revenue split, top users |
| Users | Full user table — View, Add Credits, Suspend, Delete, Restore, Invite |
| Labels & Orders | All labels across users — View, Void, Refund |
| Revenue | Gross/cost/margin, monthly bar chart, Stripe top-ups |
| Carrier Rates | Per-service markup editor with live price preview |
| Support & Logs | Flagged accounts, void requests, API error logs, failed batches |

## Assets

| File | Description |
|------|-------------|
| `shipping_dude.html` | Entire prototype — HTML, CSS, JS in one file |
| `LOGO_AJ.PNG` | Brand logo used across all screens |

## Tech

- Vanilla HTML / CSS / JavaScript — zero dependencies
- All carrier badges, modals, and interactions are self-contained
- Responsive down to 320px via CSS media queries
- Sidebar becomes a slide-out overlay on mobile (hamburger menu)
