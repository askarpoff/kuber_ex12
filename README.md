# Домашнее задание к занятию «Установка Kubernetes»

### Цель задания

Установить кластер K8s.
-----

### Задание 1. Установить кластер k8s с 1 master node

1. Подготовка работы кластера из 5 нод: 1 мастер и 4 рабочие ноды.
2. В качестве CRI — containerd.
3. Запуск etcd производить на мастере.
4. Способ установки выбрать самостоятельно.

### Ответ:

Развернул 5 ВМ на Ubuntu, установил через kubeadm

![image](https://github.com/askarpoff/kuber_ex12/assets/108946489/3fe24c36-5c92-4be7-aac1-dc0f5a532cd7)

![image](https://github.com/askarpoff/kuber_ex12/assets/108946489/d0f25d18-aba1-4465-9256-c9cb400e31ce)

Большое количество рестартов - не сразу настроил использование cgroups в /etc/containerd/config.toml
