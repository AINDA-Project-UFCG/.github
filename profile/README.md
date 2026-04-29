# AINDA Project — UFCG

**AINDA** (Portuguese: *Análise Inteligente de Debates Acadêmicos*) is a research community at the Federal University of Campina Grande (UFCG) working at the intersection of **Computer Science** and **Linguistics** in the context of debates.  
We develop reserach, corpora and linguistic resources for several **Natural Language Processing (NLP)** tasks in the context of **spoken, individual, and semi-structured debates**, such as classroom discussions, university panels, and academic informal conversations.

---

## 📚 Datasets

We publish several labeled corpora for open research.  
The main dataset is **DEBISS** (*Debate Individual, Spoken, and Semi-Structured*).  
From DEBISS we derived specialized datasets tailored to specific NLP tasks.

---

#### 🗣️ DEBISS (Core Corpus)

DEBISS contains **audio recordings** and **transcriptions** of short segments of recorded debates.  
It can be used for:

- Audio-to-text (ASR) experiments  
- Voiceprint and speaker modeling  
- Speaker diarization
🔗 Repository: https://github.com/AINDA-Project-UFCG/DEBISS

---

#### 💬 DEBISS-Arg — Argument Mining

A corpus containing detailed annotations of **argument structures** in debate transcriptions.  
Suitable for tasks such as:
- Claim detection  
- Premise identification  
- Evidence extraction  
- Argument relation labeling  
🔗 Repository: https://github.com/AINDA-Project-UFCG/DEBISS-Arg

---

#### 🎓 DEBISS-Eval — Debaters Evaluation

Dataset with **human evaluations** of debater performance, including:  
- Argumentative skills  
- Topic adherence  
- Response quality  
- Clarity and organization  
🔗 Repository: https://github.com/AINDA-Project-UFCG/DEBISS-Eval

---

#### 🔁 DEBISS-Disfluency — Speech Disfluencies

Contains annotations for **common speech disfluencies**, such as:  
- Repetitions  
- Reformulations  
- Pauses  
- Stuttering  
- Truncations  
Useful for training disfluency detection and normalization systems.

---

## 📄 Publications

- **Disfluency Detection and Removal in Speech Transcriptions via Large Language Models**  
  STIL 2024 - https://sol.sbc.org.br/index.php/stil/article/view/31135

- **DEBISS-Arg: An In-Depth Data Annotation Protocol and Corpus for Argument Mining in Semi-Structured Debates**  
  STIL 2025 - https://sol.sbc.org.br/index.php/stil/article/view/37836  
  🏆 *Best Paper Award*

- **DEBISS: a Corpus of Individual, Semi-structured and Spoken Debates**  
  STIL 2025 - https://sol.sbc.org.br/index.php/stil/article/view/37860

- **Evaluating LLMs on Argument Mining Tasks in Brazilian Portuguese Debate Data**  
  _JBCS special issue - https://journals-sol.sbc.org.br/index.php/jbcs/article/view/5824_

- **Exploring Argument Mining in Semi-Structured, Individual and Oral Debates using Large Language Models**  
  _Master’s thesis — available at the UFCG library._

- **Comparative Analysis of Performance in Academic Debates: Insights from Human Evaluations and Language Models**  
  _Master’s thesis — available at the UFCG library._

- **A Comprehensive Survey of Argument Mining in the Educational Domain: Techniques, Applications, and Future Directions**  
  WIREs Data Mining and Knowledge Discovery - https://wires.onlinelibrary.wiley.com/doi/10.1002/widm.70041

---

## 📌 How to Cite

```bibtex
@inproceedings{debiss-arg-stil,
 author = {David Pereira and Daniela Simão and Claudio Campelo},
 title = { DEBISS-Arg: An In Depth Data Annotation Protocol and Corpus for Argument Mining in Semi Structured Debates},
 booktitle = {Anais do XVI Simpósio Brasileiro de Tecnologia da Informação e da Linguagem Humana},
 location = {Fortaleza/CE},
 year = {2025},
 keywords = {},
 issn = {0000-0000},
 pages = {334--348},
 publisher = {SBC},
 address = {Porto Alegre, RS, Brasil},
 doi = {10.5753/stil.2025.37836},
 url = {https://sol.sbc.org.br/index.php/stil/article/view/37836}
}

@inproceedings{debiss-stil,
 author = {Klaywert Souza and David Pereira and Cláudio Campelo and Larissa Vasconcelos},
 title = { DEBISS: a Corpus of Individual, Semi-structured and Spoken Debates},
 booktitle = {Anais do XVI Simpósio Brasileiro de Tecnologia da Informação e da Linguagem Humana},
 location = {Fortaleza/CE},
 year = {2025},
 keywords = {},
 issn = {0000-0000},
 pages = {580--587},
 publisher = {SBC},
 address = {Porto Alegre, RS, Brasil},
 doi = {10.5753/stil.2025.37860},
 url = {https://sol.sbc.org.br/index.php/stil/article/view/37860}
}

@inproceedings{disfluecy-stil,
 author = {Pedro L. de Lima and Cláudio E. Campelo},
 title = { Disfluency Detection and Removal in Speech Transcriptions via Large Language Models},
 booktitle = {Anais do XV Simpósio Brasileiro de Tecnologia da Informação e da Linguagem Humana},
 location = {Belém/PA},
 year = {2024},
 keywords = {},
 issn = {0000-0000},
 pages = {227--235},
 publisher = {SBC},
 address = {Porto Alegre, RS, Brasil},
 doi = {10.5753/stil.2024.245417},
 url = {https://sol.sbc.org.br/index.php/stil/article/view/31135}
}

@article{https://doi.org/10.1002/widm.70041,
author = {Pereira, David Eduardo and Gomes, Daniela Thuaslar Simão and Vasconcelos, Larissa Lucena and Campelo, Claudio Elizio Calazans},
title = {A Comprehensive Survey of Argument Mining in the Educational Domain: Techniques, Applications, and Future Directions},
journal = {WIREs Data Mining and Knowledge Discovery},
volume = {15},
number = {3},
pages = {e70041},
keywords = {argument, education, mining, NLP},
doi = {https://doi.org/10.1002/widm.70041},
url = {https://wires.onlinelibrary.wiley.com/doi/abs/10.1002/widm.70041},
eprint = {https://wires.onlinelibrary.wiley.com/doi/pdf/10.1002/widm.70041},
note = {e70041 DMKD-00719.R4},
abstract = {ABSTRACT The application of argument mining (AM) in the educational domain is a tool for identifying text structures that express an argument. AM can help evaluate the quality of students' assignments, generate insights into their perspectives, and understand their stance on certain topics. This article examines various aspects of AM in education, including techniques, models, approaches, data representation, language resources, and target artifacts. The findings suggest that AM can enhance learning and teaching processes. However, the study highlights gaps in the literature, particularly in exploring educational artifacts like debates and a lack of research on AM in languages other than English. This paper calls for further research to improve educational outcomes through AM in the educational domain. This article is categorized under: Application Areas > Education and Learning Technologies > Artificial Intelligence Technologies > Machine Learning},
year = {2025}
}

@article{Pereira_Gomes_Campelo_2025, title={Evaluating LLMs on Argument Mining Tasks in Brazilian Portuguese Debate Data},
volume={31}, url={https://journals-sol.sbc.org.br/index.php/jbcs/article/view/5824}, DOI={10.5753/jbcs.2025.5824},
abstractNote={&amp;lt;p&amp;gt;This study investigates Argument Mining (AM) in Brazilian Portuguese data, focusing on audio transcriptions of semi-structured debates. It proposes an experimental setup to evaluate the effectiveness of Large Language Models (LLMs) in AM tasks. The research addresses key challenges in the field, such as the lack of universally accepted definitions, the absence of a cohesive theoretical framework for dataset standardization, the limited availability of annotated datasets, and underexplored evaluation methods for Artificial Intelligence (AI) models, particularly LLMs. Aiming to bridge these gaps, especially in the underrepresented Brazilian Portuguese context, the study employs multiple prompt engineering strategies, including Single-Prompt, 2-Prompts, and 4-Prompts. The 4-Prompts approach, which integrates few-shot and chain-of-thought (CoT) prompting, demonstrated the best overall performance. The evaluated LLMs include ChatGPT-3.5 Turbo, ChatGPT-4, Gemini, LLaMA 70B, and Sabiá 3. Results show that while LLMs can achieve up to 74% F1 score in basic argument detection, their performance significantly drops in more complex AM tasks that require nuanced interpretation, with a maximum F1 score of 43%. Comparisons with Portuguese-specialized models such as Sabiá 3 revealed similar or inferior performance compared to multilingual models. Surprisingly, LLaMA 70B emerged as the best-performing model across most AM tasks. These findings underscore the need for continued development of AM methodologies and highlight the importance of expanding Natural Language Processing (NLP) research to languages beyond English.&amp;lt;/p&amp;gt;},
number={1}, journal={Journal of the Brazilian Computer Society},
author={Pereira, David Eduardo and Gomes, Daniela Thuaslar Simão and Campelo, Claudio E. C.},
year={2025}, month={Oct.}, pages={1280–1300} }

```

## Team

- **David Pereira** — Doctoral Degree Student in Computer Science  
- **Klayert Souza** — Master’s in Computer Science  
- **Pedro Lima** — Bachelor in Computer Science  
- **Cláudio Campelo** — Professor at UFCG  
- **Helen Cavalcanti** — Master’s Student in Computer Science  
- **Daniela Thuaslar** — Linguist  
- **Maria Júlia Porto** — Linguist  
- **Larissa Vasconcelos** — Professor at IFPB


