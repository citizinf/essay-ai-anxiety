**NOTE TO SELF: remember to review all sections (for orange text anyway) even when working on a specific one; I didn't move bullets around when suggesting recategorizations**

# (I) An overview of AI anxiety

~~- GOOD | md.md | 24 | "Some fear around labor market disruption..." | Use the Keynes 15-hour-week contrast to show why AI job-loss fear is fundamentally a distribution and policy-design problem.~~**I think it fits better in the economic/labor section - transition problem most likely**

# (II) How will the ideas in this essay help society handle AI anxiety?

# (III) The pessimistic scenario - a "dark AI" future: rampant threats to physical security, and widespread economic subjugation

- EXCL | gkeep.md | 2 | "🌑 start with \"dark AI\" assumptions: centralized..." | Start from a pessimistic centralized-superhuman-AI scenario to analyze threats, concentrated power, and labor devaluation.
- EXCL | md.md | 74 | "_\"dark AI\"_ (lightly discussed..." | Describe a potentially stable “AI feudalism” equilibrium where many can’t compete for cognitive work and must rely on bad jobs, redistribution, or capital income.

# (IV) The physical world imposes limits
**re: examples include GPU/electricity/land shortages; ChatGPT brought this up as well**
**analogy for "digital is more frictionless than physical" - like playing the Sims too much and internalizing the idea that building a house is as easy as clicking a few buttons, as long as you're rich enough**

- EXCL | gkeep.md | 6 | "🔨 physical world limits..." | Note how GPU scarcity, monitored data centers, slow real-world iteration, and material constraints limit both AI deployment and physical-world harms.
- EXCL | md.md | 33 | "AI compute is _not limitless_..." | Emphasize that compute and energy are scarce physical resources, constraining both access to AI and what large-scale “superhuman” deployment can do.
- EXCL | md.md | 34 | "AI being digital & just knowledge..." | Stress that many high-end harms are bottlenecked by physical materials and detectability, so “information-only” AI is not an instant WMD unlock.
- ⭐GOOD | md.md | 83 | "model miniaturization/distillation / how hardware..." | Note that whether powerful models require centralized GPU farms or can run locally will shape centralization, monitoring, and the pace of societal adaptation. **relevance is a _bit_ of a stretch (not so much a "limit" as an opportunity) but I can frame it as hardware improvement / smaller nanometer processes, etc. so I guess it's ok to mention. This is the whole thing about the paper is already public and it could be like the transistor, widely spread tech with little value capture, which is a very important point of optimism to hit ((ChatGPT))**
**this should also be discussed in the optimistic scenario section**

# (V) Discovery is not advancement: extrapolation to infinity is unlikely

- EXCL | gkeep.md | 24 | "📈 discovery is not enhancement..." | Push back on linear extrapolation by noting NL is the big leap, many feats were already possible, and “smarter than humans” depends on what dimensions actually matter.
~~- GOOD | gkeep.md | 54 | "ai: reviewable examples - AI..." | Illustrate that AI’s speed gains can come with accuracy and audit-cost tradeoffs, so “automation” depends on how reviewable the work product is.~~ **(reviewability fits into either tech determinism or economic/labor discussion)**
- GOOD | md.md | 28 | "Does AI never regress or _forget_?..." | Flag that AI capability may not be monotonic because context limits and version-to-version regressions can undercut “inevitable superhuman” narratives.
- EXCL | md.md | 29 | "AI performs well, but does it perform..." | Argue that underspecified prompts and human-provided inputs/benchmarks remain central, so fully self-prompting AI may hit hard limits or degrade in quality.
- EXCL | md.md | 46 | "measuring agentic AI capabilities by task..." | Critique task-length benchmarks for ignoring parallelism and integration overhead, which can dominate real-world “agent” effectiveness.
- GOOD | md.md | 47 | "AI shortcomings / jagged frontier:..." | Emphasize that AI’s “jagged frontier” capability profile differs from humans, so assumptions about what work is easy or valuable may break.
- GOOD | md.md | 76 | "_powerful AI_ maximally optimal projections..." | Caution against maximalist forecasts by recalling how even transformative technologies were historically overhyped in specific ways.
- ⭐**One I forgot in the brainstorm ideas: sending info across the world has advanced from "weeks" 200 years ago to "seconds" now. Naive extrapolation would say, look at the progress of the last 200 years related to communications, imagine what the next 200 years will look like! But latency of comms cannot go negative; it's already close to 0, so extrapolating the rate of progress is misleading. Other tech advancements have shown "capping out", e.g. indoor plumbing has been around 1000s of years, while centralized water treatment is much more advanced, the whole thing with pooping in a toilet and flushing is much the same.**

# (VI) The pitfall of technological determinism: AI is not an alien invasion with its own thoughts and goals; its development and application are fully controlled by humans in society
**this section has overlap with economic/labor discussion**
**business examples: <https://www.cnbc.com/2026/03/01/ai-artificial-intelligence-economy-business-risks.html>**

- EXCL | gkeep.md | 11 | "🌐tech determinism: how we plan..." | Emphasize that AI risks depend on human integration choices, so we need strong external guardrails and tool-access design based on cost-of-failure.
- GOOD | gkeep.md | 60 | "This is kind of a management problem..." | Frame AI adoption as a supervision-and-control problem where oversight, hidden costs, and “tech debt” can offset raw automation speed.
- GOOD | gkeep.md | 68 | "reviewability: who gets \"final cut\"..." | Argue for human “final cut” in high-stakes uses because liability and accountability can’t cleanly attach to an AI model.
- EXCL | md.md | 31 | "_technological determinism_: It's not AI..." | Emphasize that AI harms and benefits depend on human deployment decisions, so “AI will do X” is often a category error.
- GOOD | md.md | 32 | "(related to _technological determinism_ and..." | Suggest requiring explicit offense/defense “attack surface” analysis for new AI capabilities and limiting access when offensive power outstrips defenses.
- GOOD | md.md | 35 | "another human nature concern: people will..." | Argue that safety-critical work stays human-supervised because trust, long physical cycles, and liability don’t disappear when a model is “good enough.”
- FAIR | md.md | 45 | "biorisk: issue is with \"hiding relevant..." | Note that some security properties (like cryptography) rely on hard problems rather than secrecy, suggesting possible analogies for bio-risk mitigation.
- GOOD | md.md | 60 | "Leisure and decision making: humans are..." | Argue that people will still demand agency over choices, creating a social limit on fully delegating everyday decisions to AI.
- ⭐EXCL | md.md | 61 | "autonomy: consider this contrived example:..." | Use a lunch-ordering/nuclear-launching thought experiment to show that safe AI deployment requires strict environment and access separation.
- EXCL | md.md | 88 | "set up explicit, well-defined _guardrails..." | Call for explicit standards for agentic AI tool access where higher cost-of-failure demands stronger predictability and containment.
- ⭐EXCL | md.md | 89 | "Don't use AI directly in sensitive..." | Recommend using AI-generated but fully auditable artifacts (like scripts and runbooks) instead of direct AI action in sensitive systems.
- GOOD | md.md | 90 | "government agencies like AISI (Britain)..." | Advocate giving AI safety institutes real regulatory power and resources so safety coordination isn’t purely voluntary.

# (VII) Entry-level people don't have to fill entry-level jobs, because the meaning of "entry-level job" is going to change
**this section has overlap with tech determinism**
**discuss support for displaced workers**

- EXCL | gkeep.md | 17 | "🎓 entry level is not..." | Argue that “entry-level” work is a flexible task bundle, so firms can re-scope roles and use AI-native junior talent to build new kinds of human capital.
- EXCL | gkeep.md | 44 | "ai: on entry level, thought..." | Use a “delete the entry-level layer” thought experiment to show the remaining gaps require human expertise and can reframe juniors as AI-enabled managers.
- GOOD | gkeep.md | 63 | "ai key reviewability point: level..." | Highlight that generating output may get easier than auditing it, which creates a training problem for juniors who still need to learn how to review correctly.
- GOOD | gkeep.md | 69 | "adaptation: AI is relatively \"easy to..." | Note that AI tools have a low learning curve but a high mastery curve, letting motivated workers upskill even in organizations that adopt slowly.
- EXCL | md.md | 36 | "Saying that _entry-level work_ is..." | Separate “entry-level work” from “entry-level people” to argue roles can evolve and AI-native juniors can still contribute and learn through auditing and apprenticeship-like paths.
- GOOD | md.md | 44 | "how replaceable work is with AI..." | Argue that automation risk depends heavily on reviewability and error detectability, since cheap auditing makes replacement easier and costly auditing preserves human roles.
~~- FAIR | md.md | 62 | "seems like cybersecurity will be wrapped..." | Suggest cybersecurity roles may be comparatively durable because AI-driven offense makes defense and safety engineering more central, not less.~~ **better fit would be a security section above**

# (VIII) Moonshots can focus higher-value labor and experienced workers
**discuss support for displaced workers**

- EXCL | gkeep.md | 30 | "🚀 moonshots / \"keep your..." | Use “moonshot” problems to surface where humans still add value (setup, context, metrics, physical execution) and to frame innovation as the durable path for workers and firms.
- GOOD | gkeep.md | 50 | "ai: the counterintuitive, cognitively..." | Advise workers to aggressively test what AI can automate while deliberately building the remaining human skills and aiming at higher-level value creation.
- ⭐EXCL | md.md | 64 | "human contribution to major tasks (moonshots):..." | Use an end-to-end “single prompt” moonshot to argue humans still matter in orchestration and physical execution, and that progress may be slow enough for policy adaptation.
- ⭐GOOD | md.md | 73 | "I think one of the biggest changes..." | Argue that fast-moving AI will make cognitive skills non-static, so workers and firms must keep re-aiming at new moonshot-like tasks as old ones get automated.**may be somewhat relevant to post-scarcity**

# (IX) Handling the post-scarcity transition problem
**it's all mixed up, let's just include both transition problems here: displacement/instability with wage-labor capitalism evolving intact; and the path to post-scarcity - I can frame this as "we won't really know which one it is while it's happening so we have to understand both"**
**distinguish post-scarcity transition (more serious paradigm shift) vs transition of mainly labor and jobs due to disruption (we have the script and prior experience, some will need support but not a massive shift) which is discussed in previous sections**
**this section is more focused on post-scarcity transition, not the disruption-transition which is discussed above**
**it may be better to frame this section with several components: (1) we may not need to ever worry about this if above sections and associated policy with precedent is applied, (2) even if we do go down this path it may not be as horribly disruptive as feared since it could be slow etc., (3) what might happen if we do go down this road at whatever speed**

- GOOD | md.md | 30 | "Belief that AI may disadvantage the..." | Question whether high-skill cognitive workers could be displaced earlier than “lower-ability” workers if AI becomes a general cognitive substitute.
- GOOD | md.md | 52 | "regarding Amodei's \"lower intellectual ability\"..." | Use workforce composition stats to argue many “lower-ability” workers are already outside white-collar jobs, complicating simple displacement narratives.
- GOOD | md.md | 63 | "is there a foundational assumption about..." | Explore how widespread capital income (a “rentier for all” model) could function as UBI-by-another-name in a post-scarcity transition.
- FAIR | md.md | 68 | "a sharp focused question could be:..." | Ask whether being outmatched by AI necessarily makes people economically surplus, or whether new roles and institutions can still absorb them.
- EXCL | md.md | 70 | "differentiate: 1% work needed..." | Argue that even if “some” human work remains, the remaining work may demand higher skill or be competed away by agents, creating a harsh transition for many.
- ⭐GOOD | md.md | 71 | "_AI Revolution vs Industrial Revolution_:..." | Warn that the AI revolution may differ from past industrialization by causing major demand loss and circular-flow problems rather than broad-based wage growth. **Citrini**
- FAIR | md.md | 75 | "_digital media/entertainment is saturated_..." | Argue that a leisure/creator-economy pivot (especially digital) has limited labor-absorption potential because it’s already saturated and hits diminishing returns.
- ⭐GOOD | md.md | 78 | "_Cost-cutting vs innovation_ incentive as..." | Explain why firms may default to cost-cutting (short-termism and financialization) and argue that incentive and regulatory design may be needed to shift behavior toward innovation.
**explain margins as "corporate wage", not all margins are bad, some margins are absolutely necessary to incentivize entrepreneurs. some firms have more significant moats like hardware/medical: I want a battle-tested pacemaker, not something from an AI startup trying to cut Abbott's margins. Some margins can be unjustified though, especially when coupled with already-high profitability and layoffs. In this case the best outcome is to set up market forces that can drive prices down and/or support employment.**
- ⭐EXCL | md.md | 79 | "The \"_transition problem_\" is similar..." | Use an inflation analogy to argue the in-between state is the real danger, so policy must bridge unemployment and price-structure mismatch before any post-scarcity end state.
- ⭐EXCL | md.md | 82 | "NOT just GDP, market indexes, etc..." | Argue that AI-driven deflation can make GDP and markets look worse even as real welfare improves, so we need better metrics than dollarized aggregates.
**Details matter; "lower GDP" can look very different "in the field", distribution problems - e.g. 3% deflation and wages drop 3% a year - very different than wages dropping 2% a year while employment shrinks 1% a year, even if the aggregate numbers, stock prices, etc would be similar. Policy response tools that are targeted and well-designed will politically go over much better than broad blunt instruments like "re-energize inflation by printing tons of money"**
- GOOD | md.md | 84 | "\"I encourage economists to consider what..." | Urge economists to define and track better disruption metrics so society can detect transition harms early and tune policy based on evidence.
- ⭐GOOD | md.md | 87 | "Ban _noncompetes_ nationally, or globally..." | Propose banning noncompetes for AI-linked layoffs to help displaced workers move, start firms, and redeploy skills during rapid change.
- FAIR | md.md | 91 | "(perhaps more far-fetched) a price floor,..." | Float a temporary tax/price-floor on routine corporate AI use to slow displacement and fund/encourage smoother adaptation during the transition.

# (X) Optimism is justified

- GOOD | md.md | 27 | "_lump of labor / size of the pie fallacies_..." | Counter the lump-of-labor intuition by arguing automation can expand the pie and reallocate human effort rather than erase it.
- GOOD | md.md | 43 | "drawing a _parallel with mechanization_..." | Use mechanization analogies to argue that, like past waves, AI may erase some tasks while leaving many human roles intact.
- ⭐EXCL | md.md | 48 | "⭐My optimistic scenario: vigorous competition..." | Sketch an optimistic path where democratized AI and strong competition compress margins, lower prices broadly, and keep incentives aimed at innovation.
**another "solution idea": if AI remains centralized, compute owners should offer generous "free tiers" like AWS to make it easier for someone with a good AI-enabled idea to experiment and productionize it without significant upfront funding required to run AI workloads. This encourages innovation & competition, and penalizes slow-to-adapt firms trying to sit on unjustified fat margins (or trying to expand them with layoffs).**
- ⭐GOOD | md.md | 69 | "2 types of new jobs: (1) AI..." | Separate AI-era job creation into AI-management roles and entirely new industries unlocked by major technological advances.
- FAIR | md.md | 77 | "keeping in mind historical failures like..." | Question whether AI will create wholly new work categories without major physical-domain breakthroughs, and argue optimism should account for that uncertainty. **some overlap with transition problem, in case physical-domain breakthroughs don't happen or happen quickly enough**
