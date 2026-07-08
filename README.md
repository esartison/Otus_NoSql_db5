# Домашнее задание Сартисона Евгения N5 #
развернуть docker локально или в облаке

поднять 3 узловый Cassandra кластер.

Создать keyspase с 2-мя таблицами. Одна из таблиц должна иметь составной Partition key, как минимум одно поле - clustering key, как минимум одно поле не входящее в primiry key.

Заполнить данными обе таблицы.

Выполнить 2-3 варианта запроса использую WHERE

Создать вторичный индекс на поле, не входящее в primiry key.

(*) нагрузить кластер при помощи Cassandra Stress Tool (используя "How to use Apache Cassandra Stress Tool.pdf" из материалов).



## развернуть docker локально или в облаке ## 
запустил Minikube
<img width="1129" height="374" alt="image" src="https://github.com/user-attachments/assets/61c4f2c0-26dc-4563-927c-b467e1aa793f" />




## поднять 3 узловый Cassandra кластер. ## 
используем оператор [k8ssandra](https://github.com/k8ssandra/k8ssandra-operator)

## Создать keyspase с 2-мя таблицами. ## 


Одна из таблиц должна иметь составной Partition key, как минимум одно поле - clustering key, как минимум одно поле не входящее в primiry key.
Заполнить данными обе таблицы.


## Выполнить 2-3 варианта запроса использую WHERE ## 

## Создать вторичный индекс на поле, не входящее в primiry key. ## 


## (*) нагрузить кластер при помощи Cassandra Stress Tool (используя "How to use Apache Cassandra Stress Tool.pdf" из материалов). ## 




## Сама работа #

Выполнил самую базовую установку, с остальными пунктами не успеваю по времени. Документация закрытая, не так просто выполнить настройку.

Через VirtualBox поднял Minikube и создал CouchBase кластер через [Create a Couchbase cluster using Kubernetes](https://kubernetes.io/blog/2016/08/create-couchbase-cluster-using-kubernetes/)

Создать  master Replication Controller
```
root@course:~/couchbase/couchbase-kubernetes-master/cluster# cat cluster-master.yml 


Базовую настройку выполнил.



  
