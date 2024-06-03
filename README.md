### This READ.md template was written based on this [repository](https://github.com/FernandoSchett/github_readme_template).

<div align="center" style="line-height: 0.5">

# Relatório SESAB
## Etapa A/Cenário 1
## Entrega 04/06

</div>

<table style="border: none;">
  <tr>
    <td align="left" style="padding-right: 90px; border: none;">
      <a href="link_for_website">
        <img height="125em" src="./assets/SESAB.png" border="0" />
      </a>
    </td>
    <td align="right" style="padding-left: 90px; border: none;">
      <a href="link_for_website">
        <img height="125em" src="./assets/ufba-logo.png" border="0" />
      </a>
    </td>
  </tr>
</table>


<div align="center">

## Integrantes do Grupo:
Adrielly Silva Ferreira de Oliveira
Danilo Oliveira Andrade
Diego Quadros dos Santos Dias
Gabriel Sinzinio Bonfim Cruz
Guilherme Castro Hora Fontes
Gustavo Jorge Novaes Silva
João Victor Leahy de Melo

</div>

## Objetivo da Etapa A/Cenário 1:
Este relatório contempla uma das entregas que devem ser realizadas para a matéria <div align="center">

**ADML - 43: ACCS: Oficina de Projetos em Inteligência Artificial**

</div>

Este relatório em específico especifica a criação de um modelo de aprendizado de máquina que, a partir dos dados disponibilizados pela SESAB, deve ser capaz de responder a seguinte pergunta:

<div align="center">

**Este indivíduo foi diagnosticado com dengue com base nos dados disponíveis?**

</div>

Para tanto, seguimos algumas regras estabelecidas pelos professores coordenadores da matéria:

- **Pré-Processamento Livre**
- **Algoritmos com hiperparâmetros definidos**
  - *K-Nearest Neighbors (KNN)*
    - Número de Vizinhos (K): Comece com K=5, podendo ser ajustado por meio de validação cruzada.
    - Métrica de Distância: Euclidiana.
    - Peso das amostras: Uniforme.
  - *Árvore de Decisão*
    - Critério de Divisão: Entropia.
    - Profundidade Máxima: Sem limite inicial, ajustável com validação cruzada.
    - Número Mínimo de Amostras para Divisão de um Nó: 2.
    - Número Mínimo de Amostras em um Nó Folha: 1
  - *Rede Neural (Multilayer Perceptron - MLP)*
    - Número de Camadas Ocultas:  2 camadas.
    - Número de Neurônios em Cada Camada Oculta: 100 neurônios.
    - Função de Ativação: ReLU.
    - Solver (Algoritmo de Otimização): Adam.
    - Taxa de Aprendizado: 0.001.
    - Número de Épocas: 200.
    - Tamanho do Lote: 32.
  - *Logistic Regression (Regressão Logística)*
    - Solver: lbfgs.
    - Penalidade: L2.
    - Máximo de Iterações: 100.
  - *Random Forest (Floresta Aleatória)*
    - Número de Árvores na Floresta: 100.
    - Critério de Divisão: Entropia.

Dessa forma, os entregáveis para 04/06 são:
- **Estatística descritiva com distribuição dos dados, padrões e outliers;**
- **Divisão dos conjuntos de treino, teste e validação;** 
- **Validação dos algoritmos com métricas de P, R e F1;**
- **Deploy em um container e conexão com dados;**
