# The Fellowship Companion - Artifact III: Representation

*`(For demonstration purposes only)`*

## System Capability

**The system helps the Fellowship make decisions.**

I chose this capability because decisions are important for the Fellowship and they have to decide a lot during the journey.

## Static Interface Implementation

`[Flow](/code/code-1-representation.html)`

> For this example see [code-1-representation.weak.html](/src/code-1-representation.weak.html)

**The interface has:**

- A heading at the top
- Three buttons underneath
- Some text

The user can see the options and decide.

## Design Rationale

This design supports the intent because it lets the user decide things. I followed the wireframe I made before. I did not implement functionality because this is only HTML and CSS.

**Assumption:** The Fellowship knows how to use the interface.

---
---

## Why this is weak

- **Capability is too vague:** *"Helps the Fellowship make decisions"* is not a clearly scoped capability.
- **No concrete context:** No reference to which decision, when, or why it matters in the journey.
- **No structural thinking:** Mentions *"buttons"* and *"text"* but no explanation of hierarchy or grouping.
- **HTML treated as decoration:** No discussion of semantic structure or layout intent.
- **Design rationale is superficial:** Restates the assignment constraints instead of reflecting on decisions.
- **Assumptions are not examined:** *"I assume the Fellowship knows how to use it"* avoids responsibility instead of reasoning.
- **No linkage:** Weak or missing connection to Homework 1 (intent/value) and Homework 2 (wireframe).
- **Reads like a checklist:** Not like a considered design step in a larger system.

*`This example is not entirely wrong, but it is very generic and would be very hard to build on in later assignments.`*
