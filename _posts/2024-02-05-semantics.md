---
layout: post
title: "Semantic Technologies: The Center of Attention"
description: 
image: assets/images/lego.png
---

Buildings, in a way, are the most complex "robots" we inteact with.  A typical commercial building contains thousands of sensing and actuation points. The control of these building systems (HVAC, lighting, etc.) is often manually programmed by engineers using heuristics.

Recent research has highlighted the significant potential of data-driven control and analysis for buildings. However, deploying such technology faces barriers, mainly because it demands considerable engineering effort to decipher the meanings of various tags (created without clear documentation or rationale). Moreover, the complexity of these data points necessitates a considerable effort to develop building-specific applications. On top of that, each building is unique and beautiful in its own way. Thus, due to the heterogeneity of buildings, the transferability of these applications from building to building is very limited. This scenario is akin to downloading an app from the app store: despite the variation in physical hardware among cellphones, apps function because they rely on standardized, machine-readable coding (i.e., semantic ontologies) rather than hard-coded tags.

Inspired by the software industry's success, numerous building-specific ontologies have been developed. A recent study reported that there are 70 ontologies related to smart cities. However, Pritoni et al. (2021) found that 28 had expired links, 7 were in foreign languages, and 42 lacked linked documentation. Just like starting this blog page, it is easy to start new ontologies. What is hard is to keep them running and supported by an active community of researchers and industry folks. In this regard, Brick is a widely recognized ontology, supported by a strong community, and it is becoming part of the new standardization efforts, such as ASHRAE 233p.

Brick serves well up to a certain point; it is a general building ontology not tailored for specific application areas. Hence, it inevitably lacks entities for certain niche applications. Looking ahead, I see Brick becoming a focal point, with additional ontologies being integrated with it for specific use cases. This is similar to using plug-ins with a browser: the browser itself is extended to meet user needs, but for more specialized requirements, plug-ins provide necessary integrations. For instance, He et al. (2023) proposed integrating an ontology with Brick for energy storage systems. When feasible, direct extensions to Brick are advisable, as Hwang et al. (2023) did by including fault symptom relationships in HVAC systems within Brick.

Then, the main question is when to extend and when to integrate. That, my friends, is an art. But, I believe the decision should be made considering whether that application is within the goals of the central ontology.

-Pritoni, Marco, Drew Paine, Gabriel Fierro, Cory Mosiman, Michael Poplawski, Avijit Saha, Joel Bender, and Jessica Granderson. “Metadata Schemas and Ontologies for Building Energy Applications: A Critical Review and Use Case Analysis.” Energies 14, no. 7 (January 2021): 2024. https://doi.org/10.3390/en14072024.

-He, Fang, Dan Wang, and Yaojie Sun. “Ontology Integration for Building Systems and Energy Storage Systems.” In Proceedings of the 10th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation, 212–15. Istanbul Turkey: ACM, 2023. https://doi.org/10.1145/3600100.3623720.

-Hwang, Min Young, Burcu Akinci, and Mario Berges. “FSBrick: An Information Model for Representing Fault-Symptom Relationships in HVAC Systems.” In Proceedings of the 10th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation, 69–78. BuildSys ’23. New York, NY, USA: Association for Computing Machinery, 2023. https://doi.org/10.1145/3600100.3623729.

