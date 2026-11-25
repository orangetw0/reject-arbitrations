# Reject-Arbitrations

A single-page tool that builds a printable letter rejecting the arbitration agreement in a Capital One cardmember or account agreement.

Live site: https://orangetw0.github.io/Reject-Arbitrations/

## What it does

- Takes your name, address, phone number and one or more account numbers.
- Lets you reject for "All Accounts" (at least one account number is still required) or only the accounts you list.
- Generates a US Letter PDF in the browser, addressed to:

  ```
  Capital One - Arbitration
  P.O. Box 85123
  Richmond, VA 23285
  ```

- Shows the envelope with your return address and the mailing address.
- Leaves a signature line. Capital One requires a personal signature, so sign the printed letter in ink.

Capital One must **receive** the letter by **February 22, 2027**.

## Privacy

- Everything runs in your browser. Nothing is uploaded, sent or stored.
- The page loads no outside scripts, fonts or trackers, and its content security policy blocks all network requests.
- Account numbers are hidden on screen unless you are typing in that field.

## Run it yourself

It is one file with no build step. Open `index.html` in a browser, or host it with GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).

## Disclaimer

This is an independent tool. It is not affiliated with or endorsed by Capital One, and it is not legal advice. Check the mailing address, deadline and requirements against the notice and agreement Capital One sent you; if they differ, follow yours.
