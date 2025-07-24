# JM-Core: A Monorepo Showcase for Software Architecture

Este repositório é um monorepo que serve como um laboratório e showcase para arquitetura de software moderna utilizando Java, Spring e padrões de projeto avançados.

## Estrutura

Todos os projetos e serviços vivem dentro do diretório `/services`. A configuração de build e as dependências são gerenciadas de forma centralizada pelo `pom.xml` na raiz do projeto.

## Como Construir o Projeto Inteiro

Para compilar, testar e empacotar todos os serviços de uma vez, execute o seguinte comando na raiz do repositório:

```bash
mvn clean install
```