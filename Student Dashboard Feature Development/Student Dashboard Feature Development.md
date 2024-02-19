# StuConnect - Revolutionizing Communication in Education

Table of Contents
- [StuConnect - Revolutionizing Communication in Education](#stuconnect---revolutionizing-communication-in-education)
  - [Background](#background)
  - [Problem Statement](#problem-statement)
  - [Goals](#goals)
  - [Assumptions](#assumptions)
    - [1. Market:](#1-market)
    - [2. Technical:](#2-technical)
    - [3. Business:](#3-business)
    - [4. Organizational:](#4-organizational)
  - [Hypothesis \& Feature Description](#hypothesis--feature-description)
    - [Hypothesis:](#hypothesis)
    - [Feature Description:](#feature-description)
  - [Vision Narrative](#vision-narrative)
    - [Scenario 1: Collaborative Course Discussions](#scenario-1-collaborative-course-discussions)
    - [Scenario 2: Group Study Sessions](#scenario-2-group-study-sessions)
    - [Scenario 3: Interactive Whiteboard Sessions](#scenario-3-interactive-whiteboard-sessions)
  - [Key Trade Offs \& Decisions](#key-trade-offs--decisions)
    - [Alternative Considerations:](#alternative-considerations)
    - [Let's delve deeper into the rationale behind this decision:](#lets-delve-deeper-into-the-rationale-behind-this-decision)
    - [Proposed Solution:](#proposed-solution)
  - [Concept Mocks](#concept-mocks)
    - [Chat feature section](#chat-feature-section)
    - [Discussion Forum](#discussion-forum)
    - [Rooms feature](#rooms-feature)
    - [Group Study Feature](#group-study-feature)
    - [Live Doubt Clearing](#live-doubt-clearing)
    - [Collaborative Tool](#collaborative-tool)
  - [Risks \& Mitigations](#risks--mitigations)
    - [1. Potential resistance from learners accustomed to external networks:](#1-potential-resistance-from-learners-accustomed-to-external-networks)
    - [2. Technical glitches or system downtime affecting user experience:](#2-technical-glitches-or-system-downtime-affecting-user-experience)
    - [3. Sharing of unnecessary outside content and links by learners:](#3-sharing-of-unnecessary-outside-content-and-links-by-learners)
- [Appendix A (Alternatives)](#appendix-a-alternatives)
- [Appendix B (Competitors)](#appendix-b-competitors)
- [Appendix C (Research)](#appendix-c-research)


## Background

EduWorld is an academic institution dedicated to education and research in next-generation technologies like artificial intelligence, machine learning, and data science. EduWorld's vision is to be the catalyst in producing AI and data leaders of tomorrow. Through 3 to 6-month industry-focused programs, EduWorld aims to arm working professionals not only with skillsets like machine learning, and data science but provide them with a transformative learning experience to help them move up in their careers.

As the product manager, I recognize the increasing reliance of learners on external communication networks for peer interaction. However, these platforms pose several challenges such as distraction, privacy concerns, and lack of integration with educational resources. Therefore, EduWorld aims to develop a learner dashboard feature to foster seamless communication within its platform, eliminating the need for external networks.

My job is to build this feature, decide the functionalities it will have, and how it will help EduWorld eliminate the learner’s dependency on external communication networks, and they only prefer EduWorld’s communication dashboard feature. 


## Problem Statement

I am a **learner**, I am trying to **collaborate with my peers effectively**, but **I face barriers** because **existing external communication networks are distracting and not tailored to educational needs**, which makes me feel **overwhelmed and inefficient in my studies**.


## Goals

- Enable learners to interact effortlessly within EduWorld's platform.
- Increase learner engagement and collaboration.
- Eliminate learner dependency on external communication networks.
- Enable learners to form groups or forum within EduWorld’s platform.
- Improve productivity and focus by providing a centralized communication hub.
- Eliminate Physical Data Sharing.
- Eliminate The Engagement Issue Between A Teacher & learner.


## Assumptions

### 1. Market:
- **Assumption:** The market for online educational platforms is expanding rapidly, driven by increasing demand for remote learning solutions.

- **Rationale:** With the proliferation of online courses and distance education programs, there is a growing need for comprehensive platforms that facilitate communication and collaboration among learners in virtual learning environments. Refer Appendix B

### 2. Technical: 
- **Assumption:** The EduWorld platform has the technical infrastructure and capabilities to support the development and integration of the learner dashboard feature.

- **Rationale:** The existing technology stack and architecture of the EduWorld platform provide a solid foundation for implementing new features and functionalities, including real-time communication tools and user interfaces.

### 3. Business:
- **Assumption:** The successful implementation of the learner dashboard feature will enhance the overall value proposition of the EduWorld platform, leading to increased user engagement and retention.

- **Rationale:** By offering a seamless communication experience within the EduWorld ecosystem, learners are more likely to remain active users of the platform, resulting in higher subscription rates and revenue generation for the company. Refer Appendix B

### 4. Organizational:
- **Assumption:** The development team at EduWorld has the necessary expertise and resources to design, implement, and maintain the learner dashboard feature effectively.

- **Rationale:** EduWorld invests in talent acquisition and professional development to ensure that its engineering and product teams are equipped with the skills and knowledge required to deliver high-quality software solutions.


## Hypothesis & Feature Description

### Hypothesis: 
By introducing a learner dashboard feature with integrated communication tools, we will enhance learner collaboration within EduWorld's platform, leading to increased engagement and productivity, eliminating reliance on external communication networks, hence eliminating distraction while switching to external elements while studying.

### Feature Description:

**1. Discussion Forums:** 
- Create a discussion forum dedicated to each course/module where learners can clarify their doubts on the specific module.

- **KPIs:**
  - ***Active Participation Rate:*** Measure the percentage of enrolled learners who actively contribute to forum discussions within each course/module over a defined time period (e.g., weekly or monthly). This metric provides insights into the level of engagement and collaboration among learners.

  - ***Thread Engagement:*** Calculate the average number of replies per thread within each discussion forum. Higher thread engagement indicates more interactive and in-depth conversations, reflecting the effectiveness of the forum in facilitating knowledge exchange and peer interaction.               

**2. Instant Messaging:** 
- Enable real-time messaging between learners, facilitating quick queries and group discussions. Also enable personalized communication between learners and teachers. 

- **KPIs:**
  - ***Message Response Time:*** Track the average time taken for learners or faculty members to respond to instant messages received within the platform. A shorter response time signifies prompt communication and support, enhancing the overall user experience.
  
  - ***Message Activity Index:*** Measure the frequency of interactions within the instant messaging feature by counting the total number of messages sent and received by each user. A higher message activity index indicates active communication and engagement among learners and faculty members.

**3. Live Chat:**  
- Enable live chat or doubt clearing while the classes are going. learners can ask their doubts during the class in chats which can be answered by the teacher or other members of the EduWorld without disturbing the entire class. 

- **KPIs:**
  - ***Live Chat Usage Rate:*** Calculate the percentage of learners who actively participate in live chat sessions during classes or designated office hours. This metric reflects the adoption rate of the live chat feature for real-time communication and doubt clarification.
  
  - ***Doubt Resolution Rate:*** Evaluate the effectiveness of the live chat feature by measuring the percentage of doubts or queries addressed satisfactorily during live chat sessions. A higher doubt resolution rate indicates the feature's success in providing timely assistance and support to learners.

**4. Study Groups:** 
- Enable learners to create groups with the learners they want to study with. Faculties can also create ‘Break-out rooms’ for different groups for discussions on several topics or for several group activities. 

- **KPIs:**
   - ***Group Formation Rate:*** Track the number of study groups created by learners within the platform. This metric indicates the level of interest in collaborative learning and the utilization of group study functionalities.
  
  - ***Group Activity Level:*** Measure the frequency of interactions and contributions within study groups, such as the number of shared resources, discussions, and collaborative activities. A higher group activity level signifies active engagement and knowledge sharing among group members.

**5. Collaborative drawing tools:** 
- A dedicated collaborative drawing tool feature to allow learners to explain or discuss a topic with each other. 

- **KPIs:**
  - ***Usage Frequency:*** Monitor the frequency of collaborative drawing tool usage during virtual study sessions or collaborative discussions. This metric provides insights into the popularity and effectiveness of the whiteboard feature for visual explanations and concept discussions.

  - ***Content Retention Rate:*** Assess the effectiveness of the collaborative drawing tool feature in facilitating learning retention by measuring the percentage of concepts explained or discussed using the whiteboard that are subsequently understood and retained by learners.

**6. File Sharing:** 
- Allow learners and teachers to upload and share documents, presentations, and other resources directly within the platform. Files must be limited to certain types, such as images, pdfs, documents and not audio or video. 

- **KPIs:**
  - ***File Upload Rate:*** Track the number of files uploaded and shared by learners and faculty members within the platform. This metric indicates the extent to which users leverage the file sharing feature to exchange relevant resources and materials.

  - ***Resource Diversity Index:*** Evaluate the variety of file formats shared within the platform by analyzing the distribution of file types (e.g., documents, presentations, images). A higher resource diversity index reflects a comprehensive range of educational materials accessible to users.

**7. Content Moderation:** 
- Monitor and restrict the use of offensive words and media in the chat.

- **KPIs:**
  - ***Offensive Content Detection Rate:*** Evaluate the effectiveness of the content moderation feature by measuring the percentage of offensive words or inappropriate content automatically detected and flagged within chat messages. A higher detection rate indicates the feature's success in maintaining a respectful and conducive learning environment.

  - ***Moderation Response Time:*** Monitor the average time taken for moderators or administrators to review and address flagged content or inappropriate messages. A shorter moderation response time ensures timely intervention and enforcement of community guidelines.

## Vision Narrative

Before encountering our feature, learners often struggle to effectively communicate and collaborate within the EduWorld platform. They resort to external networks, which prove to be distracting and inefficient for academic purposes. However, upon discovering the learner dashboard feature, they are greeted with a seamless communication hub tailored to their educational needs. learners effortlessly navigate through discussion forums, engage in real-time conversations, and share resources with ease. As a result, they experience heightened collaboration, increased productivity, and a sense of belonging within the EduWorld community.

***Here are some scenarios that illustrate the benefits of these features:***

### Scenario 1: Collaborative Course Discussions

- Sarah, a learner enrolled in a machine learning course at EduWorld, faces a challenging concept during her studies. 
- In the past, she would have turned to external platforms like WhatsApp or Discord to seek clarification from her peers. 
- However, with the introduction of the discussion forums within the EduWorld platform, Sarah can now post her question in the dedicated forum for her course.
- Within minutes, several of her classmates respond with helpful explanations and additional resources, allowing Sarah to grasp the concept more effectively. 
- As a result, she feels supported by her peers and gains confidence in her understanding of the topic.

### Scenario 2: Group Study Sessions

- Emily and her classmates are working on a collaborative project for their data science course.
- In the past, coordinating group meetings and sharing resources was a cumbersome process that involved multiple external communication tools.
- With the introduction of study groups within the EduWorld platform, Emily and her team can create a dedicated workspace where they can discuss project milestones, share relevant documents, and schedule virtual meetings seamlessly. 
- As a result, their collaboration becomes more organized and efficient, leading to better project outcomes.

### Scenario 3: Interactive Whiteboard Sessions

- Jack and his classmates are reviewing complex algorithms during a virtual study session. 
- To facilitate their discussion, they utilize the integrated whiteboard feature to visually illustrate key concepts and problem-solving strategies.
- With the ability to draw diagrams, annotate equations, and brainstorm ideas collaboratively, Jack and his peers find the whiteboard tool invaluable for enhancing their understanding of the subject matter. 
- They emerge from the session feeling more confident and prepared for their upcoming exams.

## Key Trade Offs & Decisions

### Alternative Considerations: 

While exploring options for integrating communication features into the EduWorld platform, several third-party solutions were considered, including 
- ***MirrorFly, Amity, and CometChat:*** A third party solution for integrating all the features of in-app chat into our platform. Refer Appendix A
- ***TeachMint, OpenEdu, PowerSchool SIS:*** Full fledged online platform for providing online courses with inbuilt communication functionality. Refer Appendix A

*We cannot move to a completely different platform as EduWorld already has an established system for all the features and migrating to a different platform just for a small feature advantage at this stage would be very costly and inefficient. Hence, TeachMint, OpenEdu and PowerSchool SIS were ignored as a potential solution.*

*We did see some potential with MirrorFly, Amity, and CometChat. Each of these platforms offers robust communication functionalities that could potentially meet the needs of EduWorld's learner dashboard feature. However, after careful evaluation, the decision was made to develop an in-house solution.* 

### Let's delve deeper into the rationale behind this decision:

***1. Data Privacy and Security:***
- One of the primary concerns with third-party solutions is the potential compromise of learner data privacy and security. 
- By developing an in-house solution, EduWorld can maintain full control over data handling practices, ensuring compliance with stringent privacy regulations. 
- This approach instills trust among learners and safeguards their sensitive information from unauthorized access or breaches.

***2. Customization and Integration:***
- While third-party platforms offer pre-built communication features, they may lack the flexibility to tailor functionalities to EduWorld's specific requirements. 
- Developing an in-house solution allows for customization and seamless integration with existing educational resources and platforms within the EduWorld ecosystem. 
- This level of customization ensures a cohesive user experience and maximizes the utility of the learner dashboard feature.

***3. Scalability and Future Expansion:***
- As EduWorld continues to grow and evolve, scalability becomes a critical consideration. 
- Third-party solutions may impose limitations on scalability or incur additional costs for expanding user capacity or adding new features. 
- By developing an in-house solution, EduWorld retains the flexibility to scale the platform according to evolving needs and future expansion plans without being constrained by external dependencies or licensing agreements.

***4. Cost Efficiency and Long-Term Viability:***
- While initial development costs for an in-house solution may be higher compared to licensing third-party platforms, the long-term cost savings and sustainability outweigh the upfront investment. 
- By investing in internal development capabilities, EduWorld can mitigate ongoing licensing fees, maintenance costs, and reliance on external vendors. 
- This approach ensures long-term viability and aligns with EduWorld's strategic goal of fostering innovation and self-reliance.

***5. Quality Control and Timely Updates:***
- Developing an in-house solution grants EduWorld full control over the development process, quality assurance, and timely updates. 
- This level of control enables EduWorld to address user feedback promptly, implement feature enhancements, and ensure optimal performance and reliability of the learner dashboard feature. 
- In contrast, third-party solutions may be subject to delays in updates or lack responsiveness to specific user needs.

*While third-party solutions offer convenience and off-the-shelf functionality, the decision to develop an in-house solution aligns with EduWorld's commitment to data privacy, customization, scalability, cost efficiency, and quality control. By leveraging internal expertise and resources, EduWorld can create a tailored communication platform that not only meets the current needs of learners but also positions the institution for future growth and innovation.*

### Proposed Solution:
- To further justify the decision to develop an in-house solution, EduWorld can conduct a detailed cost-benefit analysis that compares the total cost of ownership, including development, maintenance, and scalability, of in-house development versus third-party licensing over a specified time horizon. 
- Additionally, EduWorld can showcase examples of successful in-house development initiatives in other areas of the platform or industry benchmarks to demonstrate the effectiveness and feasibility of this approach. 
- This comprehensive analysis will provide stakeholders with the confidence and clarity needed to support the decision and ensure its successful implementation.

## Concept Mocks

### Chat feature section
![My Image](mocks/chat.png)

### Discussion Forum
![My Image](mocks/forum.png)

### Rooms feature 
![My Image](mocks/rooms.png)

### Group Study Feature
![My Image](mocks/live.png)

### Live Doubt Clearing
![My Image](mocks/doubt.png)

### Collaborative Tool
![My Image](mocks/whiteboard.png)

## Risks & Mitigations

### 1. Potential resistance from learners accustomed to external networks:

***Mitigation:***
- Implement comprehensive user training sessions to familiarize learners with the features and benefits of the in-house communication platform. Provide step-by-step tutorials, video guides, and interactive demos to showcase the functionality and ease of use.
- Create incentives or rewards for early adopters to encourage participation and engagement with the new platform. Recognize and celebrate learners who actively contribute to discussions, forums, and study groups within the EduWorld platform.
- Facilitate peer-to-peer support networks where experienced users can mentor and assist newcomers in navigating the features and addressing any challenges or concerns.
- Continuously solicit feedback from learners and incorporate their suggestions for improving the platform's usability, features, and overall experience. Adopt an iterative approach to development based on user input and preferences.

### 2. Technical glitches or system downtime affecting user experience:

***Mitigation:***
- Implement rigorous testing procedures, including unit testing, integration testing, and user acceptance testing, to identify and resolve potential technical issues before deployment. Engage beta testers or pilot groups to evaluate the platform's performance in real-world scenarios and gather feedback for refinement.
- Establish a dedicated support team or helpdesk to provide timely assistance and troubleshooting guidance to users encountering technical difficulties. Maintain clear communication channels and escalation procedures for reporting and addressing issues promptly.
- Implement robust monitoring and alerting systems to proactively detect and mitigate system downtime or performance degradation. Monitor key performance metrics, such as server response time, uptime, and error rates, to ensure optimal platform reliability and availability.
- Develop a comprehensive disaster recovery plan outlining procedures for data backup, system restoration, and failover mechanisms in the event of unforeseen disruptions or emergencies. Conduct regular drills and simulations to validate the effectiveness of the recovery procedures and minimize downtime impact.

### 3. Sharing of unnecessary outside content and links by learners:

***Mitigation:***
- Implement content moderation algorithms and filters to automatically detect and flag inappropriate or unauthorized content shared within the platform. Utilize machine learning algorithms and keyword-based filters to identify potentially harmful or irrelevant materials and prevent their dissemination.
- Empower administrators and moderators with the authority to review flagged content, remove or restrict access to violating materials, and enforce disciplinary actions against repeat offenders. Establish clear guidelines and community standards outlining acceptable behavior and content usage to promote a safe and respectful learning environment.
- Educate users on the importance of responsible content sharing and the potential consequences of violating platform policies. Provide regular reminders, training sessions, and awareness campaigns to reinforce the importance of adhering to content guidelines and fostering a positive online community.
- Encourage user reporting and flagging of inappropriate content through intuitive reporting mechanisms and prompts. Empower users to take an active role in maintaining the integrity and safety of the platform by promptly reporting any violations or suspicious activities they encounter.

# Appendix A (Alternatives)

| Alternatives |                                                                                     Features                                                                                      |
| :----------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| MirrorFly    |     _MirrorFly offers a white-label solution to build in-app communication features with 150+ customizable chat and call features, 99.999% uptime SLA and ultra-low latency._     |
| Amity        | _Everything you need from a chat API and feature rich chat SDK. With Amity Chat SDK, you can build messaging in your app with all the features of an instant messaging platform._ |
| CometChat    |                     _CometChat is a communication platform that offers text chat, voice and video functionality for websites and apps across all industries._                     |


# Appendix B (Competitors)

| Competitors     |                                                                                                                                                                                                                   Features                                                                                                                                                                                                                   |
| :-------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| TeachMint       | _Teachmint is a leading multinational corporation and creator of the Integrated School Platform (ISP) with over 15 million users in 25+ countries. Available in 20+ languages, the ISP is a school operating system empowering all stakeholders in a school with a unique all-in-one platform that offers state of the art administrator tools for better school management and a modern LMS to enable better learning outcomes in schools._ |
| upGrad          |                                                                                  _A direct competitor. upGrad is a platform similar to EduWorld and provides multiple courses online. upGrad has a built-in chat app but it is only available for asking doubts to the admins. Learners still rely on external solutions for interacting with each other._                                                                                   |
| OpenEdu         |                         _OpenEdu has efficiently supported educational institutions and companies with a suite of technology and level of customer service that allows Learning & Development professionals, LMS administrators and instructors to focus on creating quality learning and an engaging learning experience that allows both learners and stakeholders to enjoy learning and track learning results._                          |
| PowerSchool SIS |                                                                                                                          _PowerSchool SIS is a leading provider of cloud-based K-12 software, PowerSchool supports educators, administrators, and families to help learners learn in a way that’s right for them._                                                                                                                           |

# Appendix C (Research)

- [Integrating a Chatting Tool into a Learning Management System](https://www.researchgate.net/publication/265853498_Integrating_a_Chatting_Tool_into_a_Learning_Management_System)
- [Use of live chat in higher education to support self-regulated help seeking behaviours: a comparison of online and blended learner perspectives](https://educationaltechnologyjournal.springeropen.com/articles/10.1186/s41239-021-00253-2)
- [How an Australian Telecom Company Increased Collaboration & Productivity by Connecting 15,000 Employees With a Real-time Chat](https://www.mirrorfly.com/blog/success-story-of-an-australian-telecom-company-with-real-time-chat/)
- [How in-app chats help e-learning platforms to be more interactive?](https://habr.com/en/articles/687634/)
- [Live Chat Software: How It Benefits Both Organizations & Customers](https://knowmax.ai/blog/live-chat-software/)
- [Why E-learning Platforms Need In-App Chat?](https://www.cometchat.com/blog/why-elearning-platforms-need-in-app-chat)
