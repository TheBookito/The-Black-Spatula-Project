# The-Black-Spatula-Project

Conceptual Overview:

Core Purpose:
The platform allows a researcher to submit their already published paper (PDF, DOCX, or LaTeX source).
The system extracts all citations and automatically checks each cited paper against a curated and continuously updated database of academic critique records.
known retractions, errata, and public post-publication reviews.

AI-Driven Citation Verification:
Using large language models (LLMs) fine-tuned on scholarly literature, the platform identifies sections where the author’s arguments rely heavily on a particular cited source. 
It then cross-references that source with known issues (e.g., statistical misinterpretation, flawed methodology, retracted conclusions) documented elsewhere.
If mistakes are found, the system evaluates whether these mistakes could affect the citing author’s conclusions.
For example, if the cited work is foundational to a key argument, an acknowledged error in that work might undermine the citing author’s results.
If the error is peripheral—like a minor statistical oversight that doesn’t influence the main findings—the platform will note it but indicate a low level of impact.

Contextual Understanding of Impact:
By performing semantic analysis, the platform understands how the cited source was used in the text—was it used for a background fact, a theoretical foundation,
a methodological precedent, or something else? This contextual use guides the platform’s assessment of the severity of the error’s impact on the citing paper’s claims.

Models used:
o1, o1-pro
Gemini 2.0 FTE
DeepSeek.
Claude 3.5 Sonnet.
