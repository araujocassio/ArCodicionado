# Chamados de Ar Condicionado



Esse projeto de análise de chamados para ajuste de temperatura utilizando o Banco de Dados de uma ferramenta de manutenção InfraSpeak! Tem como objetivo analisar os dados de chamados relacionados a problemas de temperatura em um ambiente específico, a fim de identificar possíveis ajustes que possam ser feitos para melhorar a eficiência e reduzir custos.

# Funcionalidades:

 - Identificar pontos criticos de temperatura no prédio;
 - Identificar qual epoca do ano possui maior numero de chamados;

# Tecnologias utilizadas:

 - Linguagem de programação Python;
 - Banco de dados SQL para armazenamento dos dados;

# Como utilizar:

 - Clone o repositório do projeto para a sua máquina local;
 - Instale as dependências do projeto utilizando o pip;
 - Configure as credenciais de acesso ao banco de dados;
 - Compile e execute a aplicação utilizando o comando "python app.py";

Este projeto é uma solução completa e fácil de usar para o identificar pontos criticos de temperatura em um prédio, utilizando a linguagem de programação Python. Sinta-se à vontade para contribuir com melhorias e novas funcionalidades para a plataforma.

# Periodo em analise: 2022 (Téoria Pareto)

![image](https://user-images.githubusercontent.com/98669544/234097176-28605d83-13aa-4a27-817d-57fe764a4b46.png)
- Torre F claramente tem mais ocorrências do que a Torre E, logo selecionamos a torre F para analisar

![image](https://user-images.githubusercontent.com/98669544/234097287-519c7643-67e1-4b42-93a1-63a6550f6139.png)
- Na torre F temos mais chamados de frio do que de calor.

![image](https://user-images.githubusercontent.com/98669544/234097702-8a7bafb3-d072-4227-8b58-8b1bb2f59d9e.png)
- Selecionamos os pavimentos com quantidade de ocorrencia acima da mêdia

![image](https://user-images.githubusercontent.com/98669544/234582049-32886da9-ab4e-4a79-b7f6-7cdfd60739f8.png)
- Identificamos que geralmente o maior numero de ocorrencias são feitas entre 13h e 15h

![image](https://user-images.githubusercontent.com/98669544/234097484-d3af6ad2-3e23-40f0-93d7-b03cb487522d.png)

# Conclusão
 - Essas são as salas criticas de frio excessivo;
 - Faremos alguns ajustes nos setpoints do fancoil que atende essas salas
 - Diminuiremos o numero de difusores de ar dentro das salas
 - Faremos ajustes nos dampers do pavimento que antendem as salas, para que não afete as outras.


