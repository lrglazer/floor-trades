# Floor Trades

Congressional stock trade tracker. Static site (index.html + head/ cartoons).

New filings go in `data/live.json` (`trades` array, same fields as the built-in data:
m, tk, co, type, lo, hi, td, fd, own, sec, note, opt). The page polls that file every
5 minutes, so committing to it updates the live site after Render redeploys.
