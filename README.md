# unconspiracy-md

AI Unconspiracy is my upcoming book. This repository is where its ideas become tools you can use today. I’m [Anirudh Badam](https://www.anirudh-badam.com), and I build AI for a living. The book starts with an uncomfortable observation: every company wants greater productivity, every customer wants lower prices, and every worker wants better tools. All perfectly rational. Yet together, those decisions can take us toward a future none of us actually wanted: when workers are laid off, the market loses consumers, and when consumers are gone, the companies will go down with them. Nobody needs to organize it. That’s the unconspiracy -- an unconscious conspiracy where we are all marching towards that doom by making individually rational decisions.

However, I am a firm believer in humanity's capability to figure out and solve any crisis. So, I advise folks to focus on being part of this disruption rationally in the context where it makes sense while the large macro-economy fixes itself with forces that are greater than either of us. Once you believe that, you will begin to see that the disruption will be non uniform across sectors, industries, job types etc, and therein lies your opportunity. So, I am writing this book to help people convert anxiety about AI into actions that they can take now and identify opportunities to future proof themselves.

But understanding what’s happening is only useful if it changes what you do next. When everyone can access intelligence and execution gets cheaper, your advantage increasingly comes from the problems you notice, the context you bring, and the judgment you exercise. Your lived experience gives you reasons to build things that someone else might never think to ask for. The question becomes: what have you always wanted to fix, and how far can you now take it?

That’s who these checklists are for: vibers. Developers building software with agents. Accountants automating work they understand firsthand. Anyone turning “there has to be a better way” into something that actually works. Getting an agent to produce an answer is easy. Defining what a good answer looks like, giving it the right context, and knowing whether it delivered still require care. Better vibing starts before the first prompt and continues after the agent says “done.”

I’m creating this repository to turn the book’s ideas into practical checklists you can give your agents and use yourself. Use them to clarify the problem, surface assumptions, define success, and check the result. Bring them into your agent’s instructions or working context. Adapt them to your domain. The goal is to make your experience and judgment show up in what your agents build, so that faster execution translates into something worth having.

The book is coming. The newsletter is available to subscribe to today. And this repo is where you can put the ideas to work. In the Unconspiracy newsletter, I explore what this transition means for developers, accountants, and everyone watching their profession change around them. Subscribe to follow the ideas as they develop, and star this repository for the checklists as I build them. Start with a problem you care about. Give your agent a clearer definition of success. See how far you can take it.


## Files

- [`close_the_loop.md`](checklists/close_the_loop.md) — **Make Coding Hard Again: Close the Loop.** Define the outcome, connect company, organization, team, and individual contributions, then vibe and measure. Uses the two companion checklists throughout the process.
- [`5d_test.md`](checklists/5d_test.md) — applies Anirudh Badam's five-D framework: Disruptor, Delivering, Disintermediation, Deflation, and Diversification. Checks the agent's contribution and the developer's or company's short-term benefit.
- [`only_you.md`](checklists/only_you.md) — **Only yoU can beat AI.** Applies Read more, Write more, Meet more, and Talk more to check how original material and lived experience shape the agent's work.

## The 5D Test: define the value

The [5D Test](checklists/5d_test.md) helps you examine the disruption you are participating in, your agent's contribution, and the concrete short-term benefit to you or your company. Use it to define an outcome worth pursuing and revisit it with evidence from actual use.

- **Disruptor:** change your industry's economics or what customers can obtain, and identify the agent's contribution to that change.
- **Delivering:** get that contribution into real users' hands and show the useful outcome they receive.
- **Disintermediation:** remove unnecessary steps, handoffs, or layers so users reach the outcome more directly, while retaining necessary review and accountability.
- **Deflation:** make a valuable product or service dramatically cheaper, and examine whether that opens access to people previously priced out.
- **Diversification:** use existing knowledge, relationships, or capabilities to make a new market, service, or customer solution economically possible.

Look for evidence of **Disruptor + Delivering + at least one of Disintermediation, Deflation, or Diversification**. Explain how the agent contributes and how you or your company benefit; company success alone does not establish your own benefit. Separate planned benefits from observed results, and mark missing evidence **Unknown**.

## Only yoU can beat AI: build the context

[Only You](checklists/only_you.md) examines the original material and judgment you bring to an agent through four practices. **Read more:** engage with original human work or authoritative sources and record your own interpretation. **Write more:** develop original writing for another person, such as a memo, design document, or critique; prompts alone do not count. **Meet more:** capture firsthand learning from actual in-person encounters. **Talk more:** explain and test your ideas with people, in person or in live meetings, and record the questions, disagreements, and feedback that sharpen your judgment.

Bring those sources, notes, writings, and conversations into the agent's context, then point to a specific decision or output they changed. Preserve the distinction between your contribution and AI assistance with transcription, organization, or editing. The review asks what would be missing without your experience and judgment, and identifies the human material still needed. In Close the Loop, apply it separately to each phase after defining the outcome so that every link in the value chain has evidence behind it.

## Close the loop: tokens to outcomes

Understand and compress the value chain: **your work → team → organization → company → world**. Understand how each contribution supports the next, remove unnecessary steps, and bring the relevant context directly into the agent.

Picture a flat figure-eight with an **outcome contract** at the center: what should change, for whom, the baseline and target, and how and when success will be measured.

- **Stakeholder side:** work backward from the intended outcome. Vet company value with customers or C-suite leaders, organizational contribution with VPs, and team contribution with leaders and peers. Define your contribution to building the agent. Gather missing context and metrics; write notes and design documents; present, iterate, nudge, and rally. Turn that work into the agent's specification.
- **Measurement side:** vibe and measure. Build the agent, put it into use, and measure the intended outcome. Find where the contract is breaking or context is missing, then take those gaps back to the relevant stakeholders and refine the specification.

At minimum, complete the **5D assessment when defining the outcome**. Apply **Only You separately in every subsequent phase, including Vibe and measure**. The six phases in the checklist make this loop actionable.

Without that context, you can spend months improving an agent that solves the wrong problem. Keep the loop open until evidence demonstrates the intended outcome. Working code and useful learning alone do not establish success. If you revise the target, record why and preserve the previous result.

## Give the files to your coding agent

1. Copy all three files into your project's `checklists/` directory, keeping them together so their relative links work.
2. Give your coding agent the prompt below, along with the task and any existing stakeholder notes, design documents, and measurements.
3. Use its review to identify the human conversations, original writing, decisions, and evidence still needed. Bring that material back into the next iteration.

```text
Read checklists/close_the_loop.md and its companion files,
checklists/5d_test.md and checklists/only_you.md. Apply them to this task.

Start by helping me define the outcome contract and complete the 5D
assessment. Map how my work contributes to my team, organization,
company, and value in the world. Work backward through those links
to identify missing stakeholder context, metrics, and commitments.

Apply Only You separately in phases 2–6. Link each claim to evidence
and show how that evidence changes the specification or experiment.
Mark missing evidence Unknown, with an owner and next action. Never
invent meetings, notes, stakeholder opinions, or measured outcomes.

Then help me vibe and measure. Compare results with the outcome
contract, identify broken assumptions or missing context, and repeat
the affected stakeholder work. Close the loop only when the intended
outcome is supported by evidence.
```

The companion checklists can also be used independently. Treat unsupported claims as unchecked, record each checklist's result, and re-run the relevant reviews when the agent's sources, instructions, tools, intended users, or outcome change materially.

These files are advisory. Teams should adapt them to their field, risks, and obligations.
