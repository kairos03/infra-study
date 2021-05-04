# infra-study

## CE 기본
- REST API
- 암호화 (대칭키, 비대칭키) 
- Telnet vs SSH, FTP vs SFTP
- NAS, NFS
- json
- git, github
- OAuth2.0

## IaaS
1. ansible (https://blog.naver.com/alice_k106/221333208746)
  - ansible?
  - inventory
  - playbook

## 가상화 기초
0. 가상화란?
1. 전가상화, 반가상화, Container
2. 어떻게 리소스(cpu, memory, network, gpu)가 가상화 되는가?
3. virtual box?

## 클라우드
5. Docker
  - LXC(LinuX Container), UnionFS
  - Docker Daemon, Docker Client, Docker image, Docker registry, Docker Container
  - dockerfile?
  - Docker Container vs containerd vs CRI-O
  - nvidia-docker?
  -
  - 2048게임 image를 docker에서 돌려보기 (https://github.com/alexwhen/docker-2048)
  - nvidia-docker2 이용해서 pytorch 컨테이너 만들기, 간단한 학습 돌려보기. (https://hanseokhyeon.tistory.com/entry/Docker-Pytorch-GPU%EB%A1%9C-%EB%94%A5-%EB%9F%AC%EB%8B%9D-%EA%B0%9C%EB%B0%9C%ED%95%98%EA%B8%B0)
5.  Kubernetes(k8s).
  - k8s는 무엇인가? 왜 k8s가 필요한가? 출현 배경? (https://kubernetes.io/ko/docs/concepts/overview/what-is-kubernetes/)
  - k8s 컴포넌트 (https://kubernetes.io/ko/docs/concepts/overview/components/)
    - 컨트롤 플레인
    - 노드
    - 애드온
  - k8s API (https://kubernetes.io/ko/docs/concepts/overview/kubernetes-api/)
  - k8s 오브젝트 (https://kubernetes.io/ko/docs/concepts/overview/working-with-objects/) 
  - Workloads(Pod, Deployment, ReplicaSet, StatefulSet, DaemonSet, Job, CronJob) (https://kubernetes.io/ko/docs/concepts/workloads/)
  - 네트워킹 (Service, LoadBalancing, Ingress) (https://kubernetes.io/ko/docs/concepts/services-networking/)
  - 스토리지 (PV, PVC, SC, Dynamic Provisioning)
  - 구성 (ConfigMap, Secret) (https://kubernetes.io/ko/docs/concepts/configuration/)
  - 스케줄링과 축출 (스케줄러, 노드에 파드 할당, 테인트, 톨러레이션, drain, cordon) (https://kubernetes.io/ko/docs/concepts/scheduling-eviction/)
  - 쿠번네티스 기초 (https://kubernetes.io/ko/docs/tutorials/kubernetes-basics/)
  - gpu 할당하기(nvidia-device-plugin)
  -
  - k3s 설치 해보기
  - k8s에 2048게임 띄워보기
6. Helm
  - helm이란? helm 사용법. https://helm.sh/ko/docs/intro/using_helm/
  -
  - helm으로 wordpress 설치해보기

## Monitoring
1. Prometheus
  - promql 
2. Grafana
3. k8s에 적용하기 (kube-state-metrics)

## DB
1. SQL vs NoSQL
2. MySQL
3. MongoDB

## Web
1. node-js
### backend
1. express.js
2. mongoose
3. MVC 패턴
### frontend
1. Vue.js
2. Vuetify

## DevOps
1. CI/CD
  - Github Actions
  - Jenkins
