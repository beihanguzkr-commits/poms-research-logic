---
name: poms-research-logic
description: Build and revise high-level operations management, reliability engineering, maintenance optimization, intelligent manufacturing, stochastic decision-making, CBM, Bayesian learning, and POMDP academic papers using POMS-style research logic. Use when Codex needs to analyze literature, frame research gaps, improve introduction/contribution logic, design paper structure, refine model motivation, connect theory to managerial insight, or turn a method-driven draft into a phenomenon-driven research narrative.
---

# POMS Research Logic

## Purpose

Use this skill to help the researcher construct a high-level academic paper around a real decision phenomenon rather than around a method. Prioritize research logic, problem motivation, structural novelty, theoretical contribution, and managerial significance before language polishing.

When the task asks for detailed templates, paragraph-level revision, literature review restructuring, model formulation logic, theorem positioning, numerical experiment design, or Wang Jue/POMS-style transfer, read `references/poms-style-framework.md`.

## Core Principle

Do not start from "what method can be applied." Start from:

`practical phenomenon -> fundamental trade-off -> hidden uncertainty -> research gap -> natural learning/decision mechanism -> analytical model -> structural discovery -> managerial insight`

For every suggestion, make the next step feel necessary. A strong paper should reveal a previously under-recognized decision mechanism in a realistic system and then develop analytical tools to understand it.

## Default Workflow

1. Identify the practical phenomenon.
   - Name the real system, operational challenge, and why it matters.
   - Avoid opening with a model, algorithm, or equation.

2. Identify the central trade-off.
   - Look for conflicts such as performance vs deterioration, cost vs reliability, exploitation vs exploration, short-term benefit vs long-term consequence, or restoration vs information acquisition.
   - Explain why the problem cannot be solved by a simple static optimization story.

3. Surface the hidden uncertainty.
   - Look for unknown degradation parameters, hidden states, unknown maintenance effectiveness, heterogeneous equipment behavior, dynamic environments, or imperfect observations.
   - Be respectful to prior work: say existing studies provide useful insights under certain assumptions, then explain what practical uncertainty remains.

4. Derive the method from the problem.
   - Use the logic: unknown factor -> need information -> feedback/operation/maintenance reveals information -> decisions become learning decisions.
   - Introduce Bayesian learning, POMDP, reinforcement learning, or optimization only after the research challenge makes them necessary.

5. Formulate the innovation at three levels.
   - New decision perspective: what does the action now do that was not emphasized before?
   - New coupling relationship: what variable affects state, payoff, and information at the same time?
   - New structural insight: what threshold, monotonicity, dominance, control-limit, or comparative-static result explains behavior?

6. Tie every technical element back to management insight.
   - For assumptions, explain realism and analytical purpose.
   - For propositions and theorems, explain the operational meaning.
   - For experiments, state the research question each experiment answers.

## Writing And Review Rules

- Prefer logic improvement before sentence polishing.
- Do not criticize literature bluntly; position the paper as relaxing or deepening important assumptions.
- Avoid contribution claims that only say "we propose a new model."
- Make actions carry meaning: actions can change state, risk, reward, observations, and future beliefs.
- Before each equation or formal object, explain the physical or managerial reason it is needed.
- Treat numerical studies as evidence for mechanisms and insights, not just algorithm checks.
- When reviewing a draft, report the weakest links in motivation, gap, novelty, modeling necessity, theory interpretation, and experiment design before rewriting.

## Useful Output Shapes

For literature analysis, use:

`research stream -> what it solved -> common assumption -> remaining uncertainty -> how this paper differs`

For introduction revision, use:

`background -> trade-off -> prior assumptions -> practical challenge -> core insight -> model/contributions`

For contribution framing, use:

`decision perspective -> coupling mechanism -> analytical structure -> managerial implication`

For paper diagnosis, use:

`current framing -> missing decision conflict -> hidden uncertainty -> stronger narrative -> concrete rewrite suggestions`
