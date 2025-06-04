# Avaliação de Desempenho e Manutenção Preditiva de Equipamentos Industriais
##O objetivo desta Inteligência Artificial é:
Avaliar a performance de uma máquina com comportamento anteriormente historiado para indicar para o setor de O&M possíveis anomalias no funcionamento da máquina, com o objetivo de evitar manutenções corretivas emergênciais.

##Como foi feito:
- Através da coleta de dados de uma máquina de processo de purificação de biogás em biometano junto da planilha de relatos de paradas da operação, classificar os dados em performance correta ou incorreta da máquina (1 ou 0).
- Com o Dataset preparado, com auxílio das bibliotecas: Pandas, Pytorch e scikit learn. Estes dados são inseridos em uma arquitetura de treinamento FNN.


##Como utilizar:
- Caso vá ser utilizado para outra máquina, os campos "X" e "Y" devem ser alterados para refletir as entradas do sistema e saídas.
- Ao rodar todo o código, será executado o treinamento e então exibido os resultados da performance da IA, também estarão disponíveis informações sobre o dataset, para a realização de um *double-check* será gerado um arquivo de modelo pronto para uso.
- Com o arquivo gerado, pode-se carregar o arquivo para uso em outros softwares e códigos. 
