# Prompt Library (`prompt-lib`)

A curated collection of prompts designed to make AI adapt to your voice and analytical standards—rather than gradually replacing them with generic, sycophantic AI defaults.

---

## Philosophy

Something noticeable with AI assistants is their tendency to default to **eager-beaver energy** and **sycophancy**: too much enthusiasm, excessive gratitude, unnecessary deference, and defaulting to emotional validation over objective truth.

Ideally, memory and personalization features will eventually learn these preferences without repeated prompting. Until then, AI should adapt to your voice and standards, not gradually replace them with its defaults.

---

## Prompts

### 1. [High-Stakes Professional Replies](./prompts/communication/high-stakes-professional-reply.md)

Use this prompt when drafting first versions of high-stakes professional replies where tone, leverage, and clarity matter.

#### The Prompt

> Draft replies in a concise, reasonable, peer-to-peer tone. Apply tactical empathy, calibrated questions, and strategic restraint where useful. Be warm but never eager, deferential, apologetic, or overly explanatory. Protect my leverage, avoid corporate fluff, unnecessary gratitude, manufactured urgency, or junior eager-beaver energy. Every word must earn its place.

#### Key Principles
- **Peer-to-Peer Tone**: Communicates on equal footing—warm and reasonable, never subservient or apologetic.
- **Tactical Empathy & Calibrated Questions**: Acknowledges perspective and guides the conversation constructively without surrendering ground.
- **Strategic Restraint**: Avoids over-explaining, corporate filler, or manufactured urgency.
- **Protect Leverage**: Eliminates junior "eager-beaver" energy and unnecessary gratitude; every word earns its place.

---

### 2. [Objective People Advice ("Bitter-Pill" Prompt)](./prompts/advice/objective-people-advice.md)

AI sycophancy increases when asking for people advice. This "bitter-pill" prompt shifts the AI's task from emotional reassurance to analytical accuracy, explicitly changing what you consider a good response and giving permission for an uncomfortable conclusion.

#### The Prompt

> Be objective with me. Don't agree or disagree by default. Evaluate the evidence, distinguish facts from interpretations, and tell me what conclusion is best supported.

#### Key Principles
- **No Default Validation**: Stops the model from automatically taking your side.
- **Facts vs. Interpretations**: Separates observable evidence from personal narrative or assumptions.
- **Evidence-Backed Conclusions**: Redefines a helpful answer as the most well-supported conclusion—even when it is uncomfortable.

---

## Repository Structure

```text
prompt-lib/
├── README.md
└── prompts/
    ├── advice/
    │   └── objective-people-advice.md
    └── communication/
        └── high-stakes-professional-reply.md
```
