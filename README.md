# 🤖 Automação de Coleta de Dados de Municípios do IBGE

Este projeto é um robô de automação de processos (RPA) desenvolvido com **UiPath Studio**. O objetivo é extrair dados públicos de municípios brasileiros diretamente do portal [IBGE Cidades](https://cidades.ibge.gov.br/) e consolidá-los de forma organizada.

Este robô foi criado como solução para um desafio técnico para uma vaga de Desenvolvedor RPA.

## ✨ Funcionalidades Principais

* **Entrada de Dados Flexível:** Solicita ao usuário uma lista de um ou mais municípios, separados por vírgula.
* **Navegação Autônoma:** Percorre o site do IBGE, localizando a página de cada município informado.
* **Extração Precisa de Dados:** Coleta as seguintes informações para cada cidade:
    * Nome do prefeito
    * População no último censo [2022]
    * Aniversário da cidade
    * Área da unidade territorial [2023]
* **Relatório Final:** Gera um arquivo `.txt` com todos os dados coletados, formatados para fácil leitura.

## 💻 Tecnologias Utilizadas

* **UiPath Studio**
* **VB.NET**

## 🚀 Como Executar

**Pré-requisitos:**

* UiPath Studio Community Edition instalado.
* Extensão UiPath para o seu navegador (Chrome, Edge, etc.) devidamente instalada e ativada.

**Passos:**

1.  Faça o download ou clone este repositório.
2.  Abra o arquivo `Main.xaml` no UiPath Studio.
3.  Clique em **"Run" (Executar)**.
4.  Insira os nomes dos municípios na caixa de diálogo, separados por vírgula.
5.  Aguarde o robô finalizar o trabalho. O arquivo de saída será gerado na pasta do projeto.

## 📝 Exemplo do Arquivo de Saída

```text
Jaraguá do Sul
Prefeito: JOSÉ JAIR FRANZNER
População no último censo [2022]: 182.660
Aniversário da cidade: 25 de julho
Área da unidade territorial [2023]: 530,894 km²

Guaramirim
Prefeito: ADRIANO MARCEL ZIMMERMANN
População no último censo [2022]: 46.711
Aniversário da cidade: 28 de agosto
Área da unidade territorial [2023]: 267,514 km²
```
