## Abstract

**Title**: An LLM-SPARQL Hybrid Framework for Named Entity Linking and Disambiguation to Wikidata

**Keywords**: Entity Linking, SPARQL, Wikidata, Large Language Model

**Type**: Extracurricular Research

**Duration**: Feb 2024 – May 2024

**Collaborator**: [Muhammad Salman](https://scholar.google.com/citations?user=_Th0BowAAAAJ&hl=en)

**Supervisors**: [Sergio José Rodríguez Méndez](https://researchportalplus.anu.edu.au/en/persons/sergio-rodriguez-mendez/), [Armin Haller](https://comp.anu.edu.au/people/armin-haller/)

**Deliverables**: [published paper](https://link.springer.com/chapter/10.1007/978-981-96-1809-5_16), [poster](https://github.com/glowing-sea/wikidata-entity-linking/blob/main/deliverables/poster.jpg), [code](https://github.com/glowing-sea/wikidata-entity-linking)

**Description**:

- This project has developed a hybrid Entity Linking (EL) system that leverages both the language-reasoning capabilities of Large Language Models (LLMs) and the knowledge of an external, large-scale, crowdsourced Knowledge Graph (KG), Wikidata.
- EL is a key step in local Knowledge Graph Construction (KGC) from text and Knowledge Graph Alignment (KGA), and is useful in web search.
- Traditional EL models typically first assess the contextual similarity between the embeddings of two Mentions and merge them into an Entity when a threshold is reached. However, this entity may not correspond to some natural real-world entity that humans consider.
- The project addresses these issues by equipping the LLM EL model with a SPARQL query tool, enabling the system to further link the entities it generates to concrete, human-defined entities in Wikidata.
- The process of EL to Wikidata consists of two steps: (1) fetching a list of candidate entities from Wikidata along with their types and descriptions, and (2) recursively disambiguating and selecting the closest one by LLM reasoning.
- Evaluation involves matching the system-predicted entity's Wikidata QID to the ground-truth entity in labelled datasets.
- The model achieves an F-measure of 96% on the Wikidata-Disamb dataset.
- The project identifies future work to move from EL to Triple Linking to fully integrate a local KG into a subset of a global one.

**Publication**:
- Muhammad Salman, **Haoting Chen**, Sergio José Rodríguez Méndez, Armin Haller. An LLM-SPARQL Hybrid Framework for Named Entity Linking and Disambiguation to Wikidata. **In China Conference on Knowledge Graph and Semantic Computing & International Joint Conference on Knowledge Graphs**, Springer Nature Singapore, 2025, pp. 210–226. https://link.springer.com/chapter/10.1007/978-981-96-1809-5_16

**About Collaboration and Publication**:
- This was a collaboration project between the PhD student Muhammad Salman and Haoting Chen. They collectively participated in the system architecture design and iterative optimisation. Haoting Chen’s contributions to the publication included figure making, manuscript editing, and running half of the final experiments. The third and fourth authors, who were also the supervisors, provided high-level guidance throughout the project. The paper was awarded **“The Best Candidate Paper”** at the conference.
