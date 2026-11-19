Microsoft's big Outlook outage last week? The bug went in back in July.

Four months. Just sitting there. Quietly waiting.

Meet Tina. Tina fixes a dodgy hinge on the office fire door. Tests it. Opens, closes, perfect. Signs it off.

Months later there's a fire drill. Same day, half the other exits are shut for maintenance. Everyone piles through Tina's door at once.

And it jams.

Tina didn't do a bad job. Her test just never looked like the real day.

That's basically what happened at Microsoft. A fix for their 365 gateway servers passed load testing. Deployed cleanly. No issues. Then a Teams failover shifted traffic at the same moment server capacity dropped. Two things at once. In under two hours, more than 80% of servers were unresponsive.

Their own explanation? The lab didn't reflect the mix of traffic and hardware that triggered it.

I've been writing tests for a long time. I'm a big TDD fan. But a green tick only tells you the code works in the world you imagined.

The real world doesn't read your test plan.

So your tests are only as good as the scenarios you're willing to picture. Including the awkward "what if two bad things happen on the same day" ones.

Anyone else had a bug sit dormant for months before it bit? I'd love to hear them.

#SoftwareTesting #TDD
