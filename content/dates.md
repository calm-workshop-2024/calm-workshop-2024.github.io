---
title: "Important Dates"
---

## Important Dates

* **Paper submission deadline: September 23, 2024, AoE**
* **Notification to authors: October 09, 2024, AoE**
* **Camera-ready version: December 7, 2024**
* **Workshop Date: December 14, 2024**



# Panelists

[Elias Bareinboim](https://scholar.google.com/citations?hl=en&user=r5U-D7YAAAAJ)
- causal inference

[Atticus Geiger](https://scholar.google.com/citations?hl=en&user=w2Qzno8AAAAJ)
- mechanistic interpretability

[Chelsea Finn](https://scholar.google.com/citations?hl=en&user=vfPE6hgAAAAJ)
- meta-learning
- robotics

[Maria Antoniak](https://scholar.google.com/citations?hl=en&user=lNaynLcAAAAJ)
- cultural understanding

[Zhijing Jin](https://scholar.google.com/citations?hl=en&user=Mdr6wjUAAAAJ)
- causal NLP for social good

[Giambattista Parascandolo](https://scholar.google.com/citations?hl=en&user=1zCDX_UAAAAJ)
- reasoning
- interpretability


# Questions

1. How would you describe your past work: more "causality focused" or more "large model focused"? What direction would you like to be going? Why?
2. Are LLMs still satisfactory, or do we need a *paradigm shift*? Are we due for one? Where? What will it look like?
3. generalization
   - relationship between interpretability and generalizability
   - Do you need OOD generalization (guarantees) if you train on everything (except the benchmarks of-course)?
4. What is the role of causality: does it emerge (e.g. from data) or do we (have to) build it in (e.g. our learning process)?
5. Strengths and weaknesses of an explicitly causal framing
6. revising the Chinese Room: what does it mean for a model to "understand" something? What does it mean for us to "understand" a model?
   - sufficient and necessary conditions for "understanding" - are they causal?
7. In the context of safety-critical applications, are more causal methods preferrable to the alternative? Are they necessary?
   - embodied AI and robotics
8. which of the 4 directions is most exciting to you? Why?
   - Causality **for** large models
   - Causality **with** large models
   - Causality **of** large models
   - Causality **in** large models
   - are we missing some other type of interaction?
9.  structure vs function: is there a tradeoff between interpretability and performance?
10. The causality killer app: is it a myth? an actionable goal? already achieved and we do/dont know it?
11. steering/alignment: data curation problem
   - open source vs proprietary efforts
   - How long before an open-source LLM gets top of the (chat) leaderboard? Why?
12. overrated vs underrated
   - causality: counterfactual *anything* (methods, data, tasks, frameworks, etc), causal discovery, philosophy of causality, non-statistical formulations (pre-Pearl, non-analytical, logic), graphical modeling (of real systems)
   - large models: multi-modal models, scaling up everything, transformers, sim-to-real, ChatGPT, Claude, Gemini, and other consumer-facing large models, explainable AI (post-hoc interpretability)
13. Do we need more trained causality people or more large model people? What's your advice to students?

## Preview

1. How would you describe your past work: more "causality focused" or more "large model focused"? What direction would you like to be going? Why?
2. How do you feel about the current state of foundation models (transformers, diffusion models, etc.)? Do we need a *paradigm shift*? Are we due for one? What do you think it'll look like?
3. On generalization:
   - What is the relationship between interpretability and generalizability?
   - Do we need OOD generalization (guarantees) if you train on everything?
4. How can/should models use causal knowledge? Should models memorize known causal relationships, should the reasoning process have causal structure, or should the model be able to perform interventions?
5. "Learning by doing:" is interventional data the key to foundation models for physical intelligence?
6. Under what circumstances should we prioritize or even necessitate causal methods?
   - safety-critical applications: medical, autonomous vehicles, etc.
   - physical systems: embodied AI and robotics
   - socially sensitive or controversial applications: justice, social media, etc.
7. What is the role of causality: does it emerge (e.g. from data) or do we (have to) build it in (e.g. our learning process)?
8. Revisiting the Chinese Room: what does it mean for a model to "understand" something? What does it mean for us to "understand" a model?
   - What are the sufficient and necessary conditions for "understanding" - are they causal?
   - What result/behavior would convince you that a model "understands" something?
9.  Which of these directions is most exciting to you? Why?
   - Causality **for** large models - Applying ideas from causality to augment and improve large models.
   - Causality **with** large models - Leveraging large models to improve causal inference and discovery.
   - Causality **of** large models - Investigating the causal structure of how large models work and how to make them more interpretable and controllable.
   - Causality **in** large models - Assessing the causal knowledge captured by large models and their (causal) reasoning abilities.
   - are we missing some other type of interaction?
10. Structure vs function: is there a tradeoff between interpretability and performance?
11. The causality "killer app": is it a myth? an actionable goal? Already achieved and we do/dont know it?
12. Is LLM steering/alignment chiefly a matter of data curation? 
   - How should we think of open source vs proprietary efforts in this regard? Should they specialize in different areas?
   - How long before an open-source model gets to the top of the leaderboard/s? Why?
13. For each of the topics below, do you think it is *overrated* or *underrated* in our community?
   - causality: counterfactual *anything* (methods, data, tasks, frameworks, etc), causal discovery, philosophy of causality, non-statistical formulations (pre-Pearl, non-analytical, logic), graphical modeling (of real systems)
   - large models: multi-modal models, scaling up everything, transformers, sim-to-real, ChatGPT, Claude, Gemini, and other consumer-facing large models, explainable AI (post-hoc interpretability)
14. Do we need more trained causality people or more large model people? What's your advice to students?
    - Will we be sitting here in a year? What will have changed?


---

**Past Work and Future Directions**  
- How would you describe your past work: more *causality focused* or more *large model focused*?  
- What direction would you like to be going, and why?

**State of Foundation Models**  
- How do you feel about the current state of foundation models (transformers, diffusion models, etc.)?  
- Do we need a *paradigm shift*? Are we due for one?  
- What do you think such a shift would look like?

**On Generalization**  
- What is the relationship between interpretability and generalizability?  
- Do we need OOD (Out-of-Distribution) generalization guarantees if we train on “everything”?

**Using Causal Knowledge in Models**  
- How should models utilize causal knowledge?  
- Should they memorize known causal relationships?  
- Should the reasoning process have causal structure?  
- Should models be able to perform interventions?

**"Learning by Doing"**  
- Is interventional data the key to foundation models for physical intelligence?

**Prioritizing Causal Methods**  
- Under what circumstances should causal methods be prioritized or even required?  
- Safety-critical applications (medical, autonomous vehicles, etc.)  
- Physical systems (embodied AI, robotics)  
- Socially sensitive or controversial applications (justice, social media, etc.)

**The Role of Causality**  
- Does causality emerge from data, or must we build it into our learning processes?
- Is there a trade-off between interpretability and performance?
- Is the causality "killer app" a myth, an actionable goal, or something already achieved (whether we realize it or not)?

**Revisiting the Chinese Room**  
- What does it mean for a model to "understand" something?  
- What does it mean for us to "understand" a model?  
- Are the sufficient and necessary conditions for "understanding" something?  
- What results or behaviors would convince you that a model truly "understands" something?

**Directions of Interest** What direction are you most excited about? Why?
- **Causality for Large Models:** Applying causality to augment and improve large models.  
- **Causality with Large Models:** Using large models to improve causal inference and discovery.  
- **Causality of Large Models:** Investigating the causal structure behind how large models work, making them more interpretable and controllable.  
- **Causality in Large Models:** Assessing the causal knowledge and reasoning abilities captured within large models.  
- Are we missing other possible interactions?

**LLM Steering and Alignment**  
- Is alignment chiefly a matter of data curation?  
- How should we think about open-source vs. proprietary efforts in this area?  
- Should they specialize in different areas?  
- How long before an open-source model tops the leaderboards, and why?

**Overrated vs. Underrated**  
- Causality: counterfactual methods/data/tasks, causal discovery, philosophy of causality, non-statistical formulations (pre-Pearl, logic-based), graphical modeling of real systems  
- Large Models: multi-modal models, scaling up everything, transformers, sim-to-real, ChatGPT, Claude, Gemini, and other consumer-facing large models, explainable AI (post-hoc interpretability)

**Community and Education**  
- Do we need more trained causality experts or more large model experts?  
- What advice would you give to students entering the field?  
- Will we be having similar discussions in a year’s time, and what might have changed by then?


## Person-specific questions

**Elias**
- How do we convince people that causality is not just in principle but also in practice important?

**Atticus**
- How should we choose the right level of abstraction to best make sense of how large models work?

**Chelsea**
- Throughout the day we heard several speakers emphasize the importance of interactive learning
- Does a foundation model for physical intelligence require interventional data? Or more causal methods? Is that sufficient?

**Maria**
- How is causal knowledge in particular useful for cultural understanding and analysis?
- Humans learn not just by interacting with the world but also by sharing the causal knowledge they have with others, does this also hold for AI systems?
- What requirements must we satisfy to safely and reliably use large models in safety-critical applications? How can we operationalize these requirements?

**Zhijing**
- How can we translate the theory and philosophy of causality to practical applications in NLP (and beyond)?
- How can we get students excited about causal ML and make it more accessible?

**Giambattista**
- What should we prioritize: structure or function?
- Are our (current/popular) evaluation metrics sufficient? Why or why not?


## Directions

**in**
- Amit: systematically probing the causal knowledge in LLMs and formalizing natural language causal questions
- Victor Veitch: how causal knowledge is structured in the embeddings of large models to learn high-level semantic concepts and relationships

**of**
- Victor Veitch: making sense of the latent structures in the embeddings of large models

**for**
- Jane Wang: utilizing interventional and counterfactual information in video games to build foundation agents
- Elias: using a causal framing to identify and mitigate the systematic weaknesses of large models

**with**
- Amit: systematically probing the causal knowledge in LLMs and formalizing natural language causal questions
- Elias: causal neural connection

