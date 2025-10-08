# Alexey Shvechkov

**Greater Boston, MA** | **+1 (774) 278-1743** | **[jobs@shvechkov.com](mailto:jobs@shvechkov.com)** | **[GitHub](https://github.com/shvechkov)** | **[LinkedIn](https://www.linkedin.com/in/alexey-shvechkov/)**

## Summary

Principal Software Engineer with 20+ years architecting resilient systems—from Linux kernel drivers to cloud-native AI platforms. Recent focus: ML-powered ransomware detection (70% faster recovery), agentic RAG chatbot (15% support reduction), and Kubernetes-based Azure protection SaaS. Deep expertise in C++, Go, Python, PyTorch. Led distributed engineering teams while prototyping and delivering production systems at enterprise scale. Patent holder and open-source contributor.

## Core Competencies / Skills

### Leadership & Strategy
- Technical strategy, agile execution, product ownership, cross-functional influence
- Managing & mentoring teams (10+ years), roadmap planning, cost optimization

### Cloud & Distributed Systems
- AWS (EC2, S3, Lambda, API Gateway), Kubernetes, Docker, Terraform
- Scalable microservices, high-availability architectures, CI/CD pipelines, fault tolerance

### Programming Languages
- C++, Go, Python, Rust, Perl, Bash

### AI/ML
- Generative AI, RAG, transformers (LoRA fine-tuning)
- PyTorch, TensorFlow, Hugging Face, LangChain, ONNX Runtime
- Distributed training, anomaly detection

### Systems Programming
- Linux/Windows kernel drivers (eBPF, KMDF/WDM, minifilters)
- File systems, network programming, performance tuning

### Databases & Storage
- PostgreSQL, MySQL, Redis, Cassandra, object storage systems

### Frontend & APIs
- React, Next.js, REST API design, rapid prototyping

## Professional Experience

### Arcserve — Technical Director, Software Engineering
**2014 – Present** | Greater Boston, MA

**Highlights / Most Recent Projects from Last 3 Years**

#### Anomaly & Ransomware Detection for Backup/Storage
- Architected and implemented engine for detecting anomalies and traces of ransomware activities in air-gapped backups/storage using ML/statistical models; Designed and trained various ML/AI models (including BERT-based LLMs) for threat classification/detection; Built automated training and telemetry processing pipelines for models' evaluation and quality assessment. Technically led and managed team of developers (“innovation group”); According to initial studies, this feature reduced ransomware incident response & recovery times by ~70%.

**Tech stack:** Windows internals (MFT, ReFS, USN parsing, mini-filters), ML/AI (Random Forest, XGBoost, feature engineering), BERT-based LLMs (training & fine-tuning), FFT + Isolation Forest, Prophet, FAISS, ONNX Runtime, YARA, AWS Glue/SageMaker, C/C++, Python (NumPy, TensorFlow, Hugging Face).

#### Agentic RAG Chatbot for Troubleshooting & Monitoring SaaS and On-Prem Products
- Designed and implemented (end-to-end) multimodal chatbot integrated with products via APIs/MCP for products’ monitoring, troubleshooting, and documentation-based Q&A. Also, bot provided UI visual guidance, detected anomalies, performed tasks, reduced support calls by ~15%.

**Tech stack:** OpenAI API, LangChain, RAG, Ollama, Hugging Face, AWS Lambda (Python), Python FastAPI & FastMCP, React, HTML/CSS.

#### Azure Workloads Protection (Backup & Replication)
- Architected and prototyped a massively parallel/scalable Kubernetes-based SaaS solution to protect and restore Azure workloads (VMs, containers, k8s, blob storage); Implemented critical parts of the system; Led a team of developers throughout design and implementation phases.

**Tech stack:** Golang, Azure APIs/Golang SDK, k8s, containers, Terraform, gRPC/Protobuf, Redis (KV store, pub/sub).

#### Cyber-Resilient Storage Appliance
- Architected and prototyped an immutable storage appliance with hardened Linux + OpenZFS, supporting self-healing storage, immutable snapshots, and backup integration; Accelerated product delivery by 30–40% via reusable prototypes and code contributions.

**Tech stack:** Linux internals, OpenZFS, Python (backend/CLI), Golang (S3-compatible connector).

#### Ransomware Protection Module for Windows Storage Product
- Developed Windows minifilter driver and user-mode service to protect backup product services/data from ransomware tampering (Windows equivalent of AppArmor).

**Tech stack:** Windows internals, minifilters (IFS/WDK).

#### Additional Contributions
- Managed small/medium-sized distributed teams (5-15) developing and maintaining the following products:
  - High availability & real-time full host/VM replication product (aka RHA).
  - Highly scalable archival storage appliance with distributed fault-tolerant FS (aka OneXafe).
  - SaaS-based backup of on-prem data (aka Cloud Direct).
- Contributed as IC fixing bugs in legacy products and as domain expert/architect on new feature development.
- Actively participated in hackathons (winning awards); Prototyped innovative product features; Technically led and managed team responsible for company’s AI/ML strategy (“innovation group”).
- Mentoring, Hiring, Managing teams, performance reviews.

### CA Technologies (formerly Computer Associates) — Principal Engineer
**2006–2014** | Greater Boston, MA
- Led post-acquisition integration of XOsoft’s replication technologies into CA’s enterprise portfolio; Designed and developed high-availability replication, deduplication, and backup features using C/C++ for Windows and Linux; Built a Unix/Linux build automation framework with web UI, reducing manual labor by 50%.

### XOsoft (Acquired by CA Technologies in 2006) — Lead Software Engineer
**2000–2006** | Israel
- Designed and developed CDN components, including network management and monitoring tools, and high-traffic HTTP/FTP caching proxies, along with replication solutions; Led the development of kernel-mode drivers and file system modules in C/C++, improving system performance and reliability.

### Yandex — Software Engineer
**1998–2000** | Moscow, Russia
- Developed high-traffic search, advertising network, and web applications using C++ and Perl, optimizing performance for large-scale systems.

## Open-Source Projects/POCs (Examples)

- **[s3stor](https://github.com/shvechkov/s3stor)** – Deduplicating archiving/backups into S3-compatible storage (Go)
- **[gos3rve](https://github.com/shvechkov/gos3rve)** – Exposing local file systems via S3 APIs (Go)
- **[ufc](https://github.com/shvechkov/ufc)** – Fast unique file copy/indexes and stores unique files (Rust)

## Education

- **M.Sc., Applied Mathematics** | Institute of Telecommunications and Computer Science, Russia | 1996
- **Machine Learning Specialization (Stanford Online)** | 2024 (Certificate)
- Holder of multiple U.S. patents in storage and infrastructure technologies
