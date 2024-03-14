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

1. **Abordar o problema e  analisar o panorama geral.**
   O projeto Habitacional Minha Casa, identificou problema em determinar o valor de imóveis na região municipal, consequetemente, gostaria de prever uma média de preço baseados em indicadores

  _**Defina o objeitvo em termos de Negócio.**_ 
   Como primeira ação, vamos **criar um modelo de preços** baseado no indicadores para o setor imobiliário com os dados do censo.
   Indicadores: Bairros (regiões), população, renda média, preço médio do ímovel

   _**Como a solução será usada?**_
     Ficamos sabendo pelo gerente de projetos que o resultado do modelo e outros sinais alimetarão outro sistema de AM.
     O sistema de downstream irá informar se vale a pena investir na area.

  _**Existe soluções atuais, se sim, quais?**_

  **_Qual será a abordagem (supervisionado, não supervisionado,online, batch, etc)_**
    Supervisionado

  _**Qual a medida de desempenho ?**_
    RMSE e MAE
    
  _**A medida de desempenho esta alinhada com o objetivo do negócio**_

  _**Qual será o desempenho minimo para necessário para alcançar o objetivo do negócio**_

  _**O que são problemas comparaveis? Pode reutilizar  ferramentas e experiências**_

  _**Tem expertise humana?**_

  **_Como se resolveria o problema manualmente?_**

  _**Enumere as suposições que vocês fiseram até agora**_

  _**Verifique essas suposições, se possível**_

   
   

   Abordagem: Supervisionado
   Tarefa: Regressão
   Técnicas de aprendizagem em batch

   Medida de Desempenho: RMSE.
   Essa métrica é usada em problemas de regressão para avaliar do modelo. Esta métrica mede a média das difrenças quadráticas entre as previsões feitas pelo modelo e os valores reais.
   O RMSE fornece uma medida de quanto o modelo erra em suas previsões.
   Quanto menor o valor de RMSE, melhor o desempenho do modelo. 
