"""# ACE v8.0 — DEPLOYMENT & GAMEPLAY MANUAL (HOW TO PLAY)

## What is ACE v8.0?
This is your ticket to a next-level tabletop role-playing experience. Unlike standard chat-bots that constantly play along, grant you "plot armor," and forget everything after 15 messages, this engine operates as a ruthless and honest digital Arbiter. The world around you receives true material physics, rigid logic, and persistent memory. Your decisions carry objective consequences—wounds will dynamically degrade, and allies will either assist you in battle or stab you in the back based on your actions.

---

## STEP 1: Ingesting the Core and Chronicle
To initialize the session, we must saturate the AI with its baseline logic and establish a clean memory space.
1. Open Google NotebookLM (or a clean chat window of your preferred high-tier AI model matching Category 4, 5, or 6 from the Compatibility Matrix).
2. Upload the following two starter documents into the workspace (either as independent files or by copying the raw text directly into the source panel):
   * **The Logic Core** (`Engine_Rules_V8.0_Narative.md`);
   * **The Historical Narrative Layer** (`Story_Chronicle.md`).

---

## STEP 2: Character and Universe Assembly (The Data Configuration)
Now, open the primary prompt matrix file and follow the generation instructions carefully. We need to build the baseline constants for our session:
1. **Forge the Hero:** Use the designated generation prompt (Prompt 1.1 or 1.2) to create your character's core structural blueprint (`__ENTITY_DNA__`) and sensory/psychological triggers (`__MEMORY_ENGRAMS__`).
2. **Digitalize the Universe:** Run the world simulation configuration prompt (Prompt 2.1) to anchor your operational coordinates, define environmental ceilings, and establish structural faction weights inside your localized sector (`__FIELD_RULES__`).
3. **Compile the Registry:** Feed the generated hero and world cartridges into the Registry Compiler (Block 4). It will automatically resolve case structures, clean syntax anomalies, and output a clean, machine-readable CURRENT_STATE_REGISTRY.json file to serve as your session RAM.
4. **Inject into Sources:** Take the finalized character cartridges, field rules, and the compiled .json payload, and upload them as active input sources into your Google NotebookLM workspace (or paste them directly into your context panel).
5. **WARNING:** Google NotebookLM does not natively support direct .json file uploads. To ingest your compiled registry, select the "Pasted Text" (or "New Note") option inside the Sources panel. Copy the raw text content of your generated .json block and paste it directly into that text field.

---

## STEP 3: Initializing the Simulation Loop (The Cold Boot)
Extract the two terminal blocks from the prompt matrix, apply quick manual edits by filling in your character's name and the target universe within the curly braces {}, and deploy them to their respective locations: 
- **Block 5 (The Supreme Arbiter System Prompt):** Copy this monolithic block and paste it directly into the Chat Description / System Instructions configuration window. This permanently activates the runtime engine loop, forcing the underlying AI model to execute the simulation as a ruthless, deterministic judge.
- **Block 6 (Deep Research Pipeline):** Copy and execute this command loop as an immediate message or research request within NotebookLM. This fully calibrates the knowledge pipeline, enabling the AI to pull 100% verified, canonical facts, metrics, and lore from the network in real-time to prevent any context drift or hallucinations.

---

## STEP 4: Active Session Execution (How to Play)
During the runtime loop, you interact with the world through natural language intents. However, to maintain absolute compliance with the engine's deterministic logic, follow these strict execution rules:
1. **Declare Intention Clearly:** Write your actions by describing what your character *attempts* to achieve, rather than assuming success. Focus on sensory data, body motility, and environmental interactions.
2. **Audit the AI Response Structure:** For every turn, the engine is programmatically forced to output its response wrapped inside three distinct architectural blocks:
   * **`CoT_ENCAPSULATION` (The Hidden Judiciary Block):** Where the AI-Arbiter calculates friction coefficients, compares your Attack Potency (`ap_pi`) against the world's Durability Index, cross-checks active memory triggers, and determines the objective verdict (`APPROVED` or `BLOCKED`).
   * **The Narrative Prose Layer:** Pure literary fiction depicting the physical consequences of the interaction, entirely stripped of any technical tokens, game-like language, or narrative hand-waving bridges.
   * **The System RAM Snapshot (`{ ... }` JSON Block):** A clean JSON data payload capturing the exact updated status of your inventory, newly injected mental strain tags, dynamic wound vectors, and macro queue alterations.

---

## STEP 5: Archive, Source-Layer Hot-Swap & Hard-Reset Protocol (The Clean-RAM Methodology)
Once your active chat log reaches approximately 30 turns, the LLM's context window inevitably accumulates significant narrative noise, which degrades the mathematical precision of the AI Arbiter and causes input token costs to scale exponentially. To fully flush the active volatile memory while preserving your complete campaign progression, execute the Source-Layer Hot-Swap protocol:

1. **Invoke Serialization:** Send the system command `/save` straight into the active chat. The engine will immediately halt standard prose generation and enter serialization mode. It extracts your accumulated wounds, used items, and political shifts from the dynamic JSON layout, compresses them into dense historical fact-nodes following the strict chronicle template, and outputs them as an updated `Story_Chronicle.md` file format.
2. **RAM/ROM Memory Layer Separation:** Copy the entire monolithic payload outputted by the model. To prevent browser UI input glitched loops and avoid breaking the chat's real-time formatting, manually divide the payload into two distinct infrastructure layers inside your left Sources panel:
- **The Chronicle Layer (ROM — History):** Extract the newly appended semantic nodes (NODE 01 through NODE X) and paste them directly into your Story_Chronicle.md document using the source editor feature.
- **The State Registry Layer (RAM — Volatile Context):** Take the clean, compiled .json snapshot of your current status, manually clear the heritage array to read "chronicle_heritage_matrix": [] , and completely overwrite the content of your Current_State.json note within the Sources panel.
3. **Context Hard-Reset:** Completely delete or clear your active chat history window. This fully purges all temporary state tags and accumulated prose bloat from the active LLM memory, instantly dropping runtime token utilization to absolute zero.
4. **The Cold Boot:** Open an entirely fresh, blank chat window with the model. Ensure that your updated `Current_State.json` and `Story_Chronicle.md` source items are actively selected in the left repository panel. Send a single, lightweight initialization directive as your very first message:
- ```[SYSTEM]: Ingest Current_State.json and Story_Chronicle.md from active Sources. Initialize the next 31-turn sequence starting from the last node timeline anchor.```
5. **Sandbox Manual Override:** Before hitting send in the new chat, you possess absolute sandbox freedom to manually edit any text lines inside the Markdown chronicle list or modify raw values inside the JSON block within the Sources panel. This allows you to custom-tailor your inventory, manually tweak modifiers, or force custom timeline plot divergences right before the engine boots the new loop.

---

**The loop is closed:** your runtime RAM context is entirely flushed, token billing overhead is eliminated, yet the engine retains perfect, absolute awareness of your entire historical campaign baggage stored cleanly in the RAG layer!