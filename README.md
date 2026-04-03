# Esquema-Conceitual-Oficina
A visão do esquema conceitual esta nas entidades criadas.
Onde foram  criadas 5 entidades para o sistema rodar sem muita burocracia
Foi cria uma entidade cliente que é os dados do proprietário do veiculo onde ele é o unico dono ou responsavel 
Criado a entidade oficina que cadastrará os dados do veiculo e ira colher as informações do problema do veiculo
Criado a entidade de Avaliação e execução para avaliar a real situação do veiculo
Criado a entidade vendedor tecnico que venderá para o cliente os serviços e peças de substituição.A função do vendedor é passar para o cliente todo relatório feito pela equipe mecânica fechando assim a OS de serviços.
Por fim foi criado a tabela de mão de obra para vendedores.


Visão do conceito
Um cliente ele pode levar um ou uma frota para oficina
A oficina pode receber um ou uma frota de veiculo(isso depende do tamanho da oficina)
cardinalidade um pra varios

A oficina ela pode mandar para equipe de avaliação um carro ou uma frota, ja que la temos uma equipe de tecnicos
pois cada qual avalias um carro de clientes diferentes

Avaliação tecnica envia o relatorio com sues devidos problemas e as peças que serão substituidas se necessário
para os vendedores
cardinalidade 1 para muitos

Os vendedores consulta a tabela de mão de obras e repassam para o cliente descrito na OS
o cliente faz assina a autorização do serviço
o vendedor repassa a OS para equipe de execução.

A equipe de exucução finalizando a OS repassa para oficina efetuar a cobrança.
