# Hi, I'm Sriya Chittaneni

I'm a master's student in Computer Science at Blekinge Institute of Technology, Sweden. I build machine-learning and cloud projects: RAG systems, satellite-image segmentation, decision-support systems, time-series forecasting and Kubernetes microservices.

## RAG systems

| Project | What it is | Result |
|---|---|---|
| [graphrag-multihop](https://github.com/sriyaaa2003/graphrag-multihop) | Finds the second passage a multi-hop question needs by walking an entity graph and merging it with vector search. | All supporting paragraphs in the top 5 for **84.8%** of HotpotQA questions vs **77.2%** for vector search. |
| [permission-aware-rag](https://github.com/sriyaaa2003/permission-aware-rag) | Multi-tenant RAG with access control before ranking, a second check before the prompt and a tamper-evident audit log. | Retrieval matches an independent permission check on 40 random worlds; 93 tests. |
| [semantic-cache-rag-router](https://github.com/sriyaaa2003/semantic-cache-rag-router) | Semantic answer cache with small/large model routing and a cost and latency dashboard. | Cache threshold set from 40,430 labelled Quora pairs. |
| [trouble-report-investigator](https://github.com/sriyaaa2003/trouble-report-investigator) | Finds similar old bug reports and predicts the affected subsystem. | Hybrid search recall@10 **0.830** vs 0.709 for BM25 on 14,037 Mozilla reports. |

## Time-series, networks and vehicles

| Project | What it is |
|---|---|
| [tailwatch](https://github.com/sriyaaa2003/tailwatch) | Calibrated congestion-burst forecasts for a radio network, on a simulated city and a real 5G trace. |
| [nfcast](https://github.com/sriyaaa2003/nfcast) | Time-series foundation models vs classical methods on simulated 5G network-function telemetry, with LoRA fine-tuning and an autoscaling test. |
| [multipath-eval](https://github.com/sriyaaa2003/multipath-eval) | Comparing five multipath routing algorithms on generated and real network topologies. |
| [evprior](https://github.com/sriyaaa2003/evprior) | Pre-trip and live remaining-energy prediction for electric cars with a Kalman filter. |
| [fleet-memory](https://github.com/sriyaaa2003/fleet-memory) | A shared road-condition map from many vehicles, with warnings that cite their evidence. |

## Machine learning

| Project | What it is |
|---|---|
| [marine-debris-segmentation](https://github.com/sriyaaa2003/marine-debris-segmentation) | DeepSpectralUNet for finding marine debris in Sentinel-2 images (team project). |
| [human-ai-text-classification](https://github.com/sriyaaa2003/human-ai-text-classification) | Six-class classification of how a text was written, human to AI. |

## Systems and decision support

| Project | What it is |
|---|---|
| [debris-fallout-risk-engine](https://github.com/sriyaaa2003/debris-fallout-risk-engine) | Hackathon team project (EDTH, May 2026, 2nd prize): scores where debris from an intercepted drone or missile should not fall. |
| [drone-selection-dss](https://github.com/sriyaaa2003/drone-selection-dss) | Team project that ranks drones for small EU ports with AHP, TOPSIS and a RAG assistant. [Live demo](https://intelligent-dss-for-drone-selection-sandy.vercel.app) |
| [netops](https://github.com/sriyaaa2003/netops) | Kubernetes microservice app that flags anomalous components in network logs with an Isolation Forest. |

## Earlier projects
[chime-chat](https://github.com/sriyaaa2003/chime-chat) (Socket.IO, DynamoDB, S3) · [svyj-chat](https://github.com/sriyaaa2003/svyj-chat) (Firebase) · [selenium-python-practice](https://github.com/sriyaaa2003/selenium-python-practice)

## Tech
Python, PyTorch, scikit-learn, FastAPI, SQL, JavaScript/Node.js, Docker, Kubernetes, PostgreSQL, AWS, Firebase.
