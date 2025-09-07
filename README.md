

### Hybrid Explainable AI for Automated Technical Interview Feedback

**Final Year Research Project**

**Individual Contribution:**
* Developed a novel evaluation model to classify the quality of technical interview answers by engineering a hybrid feature set combining semantic similarity (S-BERT), lexical overlap (Jaccard similarity), and structural metrics.
* Applied model explainability techniques (SHAP) to interpret the predictions of the trained CatBoost classifier, enabling the extraction of salient keywords that positively or negatively influenced an answer’s evaluation.
* Pioneered a multi-stage, LLM-based feedback generation pipeline that uses Groq's Llama3 to transform raw SHAP outputs into educational insights. This included prompting the LLM to reason about logical counterfactuals (replacing incorrect concepts with correct ones), summarize user strengths in natural language, and generate contextual explanations for missing technical concepts.
* Researched and implemented an evolution of feedback methodologies, progressing from a simplistic rule-based system with random keyword pairing to a sophisticated, context-aware coaching tool that synergizes a classification model, XAI, and LLM reasoning.

**Technologies:** CatBoost, SHAP, S-BERT (Sentence Transformers), Groq LLM (Llama3), Flask, MongoDB, PyPDF2, NLTK

<img width="863" height="763" alt="image" src="https://github.com/user-attachments/assets/600257dc-52f8-4f19-9ccd-d7675a94a309" />
