 Melhorias:
•	Tempo para visualização obrigatória dos comunicados;
•	Avisos Internos;
•	Exibição de tempo e processamento de aula;
•	Adição de ícones e ajustes de nomenclaturas;
•	Validade de exibição para avisos;
•	Exibição das imagens da aula prática na aba “Detalhes da aula”;
•	Adição de informação sobre portaria regulamentadora de Sergipe ao site;
•	Implementação de um novo alerta em Painel do Usuário e no Coletor de Imagens
•	Exibição de mensagem de erro mais clara para o cliente;
•	Implementação de limiar para alerta de spoofing;
•	Permissão para seleção de quantidade de aulas práticas durante importação de aluno;
•	Distinção entre aulas pagas e aulas assistidas para veículos de 2 rodas ou 4 rodas;

Detalhamento de melhorias:

•	 Tempo para visualização obrigatória dos comunicados;
Nessa melhoria, sempre que o cliente logar no site, será obrigado a visualizar o aviso ali exibido por um tempo mínimo que será definido pelo agente interno do setor de documentação no momento do envio do aviso. Assim, evitaremos de o cliente fechar o aviso sem que a informação tenha sido passada com efetividade e em casos de algum erro na tela, o cliente poderá logar e navegar pelo painel do SuperPrático a normalmente depois da contagem do tempo. 
Veja abaixo:

<div> 
<img scr="https://www.google.com/imgres?imgurl=https%3A%2F%2Fassetsnffrgf-a.akamaihd.net%2Fassets%2Fm%2F502014285%2Funiv%2Fart%2F502014285_univ_lsr_xl.jpg&imgrefurl=https%3A%2F%2Fwww.jw.org%2Fpt%2Fensinos-biblicos%2Fperguntas%2Fjesus-era-casado%2F&docid=NbfuCHYaiCYkgM&tbnid=ErgdxKMajPMhlM%3A&vet=10ahUKEwjmmOGX28blAhWTLLkGHRMuCIcQMwiDASgAMAA..i&w=1200&h=600&bih=608&biw=1366&q=jesus&ved=0ahUKEwjmmOGX28blAhWTLLkGHRMuCIcQMwiDASgAMAA&iact=mrc&uact=8"\>
<\div>

•	Avisos Internos;
Aqui, no momento do envio de um aviso, o agente interno poderá marcar a opção "Comunicação Interna" e assim, disparar um aviso apenas pros seguintes perfis: Comercial, Financeiro, Suporte técnico, Suporte técnico - Especialista e Administrador, independentemente de ter CFC vinculado ao usuário.
Acesso em SuperPrático > Geral > Novo. Veja abaixo:
 
 
  
•	Exibição de tempo e processamento de aula;
Nessa melhoria, implementamos a exibição do tempo de aula e do processamento de uma aula, facilitando a análise do Suporte que anteriormente utilizava uma planilha para realizar o cálculo de quantos minutos e/ou tempo corrido de aula ocorreu para o atendimento ali realizado.
Acesso em: SuperPratico > Módulo Prático > Aula > Selecionar uma aula > Dados Gerais
Veja abaixo:
 
 
Acesso em: SuperPratico > Módulo Prático > Aula > Selecionar uma aula > Dados Técnicos. Veja abaixo:
 
 

•	Adição de ícones e ajustes de nomenclaturas;
Nessa melhoria, renomeamos as nomenclaturas "Usar Crédito e Liberar Crédito" para "Usar Créditos e Liberar Créditos", além de incluir os respectivos ícones nos botões.
Acesso em: SuperPratico > Módulo Financeiro > Central de Crédito. Veja abaixo: 

 
  
•	Validade de exibição para avisos;
Nessa melhoria, criamos o campo "Data de Expiração" e com isso deixamos disponível para o agente interno definir quanto tempo ele deseja que o aviso fique disponível para exibição do cliente.
Assim, evitamos que, por exemplo, em casos de comunicados de feriados, o feriado já tenha passado mas o aviso continue sendo exibido.
Acesso em: SuperPratico > Geral > Central de Avisos > Novo > Clique em Data de Expiração. 
Veja abaixo:
 

•	Exibição das imagens da aula prática na aba “Detalhes da aula”;
Nessa melhoria, disponibilizaremos da exibição das imagens de uma prática também na aba "detalhes da aula". Nesse caso, adicionamos uma coluna na primeira posição com o nome "Foto", além de alteramos a ordem da aba "Imagens" para ser a primeira na lista de exibição.
Acesso em: SuperPratico > Modulo Prático > Aula > Selecione a aula > Dados Gerais > Desça a barra de rolagem. Veja abaixo:

 .

•	Adição de informação da portaria regulamentadora de Sergipe ao site;
Adicionamos ao Site, a informação da portaria que regulamenta o monitoramento de aulas práticas e teóricas em Sergipe, através de um link que redireciona o usuário diretamente para nossa base de conhecimento. 
Acesso em: Portal Super Pratico > Suporte > Sergipe > Desça a barra de rolagem > Outros Links Importantes. Veja abaixo:
 
•	Implementação de um novo alerta – Painel do Usuário;
Nessa melhoria, para aumentar a segurança da aula prática monitorada, implementamos um alerta que identifica quando os dados de localização do GPS possivelmente foram manipulados pelo usuário através de algum software ou configuração, fazendo com que essa informação fique viciada. Nesse caso, sempre que um dado não for seguro o suficiente, o sistema identificará e um alerta será gerado com a seguinte descrição: “Detectada possibilidade de irregularidade na captura do GPS”, indo automaticamente para a aba de Alertas e tendo inicialmente como configuração o status “Em análise”. 
A liberação dessa aula está condicionada a aprovação do setor de Alertas.
Além disso, foi criada uma nova coluna na aba Localizações / Telemetria, chamado “GPS DUVIDOSO” e com seu conteúdo preenchido SIM, caso a fonte dos dados seja duvidosa e NÃO, caso não tenha sido detectada nenhuma inconsistência ou irregularidade na coleta dos dados de localização.
Para visualizar a descrição do alerta, acesse: Painel do Usuário > Módulo Prático > Aula > Dados Gerais > Alertas. 
Para visualizar o novo campo, acesse: Painel do Usuário > Módulo Prático > Aula > Dados Gerais > Localização / Telemetria. 
Veja abaixo a nova descrição e a nova coluna, respectivamente:
 

 

•	Implementação de um novo alerta – Coletor de Imagens;
Nessa melhoria, visando aumentar a segurança da aula prática monitorada, implementamos um alerta que identifica quando os dados de localização do GPS possivelmente foram manipulados pelo usuário através de algum software ou configuração, fazendo com que essa informação fique viciada. Nesse caso, sempre que o coletor a partir da versão 2.211, identificar que o dado não foi seguro o suficiente, ele identificará e um alerta será gerado com a seguinte descrição: “Detectada possibilidade de irregularidade na captura do GPS”, indo automaticamente para a aba de Alertas e tendo inicialmente como configuração o status “Em análise”.
•	Exibição de mensagem de erro mais clara para o cliente
Nessa melhoria passamos a exibir para o cliente em caso de erros durante a importação de dados biométricos, a mesma mensagem que recebemos do Detran. 
Os ajustes e os respectivos prints das melhorias estão a seguir: 
•	Se apresentar algum erro durante a operação ou o DETRAN não retornar uma informação esperada será ser exibida a mensagem: "Erro ao consultar a biometria do candidato. Tente novamente em alguns minutos ou entre em contato com o suporte."
 

•	Se o DETRAN retornar alguma informação válida, que possua código e mensagem, mas o código seja diferente de sucesso (000), deve ser exibida a mensagem: "Não foi possível importar a biometria do candidato. Mensagem do DETRAN: <código do erro> - <mensagem>"
 

•	Se o DETRAN não retornar nenhuma informação, mas a requisição tenha sido realizada com sucesso, e a informação biométrica do candidato não se encontra cadastrada, será exibida a mensagem: "Não é possível importar o processo devido ausência de alguma biometria ou foto. Entre em contato com o DETRAN."

 

•	Implementação de limiar para alerta de spoofing;
Nessa melhoria, implementamos um limiar para alerta de spoofing, pois em análise, foi verificado que o alerta “detectada possibilidade de irregularidade na validação biométrica” estava sendo acionado em cenários no qual a validação era realizada de fato com a pessoa (corretamente) e não com a fotografia, como deveria ser, fazendo com que fossem gerados vários casos do tipo “falso-positivo”. Percebendo isso, utilizamos um parâmetro para melhorar a acuracidade.
•	Permissão para selecionar quantidade de aulas práticas durante importação de aluno
Nessa melhoria, para obedecer a nova resolução Nº 778 do Cotran, que dentre outras questões, define em 20, o número mínimo de aulas exigidas para obtenção da CNH e põe o simulador como facultativo, podendo ser de até 5 aulas, disponibilizamos para os Estados de AL, GO, RN, SE e PB, a opção de selecionar a quantidade de aulas para importação de um processo prático que contemple o uso do simulador, caso o candidato assim o queira.
A quantidade de aula escolhida será a utilizada para geração do boleto de monitoramento.
Veja o exemplo:
 

 

•	Distinção entre aulas pagas e aulas assistidas para veículos de 2 rodas ou 4 rodas;
Nessa melhoria, a partir da versão 2.211, o coletor verificará antes da validação inicial do aluno, se o mesmo possui crédito disponível para realizar a aula de acordo com a categoria do processo do mesmo.
Foram criados 2 novos campos distintos: uma para informação de aulas pagas 2R e outro para aulas assistidas 2R que serão sincronizadas pela API.


HISTÓRICO DO QUE NÃO FOI DOCUMENTADO:
Card 19575 – Modificações de permissões para nível suporte
Card 19950 – Sincronização de biometria com a gráfica ao Importar Processo Prático – PE
Apesar de ser painel, o Card é de melhoria técnica, ver com Aaron
Card 19951 - Sincronização de biometria ao importar instrutores – PE
Card Server, não é interessante pro cliente, nem pro suporte.
20138 – Erro no build do coletor
Card Bug Coletor, não é interessante pro cliente, nem pro suporte.
Card 20251 – Envio de aula
Card Bug Coletor, não é interessante pro cliente, nem pro suporte.
Card 20340 - [Instrutor] Quando o instrutor se encontra minimizado não esta sendo chamada a validação aleatória
Card Bug s/ necessidade de documentação
20416 – Problema de funcionamento do Incar no Samsung J3
Card técnico s/ necessidade de documentação
20420 – Coletor – Remoção do projeto true time
Card técnico s/ necessidade de documentação
20446 – Instrutor/Coletor – Erro na validação aleatória quando o instrutor é minimizado
Card técnico s/ necessidade de documentação
