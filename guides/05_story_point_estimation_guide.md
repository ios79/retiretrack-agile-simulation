# 📏 05_story_point_estimation_guide.md  
**Purpose:** Show how we estimate and prioritize work in the RetireTrack Agile simulation using simple story points and value-based prioritization methods like WSJF and BFTB.

---

## 🧮 What Are Story Points?

Story points are a **relative measure** of effort, complexity, and uncertainty used to size user stories.  
We use them for planning and tracking progress across sprints.

---

## 🔢 Estimating Story Points

We use a **Fibonacci scale** to reflect increasing complexity:

| Story Points | Description                         |
|--------------|-------------------------------------|
| 1            | Very small, minimal effort          |
| 2–3          | Small task, low complexity          |
| 5            | Medium effort, some unknowns        |
| 8            | Large, needs discussion/splitting   |
| 13+          | Very large or unclear – split it    |

Story points are estimated **collaboratively** with the team (PO, Dev, QA).

---

## 🚦 Prioritizing Work

Once stories are estimated, we apply **two simple prioritization techniques**:

### ✅ 1. Bang For The Buck (BFTB)

This is a quick way to **maximize value per effort**:
BFTB Score = Value Points ÷ Story Points

We assign **Value Points** based on business/customer importance (e.g., 1–10), then divide by story points.

| Story | Value | Story Points | BFTB Score |
|-------|-------|---------------|------------|
| RAS-1 | 8     | 4             | 2.0        |
| RAS-2 | 6     | 2             | 3.0 ✅      |
| RAS-3 | 9     | 6             | 1.5        |

> Prioritize higher BFTB scores first.

---

### ✅ 2. WSJF – Weighted Shortest Job First

WSJF adds more depth by factoring in **urgency and strategic importance**:
WSJF = (Business Value + Time Criticality + Risk Reduction) ÷ Story Points


Still easy to calculate but better for large projects.

| Story | BV | TC | RR | Total | SP | WSJF |
|-------|----|----|----|--------|----|------|
| RAS-1 | 6  | 5  | 3  | 14     | 4  | 3.5  |
| RAS-2 | 7  | 3  | 2  | 12     | 2  | 6.0 ✅ |
| RAS-3 | 8  | 6  | 4  | 18     | 6  | 3.0  |

> Use WSJF for more **strategic prioritization**.

---

## 📈 Velocity

- Velocity = story points completed per sprint  
- In Sprint 1, we completed ~20 points  
- Future sprints aim to match or improve this pace

---

## 🎯 Summary

- **Story Points** help us size and estimate stories  
- **BFTB** is a quick way to prioritize by value per effort  
- **WSJF** adds more business context for larger projects  
- Together, they support **value-driven planning**

