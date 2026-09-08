### Q.1 Challenging situation.

One challenging situation I faced was related to a critical issue in our CAD application.

After completing 3D modeling or 2D drafting work, users were intermittently getting a **connection lost error while saving their files**. This was a critical issue because users could lose their work and might need to recreate the modeling from scratch.

I reported the defect with the workflow I initially identified. The main challenge was that the issue was intermittent and difficult to reproduce consistently.

After the developer provided a fix, I validated it using the original workflow. However, I was still able to reproduce the issue, although with different steps. Since I was the author of the defect, I took ownership of investigating it further.

I tried multiple scenarios, such as keeping the application running for a longer time, saving newly created files, saving existing files from the repository, and testing different workflows. I also discussed the issue with senior developers and other testers.

During the investigation, we identified that an **XCR flag related to load management** was enabled during testing of high-load assemblies. It was normally disabled by default, and after identifying this configuration-related cause, disabling the flag resolved the issue.

This experience taught me the importance of **not giving up on intermittent issues, trying different scenarios, and collaborating with the team to identify the root cause**.

### Q.2 How do you handle a conflict or disagreement with a developer?

In my experience, most disagreements with developers are related to the expected behavior of a functionality.

For example, our cloud-based CAD product mostly takes reference from our desktop CAD application NX. In some cases, I found a behavior that I felt could be incorrect or inconvenient from a user perspective. However, when I discussed it with the developer, they explained that the referenced application also behaves in the same way.

In such situations, instead of arguing about whether it is a bug, I discuss the impact with the developer and team and check the expected behavior and user perspective.

If the issue is critical, it may be fixed. If it is an important improvement but not critical, it can be considered as an enhancement for a future PI. If the behavior is minor and considered acceptable according to the design, it may be closed as designed.

So, I try to handle disagreements through **discussion, requirements, user impact, and collaboration**, rather than treating them as personal conflicts.

### Q.3 How do you handle tight deadlines or pressure?

In my current project, we sometimes face tight deadlines when user stories are delayed due to dependencies on other teams or technical issues. As a result, QA may get very limited time for testing.

In such situations, I **prioritize the critical functionality and key user workflows first**, and plan the remaining testing based on the available time. I also communicate any risks or concerns to the team early.

When required, I coordinate with the team and put in additional effort to complete the testing within the timeline. If there are common issues affecting multiple teams, we may also participate in activities such as a test fest.

Overall, I try to stay organized, prioritize effectively, and focus on completing the most important testing without compromising quality.

### Q.4 Where do you see yourself in 3--5 years?

In the next 3 to 5 years, I see myself as a **strong senior QA or automation engineer** with good expertise in automation, especially in Playwright and TypeScript.

I want to take more ownership of the overall testing process, contribute to automation and framework improvements, and work on more complex projects. I would also like to support and guide junior team members as I gain more experience.

Overall, my goal is to grow into a role where I can contribute both **technically and as a responsible member of the QA team**.

### Q.5 Other offers?

#### Scenario 1 — Just started interviewing

Currently, I don't have any offers. I have recently started exploring opportunities and have given a few interviews. I am mainly looking for the right opportunity that matches my skills and career goals.

#### Scenario 2 — Advanced in other interview processes

Currently, I don't have any confirmed offers, but I am in the advanced stages of discussions with a couple of companies. I am exploring the opportunities and will make a decision based on the role, responsibilities, growth, and overall opportunity.

#### Scenario 3 — You already have an offer

Yes, I currently have an offer from another company. However, I am still exploring opportunities because I want to make sure I choose the role that is the best fit for my skills, career goals, and long-term growth.

### Q.6 Do you have any questions for us?



