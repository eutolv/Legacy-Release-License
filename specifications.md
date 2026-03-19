# 📘 LRL Specification

Version: 1.0
Status: Draft

---

## 1. Purpose

This document defines the operational behavior of the Legacy Release License (LRL), including phase transitions, edge cases, and interpretation rules.

---

## 2. Phase Transition Rules

### 2.1 Start of License Timeline

The timeline begins at:

* The date of the first public release; OR
* A date explicitly defined by the Licensor

---

### 2.2 End of Support Detection

"End of Support" is considered true when ANY of the following occurs:

* The Licensor publicly declares end of support;
* No updates, patches, or releases occur for a continuous period of 36 months;
* The Licensor ceases all public communication regarding the Licensed Work

---

### 2.3 End of Production Detection

"End of Production" is considered true when:

* The Licensed Work is no longer sold, distributed, or licensed commercially; OR
* The Licensor formally declares end of production

---

### 2.4 Phase II Activation

Phase II is triggered when:

* Conditions defined in LICENSE.md are met; OR
* The default time threshold is reached

---

### 2.5 Phase III Activation

Phase III is triggered automatically when:

* The defined Phase II duration has elapsed; OR
* The Licensor explicitly declares transition to Phase III

---

## 3. Time Configuration

The Licensor may define:

* Duration of Phase I
* Duration of Phase II

If not defined, defaults apply:

* Phase II → 5 years after last official release or end of support
* Phase III → 15 years after the start of Phase II

---

## 4. Edge Cases

### 4.1 Licensor Inactivity or Disappearance

If the Licensor becomes unreachable or inactive:

* All phase transitions continue automatically based on time rules
* No manual confirmation is required

---

### 4.2 Partial Activity (Minor Updates)

Minor or insignificant updates (e.g., small patches, metadata changes, or superficial fixes) do NOT reset the timeline.

Only meaningful updates may reset the timeline, defined as:

* Functional changes
* Security fixes
* Feature additions

---

### 4.3 Forks During Phase I

Forks are NOT permitted unless explicitly authorized by the Licensor.

---

### 4.4 Multiple Licensors

In cases where multiple parties hold rights:

* The authority to define phase transitions belongs to the original Licensor or designated license issuer

---

## 5. Commercial Use Clarification

Commercial use includes:

* Direct sale
* Paid access
* Subscription-based distribution
* Integration into paid products or services

---

## 6. Attribution Enforcement

Attribution must be:

* Clearly visible
* Included in documentation, UI, or distribution materials
* Not removable by default

---

## 7. Trademark Handling

* Trademarks are NEVER transferred under this license
* Community Versions must not imply official status or endorsement

---

## 8. Irreversibility

Once a phase transition occurs:

* It cannot be reverted
* All granted rights remain permanently valid

---

## 9. Interpretation Principle

In case of ambiguity:

* Interpretations should favor preservation over restriction

---

## 10. Future Revisions

This specification may evolve in future versions of the LRL.
