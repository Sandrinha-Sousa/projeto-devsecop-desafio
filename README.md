# Desafio DevSecOps — Gerenciador de Tarefas

## Sobre o Projeto
Este repositório faz parte do desafio prático do módulo de DevSecOps da ADA Tech.
Você receberá este projeto com vulnerabilidades propositais e uma pipeline incompleta.
Seu objetivo é **implementar a pipeline de segurança** e **corrigir as vulnerabilidades**.

## Estado atual
A pipeline está **incompleta**. Os steps de segurança precisam ser implementados por você.

## Sua missão
1. Implementar os steps de segurança no `pipeline.yml`
2. Fazer a pipeline **quebrar** ao detectar os problemas
3. Corrigir as vulnerabilidades encontradas
4. Fazer a pipeline **passar** com tudo verde ✅
5. Documentar o funcionamento da pipeline neste README

## O que implementar
- [ ] Secrets Scanning com **Gitleaks**
- [ ] SAST com **Semgrep**
- [ ] SCA com **Grype**
- [ ] Deploy com **GitHub Pages**

## Como a pipeline funciona
> **Substitua este bloco pela sua explicação após implementar a pipeline.**
> Descreva cada step, o que ele faz e por que ele é importante para a segurança.
PASSO 3: Gitleaks (Secrets Scanning): identifica e previne a exposição de credenciais e chaves secretas no código-fonte.

PASSO 4: Semgrep (SAST): Analisa o código estático em busca de vulnerabilidades de segurança como o uso indevido de eval e falhas de XSS.

PASSO 5: Grype (SCA): Analisa as dependências do projeto no package.json para encontrar vulnerabilidades conhecidas em bibliotecas de terceiros.

## URL de Produção
> https://sandrinha-sousa.github.io/projeto-devsecop-desafio/
