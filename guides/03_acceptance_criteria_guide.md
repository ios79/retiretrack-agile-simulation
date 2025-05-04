# 📋 03_acceptance_criteria_guide.md  
**Purpose:** Define how we approach writing effective acceptance criteria (AC) for user stories in the RetireTrack Agile simulation project.

---

## 🎯 What Are Acceptance Criteria?

Acceptance Criteria (AC) are **clear, testable conditions** that a product or feature must meet to be accepted by the Product Owner or stakeholders.

They act as the **confirmation** part of the story — ensuring the user story delivers what’s intended.

---

## ✅ Why Acceptance Criteria Matter

- Prevent **miscommunication** between business and development  
- Define the **boundaries** of a user story or feature  
- Serve as a **contract for definition of success**  
- Help QA teams write **targeted test cases**  
- Enable **traceability** for audit and compliance  

---

## ✍️ How We Write Acceptance Criteria

We use two complementary approaches:

### 1. ✅ Gherkin Syntax (Given–When–Then–And)

A widely used format that supports behavior-driven development (BDD). It adds context, trigger, and expected result.

#### Example:

Given the case intake form is open  
And all required fields are filled  
When the user submits the form  
Then a new case is created  
And a confirmation message is displayed

### 2. ✅ Bullet-Point Style

When Gherkin is too verbose, we also use plain, simple statements that are still testable:

- Case is created only when all required fields are completed  
- Confirmation message appears after submission  
- Unique case ID is generated upon case creation  

---

## 🧠 Best Practices

- ✅ Write ACs with the team (PO + Dev + QA)  
- ✅ Include both positive and negative test paths  
- ✅ Keep ACs specific, atomic, and outcome-focused  
- ✅ Avoid vague terms like “user-friendly” or “fast”  
- ✅ Always link ACs to the Definition of Done  

---

## 📎 Common Mistakes to Avoid

- ❌ ACs that are too broad or ambiguous  
- ❌ Writing ACs after development starts  
- ❌ Confusing ACs with user story titles  
- ❌ Skipping testable behavior or edge cases  

---

## ✅ BONUS: AC vs Definition of Done

| Acceptance Criteria                       | Definition of Done                                 |
|------------------------------------------|----------------------------------------------------|
| Specific to the **individual story**     | Universal standard for **all stories/features**    |
| Defines **what needs to work**           | Defines **what must be completed and validated**   |
| Written for **functionality validation** | Covers **testing, docs, reviews, compliance**      |
