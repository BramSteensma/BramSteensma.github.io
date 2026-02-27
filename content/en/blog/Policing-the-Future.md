---
title: "Policing the Future: When Algorithms Carry a Badge and Bias"
date: 2026-02-27
draft: false
description: "Explore the ethical downfall of predictive policing as we examine why cities like Los Angeles are abandoning these controversial AI systems. This post delves into the critical concepts of algorithmic fairness, explainability, and governance, revealing how data-driven law enforcement often automates bias and erodes public trust, ultimately failing its most important ethical tests."
featured_image: "/images/predictivepolicing.png"
tags: ["Ethics", "Artificial Intelligence"]
---


Artificial intelligence in law enforcement was sold with a powerful promise: the ability to stop crime before it happens. This proactive approach, shifting from reaction to prediction, presented an alluring vision of safer streets and optimized police resources. For years, tech companies championed predictive policing systems as the key to smarter, data-driven public safety.

However, as cities across the globe have discovered, the line between science fiction and reality is fraught with ethical peril. The deployment of these algorithms has become a crucial case study in the challenges of AI ethics. When we examine these systems through the lens of ethical AI frameworks, particularly the concepts outlined by Luciano Floridi, we see a fundamental conflict between computational logic and human justice. The real-world retreat from these technologies, most notably in cities like Los Angeles, signals a critical re-evaluation of what it means to police fairly in the digital age.


## A Real-World Case Study: The LAPD and PredPol
Predictive policing systems primarily fall into two categories: place-based models and person-based models. Place-based models, like the one developed by PredPol (now Geolitica), use historical crime data—type, location, and time—to forecast where and when future crimes are most likely to occur, generating "hotspot" maps to direct patrols. Person-based systems, such as the LAPD’s "chronic offender" program, attempt to predict which individuals are at the highest risk of being involved in future violent crime—either as perpetrators or victims—often by analyzing past arrest records, known associations, and other personal risk factors.

The Los Angeles Police Department (LAPD) was an early and prominent adopter of this technology. However, after years of use, the city decided to end its contracts. In 2019, the LAPD stopped using PredPol’s hotspot software, and in 2020, it discontinued its own in-house "chronic offender" program. The reason for this reversal wasn't a failure of technology, but a failure of ethics. An audit by the city’s inspector general found it impossible to determine whether these programs actually helped reduce crime, and civil rights groups raised significant concerns about their discriminatory impact.
This high-profile withdrawal highlights the core ethical weaknesses that plague predictive policing systems nationwide.


## The Algorithm's Original Sin: Fairness and Biased Data
The most significant ethical failing of predictive policing is its inability to achieve fairness. In the context of AI, fairness means that a system does not produce discriminatory outcomes or reinforce existing inequalities. The problem for predictive policing algorithms is the data they are trained on.

These systems are fed historical crime data from police departments. This data is not a pure, objective record of all criminal activity. Instead, it is a record of reported crimes and enforced laws. For decades, policing in many American cities has disproportionately targeted low-income and minority communities. This results in more arrests for minor offenses, like loitering or drug possession, in these areas compared to more affluent, predominantly white neighborhoods where the same activities may occur but go unpoliced.
When this skewed data is fed into an algorithm, it creates a dangerous feedback loop:
- The AI analyzes historical arrest data and flags a minority neighborhood as a "hotspot."
- Police commanders dispatch more officers to patrol that specific area.
- The increased police presence naturally leads to more citations and arrests for minor offenses.
- This new arrest data is then fed back into the system, further solidifying the neighborhood’s status as a high-crime zone.

The algorithm isn't predicting crime; it's predicting policing. It provides a veneer of mathematical objectivity to historical human bias, effectively automating and amplifying discrimination. This is precisely what critics in Los Angeles argued—that the software was sending officers back to the same communities over and over, leading to over-policing and eroding public trust.


## The Black Box Dilemma and the Need for Explainability
A core tenet of ethical AI is explainability, or the ability for humans to understand how an AI system arrived at its decision. If a community is subjected to heightened surveillance because an algorithm flagged their street corner, its residents deserve to know why.

Many predictive policing algorithms are proprietary "black boxes." The companies that create them protect their code as a trade secret, making it impossible for outside auditors, civil rights organizations, or even the police departments themselves to fully vet the system. We don't know what variables the model is weighing or whether it's using proxies for protected characteristics like race or socioeconomic status. For example, could a variable like "proximity to a check-cashing store" act as a proxy for a low-income neighborhood? Without transparency, we can't know.

This lack of explainability makes it nearly impossible to challenge the system’s output, creating an environment where accountability is diffused and justice becomes opaque.


## Who’s to Blame? The Crisis of Algorithmic Accountability
As philosopher Luciano Floridi points out, AI systems possess a form of intelligence without moral agency. They can identify complex patterns but cannot comprehend the real-world consequences of their recommendations. This creates a vacuum of algorithmic accountability.

When a predictive model repeatedly directs patrols to a community, leading to the harassment of innocent residents, who is responsible?
- Is it the police officer following the computer’s recommendation?
- Is it the police chief who signed the contract for the software?
- Is it the data scientists who developed the algorithm?
- Is it the software company that sold the product?

Our legal system is built around human intent, but an algorithm has no intent. It simply optimizes for a given metric, like identifying areas with the highest probability of recorded crime. This diffusion of responsibility makes it incredibly difficult for affected individuals to seek recourse. A truly ethical AI framework insists that a human must always remain in the loop and bear ultimate responsibility for the system's impact.


## Moving Beyond the Law: The Role of Soft Ethics
The conversation around predictive policing often gets stuck on what is legal. It is legal to use public arrest data to train an algorithm. But this is where soft ethics becomes essential. Soft ethics moves beyond legal compliance to ask what we should do. It is the domain of moral and social responsibility.

Soft ethics compels us to question the fundamental premise of the technology. Even if an algorithm could be perfected to be unbiased, is it right to place entire communities under a cloud of digital suspicion? Does the potential efficiency gain justify the erosion of trust between police and the people they serve?

This is the conversation that unfolded in places like Santa Cruz, California—the birthplace of PredPol—which banned predictive policing in 2020. Community leaders decided that the social cost of algorithmic surveillance outweighed any purported benefits. Soft ethics encourages us to consider alternative solutions. Instead of sending more patrol cars to a "hotspot," perhaps the data should prompt investment in community resources, like job training programs, mental health services, or better street lighting.


## The Path Forward: AI Governance as a Public Trust
To prevent these ethical failures, we need robust AI governance. This means establishing clear policies, oversight bodies, and accountability structures to manage the entire lifecycle of an AI system, from procurement to deployment and retirement.

For technologies like predictive policing, effective governance would include:
- Mandatory Bias Audits: Independent, third-party audits to test for discriminatory outcomes before a system is purchased.
- Public Transparency: Community impact assessments and public comment periods before any surveillance technology is deployed.
- Clear Termination Criteria: Predetermined conditions under which a system will be decommissioned if it proves ineffective or harmful.
- Human Oversight: Ensuring that algorithmic recommendations are treated as one data point among many, not as an unquestionable command.

Governance is the mechanism by which we embed our societal values into our technological systems. Without it, we risk building an "infosphere," as Floridi calls it, polluted by biased data and unaccountable power.


## Conclusion
The retreat from predictive policing in major cities like Los Angeles is not a rejection of technology itself. It is a recognition that AI is not a neutral tool. It is a socio-technical system that absorbs and reflects the values of the society that creates it. The promise of an efficient, crime-free future is deeply appealing, but it cannot come at the cost of justice and equality.

By applying ethical concepts like fairness, explainability, accountability, and soft ethics, we can see that these systems failed not on a technical level, but on a human one. They automated the past instead of building a better future. As we continue to integrate AI into the core functions of our society, the lessons from the algorithmic beat cop are clear: the ultimate goal cannot be mere efficiency. It must be justice. And justice is a metric that no algorithm can compute on its own.
