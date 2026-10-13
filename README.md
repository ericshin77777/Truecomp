# Truecomp

A prototype trading card app for collectors and vendors (Pokémon, Magic: The Gathering, sports cards). It's a single HTML page with no build step.

## Features

- **Price check**: one fair value plus a defensible range, with every sale shown and why it counted or didn't
- **Binder scan**: price a 9-pocket binder page at once
- **Reprice**: flag only the stickers that need changing, in table order
- **Deal check**: see whether an offer is a lowball, and get help countering
- **Condition check and Community**: crowd condition calls, threads and tokens

## Run it

Open `index.html` in a browser, or turn on GitHub Pages for this repo.

## Limitations

- Prices are generated sample data, not live market data.
- Binder-scan card recognition is simulated.
- Condition check and Community depend on claude.ai's shared database. Outside claude.ai they show a "not available" notice. Hosting them yourself needs a real backend (for example Firebase or Supabase) with user accounts.
