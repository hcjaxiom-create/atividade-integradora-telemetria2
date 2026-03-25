# Atividade Integradora – Relatório Operacional de Pré-Decolagem

## Explicação do projeto

Este projeto foi desenvolvido para a Atividade Integradora da disciplina, com foco na análise operacional de pré-decolagem de uma nave fictícia chamada **Asterion V**. O objetivo foi simular o uso de dados de telemetria para verificar se a nave apresenta condições seguras para realizar a decolagem.

No notebook foram trabalhados os seguintes pontos:

- **1.1 Organização e descrição da telemetria**
- **1.2 Algoritmo de verificação**
- **1.3 Script em Python**
- **1.4 Análise energética**
- **1.5 Análise assistida por IA**
- **1.6 Reflexão crítica**

---

## Dados utilizados no projeto

Os dados simulados de telemetria utilizados no notebook foram:

- **Temperatura interna:** 23 °C  
- **Temperatura externa:** 32 °C  
- **Integridade estrutural:** 1  
- **Nível de energia:** 84%  
- **Pressão dos tanques:** 96 psi  
- **Módulo de navegação:** operacional  
- **Módulo de comunicação:** operacional  
- **Módulo de propulsão:** operacional  
- **Módulo de controle:** operacional  

Esses dados foram definidos para representar uma condição operacional segura de pré-decolagem.

---

## Prints da execução

### Execução do script de verificação

```python
=== DADOS DE TELEMETRIA ===
Temperatura interna: 23 °C
Temperatura externa: 32 °C
Integridade estrutural: 1
Nível de energia: 84%
Pressão dos tanques: 96 psi
Módulo de navegação: operacional
Módulo de comunicação: operacional
Módulo de propulsão: operacional
Módulo de controle: operacional

=== RESULTADO DA VERIFICAÇÃO ===
PRONTO PARA DECOLAR

=== ANÁLISE ENERGÉTICA ===
Capacidade total: 1000 kWh
Carga atual: 84%
Consumo estimado na decolagem: 250 kWh
Perdas energéticas: 5%

Energia disponível inicial: 840.00 kWh
Perdas energéticas: 42.00 kWh
Energia útil após perdas: 798.00 kWh
Autonomia inicial após decolagem: 548.00 kWh

=== ANÁLISE ASSISTIDA POR IA ===

Classificação dos dados: Condição operacional adequada
Possíveis anomalias: Nenhuma anomalia crítica identificada

Sugestões de risco:
- Nível de energia em condição segura.
- Pressão dos tanques em condição estável.
- Temperatura externa em condição aceitável.
- Manter supervisão contínua dos módulos críticos até a autorização final de decolagem.

Instruções de execução do código

O projeto foi desenvolvido no Google Colab, mas também pode ser executado em ambiente Jupyter Notebook.

Executando no Google Colab
Acesse o arquivo .ipynb disponível neste repositório.
Faça upload do notebook no Google Colab ou abra diretamente por lá.
Execute as células em ordem, do início ao fim.
Verifique as saídas geradas em cada etapa.
Executando localmente
Instale o Python 3.
Instale o Jupyter Notebook ou JupyterLab.
Baixe o arquivo .ipynb deste repositório.
Abra o terminal na pasta do projeto.
Execute o comando:
