🚀 Projeto Aurora Siger: Sistema de Telemetria e Verificação de Missão Crítica
Este repositório contém o projeto desenvolvido para o curso de Ciência da Computação (FIAP). O objetivo é simular um sistema de controle de missão espacial, integrando processamento de telemetria, cálculos de autonomia energética e algoritmos de decisão automatizados.

📋 Descrição do Projeto
O Aurora Siger é uma implementação de um sistema de monitoramento de pré-lançamento. Ele utiliza lógica de programação para interpretar variáveis físicas de sensores simulados e determinar a viabilidade de uma decolagem com base em restrições de engenharia aeroespacial.

Principais Componentes:
Módulo de Telemetria: Processamento de dados de temperatura (interna/externa), pressão de tanques e integridade estrutural.

Algoritmo de Decisão: Fluxo lógico rigoroso que valida os critérios mínimos de segurança para evitar falhas catastróficas.

Análise Energética: Cálculo dinâmico de autonomia considerando a capacidade nominal, carga atual, consumo de ignição e dissipação/perdas do sistema.

* 🛠️ Especificações Técnicas:
* Linguagem: Python 3.x
* Parâmetros de Segurança (Constraints):
  * Temperatura Interna: $15^\circ C \leq T \leq 40^\circ C$
  * Temperatura Externa: $-150^\circ C \leq T \leq 100^\circ C$
  * Integridade Estrutural: Status Binário ($1 = Nominal$)
  * Nível de Energia: Mínimo de 85%
  * Pressão dos Tanques: 3000 < P < 4500 PSI
  * Módulos Críticos: Status redundante (Check: OK)

📈 Estrutura de Código e Execução
O projeto está estruturado em um Notebook Python (.ipynb), facilitando a visualização de dados e a documentação das etapas de cálculo.

Como executar:
Acesse o ficheiro relatorio.ipynb.

Execute as células sequencialmente.

O script irá gerar uma leitura de sensores aleatória e processar o veredito: PRONTO PARA DECOLAR ou DECOLAGEM ABORTADA.

🖥️ Demonstração de Execução
(Dica: Após rodar o código no Colab, tira um print do output final e cola aqui no README para mostrar o funcionamento)

📚 Documentação Adicional (Entrega FIAP)
O projeto contempla as seguintes etapas obrigatórias:

Algoritmo: Implementado via pseudocódigo e Python.

Análise Energética: Demonstração matemática da autonomia residual pós-lançamento.

Análise Assistida por IA: Classificação de riscos e identificação de anomalias nos dados coletados.

Reflexão Crítica: Análise sobre a ética no desenvolvimento de software de missão crítica e impactos da exploração espacial.

<img width="1072" height="703" alt="image" src="https://github.com/user-attachments/assets/cf5864f2-e063-41b8-9546-b2a254658aff" />
