# Projeto ETL com Pentaho, MySQL e Power BI

Este repositório contém o código e os recursos relacionados ao projeto de Extração, Transformação e Carga (ETL) utilizando o Pentaho para ETL, o MySQL para armazenar os dados e o Power BI para criar visualizações dos dados. O objetivo principal deste projeto é demonstrar o processo completo de ETL, armazenamento e visualização de dados.

## Descrição

O projeto abrange as seguintes etapas:

- **Extração:** Os dados brutos são coletados de fontes diversas, como bancos de dados, planilhas e arquivos CSV, usando o Pentaho Data Integration.

- **Transformação:** Os dados são limpos, filtrados e transformados para se adequarem aos requisitos de análise, também usando o Pentaho Data Integration.

- **Carga:** Os dados transformados são carregados em um banco de dados MySQL para armazenamento.

- **Visualização:** Os dados armazenados no MySQL são então conectados e visualizados por meio de dashboards interativos criados no Power BI.

## Estrutura do Repositório

- A pasta `arquivo.ktr` contém os arquivos de transformação do Pentaho utilizados para realizar a ETL dos dados.
  <img src="https://github.com/antenoraires/Pentaho/assets/67292251/3a5d1740-6c93-42ef-a9a8-9a5c599e58cd.png" alt="Example Image">

- A pasta `projeto.pbix` contém os arquivos de dashboard do Power BI, que demonstram as visualizações dos dados após a ETL e o armazenamento.
<img src="https://github.com/antenoraires/Pentaho/assets/67292251/b396cd19-5876-4a4b-8bb1-6aad0314d04d.png" alt="Example Image">


- [Link para o Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjJhNjdlMjgtYjMyMy00MGY3LWFjZGUtNmUxMWM2ZGM4ZjM0IiwidCI6Ijk4ZDM1NmYyLWQzMmEtNDc0Ni04ZmNkLTJhNzM5ZDZlMWE5NSJ9/)

## Pré-requisitos

Certifique-se de ter instalado os seguintes softwares:

- [Pentaho Data Integration](https://sourceforge.net/projects/pentaho/)
- [MySQL](https://dev.mysql.com/downloads/)
- [Power BI Desktop](https://powerbi.microsoft.com/pt-br/desktop/)

## Instruções de Uso

1. Clone este repositório em sua máquina local.
2. Execute os arquivos de transformação (.ktr) no Pentaho Data Integration para realizar a ETL dos dados.
3. Abra os arquivos de dashboard (.pbix) no Power BI Desktop para explorar as visualizações interativas.


