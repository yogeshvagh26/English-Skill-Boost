## 1. Situation : Monthly Executive Review – The "Churn" Blame Game

**Context:** You are a Data Analyst at a B2B subscription software company. It's the monthly executive review. The CEO (Sarah) and the Head of Customer Success (Mike) are staring at a worrying trend: customer churn has increased from 4% to 7% over the last three months. Marketing is blaming Product for a poor user experience. Product is blaming Customer Success for not engaging clients. You walk in with the data to settle the debate and reframe the narrative.

---

## 2. Conversation

| Speaker       | Dialogue                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CEO (Sarah)** | Let's cut to the chase. Our churn rate is creeping up and I need answers. Mike, your team is on the front lines – is the product failing our customers?                                                                                                                                                                                                                                                                                                        |
| **Mike (Head of CS)** | Sarah, honestly, we're hearing complaints about missing features. But I also think we're losing customers who never really understood the value from day one.                                                                                                                                                                                                                                                                                                  |
| **You (Analyst)** | *(steps in)* Before we point fingers at Product or CS, let me share what the data actually says. I ran a **cohort analysis** on all customers who joined in the last 6 months. The headline: churn is not happening because of missing features. It's happening because of **poor onboarding adoption**.                                                                                                                                                       |
| **Sarah** | Walk me through that. How did you isolate that?                                                                                                                                                                                                                                                                                                                                                                                                               |
| **You (Analyst)** | I segmented churned customers by their activity in the first 14 days. Customers who completed our "core 3 setup tasks" (inviting teammates, uploading data, and running their first report) have a 92% retention rate after 90 days. Customers who completed 0 or 1 of those tasks? Their churn rate is 34%. So the story isn't *"Our product is broken."* The story is *"Our onboarding funnel is leaking customers before they see value."*                   |
| **Mike** | That aligns with what I'm seeing – but I didn't have the numbers to prove it. So it's not a sales or product failure – it's a **time-to-value** problem.                                                                                                                                                                                                                                                                                                       |
| **You (Analyst)** | Exactly. The root cause is a lack of structured guidance in week 1. My **recommendation**: Instead of building new features, let's invest in an interactive onboarding email sequence that walks users through those 3 core tasks. Also, let's add a "health score" to our CRM that flags any new user who hasn't completed task 1 by day 3, so CS can proactively reach out. I project this could reduce churn by 2 percentage points in the next quarter. |
| **Sarah** | I love that it's actionable and doesn't require engineering resources. Mike, can you own the email sequence?                                                                                                                                                                                                                                                                                                                                                  |
| **Mike** | Done. And I want that health score on my dashboard by end of week.                                                                                                                                                                                                                                                                                                                                                                                            |
| **Sarah** | Great work, Analyst. You didn't just give us a number – you gave us a lever to pull.                                                                                                                                                                                                                                                                                                                                                                          |

---

## 3. Vocabulary and Expressions

| Word/Phrase                     | Part of Speech | Meaning                                                                                | Example Sentence                                                                                 |
| ------------------------------- | -------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **Churn rate**                  | Noun (Metric)  | The percentage of customers who cancel or stop subscribing within a given period       | *Our churn rate spiked to 7% this quarter – we need to understand why.*                           |
| **Cohort analysis**             | Noun (Method)  | A technique that groups users by a shared characteristic (e.g., sign-up month) to track behavior over time | *Cohort analysis revealed that customers from March have a much lower retention than February.*  |
| **Retention rate**              | Noun (Metric)  | The percentage of customers who stay with your product over a specific period          | *Improving onboarding boosted our 90-day retention from 78% to 86%.*                             |
| **Onboarding**                  | Noun           | The process of guiding new users to become familiar with and derive value from your product | *Our onboarding flow is too long – users drop off after step 2.*                                 |
| **Time-to-Value (TTV)**         | Noun (Concept) | The time it takes for a new user to realize the core benefit of your product           | *If your time-to-value is longer than 7 days, you'll lose impatient users.*                      |
| **Adoption**                    | Noun           | The extent to which users actively use the key features of your product                | *Adoption of the reporting module is only 20% – we need to promote it better.*                   |
| **Health score**                | Noun (Tool)    | A composite metric that predicts the likelihood of a customer churning or renewing     | *A customer with a health score below 50 triggers an automatic check-in from CS.*                |
| **Root cause**                  | Noun Phrase    | The primary underlying reason for a problem or trend                                    | *We found the root cause of churn was not pricing, but lack of training.*                        |
| **Leading indicator**           | Noun Phrase    | A metric that predicts future performance (e.g., login frequency)                      | *Daily active users is a leading indicator for churn – if it drops, churn follows.*              |
| **Lagging indicator**           | Noun Phrase    | A metric that reflects past performance (e.g., quarterly churn rate)                   | *Churn is a lagging indicator – by the time we see it, the customer has already left.*           |
| **Leaky funnel**                | Metaphor       | A process where you lose potential customers at each stage of the journey              | *Our free trial funnel is leaky – only 10% of sign-ups ever start a task.*                       |
| **Proactive outreach**          | Noun Phrase    | Reaching out to customers before they experience a problem or express dissatisfaction | *Instead of waiting for cancellation calls, we do proactive outreach to low-engagement users.*  |

---

## 4. Key Takeaways

### Common Sentence Patterns (for Root-Cause Storytelling)

| Pattern                                                              | Use                                                                                    |
| -------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| *"Before we point fingers at [Team A] or [Team B], let me share what the data actually says."* | To de-escalate blame and ground the conversation in facts.                              |
| *"I ran a [analysis type] on [segment]."*                            | To introduce your methodology briefly (builds credibility).                            |
| *"Customers who [action] have [high metric] – customers who [don't] have [low metric]."* | To show a powerful comparative contrast (the "this vs. that" structure).                |
| *"So the story isn't [X]. The story is [Y]."*                        | To firmly reframe the narrative (use this exact pattern).                              |
| *"The root cause is [cause] – not [misconception]."*                 | To cut through assumptions and pinpoint the real driver.                                |
| *"My recommendation: [Action] because it addresses [root cause]. I project [quantified benefit]."* | To tie the recommendation directly back to the problem with a forecast.                |
| *"You didn't just give me a number – you gave me a lever to pull."*  | The ultimate compliment for a data analyst (aim to earn this feedback).                |

### Useful Phrases to Remember
- **Shifting from blame to process:** *"This is not a people problem – it's a process problem."*
- **Introducing predictive metrics:** *"Instead of waiting for churn, let's track [early indicator] to catch it early."*
- **Validating your analysis:** *"To ensure this isn't a fluke, I cross-checked this trend across 3 different cohorts – the pattern holds."*
- **Making it relatable:** *"Imagine a gym where no one shows you how to use the machines. That's what our onboarding feels like."* (Use analogies).
- **Closing with action:** *"With your approval, I can build this health score dashboard by Friday. Mike, can you draft the email sequence by Wednesday?"* (Drive accountability).

### Practical Speaking Tips (for Root-Cause Narratives)
1.  **Lead with the conclusion, not the methodology.** Do not say: *"I used Python to clean the data, then I joined 3 tables..."* Say: *"Churn is driven by poor onboarding, not product quality. Here's the proof."* Then explain the method only if asked.
2.  **Use "The 2x2 Comparison"**. Compare two groups (e.g., Onboarded vs. Non-onboarded) side-by-side. It creates a dramatic visual in the listener's mind.
3.  **Turn metrics into stories.** Don't say *"retention is 92%"* – say *"92 out of every 100 customers who finish onboarding stay with us for a year."* It humanizes the number.
4.  **Anticipate and pre-empt objections.** Before they ask, answer: *"I also checked if pricing or seasonality explains this – they don't. It's uniquely tied to the first 14 days."*
5.  **End with a "Projection"** (forecast). Stakeholders love numbers they can take to the board. Even a rough estimate like *"I project a 2-point churn reduction"* is better than no estimate.