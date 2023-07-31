# Correlação entre Escalabilidade, Desempenho e Tempo de Transação das Blockchains

## Introdução:
As blockchains têm ganhado crescente relevância e popularidade, especialmente com o surgimento de criptomoedas e aplicações descentralizadas (DApps). Contudo, a escalabilidade, o desempenho e o tempo de transação são três desafios fundamentais que afetam a adoção em massa dessas tecnologias. Esta pesquisa tem como objetivo investigar a correlação entre a escalabilidade, desempenho e tempo de transação das blockchains, concentrando-se na capacidade de processar transações de forma eficiente, rápida e com tempos de confirmação adequados.

## Definições:
- **Escalabilidade:** Refere-se à capacidade de uma blockchain lidar com um aumento no número de transações ou usuários sem comprometer seu desempenho. Em outras palavras, é a habilidade da rede de crescer e suportar uma maior carga de atividade sem sobrecarregar-se ou enfrentar atrasos significativos. A escalabilidade é uma consideração crítica, especialmente em blockchains públicas, onde a ampla adoção pode levar a um rápido aumento no volume de transações.

- **Desempenho:** Relaciona-se à eficiência e velocidade com que a blockchain processa transações. Geralmente medido em transações por segundo (TPS), indica quantas transações a rede pode confirmar e processar em um determinado intervalo de tempo. Um alto desempenho é desejável, permitindo processar mais transações em menos tempo, aumentando a utilidade e viabilidade da blockchain em diversas aplicações.

- **Tempo de Transação:** É o período necessário para que uma transação seja confirmada e incluída em um bloco na blockchain. Esse tempo pode variar de acordo com a blockchain e depende de fatores como o algoritmo de consenso utilizado e a carga atual da rede. Algumas blockchains possuem tempos de transação rápidos, levando apenas alguns segundos, enquanto outras, especialmente em períodos de alta atividade, podem levar mais tempo para confirmar as transações.



## Método:
Esta pesquisa baseia-se em dados e informações coletadas de fontes acadêmicas confiáveis, relatórios técnicos, estudos de caso, do blog da Phemex e do artigo "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain" publicado no site "news.bitcoin.com", que aborda a questão da escalabilidade de blockchains em comparação com sistemas de pagamento tradicionais.



## Resultados:

### 1. Bitcoin (BTC):
O Bitcoin, como a primeira criptomoeda, desempenhou um papel fundamental na popularização das blockchains. No entanto, enfrentou desafios significativos em escalabilidade e desempenho. Com sua arquitetura de Prova de Trabalho (PoW), o Bitcoin tem uma capacidade limitada de aproximadamente 7 TPS, e o tempo médio de confirmação das transações varia de 10 a 30 minutos. Fonte: [Bitcoin Scalability Problem - ResearchGate](https://www.researchgate.net/publication/313503768_Bitcoin_Scalability_Problem)

### 2. Ethereum (ETH):
A Ethereum é conhecida por suportar contratos inteligentes, mas também enfrentou desafios em escalabilidade. Originalmente baseada em Prova de Trabalho (PoW), a Ethereum enfrentou limitações semelhantes ao Bitcoin em relação à escalabilidade. No entanto, foram empreendidos esforços para melhorar essa questão, incluindo a transição para a Ethereum 2.0 com a adoção de Prova de Participação (PoS) e a implementação de soluções de segunda camada, como a Lightning Network. O tempo médio de confirmação das transações na Ethereum varia de 10 a 20 segundos. Fonte: [Ethereum 2.0: Challenges and Opportunities - Cornell University](https://arxiv.org/abs/2001.08966)

### 3. Binance Smart Chain (BSC):
A Binance Smart Chain é uma blockchain paralela à Binance Chain que oferece contratos inteligentes com maior escalabilidade. Utilizando o mecanismo de consenso Prova de Participação Delegada (DPoS), a BSC alcança uma taxa de TPS superior a 3.000 em comparação com a Ethereum. O tempo médio de confirmação das transações na Binance Smart Chain é de cerca de 3 segundos. Fonte: [An Introduction to Binance Smart Chain (BSC) - Binance Academy](https://academy.binance.com/pt-br/articles/an-introduction-to-binance-smart-chain-bsc)

### 4. Solana (SOL):
A Solana é uma blockchain de alto desempenho conhecida por sua escalabilidade. Com o inovador mecanismo de consenso Prova de História (PoH), a Solana alcança uma impressionante taxa de mais de 65.000 TPS, tornando-se uma das blockchains mais rápidas e eficientes em termos de processamento de transações. O tempo médio de confirmação das transações na Solana é de aproximadamente 1 segundo. Fonte: [Solana TPS - CoinCodex](https://coincodex.com/article/24666/solana-tps/)

### 5. Optimism (OPP):
A Optimism é uma solução de escalonamento para a Ethereum baseada em tecnologia rollups. Seu objetivo é aumentar a escalabilidade da rede Ethereum, possibilitando um maior número de transações por segundo e reduzindo as taxas de transação. Ao agregar várias transações em um único rollup, a Optimism melhora a eficiência e o desempenho da rede Ethereum. O tempo médio de confirmação das transações na Optimism é de cerca de 15 minutos, devido ao período de desafio e resposta. Fonte: [Optimistic Rollups - Ethereum.org](https://ethereum.org/pt-br/developers/docs/scaling/optimistic-rollups/)

### 6. Ripple (XRP):
A Ripple é uma blockchain focada em pagamentos e remessas internacionais. Com seu mecanismo de consenso chamado Algoritmo de Consenso do Protocolo Ripple (RPCA), o XRP Ledger alcança uma notável escalabilidade, com uma capacidade de mais de 1.500 TPS. O tempo médio de confirmação das transações na Ripple é de apenas 4 segundos, tornando-a uma das blockchains mais rápidas em termos de tempo de transação. Fonte: [The XRP Ledger and Consensus Algorithm - Ripple](https://ripple.com/xrp/)



## Phemex Blog. (2021). What is Transactions Per Second (TPS).
O blog da Phemex explica o conceito de "Transactions Per Second" (TPS) e sua importância na avaliação do desempenho das blockchains. O TPS representa o número de transações que uma blockchain pode processar por segundo e é uma métrica crucial para avaliar a escalabilidade e o desempenho. Um TPS mais elevado geralmente indica maior capacidade de processamento de transações e tempos de confirmação mais rápidos, enquanto um TPS mais baixo pode levar a congestionamentos e atrasos em momentos de alta demanda. O blog também enfatiza que o TPS é influenciado pelo mecanismo de consenso e pela arquitetura técnica da blockchain. Fonte: [Phemex Blog - What is Transactions Per Second (TPS)](https://phemex.com/blogs/what-is-transactions-per-second-tps)



## Métodos de Consenso:
A forma como as transações são validadas e incluídas na blockchain é determinada pelo método de consenso utilizado pela rede. Abaixo estão alguns dos métodos de consenso mais comuns:

###  1. Prova de Trabalho (Proof of Work - PoW):

- **Descrição:** A Prova de Trabalho é um mecanismo de consenso onde os nós da rede (mineradores) competem para resolver um quebra-cabeça criptográfico complexo. O primeiro nó a resolver o quebra-cabeça tem o direito de criar o próximo bloco na blockchain e recebe uma recompensa em criptomoedas. O processo exige alto poder computacional e é intensivo em energia.

- **Vantagens:** É altamente seguro, pois requer uma quantidade significativa de trabalho computacional para criar novos blocos, o que torna difícil a modificação de blocos anteriores. Além disso, é descentralizado, pois qualquer nó pode se tornar um minerador.

- **Desvantagens:** É lento e tem baixa escalabilidade devido à competição entre os mineradores e ao tempo necessário para resolver o quebra-cabeça. Além disso, consome uma grande quantidade de energia, o que levanta preocupações ambientais.

###  2. Prova de Participação (Proof of Stake - PoS):

- **Descrição:** A Prova de Participação é um mecanismo de consenso no qual os validadores são escolhidos para criar blocos com base na quantidade de criptomoedas que eles "apostam" ou bloqueiam como garantia na rede. Quanto mais criptomoedas um validador tiver, maior será sua probabilidade de ser escolhido para validar transações e criar blocos.

- **Vantagens:** É mais eficiente em termos de consumo de energia em comparação com PoW, pois não requer competição computacional intensiva. Além disso, incentiva a participação ativa dos detentores de criptomoedas para garantir a segurança da rede.

- **Desvantagens:** Pode haver um problema conhecido como "Nada em Jogo" (Nothing at Stake), onde os validadores podem tentar validar em múltiplas cadeias ao mesmo tempo sem custo, o que pode comprometer a segurança da rede.

###  3. Prova de Participação Delegada (Delegated Proof of Stake - DPoS):

- **Descrição:** O DPoS é uma variante do PoS, onde os detentores de criptomoedas elegem representantes chamados "testemunhas" para validar transações e criar blocos em seu nome. As testemunhas são selecionadas periodicamente para agir como validadores.

- **Vantagens:** Maior escalabilidade em comparação com PoW e Po
S, pois as testemunhas são responsáveis por criar blocos, reduzindo a competição entre os nós da rede. Além disso, é mais eficiente em termos de consumo de energia.

- **Desvantagens:** Pode haver preocupações com a centralização, já que um número limitado de testemunhas é responsável pelo processo de validação.

###  4. Prova de História (Proof of History - PoH):

- **Descrição:** A Prova de História é um mecanismo de consenso assíncrono usado pela Solana. Ele fornece uma prova criptográfica de que um evento ocorreu em um determinado momento, permitindo que os nós da rede concordem sobre a ordem das transações sem a necessidade de comunicação direta entre eles.

- **Vantagens:** Alta escalabilidade e eficiência, permitindo que os nós concordem sobre a ordem das transações sem a necessidade de consenso completo entre todos os nós.

- **Desvantagens:** Não é usado isoladamente como mecanismo de consenso, mas em conjunto com outros algoritmos de consenso, como PoS.

###  5. Rollups:

- **Descrição:** Rollups são uma solução de segunda camada projetada para melhorar a escalabilidade das blockchains, agregando várias transações em um único "rollup" e registrando a prova dessas transações na blockchain principal.

- **Vantagens:** Aumenta a capacidade de processamento da rede principal, reduzindo as taxas de transação e melhorando a eficiência.

- **Desvantagens:** Pode haver um pequeno período de desafio e resposta antes que as transações sejam confirmadas na blockchain principal, o que pode levar a tempos de confirmação mais longos em comparação com outros métodos de consenso direto.

### 6. Lightning Network (LN):

- **Descrição:** O Lightning Network é uma solução de segunda camada projetada para melhorar a escalabilidade e a velocidade das transações do Bitcoin. Ele permite a criação de canais de pagamento fora da blockchain principal, onde as transações podem ser realizadas instantaneamente e com taxas muito baixas. Somente quando o canal é fechado, a transação final é registrada na blockchain principal.

- **Vantagens:** Aumenta significativamente a escalabilidade do Bitcoin, permitindo que um grande número de transações seja processado fora da cadeia principal. Transações rápidas e de baixo custo.

- **Desvantagens:** Requer que os usuários bloqueiem fundos em canais de pagamento, o que pode ser inconveniente e limitar o valor total de transações que podem ser realizadas.

### 7. Algoritmo de Consenso do Protocolo Ripple (RPCA):

- **Descrição:** O RPCA é o mecanismo de consenso utilizado pelo XRP Ledger, a blockchain da Ripple. Neste método, um grupo de validadores é escolhido periodicamente para validar transações e criar novos blocos. Os validadores são escolhidos com base em um processo de votação no qual eles demonstram sua confiabilidade e reputação.

- **Vantagens:** Permite um alto nível de escalabilidade e velocidade de transações. O XRP Ledger é capaz de processar mais de 1.500 transações por segundo com tempos de confirmação de aproximadamente 4 segundos.

- **Desvantagens:** Alguns críticos apontam que a Ripple Labs, a empresa por trás da Ripple, possui controle sobre a maioria dos validadores, o que pode levantar preocupações sobre a descentralização da rede.



## Relação com o Artigo "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain":
O artigo "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain" do site "news.bitcoin.com" destaca a questão da escalabilidade de blockchains e comparações enganosas com sistemas de pagamento tradicionais, como o Visa. O texto ressalta a importância de analisar dados reais e fontes confiáveis ao avaliar as capacidades das blockchains. Essa análise crítica é relevante para o projeto de pesquisa, pois reforça a necessidade de abordar com cautela a escalabilidade e desempenho das blockchains em transações. Além disso, o artigo destaca como informações enganosas podem levar a expectativas irrealistas e desconfiança em relação a essa tecnologia.


## Impacto da Desinformação:
É essencial considerar o impacto da desinformação ao analisar as capacidades das blockchains em relação à escalabilidade e desempenho. O artigo "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain" destaca como informações enganosas podem levar a expectativas irrealistas e desconfiança em relação a essa tecnologia.

## Discussão e Análise:
As informações dos dois tópicos repetidos estão relacionadas à análise da correlação entre escalabilidade, desempenho e tempo de transação nas blockchains. A escalabilidade é um elemento crítico para permitir a adoção em massa e o uso em larga escala das blockchains. Diferentes métodos de consenso têm impactos significativos na escalabilidade, com a Prova de Trabalho apresentando limitações em relação à competição e ao alto consumo energético, enquanto o Prova de Participação e Prova de Participação Delegada oferecem maior eficiência energética e escalabilidade.
Além disso, o desempenho, medido em TPS (transações por segundo), é fundamental para a viabilidade das blockchains em aplicações do mundo real. A utilização de soluções de segunda camada, como Rollups e a Lightning Network, pode aumentar a capacidade de processamento da rede principal e reduzir as taxas de transação, tornando as blockchains mais práticas para transações diárias.
O tempo de transação é influenciado pelo método de consenso e pela capacidade de escalabilidade. Blockchains com tempos de transação mais rápidos, como o XRP Ledger da Ripple, podem ser mais adequadas para aplicações financeiras, onde velocidade e confirmação rápida são essenciais.
O artigo "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain" destaca a importância de analisar dados reais e fontes confiáveis ao avaliar as capacidades das blockchains e alerta para o impacto da desinformação, que pode levar a expectativas irrealistas e desconfiança em relação a essa tecnologia.

## Conclusão:
A correlação entre escalabilidade, desempenho e tempo de transação é essencial para avaliar a viabilidade das blockchains em diversos cenários de uso. O desenvolvimento contínuo de soluções inovadoras, como mecanismos de consenso mais eficientes e otimização de camadas de escalabilidade, continuará a impulsionar a evolução das blockchains, tornando-as mais eficientes e versáteis para atender às necessidades do futuro. A capacidade de processar transações de forma rápida, segura e eficiente é fundamental para a adoção em massa das blockchains e sua aplicação em diversos setores. É crucial abordar com cautela a escalabilidade e o desempenho das blockchains em transações e considerar o impacto da desinformação na compreensão correta das capacidades dessa tecnologia.

## Bibliografia:
1. Nakamoto, S. (2008). Bitcoin: A Peer-to-Peer Electronic Cash System. [Disponível em: https://bitcoin.org/bitcoin.pdf]
2. Eyal, I., & Sirer, E. G. (2014). Majority is not enough: Bitcoin mining is vulnerable. In Financial Cryptography and Data Security (pp. 436-454). Springer, Berlin, Heidelberg. [Disponível em: https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf]
3. Ethereum Foundation. (2021). Ethereum 2.0: Challenges and Opportunities. [Disponível em: https://arxiv.org/abs/2001.08966]
4. Binance Academy. (2021). An Introduction to Binance Smart Chain (BSC). [Disponível em: https://academy.binance.com/pt-br/articles/an-introduction-to-binance-smart-chain-bsc]
5. CoinCodex. (2021). Solana TPS. [Disponível em: https://coincodex.com/article/24666/solana-tps/]
6. Ethereum.org. (2021). Optimistic Rollups. [Disponível em: https://ethereum.org/pt-br/developers/docs/scaling/optimistic-rollups/]
7. Ripple. (2021). The XRP Ledger and Consensus Algorithm. [Disponível em: https://ripple.com/xrp/]
8. Phemex Blog. (2021). What is Transactions Per Second (TPS). [Disponível em: https://phemex.com/blogs/what-is-transactions-per-second-tps]
9. Bitcoin.com. (2021). No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain. [Disponível em: https://news.bitcoin.com/no-visa-doesnt-handle-24000-tps-and-neither-does-your-pet-blockchain/]
