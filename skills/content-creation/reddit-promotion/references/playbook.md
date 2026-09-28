# Reddit promotion playbook

Use this reference when you need concrete examples, campaign sequencing, subreddit research structure, or help transforming promotional copy into Reddit-native content.

## 1. Subreddit research worksheet

For each candidate community, capture:

| Field | What to inspect |
|---|---|
| Subreddit | Exact community name |
| Core audience | Who actually participates |
| Problem overlap | How closely the community matches the product's problem |
| Activity | Posting frequency and comment depth |
| Top formats | Text, screenshots, videos, questions, guides, case studies |
| Tone | Casual, technical, blunt, story-driven, beginner-friendly |
| Rules | Links, self-promotion, flair, account requirements |
| Repeated topics | Questions and complaints that keep returning |
| Promotion pattern | What acceptable product mentions look like |
| Bad pattern | What gets removed, downvoted, or criticized |
| Best angle | The strongest useful story for this community |
| CTA | Comment, feedback, resource, product link, demo, none |

### Fast research method

1. Read the rules.
2. Sort by top posts from the past month.
3. Sort by top posts from the past year.
4. Open 5 to 10 posts that resemble what you want to publish.
5. Read the comments, especially criticism.
6. Search the subreddit for competitor names and the core problem.
7. Write down the exact phrases users use.

Do not rely only on subscriber count.

## 2. Community selection

A useful portfolio contains different levels of specificity.

### High-intent niche communities

People already live with the problem.

Example:
- product solves data engineering hiring
- target communities include recruiting operations, data engineering hiring, technical recruiting, ATS tooling

Best content:
- workflow breakdowns
- domain-specific experiments
- detailed case studies
- lessons from real datasets

### Practitioner communities

People do the job even if they are not shopping for a tool.

Example:
- sales operations
- recruiters
- data engineers
- indie founders
- designers

Best content:
- process improvement
- mistakes
- benchmarks
- behind-the-scenes decisions

### Broad founder or maker communities

The problem may be secondary, but the business story itself is interesting.

Best content:
- launch retrospective
- distribution lesson
- cost breakdown
- how the MVP was validated
- what did not work

### Adjacent technology communities

Useful when the implementation itself is interesting.

Best content:
- architecture
- performance
- model behavior
- technical tradeoffs
- open-source examples

## 3. Post-angle library

### Pattern: "I tested X"

Use when there is a real experiment.

Title shape:
> I tested [number] ways to [goal]. [specific result or surprising lesson].

Body:
1. Why you ran the test
2. What you compared
3. What happened
4. What surprised you
5. What you would change
6. Product mention only where it affected the experiment

Example:
> I tested 3 ways to shortlist 100k candidates. Rules were fast, free-form LLM review was flexible, structured judgments were the only approach I could filter reliably afterwards.

### Pattern: "I had this annoying workflow"

Use when the product came from firsthand pain.

Title shape:
> I was spending [time/cost] on [painful task], so I tried [approach].

Body:
- old workflow
- what made it painful
- first attempt
- failure
- better approach
- what exists now

This often works better than "I launched a tool."

### Pattern: "Here is the dataset"

Use when you have original numbers.

Title shape:
> We analyzed [N] [records/events/users]. Here are the [number] things I didn't expect.

Body:
- dataset
- method
- result
- limitations
- takeaways

### Pattern: "What would you do?"

Use for real validation.

Title shape:
> If you had [constraint], would you solve it with [A], [B], or [C]?

Body:
- give enough context for a real answer
- explain the tradeoff
- do not hide the actual decision
- ask one focused question

Do not use this as a fake pretext for dropping a link.

### Pattern: teardown

Title shape:
> I broke down how [workflow/product] handles [specific problem]. The interesting part is [insight].

Body:
- observation
- mechanism
- tradeoff
- what others can copy

### Pattern: cost breakdown

Title shape:
> What it actually costs me to run [system/product] at [scale].

Useful when numbers are real.

Include:
- hosting
- model/API costs
- database
- third-party services
- margin or cost per unit
- what scales badly

### Pattern: launch retrospective

Title shape:
> [Time] after launching [category], here's what actually got users.

Body:
- what you expected
- what happened
- traffic sources
- mistakes
- what you would repeat

### Pattern: "I changed my mind"

Title shape:
> I thought [common belief]. After [experience], I think [revised view].

This can feel native because it starts from a real learning arc rather than promotion.

## 4. Promotional-to-native transformations

### Product-first launch

Weak:
> We launched Decision Cloud, an advanced AI platform that evaluates large datasets with structured semantic judgments.

Better:
> I kept hitting the same problem with big spreadsheets: the LLM could tell me what it thought about each row, but the output was messy enough that filtering 100k rows afterwards still sucked.

Then:
> I ended up building the judgment step into a tool so the output stays typed and filterable.

Why it works:
- starts with the workflow
- names a concrete pain
- delays the product
- makes the product a consequence of the problem

### Feature list

Weak:
> Our platform supports typed outputs, CSV uploads, batch processing, and multiple judgment types.

Better:
> The useful part wasn't getting the model to "understand" the rows. It was forcing every answer into the same structure so I could sort and filter the results afterwards.

Why it works:
- converts a feature into a practical lesson
- gives the reader a reason to care

### Generic excitement

Weak:
> Super excited to share what we've been building!

Better:
> I've been testing this on a 100k-row hiring dataset for the past week, and one part worked much better than I expected.

Why it works:
- opens on evidence
- creates a reason to read

### Raw link drop

Weak:
> I made this tool: [link]. Would love feedback!

Better:
> I built a small prototype for this after running into the problem above. If anyone here deals with the same workflow, I'm more interested in hearing where your current process breaks than getting generic "looks cool" feedback.

Link only where allowed and useful.

## 5. Product placement patterns

The product should enter where the reader naturally asks, "How did you do that?"

### Tool as implementation

> For the test I used a tool I'm building that returns one structured judgment per row. You could reproduce the same idea manually with an LLM and a spreadsheet, it would just be slower to run at scale.

### Tool as artifact

> I turned the workflow into a small app after doing it manually a few times.

### Tool as optional resource

> If anyone wants to inspect the exact workflow, I can share the tool or the prompt structure.

### Tool after value

> The full dataset and method are above. The only part that's specific to my product is how the judgments get returned in a filterable schema.

## 6. Link-placement decision

Use the least aggressive placement that still serves the goal.

### Direct link in body

Use when:
- explicitly allowed
- the linked resource is central to the value
- the post already contains substantial useful content

### Link at end

Use when:
- value is complete without it
- readers may want the implementation afterwards

### Link in comment

Use when:
- community prefers discussion-first posts
- body links are discouraged but comments are permitted

### Product name only

Use when:
- direct links are restricted
- readers can search if interested
- the discussion matters more than traffic

### Link only when asked

Use when:
- subreddit is strict
- the post is primarily research or discussion
- the product can be introduced naturally in replies

## 7. Subreddit adaptation example

Same underlying story: a tool filtered a 103,482-row candidate database into a smaller shortlist.

### Founder subreddit

Focus:
- validation
- distribution
- business insight
- what users cared about

Title:
> I thought the hard part of an AI recruiting tool would be the model. It was actually making the output useful after 100k rows.

### Recruiting subreddit

Focus:
- workflow
- quality
- false positives
- seniority/location criteria
- recruiter control

Title:
> How are you screening large candidate databases without turning the first pass into keyword soup?

### Data/engineering subreddit

Focus:
- structured outputs
- batching
- schema
- reliability
- failure handling

Title:
> I ran structured semantic classification across 103k rows. The schema design mattered more than the prompt.

### AI tools subreddit

Focus:
- orchestration
- model behavior
- typed judgment
- cost
- reproducibility

Title:
> LLMs are good at judging one row. The interesting problem starts when you need the same judgment across 100k.

Do not reuse the exact body across all four.

## 8. Comment strategy

A post is only half the campaign.

Reply quickly when possible, but prioritize substance.

### When someone asks how it works

Give the useful explanation first. Link only if needed.

### When someone challenges a claim

Show:
- methodology
- limitation
- sample size
- screenshot
- source

Do not get defensive.

### When someone says "this already exists"

Ask what they use and compare the workflows honestly.

This is valuable market research.

### When someone asks for the product

Now the link is naturally earned.

### When someone gives a better approach

Engage with it. A thread where the founder learns in public often feels more credible than one where every reply defends the product.

## 9. 12-week organic plan

Use this when the account is new to the relevant communities or the user wants a sustainable campaign.

### Weeks 1-2: learn

- join 10 to 15 relevant communities
- read rules
- inspect top posts
- comment where you have genuine knowledge
- collect repeated pain points
- identify 3 to 5 primary communities

Output:
- subreddit map
- language bank
- 10 post ideas

### Weeks 3-6: earn attention

Publish a small number of useful, non-launch posts:
- one case study
- one guide or teardown
- one discussion question
- one behind-the-scenes post

Reply to comments.

Track which problems create the best discussion.

### Weeks 7-12: connect value to product

Start using posts where the product is a natural part of the story:
- experiment run with the product
- launch retrospective
- benchmark
- workflow comparison
- user-requested demo
- implementation breakdown

Measure:
- traffic
- signups
- demos
- qualified conversations
- objections

Do not wait 12 weeks if the account already has relevant history and the subreddit allows direct promotion. This plan is a conservative default, not a mandatory waiting period.

## 10. Volume strategy

Performance on Reddit is noisy, so run multiple attempts.

Good volume:
- multiple relevant subreddits
- multiple angles
- multiple weeks
- rewritten posts
- repeated learning

Bad volume:
- identical post pasted everywhere
- several promotional posts in one day
- reposting removals
- creating accounts to get around limits

A useful starting range is 2 to 3 substantial posts per week across the account, but subreddit norms matter more than the number.

## 11. SEO and long-tail search

Some Reddit threads rank well in search engines because they answer narrow questions in natural language.

When search visibility matters:

1. Use the real phrase users search for.
2. Answer the question directly.
3. Include specific detail.
4. Avoid stuffing keywords.
5. Keep the thread useful enough to earn comments and links.
6. Track search traffic separately when possible.

A Reddit post should be written for the community first. Search visibility is a second-order benefit.

## 12. Tracking template

Track each post:

| Field | Example |
|---|---|
| Date | 2026-09-28 |
| Subreddit | r/example |
| Angle | Case study |
| Title | Exact title |
| Product mention | None / middle / end |
| Link placement | None / body / comment |
| UTM | campaign identifier |
| Upvotes | count |
| Comments | count |
| Useful comments | count |
| Visits | sessions |
| Signups | count |
| Demos | count |
| Purchases | count |
| Main objection | short note |
| Next idea | what to test next |

The "next idea" column is important. Reddit comments should feed the content loop.

## 13. Research-only mode

The user does not have to post to get value from Reddit.

For a niche:
1. search the problem
2. collect 20 to 50 relevant threads
3. group complaints
4. count repeated themes
5. capture exact phrases
6. compare competitors
7. extract feature requests
8. note what users already pay for
9. identify unresolved questions

Outputs can become:
- landing-page language
- sales copy
- product requirements
- roadmap ideas
- new Reddit posts
- onboarding improvements

## 14. Common failure modes

### "We launched"

Problem: nobody cares yet.

Fix: lead with the problem, experiment, lesson, or result.

### Too polished

Problem: reads like LinkedIn or PR.

Fix: shorten, remove slogans, use concrete detail, write in first person.

### No value before link

Problem: the post asks before it gives.

Fix: put the best useful detail before the product mention.

### Copy-paste distribution

Problem: communities notice repeated copy and the angle may not fit each audience.

Fix: rewrite title, framing, detail level, and CTA.

### Fake question

Problem: readers can tell the question exists only to create an excuse to mention the product.

Fix: ask something you genuinely want answered or publish a case study instead.

### Feature dump

Problem: features matter only after the reader cares about the problem.

Fix: translate features into workflow outcomes.

### Ghosting comments

Problem: wastes the highest-value part of Reddit, the discussion.

Fix: treat the thread as live customer research.

### Chasing karma

Problem: upvotes can be disconnected from qualified traffic.

Fix: track downstream behavior.

## 15. Final pre-post check

Before publishing, ask:

1. Why would this subreddit care?
2. What useful thing does the reader get before the product appears?
3. What specific evidence makes the post credible?
4. Does the title sound like a Reddit post or a launch announcement?
5. Is the product mention necessary?
6. Does the CTA match the community?
7. Have the current subreddit rules been checked?
8. Is this meaningfully adapted from other posts in the campaign?
9. What comment would be hardest to answer?
10. What will we measure after posting?
