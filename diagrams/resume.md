
# Tarun Nagineni  
[Your Email] • [Your Phone] • [https://www.linkedin.com/in/your-profile](https://www.linkedin.com/in/your-profile) • [GitHub] • [Location]

---

## 💼 Professional Summary
DevOps-oriented Software Engineer with hands-on experience deploying AI/ML and network analytics systems at scale in on-prem Kubernetes clusters. Proven expertise in distributed systems, container orchestration, real-time data pipelines, and infrastructure-as-code. Seeking to contribute to cutting-edge AI research and deployment as part of OpenAI’s ML Infrastructure or Inference teams.

---

## 🛠 Experience

**Ennetix – Network Analytics and operations Engineer**  
*Date – Present*
Let's try to take a simple example problem and identify the different infrastructural changes in order to achieve the goal.
PROBLEM: Flag all suspicious domains being accessed on your network.
Client side:
- Capturing all devices' traffic on our local network: Set up the local network with a Router ➔ WLC ➔ Port mirrored switch ➔ Main Switch ➔ APs. Thus, all traffic on our network is sent to the edge device. Full LAN diagram: https://github.com/aNameNobodyChose/Ennetix-resume/blob/main/diagrams/ennetix-port-mirror-pic.jpg.
- Extract all essential fields for the captured traffic: Created and deployed a dockerized agent written in c++ to extract important fields for further analysis(In our case: source and destination IP).
Server side:
The goal here is to create a network monitoring solution that represents on premisis to save on cloud costs.
- Deploy company's network monitoring solution: In order to deploy the company's network monitoring solution, I used kubeadm to deploy a Kubernetes cluster on premisis. 
- Architected and deployed a full-stack network monitoring solution (`xvisor`) on on-prem servers using Kubernetes (kubeadm).
- Designed the deployment pipeline using Terraform to manage Kafka, Spark, Elasticsearch, Logstash, Go backends, and Vue.js frontends as infrastructure-as-code.
- Built a custom port mirroring setup to capture live traffic into Dockerized `xources` (e.g., Zeek, PCAP processors) deployed on the `xome` edge device.
- Developed and containerized Spark Streaming jobs to consume Kafka topics, process network flows and security logs, and push enriched data into Elasticsearch.
- Engineered Go-based RESTful backend services querying Elasticsearch indices, integrated with a Vue.js frontend for real-time analytics.
- Leveraged Azure Container Registry for storing container images; integrated into the deployment workflow.
- Set up Kafka load balancers and ingress rules for scalable, resilient streaming architecture.

---

## 🚀 Projects

**QuoteCaster**  
[https://huggingface.co/spaces/aNameNobodyChose/quote-caster](https://huggingface.co/spaces/aNameNobodyChose/quote-caster)  
Built a machine learning-based quote attribution system that predicts the speaker of dialogue in fictional or news texts using contextual embeddings and transformer models. Deployed on Hugging Face Spaces with Gradio interface.

---

## 📜 Certifications

- Red Hat Certified System Administrator (RHCSA)
- HashiCorp Terraform Associate
- Certified Kubernetes Administrator (CKA)
- Microsoft Azure Administrator Associate (AZ-104)

---

## 🎓 Education

**Bachelor of Science, Computer Science**  
Minor: Economics  
GPA: 3.22

---

## 🧠 Technical Skills

**Languages:** Go, Python, Bash, SQL  
**Infrastructure:** Kubernetes, Terraform, Azure, Docker, Helm  
**Streaming/Data:** Apache Kafka, Apache Spark Streaming, Logstash, Elasticsearch  
**AI/ML Tools:** Hugging Face Transformers, Gradio, PyTorch, spaCy  
**Frontend:** Vue.js, REST APIs  
**Other:** Git, CI/CD, Prometheus, Grafana, Nginx, Linux
