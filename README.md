# 🛡️ Guia de Estudos: Cibersegurança na era da informação

## 🎯 Contexto e Objetivos
Este projeto foi desenvolvido como parte do desafio prático da **DIO**, utilizando o **NotebookLM** para criar um caderno temático inteligente. O foco principal é entender como a cibersegurança protege ativos digitais em ambientes modernos, focando em infraestrutura e nuvem.

**Objetivos de Estudo:**
* Compreender a definição moderna de cibersegurança e seus pilares.
* Identificar tipos de ataques comuns (Malware, Phishing, Injeção).
* Diferenciar camadas de proteção: segurança de rede, de aplicações e de nuvem.

---

## 📚 Curadoria de Fontes
As fontes selecionadas representam o estado da arte na indústria de segurança:

1.  **Amazon Web Services (AWS):** [O que é Cibersegurança?](https://aws.amazon.com/pt/what-is/cybersecurity/) - Foco em segurança de infraestrutura.
2.  **Fortinet:** [Cyberglossary - Cybersecurity](https://www.fortinet.com/br/resources/cyberglossary/what-is-cybersecurity) - Excelente fonte para termos técnicos e glossário.
3.  **IBM:** [Think Topics - Cybersecurity](https://www.ibm.com/br-pt/think/topics/cybersecurity) - Foco em IA na segurança e visão executiva.

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

Para extrair o melhor da IA, documentei os testes de prompts realizados:

| Teste | Prompt Estratégico | Resultado / "Cicatriz" |
| :--- | :--- | :--- |
| **Prompt 1** | "O que é cibersegurança?" | **Resultado muito amplo.** A IA deu uma resposta de dicionário, focando apenas no conceito e não no ensino. Precisarei ser mais específico. |
| **Prompt 2** | "Com base nas fontes da AWS e IBM, quais são os 3 maiores desafios da segurança em nuvem hoje?" | **Resultado bom.** A IA focou em configurações incorretas, complexidade e falta de habilidade humana. |
| **Prompt 3** | "Atue como um Especialista em Segurança. Com base na Fortinet, crie um checklist de prevenção de Malware para empresas." | **Sucesso Total.** Gerou um guia prático com 5 passos técnicos, incluindo segmentação e resposta a incidentes. |

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **A Tríade CIA:** Toda a estratégia de segurança deve garantir a **Confidencialidade** (acesso restrito), **Integridade** (dados sem alteração) e **Disponibilidade** (sistemas ativos).
* **Tipos de Ameaças:** Aprendi que os ataques mais críticos hoje envolvem **Ransomware** (sequestro de dados) e **Engenharia Social** (foco na falha humana).



### 2. Glossário de Conceitos Aprendidos
* **Endpoint Security:** Proteção de dispositivos finais como laptops e celulares.
* **Zero Trust:** Modelo de segurança onde nenhum usuário ou sistema é confiável por padrão, exigindo verificação contínua.
* **Phishing:** Técnica de fraude para enganar usuários e roubar credenciais.
* **Firewall:** Barreira que monitora e filtra o tráfego de rede.

### 3. Prompts Reutilizáveis para Revisão
* *"Explique o modelo de Responsabilidade Compartilhada da AWS para um novo usuário."*
* *"Quais são os sinais comuns de um ataque de Engenharia Social mencionados nos documentos?"*
* *"Crie um quiz de 5 perguntas sobre os termos do glossário da Fortinet."*

---
✨ *Projeto desenvolvido por Kayque Maciel Saraiva para o portfólio DIO.*
