# pensamento_computacional_projeto
Nosso primeiro repositorio do Codigo da Transformaçao para o primeiro projeto
# 💇‍♂️ Beauty Manager - Sistema de Gestão de Salão

[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/status-concluido-green.svg)]()

Este projeto foi desenvolvido para a disciplina de **Pensamento Computacional**. O objetivo é aplicar estruturas de dados fundamentais do Python (Listas, Dicionários e Conjuntos) para resolver problemas reais de logística e finanças em um salão de beleza ou barbearia.

---

## 🚀 Funcionalidades

O sistema oferece uma interface interativa via terminal com as seguintes capacidades:

1.  **Fila de Espera (FIFO):** Gestão de chegada de clientes seguindo o conceito "Primeiro a entrar, primeiro a sair".
2.  **Fluxo de Atendimento:** Conversão de clientes em espera para atendimentos realizados, vinculando o serviço prestado.
3.  **Gestão de Preços:** Painel administrativo para consulta e alteração de valores de serviços (Corte, Barba, etc.) em tempo real.
4.  **Relatório de Variedade:** Identificação de quais tipos únicos de serviços foram realizados no dia, utilizando a lógica de **Sets** para evitar duplicidade.
5.  **Calculadora de Checkout:** Processamento de pagamentos com suporte a cálculos de descontos e acréscimos.

## 🛠️ Estruturas de Dados Utilizadas

Para garantir a eficiência do programa, foram aplicados os seguintes conceitos:

* **Listas (`list`):** Utilizadas para a fila de espera e histórico cronológico.
* **Dicionários (`dict`):** Mapeamento dinâmico de serviços e seus respectivos preços.
* **Sets (`set`):** Filtro inteligente para o relatório de serviços únicos prestados.
* **Laços e Condicionais:** Estrutura robusta de `while` e `if/elif/else` para controle do menu.

## 📋 Como Executar

1.  Certifique-se de ter o **Python 3.x** instalado.
2.  Clone o repositório:
    ```bash
    git clone [https://github.com/mich2009ags-creator/pensamento_computacional_projeto.git](https://github.com/mich2009ags-creator/pensamento_computacional_projeto.git)
    ```
3.  Navegue até o diretório do projeto e execute:
    ```bash
    python projeto_app_salao_beleza.py
    ```

## 📖 Exemplo de Uso

Ao iniciar o programa, você poderá:
* **Adicionar à Fila:** Registrar o nome do cliente que acaba de chegar.
* **Confirmar Atendimento:** Retirar o cliente da fila, escolher o serviço e calcular o valor final.
* **Alterar Preços:** Atualizar o valor de um serviço diretamente no menu administrativo.

---
**Desenvolvido por Mich2009ags** como projeto prático de programação em Python.
