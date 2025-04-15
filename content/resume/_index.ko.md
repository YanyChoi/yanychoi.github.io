---
date: '2025-04-15T11:59:58+09:00'
title: '최용환 - Yany Choi'
---

## **Summary**
- 클라우드 네이티브 환경에서의 인프라 설계 및 운영에 전문성을 보유한 SRE
- AWS, Kubernetes 기반 시스템의 안정성 향상과 비용 최적화에 강점
- 한국어/영어 이중언어 구사 (미국 5년 거주)

<br />

## **Work Experiences**
### **당근페이** (강남구, 서울특별시)
**Site Reliability Engineer, 인프라팀** 2024.07 -
- Kubernetes
  - Karpenter 도입 + HPA 삽입으로 월 비용 10,000$ 감축
    - Karpenter 스케줄링 로직 관련 [사내 블로그 투고](https://medium.com/daangn/karpenter-%ED%8A%B8%EB%9F%AC%EB%B8%94%EC%8A%88%ED%8C%85-%EB%B9%84%EC%9A%A9%EA%B3%BC-%EC%95%88%EC%A0%95%EC%84%B1-%EB%91%90%EB%A7%88%EB%A6%AC-%ED%86%A0%EB%81%BC-%EC%9E%A1%EA%B8%B0-ce8bd45ec8f2)
    - 서비스 워크로드들에 Disruption 과정에 안정성을 더하기 위해 Disruption Controller 개발
  - Istio 환경 개선
    - 버전 업그레이드 방식을 Canary로 변경해 다운타임 제로 실현
    - Istio AttributeGen 도입, EnvoyFilter 추가로 메트릭 맥락 개선
    - Istio에 강하게 Coupling된 리소스를 위한 Helm Chart 작성, ArgoCD ApplicationSet을 통해 관리
  - Mimir 도입으로 메트릭 파이프라인 HA 구성 및 AZ 간 통신 최소화로 비용 절감
- AWS 네트워크 구조 개편
  - 각 VPC로 분리되어 있던 네트워크 구조를 Centralized VPC를 통해 트래픽을 통제하도록 구성
  - AWS Network Firewall 도입을 통해 기존에 NACL + SG를 통해 관리하던 Outbound, Inbound 트래픽을 Suricate Rule로 통제하도록 개선
  - VPC 간 트래픽 이동을 중앙화된 TGW에 트래픽 특성 별 라우팅 테이블을 분리해 최소한의 변경사항으로 라우팅 설정이 가능하도록 조치

**DevOps Engineer, Intern, 인프라실** 2023.06 - 2023.08
- 커밋, 컨테이너 이미지, Jira 티켓, Slack 메시지 통합 배포툴 리팩토링 및 UI 개발
- 신규 서비스 출시 및 기존 서비스의 성능 개선을 위한 부하 테스트 설계 및 수행
- GitHub Action runner의 `Amazon Linux` -> `Ubuntu 22.04` 마이그레이션 참여


### **(주)피키** (마포구, 서울특별시)
**Software Engineer Intern, Dev Team** 2022.03 - 2022.09
- 프론트엔드 -> 데브옵스 -> 백엔드 순으로 업무 확장
- 모놀리식 백엔드를 마이크로서비스로 분리하여 EC2에서 AWS ECS + Fargate로 이전, 다운타임 하루 약 1시간에서 5분으로 **90% 감소**
- CI/CD 파이프라인 구성 및 인프라 관리 (GitHub Actions, Terraform)
- 신규 인플루언서 플랫폼 웹앱 개발 및 배포 (Next.js, FastAPI)
- Next.js 웹앱 유지보수 및 신규 컴포넌트 개발

<br />

## **Activities**

### **K8s 공식문서 번역**
-  1.27 버전 한글화 번역 참가

### **Poppin'** (대학교 졸업작품) 2023.06 - 2024.04
**인구밀도와 트렌드 장소를 하이라이트하는 인터랙티브 지도 서비스**
- CI/CD (Github Actions), 인프라 구축 및 관리
- ArgoCD로 클러스터 GitOps 시스템 구축
- k8s 클러스터 위에 OpenTelemetry 기반 모니터링 스택 (Grafana, Prometheus, Tempo, Loki) 구축
- 별도 DNS 서버 구축으로 유플러스 공유기의 NAT 헤어핀 미지원 이슈 해결 [(블로그)](https://velog.io/@yhc0818/%EA%B0%80%EB%82%B4%EC%88%98%EA%B3%B5%EC%97%85-%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0-%ED%97%A4%EC%96%B4%ED%95%80-NAT-%EC%9D%B4%EC%8A%88-%ED%95%B4%EA%B2%B0)

<br />

## **Certificates**
- AWS Solutions Architect - Associate (July 2023)   [(Credly)](https://www.credly.com/badges/c5bfe72a-461b-47e6-a0e1-3934968f717d)
- Certified Kubernetes Administrator (March 2024)   [(Credly)](https://www.credly.com/badges/fe5a9899-00d8-438f-a8d2-7b79fa3fe986)
- Certified Kubernetes Application Developer (April 2024)   [(Credly)](https://www.credly.com/badges/a417e062-cc35-44e6-a8aa-64081d56728e)
- Terraform Associate (April 2025)

<br />

## **Education**
### **소프트웨어학과 학사, 가천대학교** (성남시, 경기도) 2019.03 - 2025.02
- GPA 3.82/4.5
- 2022년 2학기 GPA 4.5 만점으로 전액장학금 수령

<br />

## **Contacts**
- **Phone**: (+82) 10-9465-9818
- **Email**: yhc000818@gmail.com
- [**Github**](https://github.com/YanyChoi)
- [**Linkedin**](https://linkedin.com/in/yany-choi)
- [**Blog**](https://velog.io/@yhc0818)
