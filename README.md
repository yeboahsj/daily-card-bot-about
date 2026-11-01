# daily-card-bot

daily-card-bot is a small, private research project run by one person in Ontario, Canada. Twice each weekday it writes one short card for its owner explaining why a single stock, fund, cryptocurrency or the whole market moved that day. The cards are read by its owner only. They are not published, sold or shown to anyone else.

## What it reads

- A site's `robots.txt`, before anything else on that site, once per run. It identifies itself as `daily-card-bot/1.0 (+https://github.com/yeboahsj/daily-card-bot-about)`. The one exception is the SEC, whose fair-access policy asks every request for a name and a contact email, so the SEC is asked under `daily-card-bot` and a contact address, as the bot's SEC filing reads already are.
- If your `robots.txt` turns away any of Anthropic's crawlers (ClaudeBot, Claude-SearchBot, Claude-User, anthropic-ai, Claude-Web), or points to a licence, the bot does not open your pages for its AI to read.
- If the answer is unclear (a refusal, an error, a firewall page), the bot treats it as a no and sends nothing more.
- It never pretends to be a browser or another company's crawler, and it does not retry after a refusal.
- Search results and short excerpts from search services can still mention your pages; how the bot treats those is still being decided.
- Price and filing data come from public data services under their own terms.

## Contact

If you run a site and want the bot to stop reading it, or have any question about it, email **yeboah.slyjr@gmail.com**. If you write to say no, the bot will stop reading your site. If your robots file says no and you would like the bot to read your pages, a written yes is followed too.
