# BT Hosting Platform

This is a monorepo for the B&T Digital Hosting Platform

## Positioning

- Luxury Pricing and support
- On the client's side
  - Against vendor lockin
    - Always yours, always exportable (but always the best deal anyway).

### Product Name and Brand

*"Something"* by B&T Digital

Simple and non-technical, friendly and credible.

"ServerSorted"

Preferably Minimal Sylablles and tangential to B&T Brand - leafy maybe?

## Requirements

- Able to support more than one service
  - Start with word press
  - Alternate CMSs
  - NEXTErp
  - Vault warden?
  - Vikunja?
- Teraform Scripts to commission and decomission assets in accounts
- Integration with stripe
- Isolated Backups
- Integration with dns

## Project Management

- [Vikunja Kanban](https://vik.btdigital.com.au/projects/2/8)
- [Github issues](https://github.com/benisrael29/bt-wp-hosted/issues)
- This File

## Stack _(Technology Discovery)_

### Portal

*RedwoodJS?*

#### Front end
- React
- Astro
  - *up and comer*
  - Positive Sentiment
  - Not sure we need it
  - Allows for composite front end ie vue, react, svelte...

#### Backend

- Node *experience*
- Go *best in class*

Tony advocating againt GQL (on the basis of simplicity and security)

#### Hosted Auth

- Clerk
  - *heard it's amazing*
  - Free tier will more than accomodate possible user count - free upto 10,000 MAOs
  - Simple Integration of other tools
- Self Hosted
  - Simple.....???

#### Payment Gateway

- Stripe *pretty much already setup 30c +2.9%*
- Ayden - *Cheap, but not sure if serves smbs 13c +?%*
- PayPal - *trusted*

### Core Backend Architecture

- DNS
  - Route53
- Core
  - LightSail
    - (This seems kinda expensive/high level to me having had a look....) _(tony)_
-