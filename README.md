# DeepSeek Peak Hours

Live indicator of whether DeepSeek API pricing is currently at peak or off-peak rates.

**🔗 https://sxc562586657.github.io/deepseek-peak-hours/**

Off-peak rates are half of peak rates. Peak hours are 01:00–04:00 and 06:00–10:00 UTC,
Monday through Friday. All other hours (including weekends) are off-peak.

The page is a single static `index.html` — no backend, no build step — that computes
the current status client-side from the browser's clock and shows a live countdown to
the next peak/off-peak transition.
