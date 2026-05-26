# flap-bountyfeed

Companion package for **Flap**. Streams the per-day bounty pool size, top scores, and claimable-share calculations off the chain stream so clients can show "today's pot: X cUSD" without a per-load aggregation.

Pairs with [`@winsznx/flapwire`](https://github.com/winsznx/flapwire).

## Status

Scaffold for the publisher. Real-world wiring: `PlayOpened` + `PlaySettled` + `BountySponsored` + `BountyClaimed` rolled into a `(day, pool, top)` digest per UTC day.

## License

MIT
