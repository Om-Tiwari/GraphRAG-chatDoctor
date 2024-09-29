# Knowledge Graph for Language Models

Welcome to the **AI Knowledge Graph Project**, where we're using cutting-edge Graph-based Reasoning, Retrieval-Augmented Generation (RAG), and Language Models to organize and extract structured knowledge from unstructured data.

![Knowledge Graph Visual](./visualisation.png)

## 🔍 Project Overview

This repository contains code and resources for building **graph-based knowledge systems** that integrate with **Neo4j** and **LangChain**. By leveraging **knowledge graphs**, we can efficiently retrieve relevant information and provide better context-aware responses using **Language Models** like GPT-4, LLAMA, MISTRAL.

---

### 📜 Features

- **Neo4j Integration**: Build and query a **knowledge graph** using Neo4j to store nodes and relationships.
- **LangChain Integration**: Seamless use of Language Models to interact with the knowledge graph for better information extraction and reasoning.
- **RAG Framework**: Employ **Retrieval-Augmented Generation (RAG)** for combining generative AI and knowledge graphs for enhanced retrieval.
- **Visualization**: View your knowledge graph visually to understand the relationships between data entities (like the one above).
  
---

## 💡 How It Works

This project extracts information from various unstructured text sources, and populates a **knowledge graph** in Neo4j, providing an efficient way to query and generate insights. The graph visualization shows relationships between concepts, making it easier to understand the connections between them.

---

## 🚀 Get Started

1. Open the notebook in Colab:
    ```bash
    git clone https://github.com/your_username/AI-Knowledge-Graph.git
    ```

2. Set up the environment:
    ```bash
    pip install -r requirements.txt
    ```

3. Start your Neo4j server and load the graph:
    ```bash
    python graphRAG_basic_neo4j_langchain.py
    ```

---

### 📂 Repository Structure

- `graphRAG_basic_neo4j_langchain.ipynb`: The core notebook that demonstrates building the knowledge graph with Neo4j and LangChain.
- `train_2kchat.jsonl`: Sample data for training or testing the graph-based RAG pipeline.
- `visualisation.png`: An example of the knowledge graph visualization.

---

## 🛠️ Tech Stack

- **Neo4j**: Graph database to store knowledge nodes and relationships.
- **LangChain**: Framework for large language models, enabling connection to external tools and retrieval systems.
- **Python**: Primary language for building the backend system.
- **D3.js**: For knowledge graph visualizations.

---

## 📈 Graph Data Example

Here’s a sneak peek of what your knowledge graph might look like!

![Graph Visualisation](./visualisation.png)

---

## 📊 Analytics Dashboard

Get real-time stats and insights on your knowledge graph with this custom dashboard:


<iframe src="https://public.tableau.com/views/KnowledgeGraphDashboard"></iframe>


---

## 🎯 Future Goals

- **Expand Integrations**: Add support for more language models and other graph-based databases.
- **Advanced Visualizations**: Introduce more complex visualizations for deeper insights into graph data.
- **OpenAI API**: Integrate OpenAI GPT-4 for automated question-answering over the knowledge graph.

---

## 🤝 Contributing

We welcome contributions! Please open an issue or submit a pull request to discuss any improvements or new features you'd like to add.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Acknowledgments

Special thanks to all the contributors and the open-source community for making this project possible.

---

Feel free to add, modify, or customize any of these sections to better suit the exact content of your repo! Let me know if you'd like specific changes or more sections.
