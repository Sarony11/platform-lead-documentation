## 3. Review & Feedback Rituals: Deep Dive

These rituals are focused on inspecting completed work, verifying its quality, and collecting feedback from various stakeholders. They help ensure that the project is building the right thing, and building the thing right.

### 3.1. Sprint/Iteration Review (or Demo)

The Sprint Review, often referred to as a "Demo," is a formal meeting where the Development Team presents the increment of "Done" work completed during the sprint to stakeholders.

* **Objective:** To inspect the **increment of working software** and gather feedback from stakeholders to adapt the Product Backlog for future sprints. It's about demonstrating what was built, not just talking about it.
* **Key Activities:**
    * **Presentation of "Done" Work:** The Development Team (or Product Owner) demonstrates the features and functionalities completed during the sprint. This should be a live demonstration, not just slides.
    * **Discussion & Feedback:** Stakeholders provide feedback, ask questions, and suggest potential changes or new ideas.
    * **Backlog Review:** The Product Owner discusses the current state of the Product Backlog, including likely items for the next sprints, and gathers input on priorities.
    * **Collaboration:** It's a collaborative working session, not a one-way presentation.
* **Participants:** Development Team, Product Owner, Scrum Master/Facilitator, and crucially, **Key Stakeholders** (e.g., business owners, end-users, department heads, sales, marketing).
* **Frequency:** At the end of each sprint (e.g., every 1-2 weeks).
* **Timebox:** Typically **1-5 minutes per participant**, depending on the sprint length and complexity of the increment.
* **Benefits:**
    * **Early Feedback:** Crucial for course correction, ensuring the product stays aligned with business needs and user expectations.
    * **Transparency:** Provides stakeholders with a clear view of progress and what they can expect.
    * **Validation:** Verifies that the delivered features meet the defined acceptance criteria.
    * **Motivation:** The team gets direct feedback, seeing the impact of their work and celebrating achievements.
    * **Collaboration:** Fosters strong collaboration between the development team and business stakeholders.
* **Common Pitfalls:** Turning into a formal presentation with slides instead of an interactive demo, lack of active participation from stakeholders, focusing on "why it's not done" rather than inspecting the "done" increment, inviting too few or too many stakeholders.

---

### 3.2. Code Reviews / Pull Request (PR) Reviews

Code reviews are systematic examinations of source code by peers to identify bugs, enforce coding standards, improve code quality, and share knowledge. They are typically conducted before code is merged into the main branch.

* **Objective:** To improve code quality, catch defects early, ensure adherence to coding standards, share knowledge, and enhance security.
* **Key Activities:**
    * **Developer Creates PR:** A developer finishes a piece of work and creates a Pull Request (or Merge Request) to propose merging their changes.
    * **Peer Review:** One or more team members review the code, commenting on potential issues, style, logic, tests, and best practices.
    * **Discussion & Iteration:** Reviewers and the author discuss comments, and the author makes necessary adjustments.
    * **Approval & Merge:** Once reviewed and approved, the code is merged into the main branch.
* **Participants:** Author of the code, 1-N peer reviewers (typically other developers from the team), sometimes QA or Tech Leads.
* **Frequency:** Continuously, whenever a code change is ready to be merged.
* **Timebox:** Individual reviews should be kept short (ideally under an hour) to maintain focus and allow for quick turnaround.
* **Benefits:**
    * **Improved Code Quality:** Catches bugs, logical errors, and design flaws before they reach production.
    * **Knowledge Sharing:** Spreads understanding of the codebase and different parts of the system across the team.
    * **Mentorship:** Junior developers learn from more experienced peers, and senior developers get fresh perspectives.
    * **Consistency:** Helps enforce coding standards, architectural patterns, and best practices.
    * **Security:** Can identify potential security vulnerabilities in the code.
* **Common Pitfalls:** Reviews becoming too long or critical, focusing on trivial stylistic issues instead of fundamental problems, taking too long to complete reviews, "rubber stamping" (approving without proper review).

---

### 3.3. QA/Testing Sign-off & Acceptance Testing

These practices focus on the final validation of features before they are deployed to production, often involving formal acceptance from business stakeholders.

* **Objective:** To formally verify that the developed features meet all requirements and are free of critical defects, making them ready for release.
* **Key Activities:**
    * **Internal QA Testing:** Dedicated QA engineers or developers run thorough tests (manual, automated, exploratory) to ensure the feature works as expected and integrates correctly.
    * **User Acceptance Testing (UAT):** Business users or product owners perform tests to ensure the solution meets their business needs and is usable in a real-world scenario.
    * **Bug Reporting & Tracking:** Any identified issues are logged, prioritized, and tracked through to resolution.
    * **Sign-off:** Formal approval from relevant stakeholders (e.g., Product Owner, Business Lead) indicating readiness for release.
* **Participants:** QA Engineers, Product Owner, Business Stakeholders, Development Team (for bug fixes).
* **Frequency:** After development is complete for a feature/release, leading up to deployment.
* **Timebox:** Varies depending on the complexity and scope of the feature/release.
* **Benefits:**
    * **Quality Assurance:** Ensures a high-quality product is delivered to end-users.
    * **Risk Reduction:** Catches critical bugs and usability issues before they impact users in production.
    * **Stakeholder Confidence:** Business users gain confidence in the product's readiness and alignment with their needs.
    * **Improved User Experience:** Ensures the final product is intuitive and meets user expectations.
* **Common Pitfalls:** Rushing testing phases, lack of clear acceptance criteria, insufficient test data, not having dedicated QA or testing resources, UAT becoming a bug-finding session instead of a validation one.