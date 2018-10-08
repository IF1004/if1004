# Course Project Specification

## 2018.2
Neste semestre a temática do projeto deve tratar de algum(ns) aspecto(s) do desenvolvimento de uma aplicação, serviço ou solução de apoio ao paradigma DevOps, ou da Engenharia de Software Contínua, no ciclo de vida de software.

Vale ressaltar que o projeto tem **caráter puramente acadêmico e educacional**.

Para a estruturacao do seu projeto, leve em consideracao a utilizacao da abordagem [**Goal - Question - Metric**](https://en.wikipedia.org/wiki/GQM).

Maiores informaçoes sobre **GQM** podem ser obtidas nos links:

* [AGILE METRICS: A GQM APPROACH](https://www.leadingagile.com/2017/05/agile-metrics-gqm-approach/)
* [The Goal Question Metric Approach](https://github.com/IF1004/if1004/blob/master/GQM.pdf)
* [Goal-Question-Metric (GQM), prof. Eduardo Figueiredo (DCC/ICEx/UFMG)](https://homepages.dcc.ufmg.br/~figueiredo/disciplinas/lectures/goal-question-metric_v01.pdf)

### Sugestões de temas

1. Especificação e construção de um serviço/mecanismo de monitoramento e bilhetação de aplicações/serviços implantadas em um cluster [Swarm](https://docs.docker.com/engine/swarm/). Como sugestão utilizar o [Prometheus](https://docs.docker.com/config/thirdparty/prometheus/) e [Grafana](https://grafana.com/).
1. Especificação e construção de um serviço/mecanismo de oferta de um cluster [Swarm](https://docs.docker.com/engine/swarm/) como serviço, promovendo a separação lógica dos usuários. Discussão: você tem o usuário administrador do ecossistema, mas teria também usuários "normais", digamos assim. E um usuário não deve ter acesso logico aos outros, ou seja, uma arquitetura multi-inquilino.
1. Especificação e construção de um serviço/mecanismo de gestão de federações de cluster (multicluster) [Swarm](https://docs.docker.com/engine/swarm/) como serviço, ou seja, apoiar a conexão mais de um cluster Swarm para poder rodar essa oferta HA (alta disponibilidade).
1. Especificação e construção de um serviço/mecanismo de autoscaling para os containers em um cluster [Swarm](https://docs.docker.com/engine/swarm/). Basicamente é um mecanismo de saúde para garantir que se foi especificado que tenho que ter X containers rodando, vou ter sempre. E também para, se identificar que aumentou a demanda de alguma métrica, o mecanismo é responsável por aumentar tarde a quantidade de instâncias rodando. Sugestão utilizar o [Orbiter](https://github.com/gianarb/orbiter).
1. Especificação e construção de um serviço/mecanismo de proxy para federações de cluster (multicluster) [Swarm](https://docs.docker.com/engine/swarm/). Sugestão utilizar o [Traefik](https://traefik.io/).
1. Especificação e construção de um serviço/mecanismo de apoio a um pipeline de Integração e Implantação Contínua para aplicativos para dispositivos móveis.
1. Especificação e construção de um serviço/mecanismo de apoio a um pipeline de Integração e Implantação Contínua para aplicações de Internet das Coisas.
1. Especificação e construção de um serviço/mecanismo de apoio a um pipeline de Integração e Implantação Contínua para aplicações no contexto de Computação Ubíqua.
1. Especificação e construção de um serviço/mecanismo de apoio a um pipeline de Integração e Implantação Contínua para aplicações com arquitetura de microsserviços.

## 2017.2

### DevOps Aid Tool

#### Introduction 

This is a practical academic exercise to incentive the study of DevOps and Software Architecture.

#### Objectives
* Understanding motivations to adopt DevOps (Continuous Integration, Deployment, Delivering, Containerizing, among others)
* Using a scientific approach to detail deployment architectural design
* Promoting the adoption of tests during development step
* Promoting the knowledge of Deployment Pipeline
* Sharing tactics to support deployability, availability and scalability

#### Project

The project will address several aspects of the development of an application, service or solution supporting the DevOps paradigm in the software life cycle.

Students are expected to present and defend their project proposal in class, orally, according to the syllabus.
