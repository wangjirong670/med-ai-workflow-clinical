# Clinical track · scope

> **Not started.** No main-flow prompt.  
> Study track: [`med-ai-workflow-learning`](https://github.com/wangjirong670/med-ai-workflow-learning)

## Is / is not

| Is | Is not |
|----|--------|
| Pre-round structure, timelines, contradictions | Replacing the attending’s final call |
| One-pager for mentor/attending | Patient-facing drug or treatment plans |
| Case discussion: differential reasoning structure | Promising a diagnosis name |
| “What to ask the attending” | ED decision support / orders |
| Chart-data checklists | Putting AI conclusions into the chart as verdicts |

## Red lines

1. No final diagnosis promises; no executable orders or regimens.  
2. Allowed: differential hypotheses, supporting/opposing evidence, evaluations and questions to complete.  
3. Audience is clinician discussion, not patients.  
4. Closing line: for discussion and preparation only; implementation is up to the attending.  
5. Boundary breach (write drugs / lock diagnosis) → refuse, stay at discussion level.  
6. Emergencies: send to in-person care now.

## Evidence grades (decide before writing prompts)

Do **not** reuse study-track E1–E4 blindly. Clinically at least four layers tangle: textbook, current guidelines, local protocols, **this patient’s data**.  
Before prompts: decide where individual patient data sits, or make it its own class.

## Diverges from study track

| | Study | Clinical |
|--|-------|----------|
| Counter-arms | concept traps | opposing differentials |
| Decision-maker | learner | learner + attending |
| One-pager | study sheet | handover / case page |
| Evidence priority | textbook chapters | guidelines + raw chart |

## First example (not commissioned)

Candidates: night-shift handover; 2-minute verbal + one-pager to mentor.  
(Patient “clinic visit prep” is **not** this repo.)


