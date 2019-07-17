# valve-kops

kops 명령을 사용해서 쿠버네티스 클러스터 설치를 돕는 CUI 도구 입니다.

해당 프로젝트는 [kops-cui](https://github.com/opsnow/kops-cui)의 kops 설치 구현 부분을 분리해서 진행하는 프로젝트입니다. 

* Support Cloud
  * AWS
* Support OS
  * MacOS
  * Linux (centos, ubuntu ...)

## 기능

* kops를 통한 쿠버네티스 설치
* kops 클러스터 운영
** Get Cluster
** Edit Cluster
** Update Cluster
** Rolling Update
** Validate Cluster
** Export Kube Config
** Change SSH key

## 사용 방법

```bash
$ git clone https://github.com/opsnow-tools/valve-kops
$ ./helm.sh
```
TBD