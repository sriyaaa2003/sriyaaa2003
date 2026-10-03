# Hi, I'm Sriya Chittaneni

Student at Blekinge Institute of Technology (Sweden). I build machine-learning and cloud systems: retrieval-augmented generation (RAG), satellite-image segmentation, decision-support systems and Kubernetes microservices. Every number below links to a repo where it is reproducible, and the READMEs say what is *not* measured.

## Start here: RAG systems

| Project | What it does | Measured result |
|---|---|---|
| [**graphrag-multihop**](https://github.com/sriyaaa2003/graphrag-multihop) | Finds the *second* passage a multi-hop question needs by walking an entity graph, then fuses it with vector search. | On an untouched HotpotQA slice, all supporting paragraphs in the top 5 for **84.8%** of questions vs **77.2%** for plain vector search (+7.6 pts, 95% CI +3.6 to +11.6). The README also shows the weaker first version and the slice where the gain is smaller. |
| [**permission-aware-rag**](https://github.com/sriyaaa2003/permission-aware-rag) | Multi-tenant RAG that cannot leak: access control *before* ranking, a second check before the prompt, a tamper-evident audit log. | Retrieval equals an independent permission oracle on 40 randomised worlds plus 10 mutation sequences; 93 tests. |
| [**semantic-cache-rag-router**](https://github.com/sriyaaa2003/semantic-cache-rag-router) | Semantic answer cache with cost-aware small/large model routing and a cost and latency dashboard. | Cache threshold measured on 40,430 labelled Quora pairs: at 0.92 only about 80% of served hits were true duplicates, so the default is 0.95. |

## Machine learning and research

| Project | What it is |
|---|---|
| [**marine-debris-segmentation**](https://github.com/sriyaaa2003/marine-debris-segmentation) | DeepSpectralUNet, a segmentation network that fuses spectral indices (FDI, NDVI, NDWI, FAI) at every decoder stage to find marine debris in Sentinel-2 imagery. Team project; I designed the network. Report included. |
| [**human-ai-text-classification**](https://github.com/sriyaaa2003/human-ai-text-classification) | Six-class classification of how a text was produced (human to AI), with stylometric features, a hierarchical classifier and mined association rules for explainability. |

## Systems and decision support

| Project | What it is |
|---|---|
| [**debris-fallout-risk-engine**](https://github.com/sriyaaa2003/debris-fallout-risk-engine) | Hackathon team project (EDTH, Karlskrona, May 2026; the team won 2nd prize): scores where debris from an intercepted drone or missile must not fall. |
| [**drone-selection-dss**](https://github.com/sriyaaa2003/drone-selection-dss) | Team project: decision-support system that ranks drones for small EU ports with AHP, TOPSIS, a rule base, sensitivity analysis and a regulation-grounded RAG assistant. [Live demo](https://intelligent-dss-for-drone-selection-sandy.vercel.app) |
| [**netops**](https://github.com/sriyaaa2003/netops) | Microservice app on Kubernetes that flags anomalous components in network logs with an Isolation Forest. Node.js, Flask, Postgres, nginx. |

## Earlier projects

[chime-chat](https://github.com/sriyaaa2003/chime-chat) (Socket.IO, DynamoDB, S3) · [svyj-chat](https://github.com/sriyaaa2003/svyj-chat) (Firebase) · [selenium-python-practice](https://github.com/sriyaaa2003/selenium-python-practice)

## Tech

Python, PyTorch, scikit-learn, FastAPI, SQL, JavaScript/Node.js, Docker, Kubernetes, PostgreSQL, AWS, Firebase.
