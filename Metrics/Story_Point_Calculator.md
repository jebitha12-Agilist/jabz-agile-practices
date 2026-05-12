# Story Point Calculator 📐

## 🎯 Purpose
Provide a structured way to estimate user stories based on **Effort, Complexity, and Risk**.  
This helps Agile teams achieve consistent estimation, improve predictability, and align on Definition of Ready (DoR) and Definition of Done (DoD).

---

## 📝 Parameters

### 1. Effort
- **High** → ≥ 5 days (Development + Review + Testing + Documentation).  
- **Medium** → 1–3 days.  
- **Low** → < 1 day.  
*(Assumption: 1 day = 6 hours)*

### 2. Complexity
- **UI Components** → Input controls, navigation, informational elements.  
- **Business Logic** → Calculations, process flows, page flows, notifications.  
- **Data Access/Integration** → Objects, attributes, test data setup, test cases.  
- **High** → Large number of components/flows.  
- **Medium** → Moderate number.  
- **Low** → Few/simple components.

### 3. Risk
- **High** → >10% architectural change.  
- **Medium** → 5–10% architectural change.  
- **Low** → <5% architectural change.

---

## 📊 Example User Stories

| Epic ID | User Story | Description | Effort | Complexity | Risk | Story Points |
|---------|------------|-------------|--------|------------|------|--------------|
| 201     | US1 – Login | Admin login to Accounts Page | Low | Low | Medium | 3 |
| 202     | US2 – Asset Linking | Link assets to accounts | High | High | High | 13 |

---

## 📂 Formula (Simplified)
- **Low + Low + Low** → 1 SP  
- **Medium + Low + Low** → 2 SP  
- **High + Medium + Low** → 5 SP  
- **High + High + Medium** → 8 SP  
- **High + High + High** → 13 SP
