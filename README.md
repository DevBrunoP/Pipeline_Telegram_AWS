# Projeto Pipeline de dados - Telegram ao AWS
**Autor:** Bruno Pereira <br>

---
🎯 **Objetivo do projeto:** O objetivo deste projeto foi construir um pipeline de dados capaz de coletar informações dos chats de um grupo no Telegram, realizar a ingestão e o processo ETL, e, por fim, apresentar os dados já transformados e normalizados. As ferramentas utilizadas incluem a linguagem Python e o ambiente de cloud computing da AWS, com serviços como S3, Athena, Lambda, entre outros. O projeto está todo organizado em tópicos para facilitar a compreensão, além de imagens e explicações sobre cada tópico, boa leitura!<br>

🔎 **Explicação sobre o Notebook:** Dividi este notebook para melhor compreensão em 5 tópicos:
  
  0. **Contexto**: Apresentação inicial do projeto, incluindo uma visão geral do funcionamento, ferramentas utilizadas e sua aplicação prática.
  1. **Telegram**: Detalhamento da integração com o Telegram, abordando a criação do bot, o uso da API do Telegram e seu papel no fluxo do projeto.
  2. **Ingestão**: Explicação de como os dados brutos são transferidos para o ambiente AWS, detalhando o processamento inicial e o armazenamento.
  3. **ETL**: Descrição das etapas de extração, transformação e carregamento, o enriquecimento dos dados e a definição da frequência de reexecução do pipeline.
  4. **Apresentação**: Conclusão com a exibição dos dados enriquecidos, utilizando consultas no Athena para gerar os resultados finais.

📊 **Alguns trechos do meu projeto:**

![Escopo do projeto](https://github.com/user-attachments/assets/e06ee79f-8820-489f-a5e4-92f81e5701f9)

![Resultado final na etapa de apresentação](https://github.com/user-attachments/assets/a267f90f-26f7-4a0c-9bb3-87d372fed4fb)

![Etapa ETL onde agendo a execução d-1 do pipeline através do AWS Event Bridge](https://github.com/user-attachments/assets/6e87339a-a926-49a4-a8a8-082fee86cf07)
