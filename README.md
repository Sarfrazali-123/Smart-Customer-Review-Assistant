# Sentiment-Aware Customer Review Workflow  

This project showcases how to build an **intelligent, automated customer review handling system** using **LangGraph** and **LLMs**.  

The workflow automatically classifies customer reviews as *positive* or *negative*, generates personalized responses, and—if the review is negative—performs a deeper diagnosis to understand **issue type, tone, and urgency** before crafting an empathetic reply.  

---

## ✨ Features  

- 🔍 **Sentiment Analysis** – Detect whether a review is positive or negative.  
- 🙌 **Positive Review Handling** – Generate a warm thank-you message and encourage users to share feedback on the website.  
- 🛠️ **Negative Review Diagnosis** – Extracts key details:  
  - Issue Type: `UX`, `Performance`, `Bug`, `Support`, `Other`  
  - Tone: `angry`, `frustrated`, `disappointed`, `calm`  
  - Urgency: `low`, `medium`, `high`  
- 💬 **Negative Response Generation** – Respond empathetically with solutions tailored to the issue, tone, and urgency.  
- 🔗 **LangGraph Workflow** – Manages the entire decision flow between steps.  



## Demo
![Workflow Diagram](https://github.com/Sarfrazali-123/Smart-Customer-Review-Assistant/blob/865e7bef70e92b7837a77e1197d69dcbdccecdb4/Capture-455.PNG)  
![Workflow Diagram](https://github.com/Sarfrazali-123/Smart-Customer-Review-Assistant/blob/865e7bef70e92b7837a77e1197d69dcbdccecdb4/Capture-jfdjfd.PNG)  


