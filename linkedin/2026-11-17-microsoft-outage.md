# LinkedIn post: 2026-11-17

**Story picked:** Microsoft's global outage, reportedly caused by a software defect introduced in a July fix (The Register, NBC News).

**Top 5 trending tech stories today:**
1. Nvidia leadership crisis: allies lobby for Jensen Huang's return as board investigation continues
2. Microsoft global outage, blamed on a defect from a July fix
3. Apple launches a 200,000-person study on trust in conversational health AI
4. Notion says a supplier breach exposed some Notion AI chats
5. CNCF survey: 75% of cloud-native devs ship AI-assisted code; Amazon warns staff against inflating token usage

---

Meet Dave.

Back in July, Dave fixed a bug. Good lad. Ticket closed, PR merged, everyone went home happy.

Dave's fix was fine. Mostly.

Tucked inside it was a tiny little defect. It didn't make a fuss. It just sat there. Quietly. For about four months.

Then one day it woke up and took a chunk of the internet with it.

That's roughly what's being reported about Microsoft's big outage this week. Services are back, but the cause apparently goes back to a fix from July.

And honestly? I've been Dave.

Not at Microsoft's scale, thankfully. But 25 years in, I've shipped a "quick fix" that broke something three screens away. Back in the Visual SourceSafe days, the only regression suite I had was me, clicking around and hoping.

Here's the thing people forget about fixes.

A fix is just new code. It deserves the same suspicion as any other code. Maybe more, because it usually gets written in a hurry, with someone breathing down your neck.

This is basically why I bang on about TDD so much. Write the failing test first. Then fix it. Now that test sticks around and guards that spot forever. Future Dave gets a red build instead of a 3am phone call.

It won't catch everything. Nothing does. But it makes the quiet four-month defect a lot less likely.

Be kind to Dave, by the way. Dave isn't the problem. A process that lets one change sit unnoticed for months is.

What's the longest a bug has hidden in your code before it finally showed up?

#TDD #SoftwareEngineering
