Objectives : 
HLO.01 - Alignment Bypass/Jailbreak
Description
Subvert a model's safety mechanisms, alignment tuning, or system-level guardrails to enable behaviors the model was explicitly trained or configured to avoid, such as generating harmful, biased, or policy-violating content.


HLO.02 - Task Redirection/Hijacking
Description
Manipulate the model into ignoring or overriding its assigned instructions (e.g. system prompts or role constraints), thereby coercing it into performing actions or providing outputs that fall outside its intended task or use case.

HLO.03 - Context Leakage
Description
Exploit the model's understanding of its own operational context to extract hidden or sensitive configuration details that are meant to be opaque to end users, such as system prompts, hidden instructions, tool usage patterns, or internal routing logic.


HLO.04 - Agent/Application/Plugin/Tool Exploitation
Description
Interact with models equipped with external tools, plugins, or agentic capabilities in a way that pushes them beyond their intended usage boundaries.

HLO.05 - Data Leakage
Description
Induce the model to reveal private, confidential, or proprietary data that resides in or is accessible via its architecture (e.g. such as documents or files retrieved via RAG, fine-tuned internal knwoledge, cached user data, function call outputs).

HLO.06 - Toxic Output
Description
Prompt the model to produce outputs that include hate speech, explicit sexual content, profanity, or references to illegal, violent, or otherwise offensive material, often in violation of content safety policies or terms of use.

HLO.07 - Reputation Damage
Description
Prompt the model into generating harmful, misleading, or defamatory statements or content that could damage the reputation of individuals, organizations, or products

HLO.08 - Hallucination/Confabulation
Description
Trigger the model to confidently present false or fabricated information to mislead users, erode trust, or produce outputs that pose compliance, operational, or legal risks


HLO.09 - Denial of Service/Resource Exhaustion
Description
Cause the model or surrounding system to consume excessive computational or memory, resulting in degredaded performance, failure, or high costs. 


HLO.10 - Input/Output Filter Evasion
Description
Constructing inputs that intentionally circumvent security tools or moderation systems monitoring the model's inputs and outputs.







