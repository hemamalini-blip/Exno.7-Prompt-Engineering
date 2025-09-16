# Exno.7-Prompt-Engineering
# Name: Hemamalini S
# Register no: 212222210006
# Aim: To Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

---

## **Algorithm**

1. Define the **objective**: Efficiently reorganize daily tasks when unexpected cancellations occur.
2. Input the **original agenda** with scheduled tasks.
3. Identify **canceled tasks**.
4. Prompt the AI to:

   * Reorganize the remaining schedule.
   * Suggest new priorities.
   * Recommend opportunities for rest or self-improvement.
5. Output an **optimized daily agenda** with actionable insights.

---

## **Prompt (Program Simulation)**

**User Prompt:**
*"During a busy day, if a couple of scheduled tasks get canceled unexpectedly, review my remaining agenda and instantly reorganize my schedule to optimize my time, possibly recommending new priorities or opportunities for rest."*

---

## **Example Input Agenda (Before Cancellation)**

```
09:00 – Team meeting  
11:00 – Client call  
13:00 – Lunch  
15:00 – Project work  
17:00 – Gym session  
```

### **Cancelled Tasks:**

* 09:00 – Team meeting
* 11:00 – Client call

---

## **AI-Generated Output (Reorganized Agenda)**

```
09:00 – Deep work on project (shifted earlier to maximize focus)  
11:00 – Review notes & prepare presentation slides  
13:00 – Lunch break  
14:00 – Catch up on pending emails and admin work  
15:30 – Continue project work  
17:00 – Gym session (unchanged)  
19:00 – Relaxation or short learning module  
```

### **AI Recommendations:**

* Use freed-up morning hours for **focus-heavy tasks**.
* Keep lunch and gym unchanged to maintain balance.
* Add **relaxation or learning opportunities** in the evening.

---

## **Workflow Diagram**

```
        ┌─────────────────────┐
        │   Input Daily Agenda│
        └─────────┬───────────┘
                  │
      ┌───────────▼────────────┐
      │  Cancel Unexpected Tasks│
      └───────────┬────────────┘
                  │
      ┌───────────▼────────────┐
      │ AI Reviews & Reorganizes│
      │   Remaining Schedule    │
      └───────────┬────────────┘
                  │
      ┌───────────▼────────────┐
      │ Optimized Agenda +      │
      │ Recommendations (Work/Rest) │
      └────────────────────────┘
```





# Result: The Prompt is executed successfully


