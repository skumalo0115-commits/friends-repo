# Design Collective SA

A responsive, static first-look website for the South African creative marketplace described in the pitch. It introduces the concept, shows example categories and creators, and explains the value to makers, customers and the wider creative community.

## Preview locally

Open `index.html` in a browser, or run any static file server from this directory.

## Deploy on Vercel

1. Put this directory in a Git repository and import it into Vercel.
2. Select **Other** as the framework preset.
3. Leave the build command empty and use `.` as the output directory.
4. Deploy. The site is plain HTML, CSS and JavaScript; it has no build step or server runtime.

## Before presenting this as a live marketplace

This version is a concept and visual preview. The work cards are sample content; they do not represent verified sellers or live inventory. The site does not create accounts, accept listings, process orders or payments, collect enquiries, or provide search across a real catalogue. Its browsing controls only filter the sample cards.

To launch the marketplace, decide and implement:

- Creator registration, profile review, listing creation, image uploads and moderation.
- Customer accounts (if needed), catalogue search, availability, order and delivery flows.
- Checkout and a payment provider, with clear commission, fees, refunds, cancellations and seller payout rules.
- The chosen business model. The pitch mentions sales commissions, sponsored listings, brand advertising, partnerships, workshops/masterclasses and community events; none are implemented here.
- A real contact address, creator onboarding path and launch/waitlist flow.
- Privacy notice, terms for creators and buyers, cookie/analytics choices, and applicable South African consumer, privacy, tax and payment obligations.
- Real creator permissions, product photography, accurate locations/prices, social links and brand assets.
- Production checks for accessibility, responsive layouts, metadata/social previews, analytics consent, security and performance.

The business-reference dictionary and CatBoost/NLP classification pipeline described in the request are not part of this marketplace front end and have not been changed or represented as running on this site.
