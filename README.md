### Kubernetes Node & Pod Auditor**

**Description:**
Kubernetes Node & Pod Auditor is a CLI tool written in Go that connects to a Kubernetes cluster and performs quick health and status audits. It gathers information about nodes, pods, and deployments, identifying issues such as resource bottlenecks, pending workloads, or unhealthy pods.
The goal is to provide platform engineers with an at-a-glance summary of cluster health directly from the command line.

**Key Features (planned):**

* Connect to clusters via local kubeconfig.
* List nodes, pods, and deployments with health and resource summaries.
* Detect unhealthy or pending pods automatically.
* Output audit summaries in JSON or Markdown.
* Optional webhook or email report generation.
