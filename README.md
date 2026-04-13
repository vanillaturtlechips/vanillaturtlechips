# 안녕하세요! 엔지니어 이명일입니다!

제 GitHub 프로필에 오신 것을 환영합니다.

---

## 자기소개

새로운 기술을 만날 때마다 심장이 뛰는 엔지니어, **이명일**입니다.

보안 관제에서 시작된 왜?라는 질문을 품고 개발의 세계로 뛰어들었습니다.  
문제를 발견하는 것을 넘어, 직접 코드로 해결하고 더 나은 시스템을 만드는 과정에서 큰 성취감을 느낍니다.  
클라우드 인프라와 ML이 만나는 지점에서 생기는 문제들을 특히 좋아하고, 도전적인 과제를 해결하는 데 열정을 쏟고 있습니다.

---

## 기술 스택

**Languages**
- GoLang, Python, TypeScript, PyTorch, Flask, FastAPI

**Cloud & Infra**
- Linux, Docker, Kubernetes, AWS, Terraform, Oracle Cloud

**DevSecOps**
- GitHub Actions, ArgoCD, Helm Chart

**Learning**
- Node.js, Next.js, Spring, Rust, Ray Serve

---

## 대표 프로젝트

### [HoneyBeePF](https://honeybeepf.io) — Rust 기반 경량 eBPF 관측성 플랫폼
> AI 워크로드의 비용·성능 병목을 파악하기 위해 LLM 토큰 사용량과 시스템 메트릭을 커널 레벨에서 수집하는 플랫폼입니다.  
> 코드 수정 없이 프로세스 생명주기를 추적하며, Kubernetes(Helm)와 전통적인 AI 데이터센터 환경 모두에 배포할 수 있습니다.  
> `Rust` `eBPF` `Kubernetes` `Helm` `Terraform` `GitHub Actions`

### [PawFiler ML Pipeline](https://github.com/vanillaturtlechips) — AI 생성 영상 탐지 플랫폼
> "이 영상은 Sora로 만들어졌습니다 (87%)"와 같은 설명 가능한 판별 결과를 제공하는 교육 플랫폼입니다.  
> 35개 클래스(AI 모델 23종 포함) 다중 분류, SageMaker 분산 학습, Ray Serve 멀티 에이전트 서빙까지 전체 ML 파이프라인을 구축했습니다. 현재 Macro F1 0.8561 달성.  
> `Python` `PyTorch` `AWS SageMaker` `Ray Serve` `XGBoost` `EfficientNet` `EKS`

### [G.U.S.S](https://github.com/vanillaturtlechips) — 헬스장 예약 및 실시간 혼잡도 관리 서비스
> AWS 3-Tier 아키텍처(Nginx → Go WAS → RDS) 위에 구축한 서비스입니다.  
> ASG와 ALB를 활용한 고가용성 인프라를 Terraform으로 코드화하고, SQS FIFO와 Lambda를 통한 비동기 예약 처리 구조를 구현했습니다.  
> `Go` `AWS EC2` `ALB` `ASG` `RDS MySQL` `DynamoDB` `SQS` `Lambda` `Terraform`

### [12-STREETS](https://github.com/vanillaturtlechips/12-streets) — Kubernetes 기반 이커머스 플랫폼
> Spring(Tomcat) 기반 회원·게시판 서비스를 Kubernetes 위에 배포하고, HPA를 통한 자동 확장과 부하 테스트로 안정적인 트래픽 처리 구조를 검증했습니다.  
> `Java` `Spring MVC` `Kubernetes` `HPA` `Nginx` `AWS ECR` `MetalLB`

### [SoftBank Hackathon](https://github.com/vanillaturtlechips) — DevSecOps CI/CD 파이프라인 구축
> 5개 마이크로서비스로 구성된 PaaS 플랫폼에 Trivy(SCA)와 Semgrep(SAST)을 통합한 DevSecOps 파이프라인을 구축했습니다.  
> GitHub Actions 파이프라인 실행 시간을 5분 30초 → 3분 12초로 단축했습니다.  
> `Java` `Spring Cloud` `Docker` `GitHub Actions` `Trivy` `Semgrep` `AWS EC2` `Gradle`

### [Intellisia Platform](https://github.com/GRPC-OK/Intellisia) — DevSecOps 통합 개발 플랫폼
> GitHub 저장소를 연결하면 코드 분석 → 빌드 → 보안 스캔 → 승인 → Kubernetes 배포까지 전체 파이프라인을 자동화하는 플랫폼입니다.  
> Semgrep(SAST), Trivy(SCA) 결과를 시각화하고 ArgoCD GitOps 방식으로 배포를 관리합니다.  
> `Next.js` `TypeScript` `Kubernetes` `ArgoCD` `Helm` `GitHub Actions` `Semgrep` `Trivy`

### [AI 유해 콘텐츠 필터링](https://github.com/vanillaturtlechips/2024_ai_con) — 한국어 유해 발화 탐지 서비스
> 한국어 유해 발화 데이터셋을 활용해 게시판의 욕설·혐오 표현을 실시간으로 탐지하고 차단하는 Flask 기반 웹 서비스입니다.  
> 2단계 탐지 파이프라인(금지어 사전 검사 → 패턴 매칭)으로 오탐을 최소화했습니다.  
> `Python` `Flask` `MySQL` `SQLAlchemy`

### [Vulnerability Script](https://github.com/vanillaturtlechips) — 보안 취약점 점검 자동화
> KISA 주요정보통신기반시설 보안 취약점 점검 가이드 기준 19개 항목을 Shell Script로 자동화한 프로젝트입니다.  
> 점검 결과를 [양호] / [취약] / [의심] 3단계로 자동 출력합니다.  
> `Shell Script` `Ubuntu` `Linux` `Security`

### [Malware Analysis](https://github.com/vanillaturtlechips) — 악성코드 정적·동적 분석
> 가상화된 격리 환경에서 랜섬웨어, 트로이목마, 미레이 봇넷 등 3종을 분석하고 실무 형식의 보고서를 작성했습니다.  
> `VMware` `Wireshark` `PEStudio` `dnspy` `IDA Free` `Regshot`

### [Datalocker](https://github.com/vanillaturtlechips/datalocker) — 파일 암복호화 보안 솔루션
> 개인 데이터 파일 및 폴더 암복호화를 통한 데이터 유출 위험을 최소화하는 보안 솔루션입니다.  
> Python/Tkinter 초기 구현에서 Go/Wails 기반으로 리팩토링하며 AES-256-GCM + PBKDF2-SHA256으로 업그레이드했습니다.  
> `Go` `Wails` `AES-256-GCM` `PBKDF2` `GORM` `Python` `Fernet`

### [Security Infra Setup](https://github.com/vanillaturtlechips) — 보안 네트워크 인프라 구축
> iptables와 Snort를 이용해 패킷 필터링 및 침입탐지 기능을 구현한 프로젝트입니다.  
> VMware 가상 환경에서 WAN / DMZ / 내부망을 분리한 3-tier 네트워크를 설계했습니다.  
> `Linux` `iptables` `Snort IDS` `VMware` `Wireshark` `Shell Script`

### [Gopra Portfolio](https://myong12.site) — React + Go 포트폴리오 사이트
> React, Go, Docker로 구축한 인터랙티브 포트폴리오 사이트입니다.  
> Docker Multi-stage build로 이미지 크기를 1.2GB → 30MB로 경량화하고, GitHub Actions CI/CD 파이프라인을 구축했습니다.  
> `Go` `React` `Docker` `Terraform`

---

## GitHub 통계

![vanillaturtlechips's GitHub stats](https://github-readme-stats.vercel.app/api?username=vanillaturtlechips&show_icons=true&theme=radical)

---

## 연락하기

- **Email:** [wkdqkdgud@gmail.com](mailto:wkdqkdgud@gmail.com)
- **LinkedIn:** [이명일](https://www.linkedin.com/in/%EB%AA%85%EC%9D%BC-%EC%9D%B4-342075399/)

---

> 방문해주셔서 감사합니다!
