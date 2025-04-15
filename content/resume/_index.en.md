---
date: '2025-04-15T11:59:58+09:00'
title: 'Yany Choi'
---

## **Summary**
- SRE specialized in infrastructure design and operations in cloud-native environments
- Proven track record in improving reliability and cost optimization of AWS and Kubernetes-based systems
- Broad technical expertise spanning frontend, backend, and DevOps
- Bilingual in Korean and English (5 years of residence in the U.S.)

<br />

## **Work Experiences**

### **Danggeun Pay** (Gangnam-gu, Seoul)
**Site Reliability Engineer, Infrastructure Team** Jul 2024 - Present
- **Kubernetes**
  - Reduced monthly costs by $10,000 through Karpenter adoption and HPA implementation
    - Published [internal blog post](https://medium.com/daangn/karpenter-%ED%8A%B8%EB%9F%AC%EB%B8%94%EC%8A%88%ED%8C%85-%EB%B9%84%EC%9A%A9%EA%B3%BC-%EC%95%88%EC%A0%95%EC%84%B1-%EB%91%90%EB%A7%88%EB%A6%AC-%ED%86%A0%EB%81%BC-%EC%9E%A1%EA%B8%B0-ce8bd45ec8f2) on Karpenter scheduling logic
    - Developed Disruption Controller to enhance service workload stability during disruption processes
  - Enhanced Istio environment
    - Achieved zero downtime by implementing Canary deployment for version upgrades
    - Improved metric context through Istio AttributeGen and EnvoyFilter implementation
    - Created Helm Charts for Istio-coupled resources, managed via ArgoCD ApplicationSet
  - Implemented Mimir for HA metric pipeline, reducing costs through minimal inter-AZ communication
- **AWS Network Architecture Redesign**
  - Restructured network architecture to control traffic through Centralized VPC
  - Enhanced traffic control by replacing NACL + SG with AWS Network Firewall using Suricate Rules
  - Optimized inter-VPC routing through centralized TGW with traffic-specific routing tables

**DevOps Engineer, Intern, Infrastructure Division** Jun 2023 - Aug 2023
- Refactored and developed UI for integrated deployment tool combining commits, container images, Jira tickets, and Slack messages
- Designed and executed load tests for new service launches and performance improvements
- Participated in GitHub Action runner migration from `Amazon Linux` to `Ubuntu 22.04`

### **Picky, Inc.** (Mapo-gu, Seoul)
**Software Engineer Intern, Dev Team** Mar 2022 - Sep 2022
- Expanded role progression: Frontend → DevOps → Backend
- Reduced downtime by 90% (from ~1 hour to 5 minutes daily) by migrating monolithic backend from EC2 to AWS ECS + Fargate
- Established CI/CD pipelines and managed infrastructure (GitHub Actions, Terraform)
- Developed and deployed new influencer platform web app (Next.js, FastAPI)
- Maintained Next.js web app and developed new components

<br />

## **Activities**

### **K8s Official Documentation Translation**
- Contributed to Korean localization for version 1.27

### **Poppin'** (University Graduation Project) Jun 2023 - Apr 2024
**Interactive Map Service Highlighting Population Density and Trending Locations**
- Managed CI/CD (Github Actions) and infrastructure
- Implemented cluster GitOps system using ArgoCD
- Deployed monitoring stack (Grafana, Prometheus, Tempo, Loki) with OpenTelemetry on k8s cluster
- Resolved LG U+ router NAT hairpin limitation by implementing custom DNS server [(Blog)](https://velog.io/@yhc0818/%EA%B0%80%EB%82%B4%EC%88%98%EA%B3%B5%EC%97%85-%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0-%ED%97%A4%EC%96%B4%ED%95%80-NAT-%EC%9D%B4%EC%8A%88-%ED%95%B4%EA%B2%B0)

<br />

## **Certificates**
- AWS Solutions Architect - Associate (July 2023)   [(Credly)](https://www.credly.com/badges/c5bfe72a-461b-47e6-a0e1-3934968f717d)
- Certified Kubernetes Administrator (March 2024)   [(Credly)](https://www.credly.com/badges/fe5a9899-00d8-438f-a8d2-7b79fa3fe986)
- Certified Kubernetes Application Developer (April 2024)   [(Credly)](https://www.credly.com/badges/a417e062-cc35-44e6-a8aa-64081d56728e)
- Terraform Associate (April 2025)

<br />

## **Education**
### **B.S. in Software Engineering, Gachon University** (Seongnam, Gyeonggi-do) Mar 2019 - Feb 2025
- GPA: 3.82/4.5
- Awarded full scholarship for achieving perfect GPA (4.5) in Fall 2022

<br />

## **Contacts**
- **Phone**: (+82) 10-9465-9818
- **Email**: yhc000818@gmail.com
- [**Github**](https://github.com/YanyChoi)
- [**Linkedin**](https://linkedin.com/in/yany-choi)
- [**Blog**](https://velog.io/@yhc0818)
