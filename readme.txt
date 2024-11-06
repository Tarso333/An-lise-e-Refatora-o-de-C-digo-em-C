README
Projeto: Sistema de Cadastro de Veículos
Descrição
Este projeto implementa um sistema de cadastro de veículos usando a linguagem C. Ele permite o cadastro, listagem e manipulação de dados de veículos com diferentes filtros de pesquisa. Esta versão foi refatorada para melhorar a manutenibilidade e legibilidade do código, eliminando dependências de sistema e melhorando a validação de entradas.
Funcionalidades
•	Cadastro de Veículo: Permite adicionar um novo veículo com informações como proprietário, combustível, modelo, cor, placa e ano de fabricação.
•	Listagem de Veículos a Diesel (após 2010): Exibe proprietários de veículos movidos a diesel com ano de fabricação de 2010 ou posterior.
•	Listagem de Veículos com Placas Específicas: Exibe placas que começam com a letra 'J' e terminam com dígitos específicos.
Tecnologias
•	Linguagem C
Estrutura do Código
•	Modularização: Funções auxiliares foram criadas para validação de dados e limpeza de buffer.
•	Validação de Entrada: Melhorias na verificação de formato e conteúdo dos dados.
•	Portabilidade: Remoção de dependências de system("cls"); e fflush(stdin);, que eram específicas para sistemas Windows.
Executando o Projeto
1.	Clone este repositório.
2.	Compile o código com um compilador C (exemplo: gcc).
3.	Execute o arquivo compilado para iniciar o sistema de cadastro de veículos.
