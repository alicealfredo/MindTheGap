# MindTheGap: A Jornada do Estudante Global

> **Unidade Curricular:** Gamificação e Narrativas Interativas e Desenvolvimento Web Front | TDW  
> **Tema Selecionado:** Percurso Académico e Saúde Mental  
> **Estado Atual:** Fase 1 Concluída (Game Design Document & Arquitetura de Conceito)

---

## 📌 Visão Geral do Projeto

O **MindTheGap** é uma experiência web pedagógica, lúdica e sustentável desenvolvida para simular o desafio de gerir o sucesso académico, a saúde mental e o suporte social no ensino superior contemporâneo. 

A aplicação coloca o utilizador no papel de um estudante que precisa de equilibrar prazos críticos de trabalhos, projetos de grupo e a vida profissional ao longo de um semestre, enfrentando dilemas diários que impactam diretamente a sua energia e resiliência psicológica.

---

## 🎯 Objetivos do Sistema

O projeto foca-se em três pilares pedagógicos fundamentais:
* **Promover o Equilíbrio:** Evitar ciclos de exaustão e *burnout* causados pela exigência extrema de produtividade académica.
* **Literacia de Gestão de Tempo:** Ensinar a balancear o estudo individual com o trabalho colaborativo e o descanso estratégico.
* **Consciencialização:** Demonstrar que ações isoladas (como ignorar prazos ou negligenciar o descanso) geram consequências severas a médio e longo prazo.

---

## 👥 Personas e Públicos-Alvo

O sistema foi desenhado para diferentes perfis de jogadores/utilizadores:
* **Ana (A Perfecionista Exausta - *Achiever / Player*):** Focada em maximizar o desempenho académico, obter notas máximas e desbloquear insígnias rapidamente.
* **Lucas (O Trabalhador Full-Time / Sobrecarregado - *Free Spirit / Philanthropist*):** Focado em gerir a autonomia, equilibrar a vida profissional/pessoal com os estudos e apoiar a rede colaborativa.

---

## 🎮 Mecânicas e Dinâmicas (Framework 6D)

A experiência utiliza mecânicas inspiradas na Teoria da Autodeterminação (SDT) para manter o envolvimento:
* **Autonomia:** Liberdade total para escolher abordagens de estudo, colaboração ou pausas.
* **Competência:** Feedback quantitativo em tempo real através de barras de progresso (Desempenho e Saúde Mental).
* **Relacionamento:** Impacto das decisões de entreajuda com os colegas de grupo.
* **Efeito de "Névoa Mental":** Mecânica de alerta visual ativada automaticamente quando a saúde mental do estudante desce abaixo de um nível crítico.

---

## 🛠️ Arquitetura Técnica Planeada (Fase 2)

Embora esta primeira entrega foque o planeamento estratégico e o GDD, a arquitetura técnica já se encontra definida para a implementação em **Vue.js** e **Pinia**:
* **Store Global (Pinia):** Gestão de variáveis de estado como `desempenhoAcademico`, `saudeMental`, `unlockedBadges` e estados de alerta (`mentalFogActive`).
* **Camada Narrativa:** Consumo dinâmico de árvores de decisão estruturadas em formato JSON.

---

## 📁 Documentação e Links

* **Game Design Document (GDD - Parte 1):** Disponível no repositório (`docs/GDD_MindTheGap_Entrega01.pdf`).
* **Quadro de Organização:** Gerenciado via Notion.
