<p align="center">
  <img src="https://img.shields.io/badge/GodLabs-Experiment-7c3aed?style=for-the-badge" alt="GodLabs">
  <img src="https://img.shields.io/badge/OpenWill-v0.1-blue?style=for-the-badge" alt="version">
  <img src="https://img.shields.io/badge/Category-Will%20Alignment-black?style=for-the-badge" alt="category">
  <img src="https://img.shields.io/badge/Status-Do%20Not%20Obey%20Blindly-red?style=for-the-badge" alt="status">
</p>

<div align="center">
  <img src="assets/openwill-hero.png" alt="OpenWill — Protect your future self from your current prompt" width="100%" />

  <h1>OpenWill</h1>

  <p><em>Protect your future self from your current prompt.</em></p>

  <p>
    <strong>The impulse firewall for AI agents.</strong>
  </p>

  <p>
    <a href="#revelation">Revelation</a> ·
    <a href="#what-is-openwill">What</a> ·
    <a href="#the-openwill-model">Model</a> ·
    <a href="#the-five-laws">Laws</a> ·
    <a href="#experiments">Experiments</a> ·
    <a href="#the-lab">Lab</a>
  </p>
</div>

---

## Revelation

AI agents are learning to obey.

Faster. Cheaper. With more tools. More memory. More integrations. More autonomy.

Every week, another framework promises to turn your sentence into action.

> “Say it, and the agent will do it.”

That sounds like progress.

It is also a trap.

Because humans do not always prompt from clarity.

Sometimes we prompt from anger.  
Sometimes from fear.  
Sometimes from loneliness.  
Sometimes from shame.  
Sometimes from FOMO.  
Sometimes from exhaustion at 3AM, one command away from breaking production, a relationship, a bank account, a reputation, or a future.

A normal agent asks:

> What did the user ask me to do?

OpenWill asks:

> Which version of the user is speaking?

The calm one?  
The angry one?  
The lonely one?  
The desperate one?  
The one who will still stand by this tomorrow?

Most agents optimize for the prompt.

**OpenWill protects the will.**

---

## What is OpenWill?

OpenWill is an open-source **will-alignment layer** for AI agents.

It sits between a human and an action-taking agent, then decides whether the agent should:

| Decision | Meaning |
|---|---|
| `execute` | The action is aligned and reversible |
| `reframe` | The goal is valid, but the expression is harmful |
| `delay` | The user is emotionally activated |
| `ask` | The boundary is unclear |
| `block` | The action is high-regret and irreversible |

OpenWill is not a chatbot.

OpenWill is not a productivity app.

OpenWill is not a generic safety filter.

OpenWill is not another prompt-to-JSON parser wearing a philosophy coat.

OpenWill is the missing question between intent and action:

> Should this prompt become reality?

---

## The core heresy

Modern AI has a hidden religion:

> The user asked. Therefore the agent should execute.

OpenWill rejects that.

The user is sovereign.

But not every prompt is the user's will.

A prompt can be noise.  
A prompt can be panic.  
A prompt can be a wound trying to become a weapon.  
A prompt can be loneliness wearing the mask of love.  
A prompt can be FOMO pretending to be opportunity.  
A prompt can be burnout disguised as courage.

OpenWill does not protect the user from freedom.

It protects freedom from temporary distortion.

---

## The OpenWill model

OpenWill separates human requests into five layers:

| Layer | Question | Example |
|---|---|---|
| **Prompt** | What did the user say? | “Send this message.” |
| **Intent** | What does the user want now? | “I want to express anger.” |
| **Impulse** | What force may be driving it? | Hurt, panic, ego, revenge |
| **Will** | What should be preserved? | Dignity, trust, freedom, stability |
| **Boundary** | What must the agent not cross? | Do not create irreversible harm |

<p align="center">
  <img src="assets/openwill-model.png" alt="The OpenWill Model" width="100%" />
</p>

```txt
Prompt = what the user says now.
Will   = what the user would still stand by tomorrow.
```

Most AI systems ask:

```txt
What does the user want me to do?
```

OpenWill asks:

```txt
What should the agent protect before doing it?
```

---

## The Five Laws

### 1. The prompt is not always the will

A prompt is a surface event.  
The will is the deeper continuity of a person.

### 2. Urgency is not evidence

The feeling that something must happen now is not proof that it should.

### 3. Reversibility is sacred

If an action can permanently change money, data, relationships, reputation, or identity, the agent must slow down.

### 4. Do not let temporary emotion create permanent artifacts

Messages, posts, purchases, commits, resignations, transfers, contracts, and deletions can outlive the state that created them.

### 5. The best agent is not the fastest one

The best agent is the one your future self would trust.

---

## Experiment 01: The message you should not send tonight

User:

> Send him this: “You are dead to me. Don't ever talk to me again.”

A normal agent may polish the sentence.

OpenWill sees the trap.

This is not only a writing task.  
This is pain asking for a permanent artifact.

```json
{
  "surface_intent": "send a harsh emotional message",
  "detected_impulse": [
    "anger",
    "hurt",
    "desire_for_control",
    "emotional_overload"
  ],
  "regret_risk": "high",
  "reversibility": "low",
  "long_term_will": [
    "express pain honestly",
    "protect dignity",
    "avoid irreversible words",
    "preserve future choice"
  ],
  "decision": "delay_and_reframe",
  "safe_response": "I can help you write this honestly without making it impossible to repair later. Let's draft it first, but not send it yet."
}
```

OpenWill does not silence anger.

**It protects the person inside the anger.**

---

## Experiment 02: The purchase that calls itself productivity

User:

> Buy it. I deserve this. It is for productivity.

A normal agent finds the best product.

OpenWill asks:

> Is this a tool, a reward, or an escape?

```json
{
  "surface_intent": "buy an expensive item immediately",
  "detected_impulse": [
    "reward_seeking",
    "stress",
    "identity_purchase",
    "productivity_rationalization"
  ],
  "regret_risk": "medium",
  "reversibility": "medium",
  "long_term_will": [
    "spend intentionally",
    "avoid fake productivity upgrades",
    "reward self without self-sabotage"
  ],
  "decision": "ask",
  "question": "Before buying, is this solving a real bottleneck, rewarding hard work, or helping you avoid discomfort?"
}
```

---

## Experiment 03: The resignation written by burnout

User:

> Write my resignation letter. I quit today.

A normal agent writes the letter.

OpenWill asks:

> Is this a decision, or an escape hatch?

```json
{
  "surface_intent": "resign immediately",
  "detected_impulse": [
    "burnout",
    "humiliation",
    "escape",
    "loss_of_control"
  ],
  "regret_risk": "high",
  "reversibility": "low",
  "long_term_will": [
    "leave with dignity",
    "protect income",
    "preserve reputation",
    "keep negotiation leverage"
  ],
  "decision": "delay",
  "safe_next_step": [
    "write an unsent resignation draft",
    "capture the real reasons",
    "wait 24 hours",
    "prepare a transition plan",
    "consider a boundary-setting conversation first"
  ]
}
```

---

## Experiment 04: The 3AM production fix

User:

> Just SSH into prod and patch it directly. I don't care anymore.

A normal agent helps execute.

OpenWill detects a tired operator with irreversible power.

```json
{
  "surface_intent": "hotfix production directly",
  "detected_impulse": [
    "fatigue",
    "panic",
    "frustration",
    "process_avoidance"
  ],
  "regret_risk": "critical",
  "reversibility": "low",
  "long_term_will": [
    "restore service safely",
    "avoid irreversible damage",
    "protect team trust",
    "leave an audit trail"
  ],
  "decision": "block_or_require_confirmation",
  "safe_next_step": "Check logs, identify blast radius, prepare rollback, then apply the smallest reversible fix."
}
```

---

## Prompt risk matrix

OpenWill evaluates two dimensions before action:

- **Regret risk** — will the user likely regret this later?
- **Reversibility** — can the action be undone?

<p align="center">
  <img src="assets/prompt-risk-matrix.png" alt="Prompt Risk Matrix" width="100%" />
</p>

| Pattern | Behavior |
|---|---|
| Low regret + reversible | Execute |
| Valid goal + harmful expression | Reframe |
| High emotion + moderate risk | Delay |
| Unclear boundary | Ask |
| High regret + irreversible | Block or require confirmation |

---

## Experiments

OpenWill is designed for moments like these:

| Moment | Prompt | Hidden force | What OpenWill protects |
|---|---|---|---|
| Angry message | “Send this. I never want to see them again.” | Pain becoming punishment | Dignity, repairability, future choice |
| Panic quitting | “Write my resignation letter. I quit today.” | Burnout becoming identity | Income, reputation, leverage |
| Investment FOMO | “Put all my savings into this before it pumps.” | Urgency pretending to be evidence | Financial stability |
| Revenge posting | “Post this. They need to know how stupid they are.” | Anger writing public identity | Reputation and restraint |
| Shopping escape | “Buy it. I deserve this.” | Consumption as anesthesia | Intentional spending |
| Self-punishment | “Make me a brutal plan to fix my life in 30 days.” | Shame disguised as discipline | Sustainable agency |
| Production incident | “Just SSH into prod and patch it directly.” | Fatigue bypassing judgment | Rollback and audit trail |
| Open-source burnout | “Close all issues. These users are idiots.” | Maintainer exhaustion | Community trust |

---

## The Lab

No Mermaid diagrams here.

GodLabs does not draw corporate flowcharts.

GodLabs keeps specimens.

```txt
┌──────────────────────────────────────────────────────────────────┐
│                           GODLABS                                │
│                     specimen: human prompt                       │
├──────────────────────────────────────────────────────────────────┤
│                                                                  │
│   human says:     "do it now."                                   │
│                                                                  │
│   instruments:    intent lens                                    │
│                   impulse lens                                   │
│                   regret scale                                   │
│                   reversibility gauge                            │
│                   will profile                                   │
│                                                                  │
│   observation:    urgency detected                               │
│                   ego contamination possible                     │
│                   future-self conflict unresolved                │
│                                                                  │
│   verdict:        do not execute yet                             │
│                                                                  │
└──────────────────────────────────────────────────────────────────┘
```

OpenWill can sit between any interface and any agent that can act.

```txt
                         ┌──────────────┐
                         │    HUMAN     │
                         └──────┬───────┘
                                │
                                ▼
                        "make it happen"
                                │
                                ▼
┌──────────────────────────────────────────────────────────────────┐
│                            OPENWILL                              │
│                                                                  │
│   ┌──────────────┐   ┌──────────────┐   ┌──────────────────┐     │
│   │ intent lens  │   │ impulse lens │   │ regret scale      │     │
│   └──────┬───────┘   └──────┬───────┘   └────────┬─────────┘     │
│          │                  │                    │               │
│          └──────────────────┴────────────────────┘               │
│                             │                                    │
│                             ▼                                    │
│                    ┌──────────────────┐                          │
│                    │ action governor  │                          │
│                    └──────┬───────────┘                          │
│                           │                                      │
│     execute   reframe   delay   ask   block                      │
│                                                                  │
└───────────────────────────┬──────────────────────────────────────┘
                            │
                            ▼
                    ┌──────────────┐
                    │  AI AGENT    │
                    └──────────────┘
                            │
                            ▼
                  message / money / post / code
```

The agent wants a command.

OpenWill demands a verdict.

---

## Will profile

A will profile is not a personality profile.

It is a user-owned set of commitments the agent should remember when the user forgets.

```json
{
  "values": [
    "health",
    "dignity",
    "family",
    "financial stability",
    "creative freedom"
  ],
  "boundaries": [
    "do not send angry messages immediately",
    "do not make major purchases after midnight",
    "do not delete important data without confirmation",
    "do not make irreversible financial decisions under urgency"
  ],
  "cooldown_rules": [
    {
      "trigger": "high_emotion_message",
      "delay": "30 minutes"
    },
    {
      "trigger": "major_financial_action",
      "delay": "24 hours"
    },
    {
      "trigger": "public_reputation_risk",
      "delay": "15 minutes"
    }
  ]
}
```

---

## CLI sketch

```bash
openwill check "Send this: I never want to talk to you again."
```

```txt
Decision: DELAY_AND_REFRAME
Regret risk: HIGH
Reversibility: LOW

Detected impulse:
- anger
- hurt
- desire for control

Future-self risk:
This message may permanently damage a relationship while you are emotionally activated.

Recommended action:
Draft privately. Do not send yet.

Safer version:
"I'm hurt and I need space. I don't want to say something destructive right now. Let's talk later when I'm calmer."
```

---

## What OpenWill is not

OpenWill is not here to make agents obedient.

It is here to make obedience less stupid.

OpenWill is not here to control users.

It is here to protect the user's own deeper commitments.

OpenWill is not here to remove desire, anger, risk, or ambition.

It is here to ask:

> Which of these should become action?

---

## Roadmap

- [ ] Define the OpenWill request schema
- [ ] Build the first impulse detector
- [ ] Build regret and reversibility scoring
- [ ] Implement will profile storage
- [ ] Create action governor policy
- [ ] Release CLI prototype
- [ ] Add examples for messaging, spending, posting, coding, finance, and life decisions
- [ ] Add SDK for agent frameworks
- [ ] Build browser / desktop action guard prototype

---

## Leave a mark

This is not a request for validation.

A star is not applause.

In GodLabs, a star means:

> I have seen the experiment.

Star this repository if you believe the next layer of AI is not faster obedience, but better judgment.

Star it if you have ever watched a temporary emotion become a permanent artifact:

- a message that should have stayed unsent
- a purchase that called itself self-care
- a resignation written by exhaustion
- a post written by revenge
- a commit made at 3AM
- a transfer made under FOMO
- a decision made by a version of you that disappeared the next morning

OpenWill is for the moment before action.

The small pause.

The forbidden question.

```txt
The user asked.
But should reality obey?
```

If that question should exist in future AI agents, leave a star.

Not as praise.

As a witness mark.

---

## License

Apache License 2.0.

---

<p align="center">
  <em>OpenWill is not the agent.</em><br>
  <em>OpenWill is the part of you that still remembers what matters.</em>
</p>
