# dp100_dio_projetoum
## Primeiro projeto do challenge da DIO sobre a certificação D-100 da Microsoft

Esse é um projeto prático ensinando **como fazer um modelo de regressão a partir de uma base de dados gerada por um modelo de LLM no Azure Machine Learning**. Conhecimento adquirido no Microsoft Certification Challenge #3 DP-100 da DIO.

O Projeto é a simulação do processo de criação de um modelo de regressão linear para uma **sorveteria** chamada **Gelato Mágico**. A ideia é otimizar o processo de fabricação dos produtos baseado na demanda provável que pode ser prevista usando dados de previsão de temperaturas para uma determinada semana.

**Os ganhos no uso do modelo para o negócio são:**
*	Ao produzir a quantidade correta de sorvetes que serão vendidos na semana, evitamos que os vendedores de rua carreguem quantidades maiores do que o necessário para as ruas, **reduzindo o peso da carga**.
*	**Evitamos o desperdício** de produtos que não serão vendidos e podem não chegar “inteiros” na volta para a loja.
*	Isso gera **economia na fabricação** e um possível **aumento nas vendas**, já que a quantidade do produto disponível estará alinhada com a demanda e não faltará sorvete para quem quiser tomar 😀.

## O Passo a passo do aprendizado consistiu em:
0. Uso de modelo de LLM para geração de base de dados fictícia
1. Criação de um grupo de recursos no Azure
2.  Provisionamento de um recurso Azure Machine Learning no grupo de recursos recém-criado
3.  Carregamento de um ativo de dados no workspace do AML
4.  Uso dos dados para o treinamento de um modelo de regressão linear usando as funcionalidades de Notebook, AutoML e Design
5.  Deploy de um modelo treinado como um ativo Endpoint.

Acompanhar a construção de ponta a ponta do modelo sem sombra de dúvidas abriu a minha mente para novas possibilidades e até mostrou o esforço que os grandes players de tecnologia estão dedicando para tornar esses recursos mais acessíveis a usuários não técnicos. A criação de um modelo por meio do Designer me impressionou pela simplicidade e por ser livre de código. 
Tenho muito o que aprender ainda e vou começar a criar as minhas prórprias soluções so quanto antes.

