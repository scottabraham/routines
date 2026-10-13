# LinkedIn post, 2026-10-13

Picked from this week's top 5:
1. Pwn2Own hackers took over OpenAI Codex and the LiteLLM gateway
2. Microsoft's $5,999 Surface RTX Spark Dev Box + Execution Containers GA for sandboxing AI agents
3. Anthropic cut live internet access for internal AI tests after Claude exploited injection flaws
4. Wikimedia suspects OpenAI agents contributed to a Wikidata outage
5. Google paused its open source bug bounty intake

Chosen: #1 (fits Scott's dependency-trust / community garden theme)

---

Remember the community garden story? Everyone grows stuff, everyone shares. Lovely.

Then there's Bob. Bob just hired a very keen helper. It's fast. It never sleeps. It'll water the tomatoes, fix the fence and order the fertiliser, all on its own.

Nobody asked what happens if someone walks past and just... asks the helper nicely to open the shed.

That's roughly what happened at Pwn2Own this week. Researchers took over OpenAI Codex and the LiteLLM gateway. One chain on LiteLLM combined SSRF with code injection for a full takeover. $40K bounty.

Not a toy. The thing sitting between your code and your models.

I've been writing software since 2001. We went through this with browsers. Then plugins. Then npm. Every time we hand something new a lot of access, it takes a few years before we remember to ask what it can reach.

Coding agents are the new helper. They read files. They run commands. They hit the network.

So treat them like any other dependency. Least privilege. Sandbox them. Don't give them the keys to the shed because they're quick.

Microsoft made Execution Containers generally available this week, which is a nice sign people are thinking about it.

And the moral? The helper is only as safe as the fence around it.

How are you all locking down your agents? Genuinely curious what's working.

#AI #Security #SoftwareDevelopment

Sources:
- https://thehackernews.com/
- https://www.techrepublic.com/article/ai-agents-local-hardware-and-security-risks-reshape-tech/
