# AI Glossary for Project Managers

A companion to the *AI Project Management with Claude* training syllabus.
Short definitions, grouped by topic.

## 1. AI basics

| Term | Meaning |
|---|---|
| **LLM** (Large Language Model) | A large language model such as Claude |
| **Generative AI** | AI that **creates** text, images or code |
| **Model** | The AI itself (e.g. Claude Opus, Sonnet, Haiku) |
| **Token** | A piece of text the model reads and writes; pricing and limits are measured in tokens |
| **Context window** | How much text the model can "keep in mind" at once |
| **Hallucination** | The model confidently making up wrong information |
| **Training data** | The data the model was trained on |
| **Knowledge cutoff** | The date the model's knowledge ends |

## 2. Prompting

| Term | Meaning |
|---|---|
| **Prompt** | The instruction given to the model |
| **System prompt** | Background instruction that sets the model's overall behaviour |
| **Prompt engineering** | Designing instructions to get better results |
| **Few-shot prompting** | Adding a few examples to the instruction |
| **Role prompting** | Giving the model a role ("you are a senior PM") |
| **Chain of thought** | Asking the model to reason step by step |
| **Prompt template** | A reusable, ready-made instruction pattern |

## 3. Claude and agents

| Term | Meaning |
|---|---|
| **AI agent** | AI that plans steps and uses tools on its own |
| **Agentic workflow** | A multi-step workflow carried out by an agent |
| **Tool use / function calling** | The model using tools such as files, the web or APIs |
| **Skill** | A reusable method or instruction file |
| **Subagent** | A focused helper agent working in its own context |
| **Plugin** | A package that bundles skills, subagents, commands and connections |
| **Slash command** | A shortcut called as `/command` |
| **Hook** | A rule that runs automatically when a given event happens |
| **CLAUDE.md** | A project file with lasting instructions and memory |
| **Orchestration** | Coordinating the work of several agents |

## 4. Integration and automation

| Term | Meaning |
|---|---|
| **Automation** | Letting software do a task without manual steps |
| **Workflow automation** | Automating a whole workflow from start to finish |
| **Task automation** | Automating a single task, e.g. sending an email |
| **API** | The door through which programs talk to each other |
| **API key** | The access key for an API (keep it secret) |
| **MCP** (Model Context Protocol) | The standard for connecting Claude to systems such as CRM, ERP or Gmail |
| **Connector** | A ready-made connection to a system (e.g. Gmail, Notion) |
| **Webhook** | One system notifying another when an event happens |
| **Trigger** | The event that starts an automation (e.g. "when a new email arrives") |
| **Scheduled task / cron job** | A task that runs by itself at set times |
| **Human-in-the-loop** | A person approves the critical steps — e.g. "draft the email, I'll send it" |

## 5. Data and knowledge

| Term | Meaning |
|---|---|
| **RAG** (Retrieval-Augmented Generation) | The model pulls information from your documents before answering |
| **Embedding** | Representing the meaning of text as numbers; search and RAG are built on it |
| **Vector database** | A database that stores and searches embeddings |
| **Fine-tuning** | Further training a model on your own data |
| **Data governance** | Rules for who may use data, and how |
| **PII** (Personally Identifiable Information) | Personal data such as names or phone numbers; handle with care when giving it to AI |

## 6. Quality, risk and evaluation

| Term | Meaning |
|---|---|
| **Eval** (evaluation) | Systematically measuring the quality of AI output |
| **Benchmark** | A standard test used for comparison |
| **Guardrails** | Rules that limit what the model must not do |
| **Prompt injection** | Malicious instructions hidden inside a document or web page |
| **Bias** | Systematic skew in the model's output |
| **Responsible AI** | Principles for using AI safely, fairly and transparently |
| **Grounding** | Basing answers on real sources (like evidence labels in a discovery log) |

## 7. Product and project management

| Term | Meaning |
|---|---|
| **AI PM** | A person who manages AI projects or products |
| **PoC** (Proof of Concept) | A small trial that answers "does this work at all?" |
| **MVP** (Minimum Viable Product) | The smallest working product released to users |
| **PRD** (Product Requirements Document) | A document describing what a product must do |
| **Use case** | A concrete business problem the AI will solve |
| **ROI** (Return on Investment) | What an investment pays back, e.g. hours saved |
| **Pilot** | A trial in a real setting with a limited group |

## 8. Further terms

### Technical foundations

| Term | Meaning |
|---|---|
| **Machine learning (ML)** | Systems that learn patterns from data instead of following hand-written rules |
| **Neural network** | A model made of layers of connected "neurons"; the basis of modern AI |
| **Deep learning** | Machine learning with large, many-layered neural networks |
| **Transformer** | The neural network architecture behind today's LLMs |
| **Foundation model** | A large general-purpose model that many applications are built on |
| **Inference** | Running a trained model to get an answer (as opposed to training it) |
| **Latency** | How long the model takes to respond |
| **Parameters** | The internal numbers a model learns; often used to describe model size |

### Model settings and output

| Term | Meaning |
|---|---|
| **Temperature** | How random or creative the output is; low = consistent, high = varied |
| **Max tokens** | The maximum length of the model's answer |
| **Structured output** | Output in a fixed format such as JSON, so other software can use it |
| **Rate limit** | How many requests or tokens you may use per minute |
| **Multimodal** | A model that handles more than text, e.g. images, PDFs or audio |
| **Prompt caching** | Reusing a repeated part of a prompt to cut cost and latency |
| **Streaming** | Showing the answer word by word as it is generated |

### How models are trained

| Term | Meaning |
|---|---|
| **Pre-training** | The first, large-scale training on general text |
| **Supervised learning** | Learning from examples that come with correct answers |
| **RLHF** (Reinforcement Learning from Human Feedback) | Improving a model using human ratings of its answers |
| **Constitutional AI** | Anthropic's method of training a model to follow a written set of principles |
| **Open vs closed models** | Open: weights can be downloaded and run yourself; closed: used only via a provider's service (like Claude) |
| **On-premise / self-hosted** | Running a model on your own servers instead of a cloud service |

### Safety, law and governance

| Term | Meaning |
|---|---|
| **Red teaming** | Deliberately trying to make the AI fail or misbehave, to find weaknesses |
| **Jailbreak** | A prompt that tries to get around the model's safety rules |
| **Model card** | A document describing a model's purpose, limits and test results |
| **Alignment** | Making a model's behaviour match human intentions and values |
| **Explainability** | Being able to understand why the AI gave a particular output |
| **EU AI Act** | The EU law that regulates AI systems by risk level |
| **GDPR / KVKK** | EU and Turkish personal data protection laws; they apply when AI processes personal data |
| **Data residency** | Where data is physically stored and processed (e.g. inside the EU) |

### Big-picture concepts

| Term | Meaning |
|---|---|
| **AGI** (Artificial General Intelligence) | Hypothetical AI matching human ability across most tasks |
| **Copilot / assistant** | AI that works alongside a person, who stays in control |
| **Autonomy level** | How much an AI decides and acts on its own versus asking a human |
| **Vibe coding** | Building software by describing what you want to an AI in plain language |

## 9. Working concepts

### Pseudocode

| Term | Meaning |
|---|---|
| **Pseudocode** | Writing the logic of a program step by step in plain language, without the rules of a real programming language. Useful for explaining an automation or hook to a developer or to Claude before it is built |

```
IF a new email arrives
    summarise the email
    save the summary as a draft
ELSE
    wait
```

### Hook events in Claude Code

A hook is a command that runs **every time** a given event happens — unlike an
instruction in a skill or CLAUDE.md, which Claude follows most of the time.
Hooks are configured in `settings.json`.

| Event | When it fires | Example use |
|---|---|---|
| **PreToolUse** | Before Claude uses a tool | Block edits to certain files |
| **PostToolUse** | After Claude uses a tool | Format code or run tests after a file is edited |
| **UserPromptSubmit** | When you send a message | Add context to the message automatically |
| **Stop** | When Claude finishes its work | Send you a notification |
| **SessionStart** | When a session starts | Load the project's current status |

### Plugin vs automation

| | Plugin | Automation |
|---|---|---|
| **What it is** | A **package** that adds capabilities to Claude (skills, subagents, commands, hooks, connectors) | A task that runs **without manual steps** |
| **Question it answers** | *What can Claude do?* | *Does the work happen by itself?* |
| **Analogy** | A toolbox | A machine that runs on its own |
| **Example** | An application-adaptation plugin with cover-letter and CV skills | "Every Monday at 09:00, prepare the weekly report" |

A plugin **can contain** automation (a hook or a scheduled task), but most
plugins run only when you ask. Automation can also exist **without** a plugin —
a single scheduled task or hook is enough.
