![DX at Scale"](../../resources/dxatscale_logo.jpg) 

[Home](../../) » Articles » Applying the Gemba Walk Methodology to Software Development Agile Teams

# Applying the Gemba Walk Methodology to Software Development Agile Teams  
A practical guide to leveraging Gemba Walks for process improvement and team collaboration in Software Development Agile environments.

> Disclaimer: The following article provides practical insights into how Gemba Walks can be applied within Software Development Agile teams to foster transparency, collaboration, and continuous improvement. Its purpose is not to present a rigid formula but to share a flexible approach adaptable to your team’s unique context. Every organization has its own characteristics—culture, processes, and priorities—so be sure to tailor the insights from this article to your specific situation. This adaptability is, in fact, the essence of being Agile.

You probably came to this article because you’re exploring ways to enhance team dynamics and operational efficiency. Maybe you’ve heard about Gemba Walks from Lean manufacturing, or you’ve seen success stories and are now wondering how they might fit into software development. Regardless of your current stage, you likely share a common goal: finding practical steps to help your Agile teams continuously improve. This guide aims to bridge theory and practice, outlining how you can apply Gemba Walks in a Software Development Agile environment.

Before diving in, please note that the Gemba Walk approach is just one tool in your Lean-Agile toolbox. This article assumes you already have a basic understanding of what a Gemba Walk is, and now you want to adapt it for use in software development teams so you can realize its benefits—ranging from boosting morale to driving continuous improvement.


__Navigation__

- [First things first](#first-things-first)  
- [What is a Gemba Walk?](#what-is-a-gemba-walk)  
- [Benefits of Gemba Walks in Agile Teams](#benefits-of-gemba-walks-in-agile-teams)  
- [Key Elements of a Successful Gemba Walk](#key-elements-of-a-successful-gemba-walk)  
- [Metrics to Track During a Gemba Walk](#metrics-to-track-during-a-gemba-walk)  
- [Post-Gemba: Turning Insights into Actions](#post-gemba-turning-insights-into-actions)  
- [Conclusion](#conclusion)  
- [References](#references)

## First things first
Any significant initiative—whether it’s a large-scale technical upgrade or introducing a new Lean-Agile practice—benefits from clear communication and real commitment from senior management. Leaders who actively support new approaches set the tone for the rest of the organization, making it easier for teams to embrace change. According to *The Scrum Guide* (Schwaber & Sutherland, 2020), supportive leadership is critical in fostering an environment where teams can experiment and adapt safely.

Management backing is especially important for Gemba Walks. Without it, teams might not see the value or may lack the time and resources to participate fully. Additionally, ensure that your Agile teams have the necessary context and knowledge to benefit from Gemba Walks. Access to product owners, stakeholders, and real-time metrics is essential. If these foundational pieces aren’t in place, address them before moving forward.

Finally, remember that Gemba Walks are not a one-off event. They are part of a continuous improvement cycle (*Kaizen*), which is central to Lean thinking (Liker, 2004). As the business, teams, and technology evolve, so should your Gemba Walk process.

With these foundational elements in mind, let’s explore how Gemba Walks can be adapted for software development.

---

## What is a Gemba Walk?
The term “Gemba” is derived from the Japanese phrase *Genchi Genbutsu*, which translates to “go to the real place.” This concept originated in the Toyota Production System and was popularized in works like *The Toyota Way* (Liker, 2004) and *Gemba Kaizen* (Imai, 1997). In traditional manufacturing, a Gemba Walk involves physically observing a production floor to spot inefficiencies and opportunities for improvement.

### Adapting Gemba Walks for Software Development
In Agile software development, the principles remain the same but the focus shifts to knowledge work. Instead of watching assembly lines or machinery, we observe how teams collaborate—often across both physical and digital environments. A Gemba Walk might include sitting in on a virtual stand-up, reviewing a team’s board in Jira or Azure DevOps, or discussing the current sprint backlog in person.

While in traditional Lean settings a single worker might be stopped and observed, in software development—particularly in *Scrum*, where the entire team aims for a single Sprint Goal—we engage the whole team. Everyone collaborates to provide a clear, collective understanding of the current situation (Sutherland, 2014). This collaborative pause ensures that insights are comprehensive, capturing not just individual tasks but also the team’s coordination, blockers, and workflow patterns.

## Benefits of Gemba Walks in Agile Teams
Implementing Gemba Walks in an Agile software environment can yield numerous advantages:

1. **Boosting Team Morale**  
   - **Example:** When leaders take an active interest in day-to-day tasks—reviewing the sprint backlog or pair-programming sessions—team members feel seen and valued. This sense of recognition can lead to higher motivation, as people realize their work is both noticed and appreciated.

2. **Highlighting Success Stories**  
   - **Example:** Suppose one squad has significantly reduced bug count by adopting test-driven development (TDD). A Gemba Walk can spotlight this best practice, prompting other teams to try TDD for similar benefits.

3. **Encouraging Transparency**  
   - **Example:** By physically or digitally showing in-progress user stories, sprint burn charts, or pipeline dashboards, the entire organization gains a clear view of what’s happening. In turn, problems like bottlenecks become more visible and can be addressed earlier.

4. **Streamlining Processes**  
   - **Example:** Perhaps the build time for a particular microservice is unusually long. Observing the CI/CD pipeline during a Gemba Walk might reveal inefficient scripts or outdated dependencies. Addressing these can save hours or days over the course of many sprints.

5. **Driving Continuous Improvement**  
   - **Example:** By collecting real-time feedback during the walk, leadership and the team can make immediate course corrections. Over several Gemba Walks, these small improvements compound, aligning with the Kaizen philosophy of ongoing, incremental progress (Imai, 1997).

Realizing these benefits requires consistency and a structured approach, ensuring that insights gained are translated into actionable tasks and shared learnings.

## Key Elements of a Successful Gemba Walk
When introducing Gemba Walks to Agile teams, consider these core components:

### 1. Audience
Aim for a balanced mix of stakeholders, team leads, and management. Each group brings a unique perspective:  
- **Stakeholders:** May highlight business priorities or customer feedback that the development team lacks.  
- **Team Leads:** Can quickly assess the feasibility of improvements, streamline newly observed or shared processes, and facilitate knowledge transfer.  
- **Management:** Ensures that organizational backing and resources are available to address the issues or leverage the opportunities discovered.

By bringing diverse views to the table, you uncover details that might otherwise stay hidden.

### 2. Cadence
Many organizations find value in scheduling Gemba Walks every 3 months, dedicating about 60 minutes to the process. This timeframe is a guideline; some teams may opt for shorter intervals (e.g., once per sprint) if they’re in a rapid growth phase, while others may extend it if their domain is more stable. The key is to ensure that the frequency aligns with your team’s workload and ability to implement feedback in a timely manner.

### 3. The Situation Wall
A “Situation Wall” is a visual management tool—either a physical board or a digital dashboard—that displays the team’s current progress, tasks, blockers, and any relevant metrics. Think of it as a large, transparent window into the sprint.  
- **Physical Example:** Sticky notes on a Kanban board with columns like *To Do*, *In Progress*, *Review*, *Done*.  
- **Digital Example:** An online Kanban or Scrum board (e.g., Jira, Azure DevOps) projected or shared on-screen so everyone sees the same real-time view.

By centralizing important information, the Situation Wall serves as the focal point for structured, data-driven conversations during a Gemba Walk.

> **Tip:** While structure is necessary, allow space for open-ended questions. Overly rigid agendas can stifle creativity and hide deeper issues.

## Metrics to Track During a Gemba Walk
In Agile, data is your friend. It highlights trends, spots problems early, and measures progress. During a Gemba Walk, focusing on a handful of well-understood metrics prevents the session from devolving into superficial reporting. Below are common metrics, explained in simple terms:

1. **Burndown Chart**  
   - **What It Is:** A graphical representation showing how much work remains in a sprint, typically measured in story points or hours over time.  
   - **Key Focus:**  
     - **Timely updates:** Ensure the team updates tasks daily so the chart remains accurate.  
     - **Risk identification:** Spikes or plateaus in the chart might indicate blockers or unexpected complexities.  
     - **Trend analysis:** Comparing past and current burndowns can reveal patterns, like chronic under- or over-estimation.

2. **Maturity Score**  
   - **What It Is:** A qualitative or quantitative measure reflecting how well the team follows and improves its Agile processes (e.g., using a custom scale or a widely known model).  
   - **Key Focus:**  
     - **Incremental progress:** Look for upward trends over multiple sprints.  
     - **Action items:** Each score should be accompanied by clear steps (e.g., “implement code reviews,” “improve backlog refinement”).  
     - **Team ownership:** Encourage the team to self-assess and propose improvements.

3. **Risk Indicator**  
   - **What It Is:** A simple red-yellow-green (RYG) status or numeric scale showing the project’s risk level (technical, operational, or otherwise).  
   - **Key Focus:**  
     - **Early detection:** Red or yellow signals demand immediate attention.  
     - **Contextual insight:** What kind of risk is it? Are dependencies at play, or is it a resourcing issue?  
     - **Preventive actions:** Document and track how teams plan to mitigate these risks.

4. **Bugs per Sprint**  
   - **What It Is:** A count of how many defects are discovered and fixed during a sprint.  
   - **Key Focus:**  
     - **Quality funnel:** Where are bugs being caught—development (DEV), user acceptance testing (UAT), or production (PROD)? The earlier, the better.  
     - **Root cause analysis:** Consistent bug spikes might suggest code smells, missing unit tests, or knowledge gaps.  
     - **Resolution time:** How fast are bugs addressed and closed?

5. **Velocity**  
   - **What It Is:** The number of story points (or similar estimate units) a team completes in a single sprint.  
   - **Key Focus:**  
     - **Consistency:** Large swings in velocity may indicate unstable story sizing or external disruptions.  
     - **Scope changes:** A sudden drop might reflect newly added user stories or shifting priorities.  
     - **Forecasting:** Over time, stable velocity helps predict future delivery timelines.

During the Gemba Walk, engage with the team by asking “why” questions about each metric. This encourages deeper analysis and reinforces a culture of continuous learning, rather than superficial compliance.

## Post-Gemba: Turning Insights into Actions
Observations made during a Gemba Walk are only as valuable as the actions they inspire. The following steps help transform insights into tangible improvements:

1. **Document Findings**  
   - **Detailed Notes or Recordings:** Assign one or more people to capture comments, questions, and next steps. Video recordings or voice notes can supplement written documentation.  
   - **Accessible Repository:** Store these notes in a shared space—like Confluence, SharePoint, or a dedicated Slack channel—so the entire team and stakeholders can review them later.  
   - **Retrospective Input:** Bring these findings into your next retrospective or risk review session. This ensures that observations don’t get lost and become actionable items with due dates and owners.

2. **Celebrate Achievements**  
   - **Positive Reinforcement:** When teams meet sprint goals or significantly reduce technical debt, highlight these wins. Recognition boosts morale and sets a positive tone for future improvements.  
   - **Knowledge Sharing:** If a particular team overcame a major bottleneck (like drastically cutting build times), share it across the organization. Success stories can inspire other squads to try similar strategies.

3. **Plan Next Steps**  
   - **Concrete Action Items:** Turn observations (e.g., “Our testing pipeline is too slow”) into well-defined tasks (“Reduce end-to-end test run from 30 minutes to 15 minutes by optimizing scripts”).  
   - **Ownership and Timelines:** Assign a responsible person (or pair) and set realistic deadlines. This ensures accountability and prevents tasks from lingering indefinitely.  
   - **Continuous Improvement Cycle:** Follow up on these action items in the next sprint or at the next Gemba Walk. This loop keeps improvements front and center, embodying the Kaizen philosophy.

## Conclusion
Gemba Walks act as a powerful catalyst for continuous improvement in Agile software development, bridging the gap between leadership and day-to-day execution. By observing real work where it happens—whether in the codebase, the sprint board, or a team’s collaborative workflow—organizations foster a deeper sense of collaboration. These walks bring stakeholders, developers, and leaders together, creating transparency around obstacles and opportunities alike.

Moreover, Gemba Walks instigate an ongoing cycle of learning and adaptation, perfectly aligned with the core principles of Agile. As you refine this practice and integrate it into your culture, expect stronger stakeholder engagement, clearer communication channels, and an environment that consistently seeks and applies feedback.

> “Responding to change over following a plan” – *Agile Manifesto*

Over time, Gemba Walks can become a cornerstone of your Agile transformation journey, fueling not only continuous delivery of software but also continuous improvement in people, processes, and technology.

## References
- Imai, M. (1997). *Gemba Kaizen: A Commonsense Approach to a Continuous Improvement Strategy*. McGraw-Hill.  
- Liker, J. K. (2004). *The Toyota Way: 14 Management Principles from the World’s Greatest Manufacturer*. McGraw-Hill.  
- Schwaber, K. & Sutherland, J. (2020). *The Scrum Guide*. Scrum.org.  
- Sutherland, J. (2014). *Scrum: The Art of Doing Twice the Work in Half the Time*. Crown Business.

---

Author: @gsimplicio
Created on: 2025-01-27

---

[< Back](../../)