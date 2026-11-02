# LinkedIn post: 2026-11-02

Picked from: Binance hack, DoorDash/Instacart, Anthropic self-replication warning, Gemini 4 Carbon, Linux TCP use-after-free (CVE-2026-98432, CVSS 9.8).

---

A Linux kernel TCP bug is sitting at the top of Hacker News this week. Use-after-free. CVSS 9.8.

I'll be honest, my first reaction was a small sigh. Then a smile.

I started in 2001. Back then, patching meant a CD-ROM, a long weekend and a lot of hope. Somebody always forgot to patch the one server under the desk. Every office had one.

Let's say Tina runs the servers at a small company. Careful. Methodical. Labels everything.

Then there's Bob, who set up a test box three years ago "just for a week". Nobody's touched it since. It's still on the network.

Guess which one gets hit first.

It's never Tina's machines. It's the one nobody remembers.

And that's the part people forget. The bug is rarely the real problem. The real problem is not knowing what you're running.

So before you panic about the CVE, go and find your Bob. Ask what's actually deployed. Then patch.

Anyone else got a Bob? Go on, you can tell me.

#Linux #Security
