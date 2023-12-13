# Especificações técnicas

### 3. Detalhes e Especificações Técnicas

Neste capítulo, discutiremos os detalhes técnicos e as especificações da criptomoeda BitBlocks, fornecendo informações adicionais para ajudar os usuários a entenderem como essa moeda digital funciona e quais são suas principais características.

#### 3.1 Algoritmo de Consenso

A criptomoeda BitBlocks utiliza o algoritmo de consenso Proof-of-Stake (PoS), combinado com Masternodes.

#### 3.2 Especificações Técnicas

* Tipo: POS + Masternodes
* Porta padrão: 58697
* Fornecimento máximo: 584 milhões
* Início do endereço público: B
* Taxa de transação: 0
* Transações por segundo: 346 TPS (aproximadamente)
* Tamanho máximo do bloco: 2 MB
* Tempo estimado do bloco: 60 segundos

#### 3.3 Recompensas por Bloco

As recompensas por bloco são distribuídas aos masternodes e aos stakers que participam do processo de validação de transações. O valor dessas recompensas varia de acordo com a quantidade de moedas em circulação e a participação dos usuários no processo de validação. A tabela de recompensas por bloco é a seguinte:

*   | Intervalo de Bloco      | Recompensa por Bloco |
    | ----------------------- | -------------------- |
    | 1 - 19.999              | 10 moedas            |
    | 20.000 - 40.000         | 20 moedas            |
    | 40.001 - 60.000         | 40 moedas            |
    | 60.001 - 80.000         | 60 moedas            |
    | 80.001 - 100.000        | 80 moedas            |
    | 100.001 - 400.000       | 100 moedas           |
    | 400.001 - 700.000       | 90 moedas            |
    | 700.001 - 1.000.000     | 80 moedas            |
    | 1.000.001 - 1.200.000   | 70 moedas            |
    | 1.200.001 - 1.500.000   | 60 moedas            |
    | 1.500.001 - 2.000.000   | 50 moedas            |
    | 2.000.001 - 2.500.000   | 45 moedas            |
    | 2.500.001 - 3.000.000   | 40 moedas            |
    | 3.000.001 - 3.500.000   | 35 moedas            |
    | 3.500.001 - 4.000.000   | 30 moedas            |
    | 4.000.001 - 4.500.000   | 25 moedas            |
    | 4.500.001 - 5.000.000   | 20 moedas            |
    | 5.000.001 - 5.500.000   | 15 moedas            |
    | 5.500.001 - 6.000.000   | 10 moedas            |
    | 6.000.001 - 7.000.000   | 8 moedas             |
    | 7.000.001 - 8.000.000   | 6 moedas             |
    | 8.000.001 - 9.000.000   | 4 moedas             |
    | 9.000.001 - 10.000.000  | 2 moedas             |
    | 10.000.001 - 20.000.000 | 1 moeda              |
    | 20.000.001 - 50.000.000 | 0.5 moedas           |
    | 50.000.001 e mais       | 0.1 moedas           |

    \


**3.4 Especificações de Masternodes**

As porcentagens de recompensa para os Masternodes são ajustadas de acordo com o seguinte intervalo de blocos:

| Intervalo de Bloco	     | Porcentagem de Recompensa |
| ----------------------- | ------------------------- |
| 101 - 19,999            | 60%                       |
| 20,000 - 40,000         | 65%                       |
| 40,001 - 60,000         | 70%                       |
| 60,001 - 80,000         | 75%                       |
| 80,001 - 100,000        | 80%                       |
| 100,001 - 400,000       | 70%                       |
| 400,001 - 700,000       | 70.5%                     |
| 700,001 - 1,000,000     | 71%                       |
| 1,000,001 - 1,200,000   | 71.5%                     |
| 1,200,001 - 1,500,000   | 72%                       |
| 1,500,001 - 2,000,000   | 72.5%                     |
| 2,000,001 - 2,500,000   | 73%                       |
| 2,500,001 - 3,000,000   | 73.5%                     |
| 3,000,001 - 3,500,000   | 74%                       |
| 3,500,001 - 4,000,000   | 74.5%                     |
| 4,000,001 - 4,500,000   | 75%                       |
| 4,500,001 - 5,000,000   | 75.5%                     |
| 5,000,001 - 5,500,000   | 76%                       |
| 5,500,001 - 6,000,000   | 76.5%                     |
| 6,000,001 - 7,000,000   | 77%                       |
| 7,000,001 - 8,000,000   | 77.5%                     |
| 8,000,001 - 9,000,000   | 78%                       |
| 9,000,001 - 10,000,000  | 78.5%                     |
| 10,000,001 - 20,000,000 | 79%                       |
| 20,000,001 - 30,000,000 | 79.5%                     |
| 30,000,001 - 50,000,000 | 80%                       |
| 50,000,001 e mais       | 90%                       |

Este esquema permite uma compensação variável com base na quantidade de BBKs ativos que você tem em seu masternode. Quanto mais BBKs ativos, maior a porcentagem de recompensa



<figure><img src="../../.gitbook/assets/BBK HALVING.jpg" alt=""><figcaption><p>Taxa de emissao da BitBlocks</p></figcaption></figure>

#### 3.5 Masternodes e Requisitos

Para operar um masternode na rede BitBlocks, é necessário possuir um saldo mínimo de 150.000 BBK (BitBlocks) como garantia. Isso ajuda a garantir que os operadores de masternodes estejam comprometidos com o projeto e tenham um interesse pessoal em garantir a segurança e a eficiência da rede.

#### 3.6 Segurança e Descentralização

A combinação do algoritmo PoS e do uso de masternodes permite que a rede BitBlocks opere de forma descentralizada e segura. Como resultado, a plataforma é mais resistente a ataques e a manipulações, garantindo a integridade das transações e dos dados armazenados na blockchain.

\
**3.7 Velocidade e Escalabilidade**

A BitBlocks foi projetada para lidar com um alto volume de transações por segundo (TPS) de aproximadamente 346 TPS. Isso é possível graças ao tamanho máximo do bloco de 2 MB e ao tempo estimado de bloco de 60 segundos. Essas características permitem que a rede seja escalável e capaz de suportar um número crescente de transações à medida que a adoção da criptomoeda aumenta.

#### 3.8 Taxas de Transação e Uso no Mundo Real

A BitBlocks oferece taxas de transação zero, tornando-a uma opção atrativa para pagamentos e transferências digitais. Isso incentiva a adoção em larga escala da criptomoeda, pois permite que os usuários economizem em comparação com outras opções de pagamento tradicionais ou digitais. A velocidade das transações também é um fator importante, permitindo pagamentos instantâneos em um ambiente cada vez mais digital.

Em resumo, a criptomoeda BitBlocks apresenta várias características que a tornam uma opção atraente para investidores, comerciantes e consumidores. Com o seu algoritmo de consenso PoS, masternodes, recompensas por bloco, segurança, descentralização, velocidade e escalabilidade, a BitBlocks tem o potencial de se tornar uma moeda digital amplamente utilizada em todo o mundo.\
