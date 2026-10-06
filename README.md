# Québec Votes 2026

Live election night dashboard for the October 5, 2026 Québec general election: 127 ridings, race to 64 seats.

**Open it:** https://naimouellet.github.io/qc-election-night/

The page reads the [Élections Québec open data results feed](https://www.dgeq.org/donnees.html) directly from your browser and checks for new results every minute. Élections Québec updates the feed every 2 to 5 minutes.

`data/qc-data.js` holds the 2026 riding boundaries (simplified) and the official candidate list, both from Élections Québec open data.

Seats are marked won by this page's own rule (all polls in, or a lead that's safe for the share of polls still out). Élections Québec doesn't declare winners on election night, and TV networks may call ridings differently.
