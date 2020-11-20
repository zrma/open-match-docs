---
title: "Tutorials"
linkTitle: "Tutorials"
weight: 5
description: >
  Open Match Tutorials
---

해당 튜토리얼을 보려면 [release branch](https://github.com/googleforgames/open-match/blob/{{< param release_branch >}}/tutorials)를 확인하세요.
{{% alert title="Note" color="info" %}}
Minikube 사용자는 아래의 명령을 실행하여 Minikube에서 로컬의 도커 이미지를 사용하도록 설정합니다.

```bash
# Instructs Minikube to use local images
# https://kubernetes.io/docs/setup/learning-environment/minikube/#use-local-images-by-re-using-the-docker-daemon
eval $(minikube docker-env)
```
{{% /alert %}}