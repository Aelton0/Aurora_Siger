🚀 Projeto Aurora Siger: Sistema de Telemetria e Verificação de Missão Crítica
Este repositório contém o projeto desenvolvido para o curso de Ciência da Computação (FIAP). O objetivo é simular um sistema de controle de missão espacial, integrando processamento de telemetria, cálculos de autonomia energética e algoritmos de decisão automatizados.

📋 Descrição do Projeto
O Aurora Siger é uma implementação de um sistema de monitoramento de pré-lançamento. Ele utiliza lógica de programação para interpretar variáveis físicas de sensores simulados e determinar a viabilidade de uma decolagem com base em restrições de engenharia aeroespacial.

Principais Componentes:
* Módulo de Telemetria: Processamento de dados de temperatura (interna/externa), pressão de tanques e integridade estrutural.

* Algoritmo de Decisão: Fluxo lógico rigoroso que valida os critérios mínimos de segurança para evitar falhas catastróficas.

* Análise Energética: Cálculo dinâmico de autonomia considerando a capacidade nominal, carga atual, consumo de ignição e dissipação/perdas do sistema.

* 🛠️ Especificações Técnicas:
* Linguagem: Python 3.x
* Parâmetros de Segurança (Constraints):
  * Temperatura Interna: $15^\circ C \leq T \leq 40^\circ C$
  * Temperatura Externa: $-150^\circ C \leq T \leq 100^\circ C$
  * Integridade Estrutural: Status Binário ($1 = Nominal$)
  * Nível de Energia: Mínimo de 85%
  * Pressão dos Tanques: 3000 < P < 4500 PSI
  * Módulos Críticos: Status redundante (Check: OK)
