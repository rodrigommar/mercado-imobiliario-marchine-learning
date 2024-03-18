# mercado-imobiliario-marchine-learning
Este projeto de Machine Learning tem como objetivo ilustrar os principais níveis de um projeto de ML. Trata-se de um problema real, porém fictício. Não se trata de aprendizado do mercado imobiliário.<br>
**Steps**:
1. Analisar o panorama geral.
2. Obter os dados.
3. Identificar e visualizar os dados para obter informações úteis.
4. Preparar os dados para os algoritmos de AM.
5. Selecionar e treinar um modelo.
6. Aperfeiçoar o modelo.
7. Apresentar a solução.
8. Disponibilizar em produção, monitorar e fazer a manutenção do sistema.
<br>

# 1. Abordar o problema e  analisar o panorama geral.
   <br>O projeto Habitacional Minha Casa, identificou problema em determinar o valor de imóveis na região municipal, consequetemente, gostaria de prever uma média de preço baseados em indicadores

  _**Defina o objeitvo em termos de Negócio.**_ 
   <br>Como primeira ação, vamos **criar um modelo de preços** baseado no indicadores para o setor imobiliário com os dados do censo.
   Indicadores: Bairros (regiões), população, renda média, preço médio do ímovel

   _**Como a solução será usada?**_
    <br> Ficamos sabendo pelo gerente de projetos que o resultado do modelo e outros sinais alimetarão outro sistema de AM.
     O sistema de downstream irá informar se vale a pena investir na area.

  _**Existe soluções atuais, se sim, quais?**_

  **_Qual será a abordagem (supervisionado, não supervisionado,online, batch, etc)_**
    <br>Supervisionado

  _**Qual a medida de desempenho ?**_
   <br> RMSE e MAE
   <br>Essa métrica é usada em problemas de regressão para avaliar do modelo. Esta métrica mede a média das difrenças quadráticas entre as previsões feitas pelo modelo e os valores reais.
   O RMSE fornece uma medida de quanto o modelo erra em suas previsões.
   Quanto menor o valor de RMSE, melhor o desempenho do modelo. 
    
  _**A medida de desempenho esta alinhada com o objetivo do negócio**_

  _**Qual será o desempenho minimo para necessário para alcançar o objetivo do negócio**_

  _**O que são problemas comparaveis? Pode reutilizar  ferramentas e experiências**_

  _**Tem expertise humana?**_

  **_Como se resolveria o problema manualmente?_**

  _**Enumere as suposições que vocês fiseram até agora**_

  _**Verifique essas suposições, se possível**_

# 2. Obter Dados
   <br> **Nota**: É importante automatizar algumas tarefas para facilitar na obtenção de dados com mais facilidade.<br>
   
   _**Liste os dados que você precisa e de quanto precisa**_
   <br> Os dados usados neste projeto são reais, porém não estão atualizados.
   
   _**Encontre e documente onde você pode obter os dados**_
   <br> https://github.com/ageron/handson-ml2/tree/master/datasets/housing
   
   _**Verifique quanto de espaço é preciso para armazenar os dados**_
   
   _**Obtenha autorização para manipular os dados**_
   <br> Fale com o responsável pela base de dados, caso os dados sejam retirados de um site, é sempre bom citar a fonte.
   <br> Se a compania tem um setor de controle de dados, peça permissão e autprização para manipular os dados, pois pode haver dados sensíveis.
   
   _**Obtenha permissão de acesso**_
   <br> Toda empresa tem um responsável pelo gerenciamento de dados, formalize por e-mail a necessidade de acessar os dados. Mantenha uma relação cordial e respeitosa com o responsável pelo gerenciamento das informações que você deseja obter. 
   
   _**Criar um workspace**_
   <br> Crie um workspace de acordo com suas necessidades, porém um bom workspace pode cinluir:
      <br> Padronização: Estrutura e organização das pastas pode garantir uma melhor compreensão  e navvegação por todos os membros do time.
      <br> Versionamento e controle de mudanças: Onde várias pessoas contribuem com o mesmo projeto é importante estar configurado para um gestão de versionbamento e controle de mundanças.
      <br> Compartilhar recursos e ferramentas: Tools, documentação,  e bibliotecas são essenciais para a equipe.
      <br> Ambiente de Desenvolvimento Integrado (IDE): Uma IDE com todas as configurações e extensões necessárias para facilitar o desenvolvimento.
   
   _**Obter os dados**_
   <br> A relaidade pode ser muito diferente dos projetos acadêmicos, onde trabalhamos com datasets compartilhados e de fácil acesso na internet. Mas quando precisamos minerar esses dados da internet.
   <br> Nesse momento da jornada, é necessário proatividade pra juntar uma base de dados que façam sentido para o projeto. <br> No entanto, na maioria das vezes você entrará num time onde a base de dados existe e estão convertidas de acordo com o interesse do time.
   
   _**Converter os dados (DataFrame)**_
   <br>Nesta fase é onde o profissional precisa ter a competência de uma Cientista de Dados, pois exigirá esforço para tratar os dados, converter alguns dados, manipular dataframes, editar, e talvez exluir.
   
   _**Cuidado com as informações confidenciais (excluir ou oculta-las)**_
   
   _**Verificar o tamanho e tipo de dados (serie atemporal, geograficos, amostrados, numericos)**_
   
   _**separe os dados em teste e treinamento**_
