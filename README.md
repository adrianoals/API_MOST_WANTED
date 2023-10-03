# API: MOST WANTED

Este repositório corresponde a um projeto de construção de uma API que disponibiliza informações sobre os "mais procurados" da FBI e Interpol.

## **Tecnologias Utilizadas**

- Linguagens: C#, Python
- Banco de dados: Oracle

## **Descrição do Projeto**

Este projeto envolve duas etapas principais:

### **Parte 1 - Coleta de Dados da API do FBI e Interpol e Armazenamento no Banco de Dados Oracle**

Nesta fase, desenvolvi um código em C# responsável por coletar dados das APIs públicas do FBI e da Interpol e armazená-los em um banco de dados Oracle. O processo incluiu:

- Estabelecimento de conexão com o banco de dados Oracle.
- Criação de tabelas no Oracle com base nas propriedades de classes genéricas.
- Recuperação de dados da Interpol e do FBI utilizando a biblioteca RestSharp.
- Manipulação e inserção de dados na tabela Oracle.
- Controle de paginação para recuperar lotes de dados.

### **Parte 2 - Criação da API dos Mais Procurados**

Nesta etapa, desenvolvi uma API em Python utilizando o framework Flask, que fornece informações sobre os "Mais Procurados" da Interpol e do FBI, disponibilizando os dados. O processo envolveu:

- Configuração da conexão com o banco de dados Oracle.
- Implementação do Swagger para a documentação da API.
- Definição de rotas para acessar os dados da Interpol e do FBI.
- Consulta ao banco de dados Oracle para recuperar os dados.
- Processamento e transformação dos resultados em objetos JSON.
- Resposta da API com os resultados processados.

## **Conclusão**

Este projeto demonstra a integração de várias tecnologias para criar uma API útil que disponibiliza informações relevantes sobre os "Mais Procurados" da FBI e Interpol.

E os desafios enfrentados incluíram: gerenciamento de conexões com o banco de dados, tratamento de erros e problemas de conexão com as APIs externas, assegurar a estrutura adequada das tabelas Oracle e a implementação de um controle de paginação eficaz.

## Vídeo Coleta de dados C#
https://github.com/adrianoals/API_MOST_WANTED/assets/102778237/bd7914e1-2dda-4013-a298-4243408ee32a


