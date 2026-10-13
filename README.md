# BOGEY BRAWL · Battle Golf

Everyone tees off at once on four holes, from a lakeside par 4 to a desert canyon, a frozen fjord and a volcano island at night. First ball in the cup scores the most, but golf carts, rockets, orbital lasers, tornadoes and banana peels mean nobody gets a quiet putt.

Built with Three.js · Custom 3D golfer & props. Part of [Shreyansh Sharan's portfolio](https://shreyansh-sharan.github.io/shreyanshsharan-portfolio/), split into its own site.

```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # production build in dist/
npm run lint     # oxlint
```

The site is a single page: `#/` is the game's menu, and the same query parameters the portfolio used still work
(for example `#/?auto=...` to skip the menu, `#/?join=CODE` for an invite link).

## Controls

- `W` `A` `S` `D` run · mouse to look
- `LMB` hold to charge, release to swing (near a rival: club them)
- `RMB` or `X` while charging: cancel the shot
- `Wheel` loft · `RMB` use item
- `1` `2` `3` / `Q` pick slot · `F` drop
- `Space` jump · `Shift` dive · `C` creep
- `E` get in/out of a cart · in a cart: `W`/`S` drive, `A`/`D` steer, `Space` handbrake, `H` horn
- `Esc` release the mouse

## Ads and gear

Optional AdSense and Amazon affiliate IDs come from environment variables (see `.env.example`). Leave them empty and
no ad or shop code loads.
