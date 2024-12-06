---
permalink: /Projects/
title: "Projects"
author_profile: true
redirect_from: 
  - /projects/
  - /projects.html
---

## Improving the Design and Evaluation of Explanations in AI Systems
A core assumption of Explainable AI (XAI) is that explanations are useful to users—that is, users will do something with the explanations. But as we design, create, and evaluate explanation methods, we often fail to consider users’ actions. My work addresses this problem in several ways.

First, I’ve worked to clarify the connection between explanations and actions. One big hindrance to considering users’ actions is a lack of consensus about the kinds of information we can present in explanations and the actions that people can take in response. This makes it difficult to understand and measure how technical methods are changing people’s actions. My work breaks that barrier down by creating a user-centered taxonomy of the kinds of information we provide in explanations and the resulting actions. In this way, it supports the measurement and evaluation of AI explanations in terms of actions. It also helped uncover key principles for how to include information to make explanations relevant to users.

<p align="center">
  <img src="/images/Design_References.jpg" />
</p>

Second, I uncovered an under-explored need from AI explanations. I was interviewing doctors about their use of AI explanations while I was validating the taxonomy. They expressed that they are called on to provide oversight of AI medical systems, but they face legal liability for harm that befalls their patients. AI explanations didn’t help understand or mitigate their legal risk, which seriously impacted their ability to rely on them.


Now I’m using the taxonomy to address this need. I used my taxonomy to identify the actions doctors would take if an AI explanation was addressing their legal concern. I’m working backwards to identify the information we should include in AI explanations. While doctors want to mitigate their legal risk, they’re not as good at understanding the law. I’m developing an interview method for use with lawyers to identify this information. I’m using the taxonomy to analyze my conversations with lawyers and identify the factors impacting legal risk and information users need to manage risk. I’ll synthesize my findings into design references that I and others can use to build explanations that can help address users’ legal concerns, creating a clearer path for users to act with AI explanations.

- **Mansi, G.**, Kim, J., Riedl, M. Rethinking Actionability in Explainable AI. (In Prep)
- **Mansi, G.** & Riedl, M. Recognizing Lawyers as AI Creators and Intermediaries in Contestability. Workshop ”From Stem to Stern: Contestability Along AI Value Chains” at the Conference for Computer Supported Collaborative Work 2024 (CSCW ’24)
- **Mansi, G.** & Riedl, M. Why Don’t You Do Something About It? Outlining Connections between AI Explanations
and User Actions. Workshop on Human-Centered Explainable AI at the 2023 Conferences on Computer-Human
Interaction (CHI ’23).


## Concept Catalyst

<p align="center">
  <img src="/images/ConceptCatalyst.jpg" />
</p>

In K-12 engineering classrooms, teachers help students develop critical thinking skills by requiring them to document their design decisions for hands-on projects. To help students practice iterative design practices through their documentation, teachers write scaffolding questions, creating a large cognitive burden that redirects teachers’ energy away from hands on engagement. Generative AI could help address this challenge, but teachers often do not know how to prompt these systems. We present our design of Concept Catalyst as a case study in addressing these needs. Concept Catalyst is a ChatGPT-based tool that helps teachers better scaffold students’ documentation process, so they are empowered to engage students’ thinking while incorporating AI into their pedagogy. We discuss the results from Wizard-of-Oz studies with 10 engineering teachers, and how Concept Catalyst helps teachers reflect on their teaching practices while improving efficacy, efficiency, and motivation in using AI. We end with implications for design around how structuring AI interactions can support more than improved AI interactions.

- **Mansi, G.**, Newton, S., Moore, R., Alemdar, M., Riedl, M. Concept Catalyst: Supporting K-12 Engineering
Design Teachers with Generative AI. (Under Review)

## Experiential Explanations

Reinforcement Learning (RL) systems can be complex and non-interpretable, making it challenging for non-AI experts to understand or intervene in their decisions. This is due in part to the sequential nature of RL in which actions are chosen because of future rewards. However, RL agents discard the qualitative features of their training, making it difficult to recover user-understandable information for “why” an action is chosen. We propose a technique Experiential Explanations to generate counterfactual explanations by training influence
predictors along with the RL policy. Influence predictors are models that learn how sources of reward affect the agent in different states, thus restoring information about how the policy reflects the environment.

I helped coordinate and conduct the qualitative analysis of a human evaluation study that revealed that participants presented with experiential explanations were better able to correctly guess what an agent would do than those presented with other standard types of explanation. Participants also found that experiential explanations are more understandable, satisfying, complete, useful, and accurate. The qualitative analysis was used to also further provide insights into the factors of experiential explanations that are most useful and guide further technical development.

- Alabdukarim, A., Singh, M., **Mansi, G.**, Hall, K., Ehsan, U., and Riedl, M. Experiential Explanations for Reinforcement Learning. Nerual Computing and Applications 2024 (NCAA ’ 24).
- Alabdulkumar, A., **Mansi, G.**, Hall, K., and Riedl, M. Experiential Explanations for Reinforcement Learning. Workshop on Explainable AI at the 2023 International Joint Conferences on Artificial Intelligence (IJCAI ’23).

## Remote  Art Education

<p align="center">
  <img src="/images/Merged-Scissors-Screens.png" />
</p>

Art education plays a central role in early childhood development, and museum outreach programs can significantly enhance art education experiences for K-2 learners in schools. Increased demand for remote learning environments where students and teachers are not co-located has forced educational contexts to adopt technology-mediated learning. However, little research has investigated how technology can integrate museum content into fully remote, K-2 school art education. We elicited design requirements for K-2 art education platforms in a needs assessment study through surveys (N = 22) and interviews (N = 4) with educators. We created a typology of existing platforms, which we evaluated against these requirements. We identified a key unmet need for students to receive feedback on their fine motor skills, and, in response, we created a prototype system with interactive scissors called Chameleon Clippers. We demonstrate its potential to provide this feedback through preliminary user tests with 4–7-year-old children (N=12).

- **Mansi, G.**, Roberts, J. Ready, Set, Art: Technology Needs and Tools for Remote K-2 Art Education 21st
ACM International Conference on Interaction Design and Children (IDC ’22).
- **Mansi, G.**, Boone, A., Kim, S., Roberts, J. Chameleon Clippers: A Tool for Developing Fine Motor Skills in Remote Education Settings. 2022 International Conference on Computer-Supported Collaborative Learning. Best Technical Paper.


