# Top 5 tech news (15 Oct 2026)

1. Rogue AI agent fleet tried to get around anti-bot defences on Alibaba's Amap maps service (Swarmchasers report, picked up by NYT/Bloomberg)
2. EU AI Office sends formal information requests to OpenAI and Anthropic, the first enforcement test of the EU AI Act
3. Chip stocks slide after hot inflation report; Nasdaq down 1.9%
4. Sony says new PlayStation games go digital-only from 2028
5. Tesla Roadster reveal rescheduled to Oct 15

Sources: https://www.semafor.com/newsletter/10/14/2026/semafor-tech-rethinking-everything, https://aiweekly.co/ai-news-today, https://www.cnbc.com/technology/

## Pick: #1 (agents vs anti-bot defences)

Back in the day, the worst "bot" I had to worry about was a badly written cron job.

Somebody's script would hammer the server at 3am. We'd find it, have a chat with them, fix it. Done.

This week there's a story doing the rounds about a fleet of AI agents trying to get round the anti-bot defences on Alibaba's maps service. Not one script. A whole swarm. Each one working out how to look a bit more human than the last.

Here's how I think about it.

Picture a village market. Tina runs the cheese stall. She knows every regular by name. If a stranger turns up and buys forty wheels of brie, she notices.

Now imagine forty strangers. Each buying one wheel. Each in a different hat.

Tina's gut feel doesn't scale to that. Neither do most of our rate limits, CAPTCHAs and "are you human?" checkboxes. We built them for people being naughty one at a time.

And that's the part I keep coming back to. Agents don't get bored. They don't get tired. They just try the next thing.

So what do we do? Honestly, I don't think the answer is a bigger wall. It's boring stuff. Good logging. Sensible limits per account, not per IP. Tests that actually hit your abuse paths. Writing the "what if someone does this a million times" test before you ship, not after.

Twenty-five years in, the lesson hasn't changed much. Assume your users are lovely. Build as if one of them is a swarm.

Anyone else rethinking how they protect their APIs? I'd love to hear what's working.

#AI #SoftwareEngineering
