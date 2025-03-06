# DHNB_2025_Tartu
Notes on DHNB 2025 Tartu 

https://dhnb.eu/conferences/dhnb2025/

## Opening Keynote

https://computationalstylistics.github.io/presentations/dhnb2025/#/text-analysis

Optimism on digital humanities, computing

Drama Corpora Hub: https://dracor.org/

Tools - https://clsinfra.io/resources/d3-2-methods/


### theoretical foundations

From: https://github.com/computationalstylistics/presentations/blob/master/dhnb2025/index.qmd

- "Computation into criticism" (John Burrows)
- "Algorithmic criticism" (Steve Ramsay)
- "Distant reading" (Franco Moretti)
- "Macroanalysis" (Matt Jockers)
- "Riddle of literary quality" (Karina van Dalen-Oskam)

- ## Long Papers

- Further developing the Word Rain text visualisation technique in a digital history project

Maria Skeppstedt1, Magnus Ahltorp2, Gijs Aangenendt1,3, Ylva Söderfeldt3

1: Centre for Digital Humanities and Social Sciences Uppsala, Department of ALM, Uppsala University; 2: Language Council of Sweden, Institute for Language and Folklore; 3: Department of History of Science and Ideas, Uppsala University

- https://www.actdisease.org/ - Word Frequency

- ## Short Papers


## - March 6th

### Long Papers Morning Session 9:00 06/03/2025

* ColaboFlow: A Platform for Visual
and AI-Augmented Workflows in
Digital Humanities
Sasha Rudan
1,3
, Sinisha Rudan
1
, Lazar
Kovacevic
1,2
1: LitTerra Foundation, Serbia; 2:
Inverudio, USA; 3: Oslo University

### **Summary of the DHNB’25 ColaboFlow Presentation**

[ColaboFlow](https://colabo.space/en/home/)

#### **Title:** ColaboFlow: A Platform for Visual and AI-Augmented Workflows in Digital Humanities

#### **Key Points and Insights**

1. **Challenges in Digital Humanities (DH) Research**
   - Handling large, diverse corpora (e.g., *www.litterra.net*).
   - Running multiple semi-identical experiments.
   - Ensuring experiment reproducibility for verification and benchmarking.
   - Managing dataset sharing, reusability, and open-science readiness.
   - Handling input dataset errors, task failures, and experiment modifications.
   - Addressing tool interoperability and dataset representation differences.
   - Conducting hypothesis checking and determining experiment significance.

2. **Bukvik: An Infrastructure for DH Experiments**
   - Provides a structured pipeline for organizing DH tasks and datasets.
   - Supports **sub-experiments**, facilitating bulk processing of large datasets.
   - Includes **namespacing, versioning, and live transformation** of datasets.
   - Enables **multi-view visualization** using diagrams, comparative graphs, and other analytical tools.
   - Enhances **tool abstraction and unification**, reducing inconsistencies in complex DH workflows.

3. **Key Features of Bukvik**
   - **Preprocessing tools:** OCR, proofreading, Unicode correction, paragraph alignment.
   - **Linguistic analysis tools:** POS tagging, WordNet integration, sentiment analysis.
   - **Network analysis tools:** Etymology tracking, text comparison, parallel corpus analysis.
   - **Mathematical & statistical tools:** Relative entropy (information theory), Society of Words.

4. **Integration with LitTerraAI**
   - Investigates **Natural User Interfaces (NUI)** in DH platforms.
   - Explores **AI-augmented workflows** for distant reading and research automation.
   - Balances trade-offs between:
     - **Power vs. privacy**
     - **Richness vs. AI hallucinations**
     - **Creativity vs. accuracy**

5. **Workflow Solidification Process**
   - **Phase 1: Defining and Structuring the Workflow**
     1. **Ideation:** Defines workflow scope, description, and keywords.
     2. **Taskation:** Lists required tasks and datasets.
     3. **Health Check:** Ensures workflow consistency (similar to static code analysis).
     4. **Tooling:** Matches tools/services to workflow tasks.
     5. **Schemation:** Semantically annotates datasets and tasks.

   - **Phase 2: Refining and Testing the Workflow**
     1. **Patching:** Resolves mismatches between expected and actual dataset schemas.
     2. **Plumbing:** Fills workflow gaps by adding missing tools (external or AI-generated).
     3. **Parametrization:** Configures workflow elements for execution.
     4. **Testing:** Ensures all tasks and datasets function without errors.
     5. **Execution:** Runs the finalized workflow, producing reliable results.

6. **Future Work and Considerations**
   - Exploring the *“Simplify” Nightmare*—the challenge of reducing complexity while maintaining depth.
   - Incorporating a **human-in-the-loop approach** to balance AI automation with researcher control.
   - Enhancing collaboration through **collaborative solidification** of workflows.
  
#### TEI in ColaboFlow

The official and authoritative source for the **Text Encoding Initiative (TEI)** is:

🔗 [**TEI Official Website**](https://tei-c.org/)

The presentation briefly mentions **TEI (Text Encoding Initiative)** in the context of **interoperability** between different tools and dataset representations. It highlights the challenge that different DH tools often require different dataset formats and representations, and TEI is mentioned as part of the broader discussion on standardizing textual data for better compatibility across research workflows.

The key points related to TEI in this presentation:
- **Interoperability Issue**: Different DH tools have varying requirements for dataset representation, which complicates research workflows.
- **Standardization Need**: TEI is referenced as an example of an initiative that aims to create standardized text representations, which could help mitigate these issues.
- **Scientific Discussion**: The discussion around datasets, methodologies, experiments, and tools includes the role of TEI in facilitating structured data sharing and analysis.

TEI is not the central focus but is mentioned as part of the broader challenge of ensuring **data consistency and interoperability** in Digital Humanities research.

### **Final Insights**
The **ColaboFlow** platform aims to streamline **AI-augmented research workflows** in Digital Humanities, ensuring reproducibility, interoperability, and efficiency. It integrates structured **workflow management**, advanced **data visualization**, and **AI-powered augmentation** to tackle the complexities of DH research. The project underscores the importance of **balancing automation with human oversight**, ensuring **scientific rigor and transparency** in digital humanities experiments.

### Multimodal pre-training > Uni-modal

[Center for Humanities Computing](https://chc.au.dk/)

Multimodal pre-training of vision
models yields better embeddings
for visual art
Louise Brix Pilegaard Hansen
1
, Jan
Kostkan
1
, Roberta Rocca
2
, Kristoffer
Nielbo
1
1: Center for Humanities Computing,
Aarhus University, Denmark; 2: Interacting Minds Centre, Aarhus University, Denmark

Used WIkiArt 81,144

Labels

COnvNext
Eva-02
BeIt

Some Distillation, some Vision, Some Vision+Language, differnet immage sizes

EVA-02-CLIP
EVA-02 indirect also performs best

Multi-models confused by cATEGORY OVERLAP, which is fine.

### Large-Language-Model Tools and the Theory of Lexical Priming: convergence and divergence of concepts of language

Michael Thomas Leonce Pace-Sigge
University of Eastern Finland, Finland

#### What is Lexical Priming

Talking about 'hospital' you expect nurse or doctor

Ross M. Quillian in 1960s so vs Chomsky innate approach


Flooding some audience with some lie (like some Politicians do these days) primes us to accept related lies and this lie.

#### linkage between LLM and LPT

Story Grammar - Norvig 1992 !

#### BNC corpus

[BNC corpus](http://corpora.lancs.ac.uk/bnc2014/)

BNC-2014 link btweeen potentate
vs generated sample sentences with potentate by BARD and GPT  

#### usage of TRAIN in BNC-2014 and in Chat-GPT and BARD

Usage of train differs in BNC-2014 and in LLM usage

#### Chat-GPT and structures

Architects - lots of metaphors, no Accountant metaphors, Actor, Carpenter

#### Emergent Grammar

Paul Hopper 1998

#### Key Points
Hoey-s Lexical Priming Theory ther is connections

Firth's dictum "You shall know a word by its neighbor"

LLMS seem too rigitd

#### Evolution of priming

Priming is never fixed - we adjust during our lifetimes.
We create a joke by breaking priming..

### **Theory of Lexical Priming**

**Lexical Priming** is a theory in linguistics and psycholinguistics that explains how words and phrases are naturally associated with certain contexts through repeated exposure. The theory suggests that every time we encounter a word, it leaves a "trace" in our mental lexicon, influencing future language use.

#### **Who Started It?**
The theory of **Lexical Priming** was developed by **Michael Hoey**, a British linguist, and introduced in his 2005 book *Lexical Priming: A New Theory of Words and Language*.

#### **Main Tenets of Lexical Priming**
Lexical Priming proposes that our knowledge of words is shaped by repeated encounters in specific contexts, rather than by abstract rules or innate structures. The key ideas of the theory are:

1. **Words are Primed by Context**  
   - Every time we read, hear, or use a word, it is "primed" to appear in certain environments.
   - This priming affects **collocation** (which words tend to co-occur), **grammatical structures**, and **semantic associations**.

2. **Collocational Priming**  
   - Words have tendencies to appear with specific other words (e.g., "utterly" is more likely to precede "ridiculous" than "happy").
   - These tendencies are developed through repeated exposure.

3. **Grammatical Priming**  
   - Words are primed for specific grammatical structures (e.g., "suggest" is often followed by a that-clause, while "recommend" is frequently followed by a noun phrase or -ing form).

4. **Semantic Priming**  
   - Words are associated with particular meanings due to how they are encountered in real-world discourse.
   - For example, "hospital" is often primed to be associated with "doctor," "nurse," and "patient."

5. **Discourse Priming**  
   - Words and phrases are primed for specific functions within discourse.
   - For example, in news articles, "the incident" often refers back to a previously mentioned event.

6. **Priming is Dynamic and Individualized**  
   - No two speakers have identical priming because everyone has different language experiences.
   - Our lexical priming changes over time as we are exposed to new linguistic environments.

### **Implications of Lexical Priming**
- It challenges traditional views of language as a rule-based system, emphasizing **usage-based learning**.
- It explains why learners and native speakers may use language differently (due to different priming histories).
- It has applications in **language teaching**, **corpus linguistics**, **translation studies**, and **natural language processing**.
- 
### 10:30am - 11:00am Multimodal LLM-assisted Information Extraction from Historical Documents: The Case of Swedish Patent Cards (1945-1975) and ChatGPT

Yunting Xie
1
, Matti La Mela
2
, Fredrik
Tell1
1: Department of Business Studies,
Uppsala University; 2: Department of ALM,
Uppsala University

#### Challenges for Digitalize
120000 digitalized cards
275000 more to digitalize


Mix of cards

#### MLLM for extract info from patent cards

#### Challenges

*Digitized but not transcribed
*Meta Data, agent, patentees,inventors location

#### Solutions

* Manual transcription 15 assistants part time 110,000 patents from 1885-1945

#### Errror flags and confidence

* no accurate confidence numbers
* Can add additional flags for classification

#### Results of transcription

* Very High Accuranty for sytandard fields, application date, residence data
* Under 50% for fee date which is uses strange stamnp
* Some lazy generatee Cards

about 0.85 USD for 100 cards

#### Further WOrk

* Currently Light Work
* open-access models
* fine-tuning
* prompt-engineering

SINGLE PROMPT for all 4 cards.

yunting.xie@fek.uu.se
Swedish Historical Patents - https://svenskahistoriskapetent.se


  







