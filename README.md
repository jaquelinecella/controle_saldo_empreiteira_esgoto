## Controle automatizado de saldo de contrato
Este modelo de controle de saldo de contrato via Excel foi elaborado em meu último emprego na Companhia de Água do Estado do Rio Grande do Sul(Corsan) e adicionei nesta rede para apresentar meu trabalho, pois iria facilitar e automatizar meus lançamentos de pagamentos de serviços para um terceirizada. Apesar dos dados serem públicos, optei por realizar algumas alterações, visto que o objetivo é somente apresentar a automatização no excel.

## Objetivo

A ideia de automatizar uma planilha surgiu quando o novo coordenador de esgoto da Região Metropolitana de Porto Alegre solicitou que de alguma forma houvesse o controle do saldo de um contrato  que visava executar ramais e instalação de caixas de esgoto para residências de 6 municípios da Região Metropolitana. Naquele momento eu estava assumindo o lançamento do pagamento para a empresa terceira destes municípios que progressivamente iriam receber as melhorias em saneamento e não poderia controlar manualmente os saldos. Até então, as planilhas de controles dos contratos anteriores de esgoto eram simples e não automatizadas, e delas partiam os pagamentos mensais. Como a empresa era fiscalizada pelo Tribunal de Contas do RS, havia a necessidades de não extrapolar os limites contratuais, e caso ocorressem poderiam virar objeto de fiscalização. 


## Apresentação da planilha

A planilha que foi anexada junto a este repositório é a planilha "master", visto que há outras seis planilhas "slaves" alimentando ela. Cada planilha "slave" tem origem em um município diferente. A alimentação manual era realizada nas planilhas "slaves" que instantâneamente se comunicavam com a master realizando a baixa e/ou adição de valores, tanto unitários, quanto financeiros. O saldo contratado via Licitação está na aba "valores contrato". Já na aba "total de caixas instaladas" é possível acompanhar o andamento dos serviços (Se atendidos os prazos ou não). Na aba "saldo contrato anual Lote 01" é onde estão as fórmulas que permitiram a automatização. Enquanto o "saldo financeiro restante sem ADM" permanecesse abaixo de 50% do saldo total, a linha ficava preenchida de verde e sucessivamente ía mudando de cor para amarelo, laranja e por último vermelho.  

## Conclusão

O objetivo proposto pelo coordenador foi atingido durante e no final do contrato. Os valores não foram extrapolados, a empresa não sofreu sanções do Tribunal de Contas, inclusive o setor jurídico da Corsan solicitou esta planilha para elaborar a defesa da Companhia, visto que a empresa terceirizada teve o contrato rompido dois meses antes do prazo contratual ter finalizado, pois houve a mudança para Parceria Público-Privada que assumiu toda a administração e operação dos serviços de esgoto da Região Metropolitana. Como a planilha estava automatizada foi possível perceber que mesmo nestes dois últimos meses que faltavam para finalizar o contrato, a contratada não atingiria o proposto em contrato, pois em 10 meses de serviço atingiu menos de 15% do total contratado.

## Autor

Jaqueline Cella
* Linkedin- @jaqueline-cella
* Github- @jaquelinecella




