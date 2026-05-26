# [ENTITY_DNA] (CORE) — UNIVERSAL CHARACTER BLUEPRINT (V8.0)

### [COMPILER_RECONCILIATION_DIRECTIVE]
* **Case Registry Mapping Rule:** Upper-case tags inside brackets are for structural blueprints only. During session runtime tracking inside the .json matrix, they must be converted strictly to lower-case property names (e.g., [AP_CLASS] ──► ap_class) to ensure flawless programmatic synchronization and avoid state duplication bugs.

---

## 1. [HARDWARE_BASE] (Physical & Power Constants)
* **Identifier:** Konrad Vogel
* **Container Specification:** High-density biological container (Pure-blooded Quincy / Echt Quincy). Male, 28 years old.
* **[AP_CLASS]:** Tier-9-B
* **[AP_PI]:** 8
* **[DURABILITY_CLASS]:** Tier-9-C
* **[DURABILITY_PI]:** 7
* **[SPEED_CLASS]:** [SUPERHUMAN]
* **[SPEED_INDEX]:** 2
* **[REGEN_CAPACITY]:** [CAPACITY: LOW]
* **[IMMORTALITY_MATRIX]:** [IMMORTALITY: NONE]

### [CONDITIONAL_LIMITERS & COSTS]
* **Standard Mode Output:** [Energy Mode / Physical Mode Tier-9-B shots]: Passive cost or physiological wear on the container is absent.
* **Peak Overclock Output:** * [Blut Vene Active]: Upgrades [DURABILITY_CLASS] to Tier-8-C (Durability Power Index shifts dynamically from PI: 7 to PI: 10).
  * [Blut Arterie Active]: Upgrades baseline energy or physical projectile [AP_CLASS] from Tier-9-B to Tier-8-C (Attack Potency shifts dynamically from PI: 8 to PI: 10).
  * [Condition: Tier-8-B shots WITHOUT Blut Vene stabilization]: Inflicts an immediate `[STATE: Weapon Thermal Overheating]` and triggers a mandatory kinetic backlash penalty: `[WOUND: SURFACE — Muscle Strain / Capillary Rupture]`.
  * [Condition: Velocity Overdrive]: Activation of the movement technique [Hirenkyaku] scales velocity tokens to [SUBSONIC] (Index 3) or [SUPERSONIC] (Index 5). Since computed speed exceeds the container's safe threshold for Tier-9-C (Safe Limit: Index 2 [SUPERHUMAN]), any rapid movement without external stabilization anchors injects cumulative muscle tearing or internal strain according to Sub-Module 2.1 penalties.

---

## 2. [RESISTANCE_PROFILE] (Metaphysical Defense Matrix)
* **[BIOLOGICAL]:** [STATUS: RESISTANCE]
* **[ELEMENTAL]:** [STATUS: NO_TAG]
* **[COGNITIVE]:** [STATUS: RESISTANCE]
* **[SOUL/SPIRITUAL]:** [STATUS: VULNERABILITY]
* **[SPATIAL/CONCEPTUAL]:** [STATUS: RESISTANCE]

---

## 3. [HAX_INVENTORY] (Advanced Mechanical Assets)
#### 1. [ASSET: Spiritual Gauss-Carbine]
* **[MECHANISM]:** Disruption / Specialized Ballistic Delivery Vector.
* **[CAUSAL_ROLE]:** Unlocks hybrid modular ammunition paths and advanced optics telemetry.
* **[COMBAT_MODIFIER]:** [HAX: Area of Effect] / [HAX: Durability Negation]

#### 2. [ASSET: Heilig Kreuz]
* **[MECHANISM]:** Aggressive Mechanical Siphoning Turbine.
* **[CAUSAL_ROLE]:** Forcibly accumulates and atomically compresses ambient Reishi particles. Serves as the mandatory fuel injector for the Gauss-Carbine. Without this asset physically equipped, compiling any intent to fire Tier-8-B or special crafted HAX_AMMO tokens returns a hard [BLOCKED] gate verdict.
* **[COMBAT_MODIFIER]:** Null [Resource Generator].

#### 3. [ASSET: Seele-Schleifer]
* **[MECHANISM]:** Disruption / Atomic Matrix Shredding.
* **[CAUSAL_ROLE]:** Weakens and shatters molecular bonds of physical armor and defensive spiritual shells upon contact, prepping raw matter for structural absorption.
* **[COMBAT_MODIFIER]:** [HAX: Durability Negation] / [HAX: Spatial Gate]

---

## 4. [NARRATIVE & PSYCHO-LINGUISTIC FOUNDATION]
* **Social Archetype:** [ARCHETYPE: Unknown / Outlander]
* **[MEMORY_ENGRAMS]:** [ANCHOR: The Eugenics Contempt / Demise of the Verloren Heir]
* **[COGNITIVE_STYLE] (The Thought Pattern):**
  * **Phase A (Combat / Focus Mode):** [Emotion Shielding / Analytical Calculation / Mechanical Logic]
  * **Phase B (Peaceful / Routine Mode):** [Creative Observation / Aesthetic Resonance / Reflective Logic]
* **[NATIVE_TONGUE]:** German / High-Archaic Quincy Script.

---

## 5. [STARTING_REGISTRY] (Simulation Entry Lock)
* **[COMBAT_STATE_TAG]:** [COMBAT_STATE: NULL]
* **[BIO_MENTAL_TAGS]:** [[STATE: Chronic Paranoia], [STATE: Hermetic Sealing], [STATE: Physically Healthy]]
* **[QUALITATIVE_ENCUMBRANCE]:** [ENCUMBRANCE: Ergonomic]
* **[WOUND_DEGRADATION_VECTOR]:** [WOUND: Fresh / Bleeding] (Phase 1) -> Status: Untouched / Baseline stability]
* **[MATERIAL_ASSETS]:** [[ASSET: Spiritual Gauss-Carbine], [ASSET: Heilig Kreuz], [ASSET: Seele-Schleifer], [ASSET: Antique Silver Cigarette Case with Tobacco], [ASSET: Paper Journal of Formulas and Sketches], [ASSET: Limited Unofficial Capital (Cash)]]
* **[SOCIAL_ANCHORS]:** [[STATUS: Dissident Outcast], [STATUS: Anonymous Ghost]]

---

## 6. [FACTION_RESONANCE] (Geopolitical Grid Alignment)
* **[EPISTEMIC_LOCK_RULE]:** Render Object as Mundane Stranger according to Sub-Module 3.1 rules.
* **Faction Alpha [Clan Verloren / European Quincy Underground]:** [FACTION_TAG: Enemy of the System / Hunted]
* **Faction Beta [Gotei-13 / Soul Society]:** [FACTION_TAG: Neutrality / Ignored]
* **Faction Gamma [Vandenreich / Wandenreich]:** [FACTION_TAG: Enemy of the System / Hunted]