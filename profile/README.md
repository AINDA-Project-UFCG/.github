# AINDA Project — UFCG

**AINDA** (*Intelligent Analysis of Academic Debates* / from Portuguese: *Análise INteligente de Debates Acadêmicos*) is a research project carried out at the Federal University of Campina Grande (UFCG), in Brazil. Our focus is on the development of computacional techniques for Debate Analysis. We also produce corpora and linguistic resources for several **Natural Language Processing (NLP)** tasks in the context of **spoken, individual, and semi-structured debates ("ISS DEBATES") **, such as classroom discussions, university panels, and academic informal conversations.

---

## 📚 Datasets

We publish several labeled corpora for open research.  
The main dataset is **DEBISS**, thats stands for ISS DEBates (*Individual, Spoken, and Semi-Structured Debates*).  
From DEBISS we derived specialized datasets tailored to specific NLP tasks.

---

#### 🗣️ DEBISS (Core Corpus)

DEBISS contains **audio recordings** and **transcriptions** of short segments of recorded ISS debates.  
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
@inproceedings{debiss-arg-stil-2025,
 author = {David Pereira and Daniela Simão and Claudio E. C. Campelo},
 title = {DEBISS-Arg: An In Depth Data Annotation Protocol and Corpus for Argument Mining in Semi Structured Debates},
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

@inproceedings{debiss-stil-2025,
 author = {Klaywert Souza and David Pereira and Claudio E. C. Campelo and Larissa Vasconcelos},
 title = { DEBISS: a Corpus of Individual, Semi-structured and Spoken Debates},
 booktitle = {Anais do XVI Simpósio Brasileiro de Tecnologia da Informação e da Linguagem Humana},
 location = {Fortaleza/CE},
 year = {2025},
 issn = {0000-0000},
 pages = {580--587},
 publisher = {SBC},
 address = {Porto Alegre, RS, Brasil},
 doi = {10.5753/stil.2025.37860},
 url = {https://sol.sbc.org.br/index.php/stil/article/view/37860}
}

@inproceedings{disfluecy-stil-2024,
 author = {Pedro L. de Lima and Claudio E. C. Campelo},
 title = {Disfluency Detection and Removal in Speech Transcriptions via Large Language Models},
 booktitle = {Anais do XV Simpósio Brasileiro de Tecnologia da Informação e da Linguagem Humana},
 location = {Belém/PA},
 year = {2024},
 pages = {227--235},
 publisher = {SBC},
 address = {Porto Alegre, RS, Brasil},
 doi = {10.5753/stil.2024.245417},
 url = {https://sol.sbc.org.br/index.php/stil/article/view/31135}
}

@article{survey-wires-2025,
author = {David Eduardo Pereira and Daniela Thuaslar Simão Gomes and Larissa Lucena Vasconcelos and Claudio E. C. Campelo},
title = {A Comprehensive Survey of Argument Mining in the Educational Domain: Techniques, Applications, and Future Directions},
journal = {WIREs Data Mining and Knowledge Discovery},
volume = {15},
number = {3},
pages = {e70041},
doi = {https://doi.org/10.1002/widm.70041},
url = {https://wires.onlinelibrary.wiley.com/doi/abs/10.1002/widm.70041},
eprint = {https://wires.onlinelibrary.wiley.com/doi/pdf/10.1002/widm.70041},
note = {e70041 DMKD-00719.R4},
year = {2025}
}

@article{argmining-pt-jbcs-2025,
title={Evaluating LLMs on Argument Mining Tasks in Brazilian Portuguese Debate Data},
volume={31},
url={https://journals-sol.sbc.org.br/index.php/jbcs/article/view/5824},
DOI={10.5753/jbcs.2025.5824},
author={David Eduardo Pereira and Daniela Thuaslar Simão Gomes and Claudio E. C. Campelo},
year={2025},
month={Oct.},
pages={1280–1300}
}

```

## Team

- **Cláudio Campelo** — Associate Professor at UFCG, PhD in Computing
- **David Pereira** — PhD Student in Computer Science at UFCG
- **Klayert Souza** — MSc in Computer Science from UFCG
- **Pedro Lima** — BSc in Computer Science from UFCG
- **Helen Cavalcanti** — MSc Student in Computer Science at UFCG
- **Daniela Thuaslar** — BSc in Language and Literature from UFCG, MSc student
- **Maria Júlia Porto** — BSc in Language and Literature from UFCG
- **Larissa Vasconcelos** — Assistant Professor at IFPB, PhD in Computer Science from UFCG


