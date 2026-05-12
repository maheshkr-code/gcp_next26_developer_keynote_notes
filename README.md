### My napkin notes of [Google Cloud Next '26 Developer Keynote](https://www.youtube.com/watch?v=A01DQ8_xy7Q)

[Announcement Blog](https://cloud.google.com/blog/products/ai-machine-learning/introducing-gemini-enterprise-agent-platform)

Google Cloud Next 26 Openinng keynote - highlights

**Gemini Enterprise Agent Platform** (~~Vertex AI~~)

[ Build - Scale - Govern - Optimize ]

```
    1. Agent Taskforce
    2. Agentic Platform and Models
    3. Agentic Defence
    4. Agentic Data Cloud 9
    5. AI Hypercomputer
```
 GA
 ```
  - Agent Identity
  - Agent Runtime
  - Agent Identity
```
 Preview
 ```
   - Agent Studio
   - Agent Registry 
   - Agent Gateway 
   - Agent Simulation 
   - Agent Observability
```
Agentic Data Cloud

BigQuery and Spanner are the "muscles" and "memory," while the Agentic Data Cloud is the "nervous system" that allows Gemini to use them to take real- world actions. The reason these two services are grouped under the Agentic Data Cloud is the new Knowledge Catalog (formerly Dataplex). It acts as the translator. If an agent wants to know "How is the Merck deal going?", the Knowledge Catalog looks across BigQuery (historical data), Spanner (current orders), and Google Cloud Storage (the contract PDF) to provide a single, grounded truth.

    Gemini 3.1 pro - new 
    Gemini 3.1 Flash image - nano banano 2 - preview 
    Veo 3.1 Lite - preview 
    Lyria 3 - preview (audio/music) 
    Anthorpic Claude Opus 4.7
----------------------------------------------------

Projects in Gemini Enterprise

Google Cloud Data Agent Kit

    Current Product name : New Name (post Google Next 26)
    BigLake             -> Lakehouse (managed Apache Iceberg storage)
    BigLake Metastore   -> Lakehouse Runtime Catalog
    Dataplex            -> knowledge Catalog
    Dataproc            -> Managed service for Apache Spark
    Composer            -> Managed service for Apache Airflow
    Looker Studio       -> Data Studio 
    Vertex AI           -> Gemini Enterprise Agent Platform
    Agentspace          -> Gemini Enterprise
    Gemini for Workspace-> Gemini Enterprise App 
    Vertex AI Designer  -> Gemini Enterprise app includes Agent Designer
----------------------------------------------------
All about Apache services offered as Managed svc from Google Cloud

    Managed Service for Apache Spark (Dataproc)	   -> Apache Spark	 - Large-scale data processing and analytics.
    Cloud Composer	                              -> Apache Airflow	 - Workflow orchestration and pipeline management.
    Managed Service for Apache Kafk                -> Apache Kafka	 - Real-time event streaming and messaging.
    Dataflow	                                    -> Apache Beam	    - Unified stream and batch data processing.
    Memorystore for Med	                           -> Apache Memcached - Distributed in-memory key-value store for caching.
    Cloud Bigtable	                              -> Apache HBase	- High-performance                
    Dataproc Metastore	                           -> Apache Hive	 - Centralized metadata management based on the Hive Metastore.
    Managed Service for Apache Flink	            -> Apache Flink	- Stream processing
----------------------------------------------------

**Gemini Enterprise Agent Platform** (formerly known as Vertex AI Agent Builder) and the core Vertex AI platform depends entirely on how much control you want over the "plumbing" of your AI vs. how fast you want to deploy a functional agent.

**Gemini Enterprise Agent Platform**
This is a high-abstraction environment. It is designed for developers and business users who want to build "Agentic" systems—AI that doesn't just talk but acts—without managing the underlying machine learning infrastructure. It bundles grounding, orchestration, and tool-calling into a unified interface.
   - Building and deploying "Agents" quickly.
   - Product Managers, Devs, Business Users.
   - Low to Medium (No-code / Low-code).
   - Opinionated (Google handles chunking/RAG).
   - Chatbots, Search apps, Support agents.
     
**Vertex AI (Core Platform)**
This is a low-abstraction environment. It is the full-stack home for data scientists and ML engineers. It provides the raw tools to train models from scratch, fine-tune existing ones (like Gemini 1.5 Pro), and build custom RAG (Retrieval-Augmented Generation) pipelines where you control every single variable
   - Managing the full ML lifecycle.
   - Data Scientists, ML Engineers.
   - High (Pro-code / DIY).
   - Full control over embeddings & logic.
   - Custom models, specialized RAG, MLOps.

1. Build
2. Scale
3. Govern
4. Optimize
   
<img width="882" height="552" alt="image" src="https://github.com/user-attachments/assets/425f29e0-acbf-4289-993b-679450b0d146"/>

<img width="944" height="536" alt="image" src="https://github.com/user-attachments/assets/c87461fc-5d28-4d34-9d6a-07a75f11dfb7" />

<img width="1003" height="582" alt="image" src="https://github.com/user-attachments/assets/04440511-2a83-4b9b-8486-017d261ce0f6" />

#### 1. Build
<img width="517" height="372" alt="image" src="https://github.com/user-attachments/assets/b71e1bc0-12c7-4203-9a21-e5e99b6d0a29" />

#### 2. Scale 
<img width="801" height="292" alt="image" src="https://github.com/user-attachments/assets/9ecbd740-9d71-4aa6-b9f3-0eb593190841" />
Sessions & memory - context of agents 

#### 3. Govern 
#### 4. Optimize 
<img width="1263" height="545" alt="image" src="https://github.com/user-attachments/assets/d42c2433-13c3-4b43-8d24-b4768ba2598c" />

---
<img width="648" height="400" alt="image" src="https://github.com/user-attachments/assets/0be0a085-8e38-420a-9600-dbcbab7ad642" />

---
<img width="1666" height="745" alt="image" src="https://github.com/user-attachments/assets/ea379f28-562e-4b76-af14-838dc2380afe" />

<img width="1086" height="796" alt="image" src="https://github.com/user-attachments/assets/ad843931-82dc-4598-8cb3-ed27aa0e2a06" />

<img width="711" height="498" alt="image" src="https://github.com/user-attachments/assets/c35108ee-5bab-4d40-bc76-c91ebb2f9137" />

<img width="1406" height="797" alt="image" src="https://github.com/user-attachments/assets/1cfdf391-2a50-4c80-ba4c-37653b6bd748" />

<img width="1705" height="857" alt="image" src="https://github.com/user-attachments/assets/ae3ae08f-3ed1-47bf-ae63-333c5f4ef124" />

<img width="1427" height="820" alt="image" src="https://github.com/user-attachments/assets/80487d64-b74d-450a-9df2-b29ad6c4b3da" />

<img width="1385" height="792" alt="image" src="https://github.com/user-attachments/assets/614e372b-58ba-4450-b837-410e0567204c" />

<img width="1405" height="800" alt="image" src="https://github.com/user-attachments/assets/bde8f42f-9e2f-48cb-b35d-cf8f1c3052b7" />

<img width="820" height="450" alt="image" src="https://github.com/user-attachments/assets/6a7db513-f6a3-453f-90d2-fa2ecd92dd40" />

<img width="1422" height="793" alt="image" src="https://github.com/user-attachments/assets/591ec401-d7f8-49be-a472-3f7aa7286d55" />

<img width="1406" height="791" alt="image" src="https://github.com/user-attachments/assets/2ffff776-df9f-4070-b742-d9193d42d6f5" />

<img width="1430" height="818" alt="image" src="https://github.com/user-attachments/assets/387c1ed9-df50-4999-bd45-bcdad518bb2f" />

<img width="1410" height="786" alt="image" src="https://github.com/user-attachments/assets/838322e6-87ab-4cfb-90ac-de338e34a933" />

<img width="1097" height="560" alt="image" src="https://github.com/user-attachments/assets/9aa70bef-b7cb-40b0-8f60-6d87c7eae0c8" />

<img width="542" height="483" alt="image" src="https://github.com/user-attachments/assets/b9f9ecb7-ccb8-4e79-967d-91cea501d155" />

---
MultiAgent System:
<img width="1267" height="558" alt="image" src="https://github.com/user-attachments/assets/3c24935b-53c4-4990-8c69-2a402ca0bcc2" />

<img width="922" height="422" alt="image" src="https://github.com/user-attachments/assets/986d8784-8aad-4075-9eb9-5bcad06e6d0a" />

<img width="935" height="455" alt="image" src="https://github.com/user-attachments/assets/fe960572-4d41-4c3e-9c55-9fbc9f997084" />

<img width="1016" height="592" alt="image" src="https://github.com/user-attachments/assets/3d63b504-a6ee-42c3-8513-cfa187b3dd5f" />

<img width="1396" height="792" alt="image" src="https://github.com/user-attachments/assets/1bedbbe4-93a5-4642-87ef-5419c48d1e6c" />


<img width="1162" height="441" alt="image" src="https://github.com/user-attachments/assets/c01c5a90-119c-4e51-b357-ef23fce10dec" />


<img width="925" height="599" alt="image" src="https://github.com/user-attachments/assets/ad5a040a-371e-4bf5-8601-e06913490f44" />

<img width="1383" height="748" alt="image" src="https://github.com/user-attachments/assets/bb27b7e3-5c11-4792-81a4-c06c2b757342" />

<img width="1397" height="760" alt="image" src="https://github.com/user-attachments/assets/210ef7f1-ac82-4911-beb0-a3628c8b6dd7" />

<img width="1347" height="792" alt="image" src="https://github.com/user-attachments/assets/1925710e-b7a6-43a4-831f-5776f5e043e0" />

<img width="1402" height="688" alt="image" src="https://github.com/user-attachments/assets/74b037f9-f9f9-45ce-bead-e54db29bc760" />

<img width="1393" height="788" alt="image" src="https://github.com/user-attachments/assets/12c4b4dd-5eb4-4f0b-bbd7-5cb932a02933" />

<img width="1337" height="717" alt="image" src="https://github.com/user-attachments/assets/10350548-dfef-4268-8fe5-b0ad3cedc20a" />

<img width="1281" height="702" alt="image" src="https://github.com/user-attachments/assets/0c8b5623-b693-4fa9-97eb-ec9b743096ab" />

<img width="1297" height="722" alt="image" src="https://github.com/user-attachments/assets/77105715-d64a-443f-9f41-6d411fc87a43" />

<img width="1358" height="761" alt="image" src="https://github.com/user-attachments/assets/33a4491f-fd08-46cc-814d-0556e7581e26" />

<img width="1357" height="682" alt="image" src="https://github.com/user-attachments/assets/fdc271ba-155e-4cbe-b20a-b426afa54466" />

<img width="953" height="757" alt="image" src="https://github.com/user-attachments/assets/a292ff73-81ba-40e4-93c9-893ece16fa46" />

<img width="1343" height="742" alt="image" src="https://github.com/user-attachments/assets/883caa4f-2589-4d3b-a41e-9dd1a0d0b949" />

<img width="1377" height="766" alt="image" src="https://github.com/user-attachments/assets/ede46dbe-70c6-495b-9e25-cc63318a3991" />
