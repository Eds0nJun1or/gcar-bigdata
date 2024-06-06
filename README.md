# Disclaimer

Vale lembrar que este dataset é um dataset público pegado em um site na internet e não representa a indústria real ao redor do mundo, ele foi feito e utilizado única e exclusivamente para tratar e tirar insights dos dados e não tem correlação nenhuma com o mundo real e se tiver, é miníma.

# Análise Completa do Dataset "gcar_data.csv"

Este README atualizado apresenta uma análise aprofundada do dataset "gcar_data.csv", que contém informações sobre 100.000 tipos de carros e modelos comprados na Alemanha entre 1995 e 2023. A análise abrange as variáveis do dataset, análises exploratórias, insights e conclusões sobre o mercado automotivo alemão, com foco em tendências, comportamentos e características relevantes.

## Variáveis do Dataset

O dataset contém 11 variáveis que descrevem as características dos veículos e suas vendas:

- brand: Representa a marca do veículo (por exemplo, Audi, BMW, Ford).
- model: Indica o modelo específico do veículo (por exemplo, A4, Série 3, Focus).
- transmission_type: Indica o tipo de câmbio do veículo (por exemplo, manual, automático, CVT).
- fuel_type: Indica o tipo de combustível utilizado pelo veículo (por exemplo, gasolina, diesel, híbrido).
- registration_date: Indica a data de registro do veículo.
- year: Indica o ano de fabricação do veículo.
- price_in_euro: Representa o preço do veículo em euros no momento da venda.
- power_kw: Indica a potência do veículo em quilowatts.
- power_ps: Indica a potência do veículo em cavalos de potência.
- fuel_consumption_l_100km: Indica o consumo de combustível do veículo em litros por 100 quilômetros.
- fuel_consumption_g_km: Indica o consumo de combustível do veículo em gramas por quilômetro.
- mileage_in_km: Indica a quilometragem do veículo no momento da venda.
- color: Indica a cor do veículo.

## Análise Exploratória

- Tipos de dados: Verificamos os tipos de dados de cada variável e identificamos que algumas contêm valores categóricos (como marca, modelo, tipo de câmbio e tipo de combustível) e outras contêm valores numéricos (como ano, preço, potência, consumo de combustível e quilometragem).

- Valores ausentes: Identificamos a quantidade de valores ausentes em cada variável e removemos as linhas com valores ausentes nas variáveis relevantes para as análises.

- Descrevendo as variáveis: Fornecemos descrições detalhadas de cada variável, incluindo sua definição, unidade de medida e formato.

- Visualizando as entradas: Exibimos algumas entradas do dataset para ter uma ideia geral dos dados.

# Análises e Insights

## Comportamento do Consumidor Alemão

- Preferência por Quilometragem: A análise da quilometragem média por marca pode revelar se os consumidores alemães valorizam veículos com alta quilometragem, sugerindo a busca por durabilidade e confiabilidade.
- Relação Preço x Potência: A análise da relação entre o preço e a potência do motor revela se há uma disposição dos consumidores em pagar mais por carros mais potentes.
- Escolha por Cores: A análise da distribuição dos veículos por cor pode indicar se existem cores mais populares ou se a preferência por cores é heterogênea.

## Tendências do Mercado Automotivo Alemão

### Marcas:

- A análise das marcas de veículos mais frequentes revela que o mercado alemão é dominado por marcas alemãs, com destaque para Audi, BMW, Mercedes-Benz, Volkswagen e Opel.
  Observamos que as marcas asiáticas também possuem uma presença significativa, com destaque para Hyundai, Kia e Toyota.
  É importante notar que a participação de mercado das marcas varia de acordo com o segmento de veículos e faixa de preço.

- Evolução das Vendas:
  A análise da evolução temporal das vendas de veículos ao longo dos anos demonstra um crescimento gradual até 2019, seguido por uma queda em 2020/21 devido à pandemia de COVID-19 e uma recuperação gradual em 2022/23.
  Essa flutuação evidencia o impacto de fatores externos no mercado automotivo, como crises econômicas e eventos globais.
  É importante acompanhar as tendências de longo prazo para identificar oportunidades e desafios para as empresas.

- Tipos de Combustível:
  A análise dos tipos de combustíveis mais utilizados revela uma predominância do diesel e da gasolina, seguidos por híbridos e combustíveis alternativos.
  Essa preferência por combustíveis tradicionais reflete a infraestrutura disponível, o custo e a cultura automobilística alemã.
  No entanto, observa-se um crescimento gradual na adoção de combustíveis alternativos, impulsionado por preocupações ambientais e políticas públicas de incentivo.
  As empresas do setor automotivo devem se adaptar às novas tendências e investir em tecnologias de combustíveis alternativos para se manterem competitivas.

- Preços dos Veículos:
  A análise da relação entre o preço dos veículos e o ano de fabricação revela uma tendência geral de aumento dos preços ao longo dos anos, com algumas flutuações.
  Essa tendência pode ser explicada por diversos fatores, como avanços tecnológicos, aumento dos custos de produção, inflação e mudanças na demanda por modelos premium.

- Segmentação por Preço:
  É interessante segmentar o dataset por faixa de preço para identificar as marcas e modelos mais populares em cada segmento.
  Essa análise permite às empresas automotivas identificar nichos de mercado rentáveis e desenvolver estratégias de marketing direcionadas.
  Por exemplo, a análise pode revelar que marcas japonesas dominam o segmento de carros econômicos, enquanto marcas alemãs lideram o segmento de carros de luxo.

- Depreciação:
  Ao analisar o preço dos veículos em relação à idade (ano de fabricação - ano de venda), podemos estimar a taxa média de depreciação das diferentes marcas e modelos.
  Essa informação é valiosa para o mercado de carros usados e permite às concessionárias precificarem os veículos de forma adequada.

- Relação Preço x Potência:
  A análise da relação entre o preço dos veículos e a potência do motor revela se os consumidores alemães estão dispostos a pagar mais por carros mais potentes.
  Essa análise pode ajudar as empresas a definir estratégias de precificação e identificar o valor ideal para diferentes níveis de potência.

- Preços x Equipamentos:
  É possível investigar a correlação entre o preço dos veículos e a presença de equipamentos específicos (como teto solar, bancos de couro, assistentes de direção).
  Essa análise ajuda as empresas a identificar quais equipamentos agregam valor para o consumidor e, consequentemente, justificam um preço mais alto.

## Insights Socioeconômicos

- Preferência por Quilometragem:
  A análise da quilometragem média por marca pode revelar que marcas alemãs geralmente apresentam quilometragens mais altas, sugerindo que os consumidores alemães valorizam a durabilidade e o alto desempenho de seus veículos.
  Esse insight pode ser explorado pelas marcas alemãs na comunicação de marketing, enfatizando a qualidade e a longevidade de seus produtos.

- Poder Aquisitivo x Segmento:
  A análise da correlação entre o preço médio dos veículos vendidos por região e o poder aquisitivo médio da população local pode revelar a relação entre renda e preferência por determinados segmentos de veículos.
  Essa informação é valiosa para as empresas automotivas alocarem recursos de marketing e distribuição de forma mais eficiente.

## Conclusão

A análise do dataset "gcar_data.csv" fornece insights valiosos sobre o mercado automotivo alemão. O estudo das tendências de preços, combustíveis preferidos, marcas líderes e comportamento do consumidor permite às empresas do setor tomarem decisões estratégicas e desenvolver produtos e serviços que atendam às necessidades e desejos do mercado.
