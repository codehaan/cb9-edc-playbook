# CB9 Small Business Playbook (prototype)

A small neighborhood help desk for businesses in Brooklyn Community District 9, from the CB9 Economic Development Committee. It's built to be demoed at the December small-business brunch, which is our first test with owners.

Open `index.html` in a browser. There's no build step, and Google Fonts is the only outside dependency.

## What CB9 does here

We curate, explain, connect and escalate. We don't replace SBS, MyCity, 311, lawyers, lenders or City agencies.

## Structure

- **Home:** "What do you need help with?", seven problem cards, How CB9 can help, what's coming up, What we're hearing, and the Tell CB9 call to action
- **Seven pathways** (`#help-lease`, `#help-city`, `#help-money`, `#help-trash`, `#help-customers`, `#help-connect`, `#help-unsure`). Each one follows: What to do first → Your next steps → Best official resource → If that doesn't solve it → Still stuck? Tell CB9
- **Doing Business in CB9** (`#local`): events, three ways to take part, and What we're hearing
- **Tell CB9** (`#tell`), the safety net, which is always one tap away
- **Join the network** (`#join`)
- **Brunch QR landing page** (`#brunch`)

## Updating content

The pathways, events and "What we're hearing" items are plain data arrays (`P`, `EVENTS`, `HEARD`) near the top of the script in `index.html`.

## Placeholders

Anything marked **VERIFY** or shown as a highlighted `[placeholder]` needs CB9 confirmation before launch. The forms and the "Did this page help?" buttons don't send data anywhere yet.
