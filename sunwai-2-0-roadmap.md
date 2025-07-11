# Sunwai 2.0 - Draft Roadmap

**Date:** 2025-07-11

## 1. Guiding Philosophy: The Humane Refactoring

This document outlines the core principles for the evolution of Sunwai from version 1.0 to 2.0. The primary driver for this overhaul is direct user feedback from the language's creator, identifying that the cognitive load required to speak and construct sentences in Sunwai 1.0 is a significant barrier to its usability and enjoyment.

The goal of Sunwai 2.0 is to **drastically reduce this cognitive load** by prioritizing clarity, consistency, and a more intuitive learning path, without sacrificing the language's philosophical depth. This refactoring embraces the programmer's ethos of "dismantling and rebuilding"—using the valuable lessons from the v1.0 prototype to build a more robust, elegant, and ultimately more humane final product.

## 2. Core Principles for Development

### Principle I: Role Clarity (One Primary Role Per Root)

*   **Problem:** The multi-role nature of v1.0 roots (e.g., `wai` as Concept, Action, and Descriptor) creates high cognitive friction, forcing the user to constantly disambiguate.
*   **Solution:** Each root word in the Base Set will be assigned **one primary, default grammatical role**. To use a word in a non-primary role, a grammatical marker will be required.
*   **How it Works:**
    *   `wai` -> **Concept:** "water"
    *   `ta wai` -> **Action:** "to flow" (Action Marker + Concept)
    *   `so wai` -> **Descriptor:** "watery, liquid" (Descriptor Marker + Concept)
*   **Benefit:** Eliminates ambiguity at the root level. The rules for sentence construction become simpler and more consistent, freeing up mental energy for expressing ideas rather than wrestling with grammar.

### Principle II: Layered Acquisition (Formalize the Word Sets via `nepisun`)

*   **Problem:** The v1.0 dictionary is a single, large pool of words, which can be overwhelming for a new learner.
*   **Solution:** The dictionary and learning path will be formally restructured to follow the `nepisun` (Spiral-Knowledge) model, embodying the principle of "Progressive Disclosure."
*   **Proposed Structure:**
    1.  **Core Set (The Beige/Purple Vocabulary):** ~30-40 essential words for tangible concepts and basic needs (`ma`, `wai`, `tape`, `heim`, `ouman`, `an`). Provides immediate utility.
    2.  **Grammar Set (The Blue Vocabulary):** Introduce the key grammatical markers (`o`, `le`, `ta`, `so`, `si`, `se`, `ro`) as the second, distinct learning step. This is the "learn the rules" phase.
    3.  **Extended Set (The Orange/Green Vocabulary):** The library of standard, useful compounds for more precise and nuanced communication (`pisu`, `penere`, `oumanwailu`).
    4.  **Specialist Sets (The Yellow+ Vocabulary):** Abstract, technical, and philosophical terms for deep, systemic discussions (`nepisun`, `paisipu`, etc.).
*   **Benefit:** Provides a clear, manageable, and psychologically supportive learning curve. Users master one layer of complexity before moving to the next, mirroring their own conceptual development.

### Principle III: Syntactic Simplicity (Standardize Default Sentence Flow)

*   **Problem:** The total flexibility of v1.0 word order, while good for poetry, can be another source of cognitive load for everyday communication.
*   **Solution:** Establish a single, **recommended default sentence structure** for standard communication. The Concept-Action-Concept (C-A-C) flow is the leading candidate.
*   **How it Works:**
    *   For 90% of use cases, speakers will default to the standard syntax (e.g., `Ouman tape paitape` - "The person eats the cake").
    *   Deviating from this structure becomes a conscious, intentional choice for artistic or poetic effect, rather than a constant variable.
*   **Benefit:** Frees the user from having to "design" every sentence's structure, allowing for more fluid and effortless communication.

## 3. Next Steps

1.  **Review and Amend:** This document should be reviewed during a future high-energy session to confirm or refine these principles.
2.  **Base Set Refactoring:** Begin the practical work of refactoring the dictionary, starting with assigning a single, primary role to each word in the new, smaller **Core Set**.
3.  **Prototype New Sentences:** Construct test sentences using the new 2.0 rules to validate their clarity and ease of use.