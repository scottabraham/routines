# LinkedIn post: Microsoft 365 outage (23 Nov 2026)

## This week's top 5 tech stories
1. Microsoft 365 outage takes down Outlook, Teams and Copilot worldwide (from 12 Nov). Microsoft traced it to a fault left behind by an earlier network-capacity upgrade. https://bleepingcomputer.com/news/microsoft/massive-microsoft-365-outage-disrupts-outlook-teams-copilot-worldwide
2. Nvidia shares have their longest weekly losing streak since 2008, and the company faces more scrutiny. https://technologymagazine.com/news/microsoft-pwc-dell-nvidia-amd-and-zoom-top-tech-news
3. Anthropic's IPO prices at $83 a share, then falls about 9% on its first full day of trading. https://singularityhub.com/2026/11/21/this-weeks-awesome-tech-stories-from-around-the-web-through-november-21-2
4. California's DMV bans Waymo robotaxis after two incidents in the Bay Area. https://singularityhub.com/2026/11/21/this-weeks-awesome-tech-stories-from-around-the-web-through-november-21-2
5. New AI models: OpenAI's GPT-6 Cyber and Google's Gemini 4 Carbon. AMD is now in more than 40% of the new TOP500 supercomputer list (SC26). https://www.tomshardware.com/tech-industry/supercomputers/

**Picked:** #1. It's about the people who keep systems running and about latent bugs, and it fits Scott's takes on prevention and testing.

---

## Post

Meet Dave. Dave's a builder.

A while back, Dave put an extension on a house. Bigger kitchen, more room, everyone happy. Job done. Dave went home.

Then, months later, someone swaps a light switch in the hallway. And the kitchen ceiling falls in.

Was it the light switch? Sort of. But really, it was something Dave left behind. Sat there quietly. Waiting.

That's basically what took down Outlook, Teams and Copilot for millions of people last week. Microsoft traced it to a fault left over from a past upgrade that added capacity to its network. A later change woke it up. 74 countries. Hours of no email.

Now, I'm not having a go at Microsoft. I've been doing this for 25 years. I've been Dave. More than once.

Back in the early 2000s I shipped a "quick fix" to a desktop app. Worked perfectly. Six months later, a completely unrelated change brought the whole thing crashing down. I spent two days blaming the new code. It was mine all along.

And that's the part that stings.

The change that breaks things is rarely the change that caused it. It's just the one that got caught holding the knife.

That's a big part of why I bang on about tests. Not because tests are fun (they are, a bit). But because a good test suite is basically a note Dave leaves for whoever comes next. "Hey, the kitchen ceiling depends on this. Be careful."

Without that note, you're just hoping. And hope isn't a deployment strategy.

Spare a thought for the folks who were up all night fixing this one. Nobody claps when the email works.

How do you all catch the stuff that's sat quietly waiting to break? Any war stories?

#SoftwareEngineering #TDD
