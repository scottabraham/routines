# LinkedIn post: 18 Nov 2026

**Source story:** Outages hit Microsoft, Apple, the FAA and JPMorgan in the same week. Apple said an internal update caused some of its outages. (CNBC, 17 Nov 2026: https://cnbc.com/2026/11/17/apple-microsoft-faa-jpmorgan-outages.html)

---

Back in about 2003 I took down a client's website by uploading one file over FTP.

One file. On a Friday afternoon.

Fast forward to this week. Microsoft, Apple, the FAA, JPMorgan. All hit by outages within a few days of each other. Apple says an internal update caused some of theirs. Officials say there's no sign of anything malicious.

So no hackers. No villains. Just... updates.

Let me tell you about Tina.

Tina is great at her job. She's shipped hundreds of changes and every one of them went fine. So when change number 501 comes along, it's tiny. Basically a config tweak. The tests pass (well, the ones that exist). She rolls it out to everyone at once. Why wouldn't she? It's just a config tweak.

You can guess the rest.

Tina didn't really do anything wrong. The system let her do it.

And that's the part people forget.

The tools have changed beyond recognition since my FTP days. Visual SourceSafe gave way to Git, and copying files by hand gave way to CI pipelines. But the fundamentals haven't moved an inch. Small changes still break big things. Feeling confident doesn't count as a test. And rolling out to 1% before 100% isn't red tape. It's how you get to go home on time.

What worries me isn't that big companies have outages. Everyone does. It's how much of everyday life now depends on one routine update going well.

How do folks handle rollouts where you work? Canary releases, feature flags, crossed fingers? And any old-timers out there got their own "one file over FTP" story?

#SoftwareEngineering #Testing
