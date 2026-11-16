# LinkedIn post: United bans AI booking agents (2026-11-16)

Source: United Airlines moves to block personal AI agents from booking flights (Skift, 11 Nov 2026)
https://skift.com/2026/11/11/united-airlines-moves-to-block-personal-ai-agents-from-booking-flights/

---

Meet Tina. Tina's busy. So she sends her assistant, Bob, to the travel agent to book her a flight.

Bob's keen. Very keen. Bob also isn't a person. He's an AI agent.

The travel agent looks at Bob. Looks at the queue. Then says, "Sorry Bob, we don't serve your sort here."

That's basically what United did this week. They updated their contract of carriage to say AI agents can't book, change or buy travel on your behalf. And from what I've read, that still applies if Tina is sat right there approving every click.

Their reasons? Security. Privacy. And, reading between the lines, they don't fancy another middleman sitting between them and their customers.

I've been building for the web since 2001. Back then the "bots" were scrapers hammering your server at 3am, and the answer was a CAPTCHA and a strongly worded robots.txt. Not much has changed, really. We're just having the same argument with much smarter bots.

And honestly? I get it from both sides.

If I'm the one maintaining that booking system, an agent I can't identify, clicking through a UI that was designed for humans, is a nightmare. Every redesign breaks it. Every edge case becomes a support ticket. And when it books Tina into Newark instead of Newcastle, who gets the blame?

But Tina just wanted a flight.

The fix isn't a ban. It's an API. A proper, authenticated, well-tested front door for agents. United have pretty much said this themselves, that they'd want direct integrations with proper controls in place first.

That's the part that's missing.

If you don't build a front door, people will keep climbing through the window.

Any other devs out there building for agents yet? Or are we all still pretending Bob doesn't exist?
