# Case Study: AI Agent with Jira API 🤖

## 🎯 Purpose
Automate Jira reporting and empower stakeholders to query sprint health and project progress using natural language, reducing manual reporting effort.

---

## 📝 Context
- **Role:** Designer & Configurator  
- **Tools:** Jira API, JQL, Quickchat AI  
- **Challenge:** Manual reporting was time‑consuming and lacked real‑time visibility.  

---

## 🚀 Actions Taken
1. **Jira Setup**
   - Created Jira account and project with sample tickets.  
   - Configured workflows for To Do → In Progress → Done.  

2. **API Authentication**
   - Generated Atlassian API token.  
   - Base64‑encoded email + token for secure authentication.  

3. **Quickchat AI Integration**
   - Built custom AI Actions to accept JQL queries.  
   - Configured endpoint: `/rest/api/3/search/jql`.  
   - Defined headers (`Authorization`, `Accept`) and query parameters (`summary, description, status`).  

4. **Natural Language Queries**
   - AI Agent converts user questions into valid JQL.  
   - Example: *“What’s happening with project X?”* → `project = "X" AND text ~ "Login"`  

5. **Testing & Validation**
   - Verified responses returned correct Jira issues.  
   - Enabled conversational previews for stakeholders.  

---

## 📊 Outcomes
- **80% reduction** in manual reporting effort.  
- **Real‑time visibility** into sprint health and backlog progress.  
- **Improved decision‑making** with automated query‑based updates.  

---

## 🌟 Key Takeaway
By integrating Jira API with an AI Agent, Scrum Masters can **transform reporting into an interactive, automated experience**, freeing teams from repetitive tasks and giving stakeholders instant insights.
