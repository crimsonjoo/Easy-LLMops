# Easy-LLMops

## 소개
이 프로젝트는 LLMops(대형 언어 모델 운영)를 위한 첫걸음으로, MLflow, RabbitMQ, RAY, vLLM, PyTorch 등을 활용하여 기본적인 개념을 학습할 수 있도록 설계되었습니다. 이를 통해 모델의 관리, 배포 및 작업 스케줄링 등에 대해 다루며, LLMops 환경에서 필수적인 도구들을 익힐 수 있습니다.

## 주요 구성 요소
### CI-CD system
#### 1. ChatGPT API
#### 2. HF transformer Library
#### 3. Docker Image(AWS:ECR, GCP:GCR)
#### 4. Docker Container(AWS;ECS)
#### 5. Kubernetes (AWS:EKS, GCP:GKE)
#### 6. Github Action (CI/CD pipeline)
#### 7. Monitor (Whylog-Langkit)
#### 8. Cloud Platform (GCP, AWS)
---
### Distributed system
#### 1. MLflow
- **MLflow**는 머신러닝 모델의 라이프사이클 관리를 위한 오픈소스 플랫폼입니다.
- **주요 기능**: 실험 추적, 모델의 버전 관리, 모델의 배포 및 저장소 기능.
- **중요 포인트**: 실험과 모델의 기록을 남기고, 다양한 플랫폼에 배포할 수 있습니다.

#### 2. RabbitMQ
- **RabbitMQ**는 메시지 브로커로서, 애플리케이션 간의 비동기 통신을 가능하게 합니다.
- **주요 기능**: 메시지 큐잉, 애플리케이션 간의 데이터 전송.
- **중요 포인트**: 대규모 분산 시스템에서 필수적인 역할을 하며, 안정적인 데이터 흐름을 보장합니다.

#### 3. RAY
- **RAY**는 분산 컴퓨팅을 지원하는 프레임워크로, 대규모 머신러닝 모델 학습에 유용합니다.
- **주요 기능**: 분산 처리를 통한 빠른 학습 및 확장성.
- **중요 포인트**: 클러스터 환경에서 여러 작업을 동시에 처리할 수 있습니다.

#### 4. vLLM
- **vLLM**은 대규모 언어 모델의 효율적인 실행을 위해 설계된 라이브러리입니다.
- **주요 기능**: 대규모 모델의 메모리 효율성 최적화.
- **중요 포인트**: 제한된 자원에서 대형 모델을 실행할 때 특히 유용합니다.

#### 5. PyTorch
- **PyTorch**는 딥러닝 모델을 구축하고 학습하는 데 널리 사용되는 프레임워크입니다.
- **주요 기능**: 동적 그래프 지원, GPU 가속화 학습.
- **중요 포인트**: 연구 및 실무 모두에 사용될 수 있는 강력한 유연성을 제공합니다.

## 설치 및 사용법
1. 프로젝트를 클론합니다:
   ```bash
   git clone https://github.com/crimsonjoo/Easy-LLMops.git
