# The Shipping Dude — Figma First Draft Prompts
## Instructions: Paste ONE prompt at a time into Figma First Draft.
## Start with STEP 1 (Design Tokens) before generating any screen.
## Reference app for UX inspiration: pirateship.com (clean, simple, step-by-step shipping flow)
## ⚠️ Each user is INDIVIDUAL — no business/org/team/workspace concept anywhere.

---

## STEP 1 — Design Tokens (Paste this FIRST)

```
Create a design system called "The Shipping Dude" with the following tokens.

Brand colors extracted from a bold navy-blue and black shipping logo:
- Primary Navy: #1A52A3
- Dark Navy: #0F3478
- Sky Blue: #6BB8D4
- Jet Black: #111827
- Success: #16A34A
- Warning: #F59E0B
- Danger: #EF4444
- Page background: #F4F6F9
- Card background: #FFFFFF
- Border color: #E5E7EB
- Text primary: #111827
- Text secondary: #6B7280
- Text muted: #9CA3AF

Typography: Inter font family.
- Display: 48px, weight 800, tracking -0.03em
- H1: 32px, weight 700, tracking -0.02em
- H2: 24px, weight 700
- H3: 18px, weight 600
- Body: 15px, weight 400, line-height 1.6
- Small: 13px, weight 400
- Label: 12px, weight 600, uppercase, tracking 0.06em

Radius: buttons 8px, inputs 8px, cards 12px, modals 16px, pills 99px.

Shadows: card shadow 0 1px 4px rgba(0,0,0,0.07), modal shadow 0 24px 64px rgba(0,0,0,0.18).

Button styles:
- Primary: #1A52A3 fill, white text, 8px radius, height 44px, font-weight 600
- Success: #16A34A fill, white text
- Ghost: white fill, #1A52A3 border 1.5px, #1A52A3 text
- Danger: #EF4444 fill, white text
- Disabled: #E5E7EB fill, #9CA3AF text

Input style: white background, #E5E7EB border 1px, 8px radius, 44px height, 14px text. Focus state: #1A52A3 border, soft blue glow ring.
```

---

## SCREEN 01 — Marketing Landing Page

```
Design a bold, modern marketing landing page for a shipping SaaS called "The Shipping Dude". Take inspiration from pirateship.com's clean, confident, slightly playful design style.

HEADER (sticky, 68px tall):
White background with a very subtle bottom shadow. Left side: circular logo badge + "The Shipping Dude" wordmark in dark navy #0F3478, bold. Right side: "Sign in" text link in gray, then "Start shipping free" button in primary navy #1A52A3 with white text, rounded corners, medium size.

HERO SECTION:
Very dark navy background #0B1E3D almost black-navy, full width. Large centered content area. Top: a bold eyebrow tag "The Cheapest Shipping Rates" in sky blue #6BB8D4, small caps, with a subtle pill border. Below: massive white headline in two lines "Ship smarter." on line one, "Pay less postage." on line two. Font: 72px, weight 900, tight tracking. Below headline: a white/60% opacity paragraph "Compare UPS, FedEx, and USPS in seconds. Buy labels instantly. No monthly fees — just pay for what you ship." Below that: a large bright navy-to-blue gradient pill button "Create free account →" (56px tall) and a ghost white-outlined button "See how it works". Small trust note below: "✓ Free forever plan  ✓ No credit card needed  ✓ Credits never expire". At the far right of the hero section, a large device mockup (laptop or wide browser screenshot) showing a clean shipping dashboard UI floating at an angle with subtle drop shadow.

SOCIAL PROOF STRIP:
White background, full width. Center: "Trusted by thousands of online sellers" in gray. A row of 5 star rating reviews from sellers, each with an avatar circle, name, star rating (5 stars in gold/amber), and a short one-line quote. Clean card style with subtle border.

FEATURES SECTION:
Light gray background #F4F6F9. Three feature rows alternating (image left / text right, then text left / image right). Each row: illustration or UI mockup on one side, and on the other: a navy category label (RATES / LABELS / WALLET), a large bold headline, a short paragraph, and a text link "Learn more →" in primary navy.
Row 1: "Compare every carrier in one click" — show a UI mockup of a rate comparison table
Row 2: "Print labels in seconds — thermal or laser" — show a label output preview
Row 3: "Load credits once, ship all month" — show a wallet balance UI

PRICING SECTION:
White background. Centered heading "Simple pricing. No surprises." H1 bold black. Two cards side by side:
Left "FREE" card: white with thin gray border, rounded corners, "$0/month" in large bold, feature checklist with green checkmarks, "Start free" navy ghost button.
Right "PRO" card: dark navy #0F3478 background, white text, a small gold "PRO" badge top right, "$29/month" large white bold, feature checklist with sky-blue checkmarks, "Upgrade to Pro" bright green button.

FOOTER:
Dark navy #0B1E3D background. Three columns: logo + tagline left, navigation links center, social icons right. Bottom bar: "© 2026 The Shipping Dude. All rights reserved."
```

---

## SCREEN 02 — Sign Up Page

```
Design a sign up page for "The Shipping Dude" shipping SaaS. Clean, modern, confidence-inspiring. Reference pirateship.com's friendly-but-professional tone.

Use a two-column layout split 55% / 45%.

LEFT COLUMN (55% width):
Very dark navy #0B1E3D background, full height. Large content centered vertically. Top: "The Shipping Dude" logo (circular badge, white version) 60px. Below: a massive white headline "Start shipping smarter today." weight 800, 40px. Below: white/70% paragraph about the platform in 2 sentences. Below: a vertical list of 4 benefit rows, each with a sky blue checkmark circle icon left and white text right:
  "Real-time rates from UPS, FedEx & USPS"
  "Both 4×6 thermal and 8.5×11 PDF labels"
  "Stripe-powered credit wallet — no monthly fee"
  "25% below retail shipping rates on average"
Bottom of left column: a faint subtle pattern or texture overlay on the dark bg for depth.

RIGHT COLUMN (45% width):
Pure white background. Content centered vertically, max width 380px inside the column. Top: heading "Create your account" 26px bold black. Subtitle "Free forever. No credit card required." in gray 14px. Gap. Form fields stacked with 16px gap between each:
  Full name — input with person icon left inside
  Email address — input with email icon left inside
  Password — input with lock icon, eye toggle button on right
Below password: a thin 4-segment password strength progress bar. Below that: a full-width primary navy button "Create free account" 48px tall. A thin "or" divider with lines. Below (optional for future): "Continue with Google" white button with Google icon, gray border. Bottom: "Already have an account? Sign in →" centered small gray text.
```

---

## SCREEN 03 — Login Page

```
Design a login page for "The Shipping Dude" shipping SaaS. Same two-column layout as the sign up page.

LEFT COLUMN:
Same dark navy #0B1E3D background. Logo at top. Bold white headline "Welcome back, captain." 40px weight 800 (fun, nautical tone matching pirateship.com's playfulness). Below: a short white paragraph. Below: a row of 3 small stat badges — "50k+ users", "1M+ labels printed", "99.9% uptime" — each as a white/10% bg rounded pill with white text.

RIGHT COLUMN:
White background, centered form max 380px. Heading "Sign in" 26px bold black. Subtitle "Good to have you back." gray. Form:
  Email address input (with icon)
  Password input (with lock icon + eye toggle)
  Row below password: "Remember me" checkbox left, "Forgot password?" navy link right.
  Full-width navy primary "Sign in" button 48px.
  Divider.
  "Don't have an account? Create one free →" centered small gray.
```

---

## SCREEN 04 — App Dashboard / Home (Ship Screen)

```
Design the main app dashboard home for "The Shipping Dude" shipping SaaS. Take strong UX inspiration from pirateship.com's web app — dark sidebar, clean white main area, simple step-by-step shipping flow. Do NOT copy their design exactly — make it better, more modern and bolder using the navy blue brand colors.

SIDEBAR (left, 220px wide, fixed full height):
Background: very dark navy #0B1E3D. Top section: logo mark (32px circle badge) + "The Shipping Dude" in white bold 15px. Below that: a subtle horizontal rule. Navigation items stacked vertically with 4px gap. Each nav item: icon (20px) left + label right, 10px vertical padding, 12px horizontal padding, 8px border radius. Active state: bright white background/12%, sky blue icon, white bold text, left accent border 3px sky blue. Inactive: white/50% text, white/30% icon. Nav items: Ship, Rates, Wallet, History, Settings, Support. Bottom of sidebar pinned: wallet balance display — a small dark card showing "Balance" label and "$25.00" in bright sky blue large, with a "Top up" link in white/60%.

TOPBAR (inside main area, 60px tall):
White background with bottom border. Left: page title "Ship a Package" in bold black 20px. Right: user avatar circle (initials "ZA") + name "Zagham Abbas" dropdown.

MAIN CONTENT AREA:
White background. Centered content, max width 780px, padding 40px.

Show a clean multi-step shipping wizard — similar concept to pirateship.com's flow but more modern:

STEP INDICATOR at top: horizontal step progress with 4 steps connected by a line. Steps: "1 Ship to" (active, filled navy circle) → "2 Package" → "3 Rates" → "4 Label". Active step has solid navy circle, completed steps have green check circles, upcoming steps have gray empty circles.

STEP 1 FORM CARD (active, white card with thin border, 12px radius, 32px padding):
Card heading: "Where is this package going?" in bold 20px black, subtitle in gray.
Inside: address form with large well-spaced inputs:
  Full name of recipient — large input, 48px tall
  Company (optional) — input
  Street address — input with map pin icon inside left
  Apartment / Suite / Unit (optional) — smaller input
  Two-column row: City (60%) | State dropdown (40%)
  Two-column row: Country dropdown (60%) | ZIP code (40%)
  Phone number (optional) — with flag dropdown for country code

Address verification banner (shown after typing): a soft blue banner "✓ Address verified by USPS" with a check icon.

Bottom of card: right-aligned "Continue to package details →" primary navy button.

Right sidebar panel (beside the card, 240px):
A subtle light gray #F4F6F9 right panel with:
  "Ship from" section — user's return address displayed as a gray card with address text and a small "Edit" link.
  A tips card below with a lightbulb icon and "💡 Tip: Make sure the ZIP code matches the city for faster delivery."
```

---

## SCREEN 05 — Step 2: Package Details

```
Design Step 2 of the shipping wizard for "The Shipping Dude" app. Same dark sidebar layout as the dashboard.

Topbar shows "Ship a Package" title.
Step indicator shows Step 2 "Package" as active (filled navy), Step 1 "Ship to" shows green check.

MAIN CARD (centered, max 780px):
Heading "Tell us about the package" bold 20px black.

Package type selector — a row of 4 large clickable type cards side by side, each card:
  Tall rounded card 90px tall, white bg, thin border.
  An icon on top (box icon, envelope icon, poly mailer icon, tube icon).
  Label below: "Box", "Envelope", "Soft Pack", "Tube".
  Selected state: navy border 2px, light navy tint bg, navy icon.

Package dimensions section heading "Dimensions (inches)":
Three inputs in a row with labels above each: Length | Width | Height. Each input 100px wide with a subtle "in" unit label inside right side.

Package weight section "Weight":
Two inputs side by side: Pounds (lb) input + Ounces (oz) input. Below: a small note "Carriers charge by actual or dimensional weight — whichever is greater."

Insurance section (optional expandable):
A collapsed row: "Add insurance?" toggle switch right-aligned + dollar value input that appears when toggled on.

Bottom: two buttons — "← Back" ghost left, "Get rates →" primary navy right.

RIGHT PANEL:
Shows a live shipping summary card: "Shipping to: John Smith, Austin TX" with address, and a package preview illustration showing a box with the dimensions entered.
```

---

## SCREEN 06 — Step 3: Rate Comparison

```
Design Step 3 of the shipping wizard — rate comparison — for "The Shipping Dude" app. Same dark sidebar layout. This is the most important screen of the whole app. Make it clean, scannable, and beautiful. Reference pirateship.com's approach: sort cheapest first, show savings clearly.

Topbar: "Ship a Package" title. Step 3 "Rates" active in step indicator.

MAIN CONTENT (centered, max 780px):
Heading "Choose your shipping rate" bold 22px. Subtitle "Sorted cheapest first. All prices include your discounted rate." in gray.

RATE LIST — NOT a table — use a card list format instead:

Each carrier rate is a large clickable card (white bg, thin border, 16px radius, 20px padding) with:
  LEFT: a large radio button circle (40px). When selected: solid navy fill with white dot.
  CENTER LEFT: carrier logo (USPS / UPS / FedEx) as a colored pill badge, then service name bold "Priority Mail 2-Day" in black 16px, then delivery estimate "Est. delivery: Wed May 28" in gray 13px below.
  CENTER RIGHT: optional feature icons — if guaranteed: a clock icon + "Guaranteed", if tracking: shield icon + "Tracked".
  RIGHT: price column — large "$8.94" in bold black 22px on top, below in green text "Save $3.18 vs retail" 12px.

Show 4 rate cards stacked:
  Card 1 SELECTED (highlighted navy border 2px, light #EFF6FF blue tint background): USPS Priority Mail 2-Day | $8.94 | Save $3.18
  Card 2: USPS Ground Advantage | $6.20 | Save $1.80
  Card 3: UPS Ground | $11.22 | Save $4.50
  Card 4: FedEx Home Delivery | $12.50 | Save $5.20

LABEL FORMAT selector below the cards:
Two large toggle card buttons side by side:
  Left: "4×6 Thermal / ZPL" — printer icon, selected (navy border + tint)
  Right: "8.5×11 PDF / Laser" — page icon, unselected

WALLET BALANCE BAR:
A sticky bar at the bottom of the main area before the button. Dark navy #0F3478 background, white text. Left: wallet icon + "Your balance: $25.00". Right: "Add funds" sky blue link. Middle: "After purchase: $16.06" in green.

Bottom: "← Back" ghost + "Buy label — $8.94 →" large emerald green button.

RIGHT PANEL (240px):
"Shipment summary" card showing: To address, package weight + dimensions, selected carrier (updates live as user selects).
```

---

## SCREEN 07 — Purchase Confirmation Modal

```
Design a purchase confirmation modal overlay for "The Shipping Dude" shipping app. The background page behind it is slightly blurred and dimmed.

The modal is centered on screen. White background, 16px border radius, 400px wide, strong drop shadow.

MODAL HEADER:
A navy blue #1A52A3 gradient banner at the very top of the modal (not just an icon — a full colored header strip 70px tall). Inside: a white shipping label icon 28px left + white bold text "Confirm your purchase" right. Below in white/80%: "This will deduct from your wallet balance."

MODAL BODY (white, 28px padding):
A clean receipt-style breakdown:

Carrier pill badge: USPS in red/blue colors + "Priority Mail 2-Day" bold.

A receipt list — thin gray dividers between rows:
  "Label cost"           right: "$8.94" bold black
  "Wallet balance"       right: "$25.00" gray
  ─────────────────────────────────────────────
  "Remaining balance"    right: "$16.06" in bold green

A subtle info note box (light blue bg, blue border-left 3px):
  ℹ️ "Label will be valid for 30 days. Unused labels can be voided for a refund."

MODAL FOOTER (light gray bg #F9FAFB, border-top, 20px padding):
Two buttons side by side equal width: "Cancel" ghost button + "Confirm & Buy" green filled button.

Also design the INSUFFICIENT FUNDS version:
Same modal but "Remaining balance" shows "−$5.06" in bold red. Below the receipt: a red warning box "⚠️ You don't have enough funds. Add at least $5.06 to continue." with a "Top up wallet →" link inside. The "Confirm & Buy" button is grayed out and disabled.
```

---

## SCREEN 08 — Label Ready Screen

```
Design the label success screen for "The Shipping Dude" app after a label has been successfully purchased. This should feel celebratory and satisfying — like a great job well done moment.

Same dark sidebar layout. Topbar shows "Label Ready!" title.

MAIN CONTENT (centered, max 780px):

TOP SUCCESS BANNER (full width card):
Bright emerald green background gradient. White content inside. Left: large white checkmark inside a white circle 48px. Center: "Your label is ready!" white bold 24px, below "USPS Priority Mail 2-Day · Purchased just now" white/80% 13px. Right: a white confetti/celebration subtle graphic element.

LABEL PREVIEW CARD (below, white bg, thin border, 12px radius):
Header bar inside the card: title "Shipping Label Preview" left, three action buttons right:
  [🖨 Print] — navy filled button with printer icon
  [⬇ PDF] — ghost outlined button
  [⬇ ZPL] — ghost outlined button

Preview area (light gray bg #F4F6F9, padding 20px):
A realistic shipping label mock inside a white rectangle with thin border, proportioned 4×6:
  Top: carrier logo (USPS) + service name
  Left: FROM address block
  Right: TO address block large bold
  Center: a realistic barcode (thick and thin black lines)
  Bottom: tracking number in monospace, large

TRACKING SECTION (below, white card):
"Track this shipment" heading. A horizontal timeline showing:
  ● Label created (today, green filled circle)
  ○ In transit (empty gray)
  ○ Out for delivery (empty gray)
  ○ Delivered (empty gray)
  Lines connecting each step.
  Tracking number: "9400111899223756150068" monospace with a copy button icon.

NEXT STEPS ROW (3 small cards in a row below):
  Card 1: "Ship another package →" with a package icon, navy link
  Card 2: "View label history →" with a clock icon, navy link
  Card 3: "Top up wallet →" with a wallet icon + balance shown, navy link
```

---

## SCREEN 09 — Wallet / Credits Page

```
Design the wallet page for "The Shipping Dude" shipping SaaS. Clean, trust-inspiring, similar feel to a modern fintech app. Dark sidebar visible.

Topbar: "Wallet" title.

MAIN CONTENT (centered, max 700px):

BALANCE HERO CARD:
A premium-feeling card with a dark navy #0F3478 to #1A52A3 gradient background, 16px radius, no border. White content inside. Top: "Available Balance" small uppercase white/60% label. Below: "$25.00" in massive white text 64px weight 900 tabular numbers. Below: "USD · Credits never expire" white/50% small. Bottom right corner: a subtle abstract pattern or wave graphic in white/10% for visual interest.

ADD CREDITS SECTION:
White card below, thin border, 12px radius, 28px padding. Section heading "Add credits" bold 18px black. Subtitle "Funds are added instantly to your account via Stripe." gray 13px.

Amount selector grid — 5 pill buttons in a row:
  Each pill: white bg, gray border, rounded 99px, 40px tall, 18px text, font-weight 600.
  Labels: $10 | $25 | $50 | $100 | $250
  Selected ($50): navy #1A52A3 bg, white text, navy border, subtle shadow.

Custom amount row below: "Or enter custom amount:" small label + a currency input field with "$" prefix, max-width 200px.

Full-width primary navy button "Add $50 to my wallet →" 50px tall, below.
Below button: centered small row — Stripe logo + padlock icon + "256-bit SSL secured payment" in gray 12px.

TRANSACTION HISTORY SECTION (below):
Heading "Transaction history" 18px bold, and a small "Export CSV ↓" ghost button right-aligned.

Transaction list — white card, thin border, 12px radius, no internal padding (rows have their own padding):
Each row (48px tall, 20px horizontal padding, thin top border divider):
  Left: transaction type icon (colored circle 32px) + transaction name bold 14px + date gray 12px below
  Right: amount colored large bold 16px tabular nums (green for credits "+$50.00", red for debits "−$8.94") + "bal $41.06" small gray below

Transaction types and icon colors:
  Credit top-up: green circle with up arrow icon
  Label purchase: navy circle with label icon
  Welcome bonus: gold circle with gift icon
  Refund: orange circle with return arrow icon

Show 5 rows. Last row: "Load more transactions" centered gray link.
```

---

## SCREEN 10 — Rate Quote (Quick Look) Page

```
Design a standalone "Quick Rate Quote" page for "The Shipping Dude" app for users who just want to check rates without going through the full shipping wizard. Dark sidebar visible.

Topbar: "Rate Quote" title.

MAIN CONTENT (two-column layout, max 1000px centered):

LEFT COLUMN (60% width) — THE FORM:
White card, thin border, 12px radius. Heading "Get a rate quote" bold 20px. Subtitle "No purchase needed — just check prices." gray.

Form sections inside the card with section dividers:

FROM section: a read-only gray display showing the user's saved return address with an "Edit address" link in navy.

TO section: address fields — Name (optional), Street, City + State row (2-col), Country + ZIP row (2-col).

PACKAGE section: heading "Package details". Dimensions row (L × W × H inputs, compact). Weight row (lb + oz inputs). Package type — 4 icon-buttons in a compact row (Box, Envelope, Soft Pack, Tube), small, 36px tall.

"Get rates" green button full width of the card, 48px tall.

RIGHT COLUMN (40% width) — RESULTS:
Shows after clicking "Get rates".
Heading "Carrier options" 18px bold.

3 result cards stacked (same card-list style as the wizard screen):
Each card: carrier badge left + service name + delivery estimate + "Save $X" green tag + price right bold.

Below the rate cards:
A compact label format toggle (small pill buttons: "Thermal 4×6" | "Laser PDF") and a "Buy this label →" green button full width.

If no results yet: show an empty state illustration (a ship/package icon, grayed out) with "Enter your shipment details to see rates." in gray centered.
```

---

## SCREEN 11 — Settings Page

```
Design a settings page for "The Shipping Dude" shipping app. Dark sidebar visible. Clean, organized — like Stripe's settings or Linear's settings style.

Topbar: "Settings" title.

MAIN CONTENT (max 680px centered):

A left mini-nav (horizontal tabs below the topbar or a small left sub-nav):
Tabs: "Profile" (active) | "Return Address" | "Label Defaults" | "Password" | "Billing"

PROFILE TAB CONTENT:

Section card "Your account":
White card, thin border, 12px radius, 28px padding.
  User avatar — large 72px circle with user's initials "ZA" in navy on light navy bg. An "Upload photo" link below the avatar.
  "Display name" labeled input pre-filled "Zagham Abbas".
  "Email address" read-only field showing email with a verified green checkmark badge next to it.
  "Save changes" navy button right-aligned, medium size.

Section card "Danger zone" below (subtle red border):
  "Delete account" — left: heading + description in gray. Right: red ghost "Delete account" button.

RETURN ADDRESS TAB CONTENT (design as a separate frame):
White card. Heading "Your return address" bold. Subtitle "This address appears as the sender on all your labels."
Address form fields: Name, Company (optional), Street, City + State row, Country + ZIP row, Phone.
"Save address" navy button.

LABEL DEFAULTS TAB (design as a separate frame):
Two preference rows with horizontal dividers:
  "Default label size" — toggle pills: [4×6 Thermal] [8.5×11 PDF]
  "Default weight unit" — toggle pills: [lbs / oz] [kg / g]
  "Default dimensions unit" — toggle pills: [inches] [cm]
"Save defaults" navy button.
```

---

## SCREEN 12 — Label History Page

```
Design a label purchase history page for "The Shipping Dude" shipping app. Clean, data-rich, scannable. Reference pirateship.com's history/shipments concept. Dark sidebar visible.

Topbar: "Label History" title. Right: "Export CSV" ghost button.

FILTER BAR (below topbar, white bg, border-bottom, 56px tall):
Horizontal row of filters with gap between each:
  Search input (240px) with magnifier icon inside — "Search by name, tracking, ZIP…"
  Status dropdown pill: "All statuses ▾"
  Carrier dropdown pill: "All carriers ▾"
  Date range pill: "Last 30 days ▾"
  Total label count: right-aligned gray text "32 labels"

SHIPMENT LIST (below filter bar, white bg):
NOT a traditional table — use a modern card list. Each shipment row is a horizontal card (white bg, thin bottom border, 70px tall, 20px horizontal padding, hover state light gray):

Row layout:
  FAR LEFT: a colored carrier badge (USPS red/blue pill | UPS brown pill | FedEx purple/orange pill), 70px wide.
  LEFT: recipient name bold 14px black + address below in gray 12px.
  CENTER: tracking number in monospace 13px gray + a copy icon button.
  CENTER RIGHT: date purchased — "May 15, 2026" gray 13px.
  RIGHT: price "$8.94" bold 15px black.
  FAR RIGHT: status badge pill (green "Delivered" | navy "Shipped" | blue "In Transit" | red "Failed") + a three-dot kebab menu icon.

Show 6 rows. Last row in red tint (failed).

ROW EXPANDED STATE (click to expand — show below the row):
Expanded area (light gray bg, padding 16px, border-top dashed):
  Left col: tracking timeline — 4 steps horizontal (Label Created ✓ → Picked Up ✓ → In Transit → Delivered)
  Right col: two buttons — [Download label ↓] ghost button + [Void label] red ghost button

PAGINATION (bottom, centered): ← Prev  "Page 1 of 4"  Next →
```

---

## SCREEN 13 — Plans & Upgrade Page

```
Design a pricing and upgrade page for "The Shipping Dude" shipping app. Should feel premium and compelling — this is the page that converts free users to Pro. Dark sidebar visible.

Topbar: "Upgrade to Pro" title.

MAIN CONTENT (centered max 800px):

TOP SECTION:
Centered heading "You're on the Free plan" gray 14px small. Below: a large bold heading "Unlock the full experience" 36px weight 800 black. Below: "Ship more, save more, and run your shipping like a pro." gray paragraph.

PLAN CARDS (two cards side by side, equal width, generous gap):

FREE CARD:
White bg, thin gray border, 16px radius, 32px padding.
Top: "FREE" small gray uppercase label + "$0 / month" large 42px bold black.
Divider. Feature list (gap 14px between items):
  ✓ Real-time rate quotes
  ✓ Single label purchase
  ✓ Credit wallet (Stripe)
  ✓ PDF + thermal ZPL labels
  ✗ Batch CSV upload (50 labels limit) — gray crossed
  ✗ Custom return address profiles — gray crossed
  ✗ White-label (no branding) — gray crossed
  ✗ Priority support — gray crossed
Bottom: "Current plan" disabled gray pill button centered.

PRO CARD (this card should dominate the design):
Rich dark navy #0F3478 background, 16px radius, 32px padding. Slightly taller with a blue glow/shadow. A "MOST POPULAR" gold amber ribbon badge at top-right corner. 
Top: "PRO" sky blue small uppercase label + "$29 / month" 42px bold white. Below price: "billed monthly — or $24/mo billed annually" white/60% small.
Divider (white/20%). Feature list (gap 14px):
  ✓ Everything in Free
  ✓ Batch CSV upload (500 labels)
  ✓ Custom return address profiles
  ✓ White-label (your brand, no Shipping Dude logo)
  ✓ Package size presets
  ✓ Priority email support
  ✓ Better carrier rates
Bottom: large bright emerald green "Upgrade to Pro →" button full width, 52px tall.

BELOW CARDS — FAQ strip (3 short questions and answers in 3 columns, light gray bg, rounded card):
  "Can I cancel anytime?" / "What payment methods?" / "Do credits carry over?"
```

---

## SCREEN 14 — Batch Upload Page (Pro Feature)

```
Design a batch CSV label upload page for "The Shipping Dude" shipping app. Pro-only feature — show a PRO badge near the title. Dark sidebar visible.

Topbar: "Batch Upload" title + small gold "PRO" pill badge.

MAIN CONTENT (centered max 780px):

A horizontal 3-step progress indicator at the very top: "1 Upload" (active) → "2 Review" → "3 Purchase". Connected by a thin line, active step is navy filled circle, others are gray.

STEP 1 — UPLOAD (active):

Top info card (light blue bg, blue left border 4px, 16px radius):
  📋 "Download our CSV template to get started. Make sure columns match exactly."
  [Download template ↓] navy text link right-aligned.

Large drag and drop zone (main feature of this view):
  White bg, border-radius 16px, border 2px dashed #CBD5E1, padding 60px, text-center.
  Large cloud-upload icon in navy blue/30% opacity, 64px.
  Bold text "Drag & drop your CSV file here" 20px black.
  Below: "or" in gray.
  "Browse files" primary navy button, medium size.
  Below button: "Supports CSV files up to 500 rows · Max 10MB" small gray.

STEP 2 — REVIEW (show as a separate frame):
Step indicator shows step 2 active, step 1 green check.
Summary bar (dark navy bg, white text, full width, 52px):
  Left: "📋 247 rows loaded" | center: "✅ 241 valid  ❌ 6 errors" | right: "Est. total $2,147.20"

Table (white card):
  Header: # | Recipient | To Address | Weight | Service | Rate | Status
  Valid rows: white bg, green "Valid" badge in Status column.
  Error rows: light red tint bg, red "Error" badge in Status, a red tooltip icon showing the error reason.

Bottom: "← Re-upload" ghost left + "Purchase 241 labels — $2,147.20 →" green button right.

STEP 3 — PROCESSING (show as a separate frame):
Large centered progress area:
  A circular progress ring (navy animated) at 65% fill.
  "Purchasing labels…" bold text center.
  "187 of 241 complete" gray below.
  A cancel link "Cancel remaining" in red small below.
```

---

## SCREEN 15 — Mobile: Dashboard (390px iPhone)

```
Design the mobile version of the "The Shipping Dude" shipping app dashboard at 390px width (iPhone 14 size).

NO sidebar. Instead: a fixed bottom tab bar (80px tall including safe area) with 6 tabs. Each tab: icon (22px) above + label (10px) below, centered. Active: navy blue icon + navy text. Inactive: gray icon + gray text. Background white, thin top border. Tabs: Ship | Rates | Wallet | History | Settings | Support.

TOP AREA (no traditional topbar — instead):
A bold full-width hero card at the very top, navy #0F3478 gradient background, 0 border radius (flush to edges). Content inside with 20px padding:
  Left: "Good morning," gray/60% small + "Zagham" white 24px bold below.
  Right: wallet balance — "$25.00" in sky blue large bold + "balance" gray/60% below.

Below the hero card: a quick actions row of 3 equal icon buttons (white cards, thin border, 12px radius, stacked icon + label):
  [📦 New label] [📊 Rate quote] [💳 Top up]

MAIN SCROLLABLE CONTENT (light gray bg, 16px padding):

Feature cards stacked full width with gap:
  Card 1 (white, thin border, 12px radius): Package icon top left + "Create a label" bold + description + "Start →" navy link bottom right.
  Card 2: Chart icon + "Check rates" bold + description + "Compare →" navy link.
  Card 3 (dashed border lighter): "Need help?" + "Email our support team →" link.

All cards full width, no grid on mobile.
Bottom padding 100px to avoid bottom tab bar overlap.
```

---

## SCREEN 16 — Mobile: Rate Wizard Step 1 — Address (390px)

```
Design the mobile rate wizard step 1 (Ship To address) for "The Shipping Dude" app at 390px iPhone width.

TOP: White header bar 56px. Left: "← Back" ghost small link. Center: "Ship a package" bold 16px. Right: "Step 1 of 4" small navy text.

BELOW HEADER: A thin step progress bar full width, 4px tall. Navy fill up to 25% (step 1 of 4).

MAIN SCROLL AREA (white bg, 20px horizontal padding):
Heading "Where's this going?" 22px bold black, margin-top 20px.

Form fields stacked with 14px gap:
  Recipient name — full-width input 50px tall
  Company (optional) — full-width input
  Street address — full-width input with map-pin icon inside
  City — full-width input
  State — full-width dropdown (native style)
  Country — full-width dropdown
  ZIP / Postal code — full-width input, numeric keyboard

A blue verification banner below (after typing ZIP): "✓ Address verified" in green.

BOTTOM STICKY BAR (white bg, border-top, 80px tall including safe area):
Full-width "Continue →" primary navy button inside, 50px tall, 20px margin.
```

---

## SCREEN 17 — Mobile: Wallet Page (390px)

```
Design the mobile wallet page for "The Shipping Dude" shipping app at 390px iPhone width.

TOP HEADER: White header bar, "Wallet" bold centered.

BALANCE CARD (full width, no side margin, flush to top below header):
Rich dark navy gradient card (#0F3478 to #1A52A3), 0 top border radius (flush to header), 24px bottom radius. White content, 24px padding.
  "Available balance" white/60% small label.
  "$25.00" massive 56px weight 900 white tabular nums.
  "USD" white/50% 12px.
  Bottom: "Credits never expire ✓" white/60% 12px.

ADD CREDITS SECTION (below balance card, white bg, 20px padding):
"Add credits" bold 18px. Subtitle gray 13px.
Amount pill buttons in a 3×2 grid (3 per row, 2 rows):
  $10  $25  $50
  $100  $250  Custom
Each pill: full pill shape (99px radius), equal width, 44px tall. Selected: navy bg + white text.

"Add $50 to wallet" full-width navy primary button 50px.
"🔒 Stripe secured" centered small gray below.

TRANSACTION LIST (below, white bg, 20px horizontal padding):
"Recent transactions" bold 16px.
4 rows with thin top dividers:
  Each: icon circle (32px) left + type + date (stacked) center + amount right.
"View all transactions →" navy link centered bottom.
```

---

## TIPS FOR BEST RESULTS IN FIGMA FIRST DRAFT

1. Open Figma → press Cmd+K → search "First Draft" OR use the AI panel (sparkle icon).
2. Create a blank frame first (1440×900 desktop or 390×844 mobile) then trigger First Draft.
3. Paste ONE prompt at a time — do not combine multiple screen prompts.
4. After generation, type follow-up refinements in plain language:
   - "Make the sidebar background darker"
   - "The balance number should be much bigger and bolder"
   - "Add more whitespace between the form sections"
   - "Make the Pro plan card stand out more with a glow effect"
   - "The rate cards need more padding and a cleaner layout"
5. Generate desktop screens first (1440px), then re-prompt for mobile (390px) separately.
6. Always generate the Design Tokens (STEP 1) first for color/type consistency.
