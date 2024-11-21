# CKS (Certified Kubernetes Security Specialist) 스터디 가이드

CKS(Certified Kubernetes Security Specialist) 자격증 준비를 위한 리포지토리입니다. 이곳에서는 학습 자료, 실습 예제, 유용한 팁 등을 제공하여 Kubernetes 환경 보안에 대한 실무 능력을 강화할 수 있습니다.

---

## 📘 CKS 자격증 소개

**CKS**는 Kubernetes 환경 보안을 테스트하는 실무 중심의 자격증입니다. Kubernetes 관리 경험과 보안 베스트 프랙티스에 대한 지식이 요구됩니다.

### 시험 정보
- **시험 시간:** 2시간
- **시험 형식:** 실습 기반 (핸즈온 과제)
- **응시 조건:** 유효한 CKA(Certified Kubernetes Administrator) 자격증 보유
- **시험 주제:**
  - 클러스터 설정 및 구성
  - 워크로드 보안
  - 네트워크 정책
  - 런타임 보안
  - 모니터링 및 로깅

공식 정보는 [CKS Certification Page](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/)에서 확인하세요.

---

## 📋 리포지토리 구조

이 리포지토리는 다음과 같은 구조로 구성되어 있습니다:


---

## 🛠 사전 준비

시작하기 전에 다음을 준비하세요:
- 유효한 **CKA 자격증**
- Kubernetes 기본 개념 이해 (Pod, Deployment, Service 등)
- Kubernetes 클러스터 접근 권한 (minikube, kind, 또는 클라우드 프로바이더 사용)

---

## 🔍 학습 주제 및 자료

### 1. 클러스터 설정
- 안전한 etcd 클러스터 설정
- 감사 로그(Audit Logs) 활성화
- RBAC 및 접근 제어

### 2. 워크로드 보안
- 안전한 Pod 구성
- Secrets 및 ConfigMap 관리
- Kubernetes Admission Controller 이해

### 3. 네트워크 보안
- NetworkPolicy 설정
- Ingress 및 Egress 트래픽 보안
- 서비스 메시(Service Mesh) 기본

### 4. 런타임 보안
- AppArmor/SELinux로 컨테이너 보안 강화
- 런타임 보안 모니터링 구현
- 위협 탐지 및 대응

### 5. 모니터링 및 로깅
- 로깅 및 모니터링 도구 설정
- Falco, Prometheus, ELK 스택 활용

---

## 🚀 시작하기

1. **리포지토리 클론**
   ```bash
   git clone https://github.com/yourusername/cks-study-guide.git
   cd cks-study-guide


