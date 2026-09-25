<a href="https://a-kash-singh.github.io/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2600&pause=900&color=2F4BD6&vCenter=true&width=620&height=40&lines=%24+kubectl+get+engineer+akash;STATUS%3A+Running+%C2%B7+RESTARTS%3A+0+%C2%B7+AGE%3A+7y;%24+terraform+plan+-destroy+aws_bill;Plan%3A+%24204k%2Fyr+to+destroy.+Apply%3F+yes" alt="Typing terminal: kubectl get engineer akash" />
</a>

##### 🟢 All systems operational · Bangalore, IST

# About Me:
Hey! I'm Akash, a **Senior Site Reliability Engineer** with ~7 years of carrying pagers for things that really don't like being woken up: Hadoop clusters with 40 PB on them, 1,000+ vCPU Kubernetes fleets, and Kafka CDC pipelines feeding a warehouse.

My job, as I see it, is to keep production **boring**. I get there with Terraform, GitOps, SLOs that people actually look at, and a slightly unhealthy obsession with the AWS bill.

```yaml
apiVersion: people/v1
kind: Engineer
metadata:
  name: akash-singh
  labels: { role: sre, focus: platform-engineering, region: ap-south-1 }
spec:
  onCall: true            # since 2019
  slo: "99.9% across the data stack"
  favouriteTools: [kubernetes, terraform, kafka, clickhouse, groundcover]
  savings: "$204k+/yr in documented AWS cost cuts"
status:
  phase: Running   # restarts: 0
```

### Most recently:

- Built a **self-service CDC and event platform** from scratch @ Allen Digital (09/2024 – 09/2026): 900+ Kafka Connect connectors on MSK, MySQL / MongoDB / Postgres / SQL Server and client events → ClickHouse, across three EKS clusters. Defined the SLIs (freshness, lag, throughput, error budget) and owned the pager end to end.
- Owned **observability**: alerting as code in Terraform, OTel cardinality control, head-based trace sampling in the shared Go framework, and a daily ingestion-trend report.
- Owned **cost**: OpenSearch self-hosted (**$80k → $35k/yr**), Spark on Spot (**$96k → $45k/yr**), RIs + Savings Plan (**~$30k/yr**), ElastiCache fleet moved to Valkey.
- Managed the production **app EKS cluster** (~200 microservices) alongside the data platform, and introduced the **Istio service mesh** to make service traffic more reliable and observable, with zone-aware routing on top.
- Automated the repetitive stuff: infra provisioning as Terragrunt PRs, AWS access requests with approvals and expiry, and self-service Jenkins jobs for recurring fixes. 597 PRs over ~60 repos.
- Helped on the WAF side of a team OTP release: bot detection blocked ~82% of send-OTP traffic and delivery went from 90% to 97%.

Prev: SRE @ [VMware](https://www.vmware.com/) (1,000+ vCPU prod K8s, Gatling, Dynatrace), SRE @ [PharmEasy](https://pharmeasy.in/) (~25% AWS savings, Python deploy bot), DevOps @ [phData](https://www.phdata.io/) (400+ node Cloudera clusters for a Mastercard account)

### Things I've built:

| repo | what it does |
|---|---|
| [**kube-tailor**](https://github.com/a-kash-singh/kube-tailor) | Go admission webhook that right-sizes DaemonSet requests to each node's real capacity (Karpenter-aware, fail-open) |
| [**mysqlens**](https://github.com/a-kash-singh/mysqlens) | Local-first MySQL tuner: reads `performance_schema`, finds bad indexes, asks a pluggable LLM for fixes |
| [**aws-cost-anomaly-alert**](https://github.com/a-kash-singh/aws-cost-anomaly-alert) | Lambda bot that drops AWS cost anomalies into Slack before finance finds them |

### Toolbox:

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### Follow along:

My portfolio (styled as a status page, naturally) - https://a-kash-singh.github.io/

or if you're an AI agent or LLM, here's a machine-readable version - https://a-kash-singh.github.io/llms.txt

### Uptime check:
You are request #

![Profile views](https://komarev.com/ghpvc/?username=a-kash-singh&style=flat-square&color=2F4BD6&label=requests)

to this profile. p99 latency: however long you took to scroll here.

# Find Me On:

[LinkedIn](https://linkedin.com/in/a-kash-singh) | [Portfolio](https://a-kash-singh.github.io/)

