---

## Ethics Lenses Journal  
### Mission Ready - Advanced Developer - Level 05 - Mission 05
### **Journal Goal:** Reflect on the ethics lenses and how they impact the decisions we make as individuals and as a team.

---

## The Five Ethical Lenses for Software Development Teams

The five ethical lenses can guide software development teams in making decisions that align with ethical principles while delivering value to users and stakeholders. Here's how they apply:

### 1. **Utilitarian Lens**: Focus on Outcomes
   - **Goal:** Maximize benefits and minimize harm for the largest number of people.
   - **Application in Software Teams:** 
     - Prioritize features that deliver the most user value (e.g., optimizing performance or usability).
     - Evaluate the impact of bugs or downtime on end-users and prioritize fixes accordingly.
     - Example: Choosing to implement robust search algorithms that improve accuracy, even if development takes longer.

### 2. **Rights Lens**: Protect Individual Rights
   - **Goal:** Respect and uphold the rights, freedoms, and dignity of all individuals.
   - **Application in Software Teams:**
     - Safeguard user privacy and data security, ensuring compliance with laws like GDPR.
     - Respect team members' work-life balance and autonomy in task completion.
     - Example: Designing features that let users control how their data is stored and used.

### 3. **Justice Lens**: Ensure Fairness
   - **Goal:** Promote fairness and equity in decisions and resource distribution.
   - **Application in Software Teams:**
     - Ensure algorithms or software features do not unintentionally favor certain user groups.
     - Distribute workload and credit fairly within the team.
     - Example: Auditing search results for biases that might disadvantage small businesses.

### 4. **Common Good Lens**: Consider the Community
   - **Goal:** Act in ways that benefit the broader community or society.
   - **Application in Software Teams:**
     - Create software that fosters trust, accessibility, and inclusivity.
     - Cultivate a collaborative team culture to enhance overall productivity and well-being.
     - Example: Ensuring APIs are accessible to small developers, not just large enterprises.

### 5. **Virtue Lens**: Cultivate Moral Character
   - **Goal:** Encourage behaviors that reflect integrity, honesty, and accountability.
   - **Application in Software Teams:**
     - Promote transparency in decision-making and commit to ethical development practices.
     - Foster a culture of mutual respect, learning, and professional growth.
     - Example: Openly discussing trade-offs and risks during sprint reviews, ensuring all voices are heard.

### Practical Implementation in Agile Teams:
- **Standups and Retrospectives:** Use these ceremonies to address ethical questions collaboratively.
- **Test-Driven Development (TDD):** Aligns with utilitarian and virtue lenses by ensuring code reliability and user satisfaction.
- **Open Communication:** Tools like MS Teams support justice and rights by enabling equitable participation in remote teams.

By considering these lenses throughout the development lifecycle, teams can create software that is not only functional but also ethically responsible.

---

### Journal Entries 
### **Date:** Mon 16, Dec, 2024

  - [CM] Reflections on how the lense may apply to our team.
  - [CM] [Rights Lens] [Autonomy] As a team we are based in different geographical locations and face different challenges in terms of work-life balance. We can respect each other right to autonomy, by scheduling daily standups at mutually convenient times that respect individuals needs and situations.
  - [CM[ [Virtue Lens] [Honesty/Truth] By having regular open and honest daily standup meetings, we aim to foster the trust between team members. 
  - [CM] [Justice Lens] [Equality] We should aim to find ways to distribute work equitably across our team, taking into consideration individual work-life balance challenges.
  - [CM] [Utilitarian Lens] [Maximise User Benifit] Use TDD to ensure the system consistently delivers a positive experience to users.
  - [CM] [Common Good Lens] [Team Morale is a Common Good] We should foster good team morale though regular, open, honest communicaton through Daily Standups, and using MS teams. Transparency and openess, help team members to feel heard, and understood, and help to align the team to a common set of goals, and foster a common understanding of their work, and the challenges they face.

---

### Journal Entries 
### **Date:** Tue 17, Dec, 2024

  - [CM] 
  - [CR] 
  - [SC] 

---

### Journal Entries 
### **Date:** Wed 18, Dec, 2024

  - [CM][Utilitarian Lens] [Maximise User Benifit] Semantic search can help to maximise the benifit for end-users, as it allows them to find auction items that are similar in a way that textual search cannot. For example a traditional search wouldn't find tricycle or three wheeler, when the user searches for trike, where is a semantic search does. Some of this utility may be lost due to latency of the search, if the vector embeddings is not designed to high concurrency.
  - [CM] [Rights Lens] [Privacy & Data Security] If you use an API to perform text embeddings using a third party. Then data privacy and security should be considered. In the case of auction listings where the listings are public, and there is tacit agreement by the user to make them public, by listing the auction. So this should not be a concern. I guess the only thing you may need to be careful with, is that you do not leak date outside of auction listing into the 3rd party API, through programming errors.
  - [CM] [Justice Lens] Does the search algorithm favour individuals or groups? Is there bias in the search, that unfairly favours certain listings or individuals. There is no seller data in the auction items records, so there is no way to favour a seller based on an auction items details. There can be some bias in the embedding model, so this should be considered.
  - [CR] 
  - [SC] 

---

### Journal Entries 
### **Date:** Thu 1, Dec, 2024

  - [CM] 
  - [CR] 
  - [SC] 

---
