 # IA Moagem de cimento
 
 <p>O moinho vertical  de rolos é um tipo de moinho usado para moer materiais em pó extremamente fino para uso em processos de revestimento mineral, tintas, pirotecnia, cimentos e cerâmica.  Essas máquinas consistem em um grande tambor de aço de serviço pesado, que depende de forças, tanto hidráulicas como pneumáticas, para pulverizar rocha ou pedra.</p>
<center><img src="https://lirp.cdn-website.com/50407a34/dms3rep/multi/opt/Cement_MVR_6000_C-6_2012_Cambodia_Touk_Meas_800x600-640w.jpg" height="300" width= "400" title="Moinho Vertical"/></center>
 
 
<p>Desta forma o sensoriamento deste tipo de máquina é fundamental para sua operação, assim existem diversos tipos de sensores para medir e fornecer características para controle da moagem. E é a partir destes dados que o painel de controle de operação pode controlar a máquina, utilizando diversas formas de comunicação para estabelecer valores e operar  o moinho. </p>
 
<center> <img src="http://static.paraiba.pb.gov.br/2015/09/Painel.jpg" height="300" width= "400" title="Painel"/></center>

<p>Dentre as diversas formas de controle das etapas da cadeia de processo de produção do cimento, a Ciência de Dados se apresenta como importantíssima ferramenta na identificação de gargalos e oportunidades de melhorias. Isto acontece pelo fato de que, cada processo realizado em ambientes industriais gera uma grande quantidade de dados a cada instante, que necessita de capacidades de armazenamento cada vez mais robustas, permitindo que análises sofisticadas possam ser realizadas a fim de se conhecer ao máximo as atividades realizadas na operação.</p>

<p>Utilizar Inteligência Artificial (IA), otimizar e automatizar processos, facilitam o tempo de resposta do operador para eventual tomada de decisão. <a href="https://mais.opovo.com.br/jornal/economia/2019/09/24/apodi-implanta-inteligencia-artificial-e-anuncia-investimentos-de-r--300-mi-em-cinco-anos.html"> A proposta de IA desenvolvida pela UFC na unidade de Pecém vem sendo utilizada com eficiência </a>, desta forma, a proposta foi iniciar uma duplicação do projeto de Pecém para os moinhos de cimento de Quixeré.</p>

<p>A IA será desenvolvida para a moagem de cimento 1, a forma de gestão do projeto foi feita a partir de Scrum metodologia que facilita e otimiza a entrega de projetos, foi dividida em 4 etapas principais, montagem do banco de dados, onde foi utilizado o MongoDB (BD) constituído por 13 coleções. Construção da coleta de dados em tempo real com um script Python que estão armazenadas em uma coleção no BD, o desenvolvimento do core, foi o mais desafiador pois a refatoração de um código complexo é de grande dificuldade. </p>

<p> Após se debruçar sobre o código e entendê-lo, fui capaz de tornar ele mais limpo e enxuto, o core tem a funcionalidade de fazer predições a cada 30 segundos à frente e retornar recomendações otimizando o processo. A última parte é a conexão junto ao OPC que faz a escrita dos valores recomendados no supervisório de controle utilizando o Framework Python PyOPC.</p>



