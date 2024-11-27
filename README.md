# Introdução à Robótica: Eletricidade, Eletrônica e Arduino

## Apontamentos Importantes

- Todas as imagens devem ser fotografias tiradas pelos próprios alunos, utilizando os equipamentos disponíveis na Universidade. Isso evitará problemas legais relacionados a direitos autorais.
- Os diagramas devem ser construídos pelos alunos, utilizando ferramentas como Inkscape, Fritzing ou criando GIFs animados.
- Cada seção deve incluir suas próprias referências bibliográficas.

## 1. Fundamentos de Eletricidade

### Conceitos Básicos

#### Carga elétrica (202110272411)

---

# Carga Elétrica: Conceito, Propriedades e Aplicações Práticas

A carga elétrica é um dos conceitos fundamentais no estudo da eletricidade e do eletromagnetismo. Ela pode ser definida como a propriedade física das partículas subatômicas responsáveis pelas interações eletromagnéticas. Esse conceito é essencial para a compreensão dos fenômenos elétricos e eletrônicos e está presente em diversas aplicações tecnológicas.

## 1. O que é Carga Elétrica?

A carga elétrica é uma propriedade intrínseca de partículas como prótons e elétrons, que determina a forma como essas partículas interagem entre si. 

1.  **Elétron**: Possui carga negativa, com valor aproximado de \( -1,6 \times 10^{-19} \) coulombs.  
2.  **Próton**: Possui carga positiva, com o mesmo valor, mas de sinal oposto ao do elétron.  
3.  **Neutron**: Não possui carga elétrica (é neutro).

Existem dois tipos de cargas elétricas: 

- **Carga Positiva**: Associada aos prótons.
- **Carga Negativa**: Associada aos elétrons.

### Unidade de Medida  
A carga elétrica é medida em coulombs (C), onde um coulomb equivale à carga de aproximadamente \(6,24 \times 10^{18}\) elétrons.

### Princípios Fundamentais
1. **Atração e Repulsão**: Cargas de sinais opostos se atraem, enquanto cargas de mesmo sinal se repelem.
2. **Conservação da Carga**: Em um sistema isolado, a carga elétrica total permanece constante.

## 2. Lei de Coulomb

A força entre duas cargas elétricas \(q_1\) e \(q_2\), separadas por uma distância \(r\), é descrita pela Lei de Coulomb:

\[ F = k \frac{|q_1 \cdot q_2|}{r^2} \]

Onde:
- \(F\) é a força elétrica em newtons (N),
- \(k\) é a constante eletrostática (\(8,99 \times 10^9 \, \text{N} \cdot \text{m}^2 / \text{C}^2\)),
- \(q_1\) e \(q_2\) são as cargas em coulombs,
- \(r\) é a distância entre as cargas em metros.

Essa lei mostra que a força é diretamente proporcional ao produto das cargas e inversamente proporcional ao quadrado da distância entre elas.

## 3. Propriedades da Carga Elétrica

### 3.1. Quantização da Carga  
A carga elétrica é quantizada, ou seja, ela ocorre em múltiplos da carga do elétron (\(-1,6 \times 10^{-19} \, C\)).

### 3.2. Conservação da Carga  
A carga elétrica não pode ser criada nem destruída, apenas transferida de um objeto para outro.

## 4. Aplicações Práticas da Carga Elétrica

### 4.1. Eletrização dos Corpos  
Existem três formas principais de eletrizar um corpo:

1. **Atrito**: Transferência de elétrons entre dois corpos ao sofrerem fricção.
2. **Contato**: Transferência de carga através do toque direto entre corpos condutores.
3. **Indução**: Redistribuição de cargas em um condutor devido à proximidade de um objeto carregado.

### 4.2. Corrente Elétrica  
O fluxo ordenado de cargas elétricas forma a corrente elétrica, fundamental para o funcionamento de dispositivos como lâmpadas, motores e eletrônicos.

### 4.3. Aplicações Tecnológicas  
1. **Circuitos Elétricos**: Uso da carga elétrica em circuitos para controlar o fluxo de corrente.
2. **Eletrostática**: Tecnologias como impressoras a laser e filtros eletrostáticos utilizam princípios de carga elétrica.

## 5. Considerações Finais

A carga elétrica é um elemento central no estudo da eletricidade e do magnetismo, com aplicações que vão desde os fenômenos naturais até dispositivos eletrônicos avançados. Sua compreensão é fundamental para o avanço da tecnologia moderna.

## Referências Bibliográficas

- HALLIDAY, David; RESNICK, Robert; WALKER, Jearl. **Fundamentos de Física: Eletromagnetismo**. 10ª ed. Wiley, 2013.  
- TIPLER, Paul A.; MOSCA, Gene. **Física para Cientistas e Engenheiros**. 6ª ed. Bookman, 2009.  
- HAMBLEY, Allan R. **Electronics: A Top-Down Approach to Computer-Aided Circuit Design**. Prentice Hall, 2011.  
- KHAN ACADEMY. Carga elétrica e lei de Coulomb. Disponível em: [Khan Academy](https://pt.khanacademy.org).  
- HYPERPHYSICS. Charge and Coulomb's Law. Disponível em: [HyperPhysics](http://hyperphysics.phy-astr.gsu.edu). 

#### Corrente elétrica (202110049611)

#### Tensão (201910402211)

#### Resistência (202310053411)

# Resistência Elétrica: Conceito, Fatores Influenciadores e Aplicações Práticas

A resistência elétrica é um fenômeno fundamental no estudo da eletricidade e da eletrônica. Ela pode ser entendida como a oposição que um material oferece à passagem de uma corrente elétrica, resultando na dissipação de energia na forma de calor. A fórmula básica que rege esse comportamento é dada pela **Lei de Ohm**:

\[
R = \frac{V}{I}
\]

onde **R** é a resistência medida em ohms (Ω), **V** representa a voltagem ou diferença de potencial em volts (V), e **I** é a corrente elétrica em amperes (A). Este conceito é essencial para o entendimento dos circuitos elétricos, já que a resistência controla o fluxo de corrente, influenciando a eficiência e o funcionamento dos dispositivos elétricos.

## Fatores que Influenciam a Resistência Elétrica

A resistência elétrica de um material depende de vários fatores, sendo os principais:

1. **Material do Condutor**:  
   Diferentes materiais possuem diferentes propriedades de condução elétrica. Os condutores, como o cobre e o alumínio, têm baixa resistência, permitindo que a corrente flua com facilidade. Por outro lado, os materiais isolantes, como a borracha e o plástico, apresentam alta resistência e são utilizados para impedir a passagem da corrente elétrica. A diferença na resistência entre os materiais é explicada pela estrutura atômica e a quantidade de elétrons livres disponíveis para o transporte de corrente elétrica. (Hambley, 2011)

2. **Temperatura**:  
   A resistência de um condutor geralmente aumenta com a elevação da temperatura. Em metais, os átomos vibram mais intensamente em temperaturas mais altas, o que dificulta o movimento dos elétrons, aumentando a resistência. Esse comportamento é conhecido como "efeito térmico". No entanto, em materiais semicondutores, a resistência pode diminuir com o aumento da temperatura, o que é explorado em dispositivos como termistores. A relação entre temperatura e resistência em semicondutores é crucial no desenvolvimento de sensores de temperatura e outras tecnologias. (Halliday, Resnick & Walker, 2013)

3. **Dimensões do Condutor**:  
   A resistência de um condutor também depende diretamente de suas dimensões físicas. O comprimento do condutor está diretamente proporcional à resistência: quanto mais longo for o fio, maior será a resistência. Por outro lado, a resistência é inversamente proporcional à área da seção transversal do condutor: fios mais espessos apresentam menor resistência. Isso explica porque cabos elétricos utilizados para transmitir grandes quantidades de corrente são geralmente feitos com uma grande área de seção transversal para reduzir as perdas de energia. (Kittel, 2004)

## Aplicações Práticas da Resistência Elétrica

A resistência elétrica tem inúmeras aplicações práticas no cotidiano e na indústria. Alguns dos principais exemplos incluem:

- **Resistores**:  
  São componentes passivos usados em circuitos elétricos para limitar o fluxo de corrente. Eles são fundamentais em dispositivos eletrônicos para garantir que a corrente seja distribuída corretamente entre os componentes, evitando sobrecargas e danos. O valor da resistência de um resistor é ajustado conforme necessário para otimizar o funcionamento de circuitos específicos. (Hambley, 2011)

- **Aquecedores Elétricos**:  
  Dispositivos como chuveiros elétricos, secadores de cabelo e aquecedores utilizam a resistência elétrica para converter energia elétrica em calor. A corrente elétrica passa por um material de alta resistência, que gera calor devido à dissipação de energia. Essa tecnologia é amplamente empregada tanto em eletrodomésticos quanto em aquecedores industriais. (Parks, 2018)

- **Supercondutividade**:  
  Um dos fenômenos mais notáveis envolvendo a resistência elétrica é a supercondutividade, que ocorre em certos materiais a temperaturas extremamente baixas. Nessas condições, a resistência elétrica se torna praticamente nula, permitindo que a corrente elétrica flua sem perda de energia. Esse fenômeno tem aplicações revolucionárias, como no desenvolvimento de trens de levitação magnética e em sistemas de transmissão de energia altamente eficientes. (Parks, 2018)

- **Semicondutores**:  
  A indústria de semicondutores depende do controle preciso da resistência elétrica em materiais como o silício para criar dispositivos como transistores e microchips. Os semicondutores podem alterar sua resistência de acordo com o estado de excitação dos elétrons, permitindo a criação de circuitos complexos usados em processadores de computador e outros dispositivos eletrônicos modernos. A compreensão e a manipulação da resistência elétrica em semicondutores são essenciais para o avanço contínuo da tecnologia digital. (Kittel, 2004)

## Referências Reais e Avanços Tecnológicos

O estudo da resistência elétrica tem permitido o avanço de várias áreas tecnológicas, como a supercondutividade e o desenvolvimento de dispositivos eletrônicos cada vez mais eficientes. Uma das descobertas mais relevantes foi o efeito de supercondutividade, onde a resistência elétrica de certos materiais desaparece quando resfriados a temperaturas próximas ao zero absoluto. Isso possibilita a transmissão de energia sem perdas e está sendo aplicado em tecnologias emergentes, como trens de levitação magnética (maglev) e em equipamentos médicos como aparelhos de ressonância magnética (MRI). (Parks, 2018)

Outro avanço tecnológico está relacionado ao uso de semicondutores, materiais que possuem a capacidade de controlar sua resistência elétrica sob determinadas condições. Essa propriedade é fundamental para o funcionamento de dispositivos eletrônicos modernos, como computadores, smartphones e tablets, onde a resistência elétrica é manipulada para processar informações e realizar cálculos. A contínua pesquisa em semicondutores e a miniaturização de circuitos integrados têm permitido a criação de dispositivos mais rápidos, menores e mais eficientes. (Kittel, 2004)

## Considerações Finais

A resistência elétrica é um dos conceitos centrais no estudo de circuitos elétricos e na engenharia eletrônica. Sua compreensão é essencial para o desenvolvimento de tecnologias avançadas, como a supercondutividade e os dispositivos semicondutores. Ao controlar a resistência em diferentes materiais, engenheiros e cientistas têm sido capazes de projetar sistemas mais eficientes e inovadores, desde eletrodomésticos até complexos circuitos eletrônicos e tecnologias de ponta que impactam o nosso cotidiano.

## Referências

- Hambley, Allan R. *Electronics: A Top-Down Approach to Computer-Aided Circuit Design*. Prentice Hall, 2011.  
- Halliday, David, Resnick, Robert, and Walker, Jearl. *Fundamentals of Physics*. 10ª ed. Wiley, 2013.  
- Parks, R. D. *Superconductivity: An Introduction to Current Research*. CRC Press, 2018.  
- Kittel, Charles. *Introduction to Solid State Physics*. 8ª ed. Wiley, 2004.  
- Khan Academy. *Resistência elétrica e resistores*. Disponível em: [https://pt.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/resistance-and-resistors](https://pt.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/resistance-and-resistors)  
- HyperPhysics. *Resistência Elétrica*. Disponível em: [http://hyperphysics.phy-astr.gsu.edu/hbase/electric/resis.html](http://hyperphysics.phy-astr.gsu.edu/hbase/electric/resis.html)  
- Instituto Nacional de Pesquisas Espaciais (INPE). *Aplicações da Supercondutividade*. Disponível em: [http://www.inpe.br/crs/geoespacial/supercondutividade.php](http://www.inpe.br/crs/geoespacial/supercondutividade.php)  


### Lei de Ohm (202110048211)

### Circuitos em Série e Paralelo (201910351011)

### Referências

## 2. Eletrônica Básica

### Componentes Passivos

#### Resistores (202010358111)
Tipos, código de cores, aplicações

#### Capacitores (201410064011)
Tipos (cerâmico, eletrolítico, poliéster), capacitância, aplicações

#### Indutores (202110272211)
Tipos, indutância, aplicações

### Componentes Ativos

#### Diodos (201810051811)
Tipos (retificador, Zener, LED), curva característica, aplicações

#### Transistores (202110048111)
Tipos (BJT, FET), princípio de funcionamento, aplicações em chaveamento e amplificação

### Circuitos Integrados

#### Amplificadores Operacionais (202110050111)
Características, configurações básicas (inversor, não-inversor, somador)

#### Microcontroladores (202010357611)
Introdução, arquitetura básica, comparação com Arduino

### Sensores e Atuadores

#### Sensores (202110271811)
Tipos (temperatura, luz, proximidade), princípios de funcionamento

#### Atuadores (201910072711)

Os atuadores são dispositivos que convertem energia em movimento mecânico, sendo amplamente utilizados para realizar tarefas automáticas em diversos sistemas eletromecânicos. Eles desempenham um papel crucial em sistemas de controle, transformando sinais de controle em ações físicas, como movimentar, girar ou empurrar objetos.  

Entre os atuadores mais comuns, destacam-se os motores DC, servomotores e motores de passo, que apresentam características específicas para diferentes aplicações.

---

### Motores DC  

Os motores de corrente contínua (DC) são amplamente utilizados devido à sua simplicidade, eficiência e facilidade de controle. Esses motores funcionam convertendo energia elétrica em energia mecânica por meio da interação entre um campo magnético e uma corrente elétrica.  

**Características principais:**  
- Velocidade ajustável através da variação da tensão aplicada.  
- Controle simples, geralmente exigindo um controlador básico.  
- Adequados para aplicações que requerem rotações contínuas, como ventiladores, bombas e robótica básica.  

**Vantagens:**  
- Controle de velocidade e torque eficiente.  
- Custos relativamente baixos.  

**Limitações:**  
- Necessitam de manutenção periódica devido à presença de escovas em motores tradicionais.  

---

### Servomotores  

Os servomotores são motores controlados por feedback, projetados para fornecer alta precisão no controle de posição, velocidade ou torque. Eles são frequentemente utilizados em robótica, sistemas CNC (controle numérico computadorizado) e automação industrial.  

**Características principais:**  
- Incluem um sistema de controle integrado que ajusta automaticamente o desempenho com base no feedback do sensor.  
- Permitem alta precisão e repetibilidade de movimentos.  
- Funcionam tanto em modos contínuos quanto em posicionamento angular.  

**Vantagens:**  
- Excelente precisão e resposta rápida.  
- Capacidade de manter posição ou torque constante.  

**Limitações:**  
- Custo mais elevado em comparação com motores DC comuns.  
- Requerem um controlador mais sofisticado.  

---

### Motores de Passo  

Os motores de passo (ou motores passo a passo) dividem uma rotação completa em "passos" discretos e controláveis, permitindo que eles se movam em incrementos precisos. São ideais para aplicações que exigem controle rigoroso de posicionamento, como impressoras 3D, scanners e sistemas de automação.  

**Características principais:**  
- Cada pulso elétrico representa um incremento fixo na rotação.  
- Não requerem sensores de feedback para controle básico.  
- Funcionam bem em sistemas que exigem movimentos repetitivos e precisos.  

**Vantagens:**  
- Alta precisão de posicionamento.  
- Estrutura simples e robusta.  
- Facilidade de controle usando sinais digitais.  

**Limitações:**  
- Torque reduzido em altas velocidades.  
- Possibilidade de perda de passo se sobrecarregados.  

---

### Considerações  

Ao escolher um atuador, é essencial considerar os requisitos da aplicação, como precisão, torque, velocidade, custo e ambiente de operação. Enquanto os motores DC são ideais para aplicações gerais de rotação contínua, os servomotores oferecem controle sofisticado para aplicações de alta precisão, e os motores de passo se destacam em sistemas que demandam movimentos discretos e repetitivos.  


### Referências

## 3. Introdução ao Arduino

### O que é Arduino? (202110048411)

### Hardware do Arduino

#### Placa Arduino (201910350611)

#### Pinos digitais e analógicos (202010077411)

#### Alimentação (202420657550)

### Software do Arduino

#### IDE do Arduino (202110047911)

#### Estrutura básica de um sketch (202110048311)

### Programação Básica

#### Variáveis e tipos de dados (202110272411)
---
# Programação Básica: Variáveis e Tipos de Dados

A programação é a base da computação, e entender conceitos fundamentais como variáveis e tipos de dados é essencial para qualquer programador. Esses conceitos formam a base para o desenvolvimento de software, permitindo o armazenamento e manipulação de informações de maneira eficaz. Este trabalho explora o conceito de variáveis e tipos de dados, suas definições, características e a importância no desenvolvimento de programas.

## Definição de Variáveis

Variáveis são espaços na memória do computador usados para armazenar dados que podem ser modificados durante a execução de um programa. Elas possuem um nome, um tipo de dado e um valor inicial. O valor de uma variável pode ser alterado ao longo do tempo, o que permite a manipulação de dados dinâmicos durante a execução de um programa.

Características das Variáveis:

1. **Nome**: Identificador usado para acessar a variável.
2. **Tipo de Dado**: Define o tipo de informação que a variável pode armazenar.
3. **Valor Inicial**: O valor que a variável possui quando é criada.

### Declaração de Variáveis

A declaração de uma variável envolve especificar o tipo de dado e o nome da variável. O tipo de dado determina que tipo de valor a variável pode armazenar, como números inteiros, ponto flutuante, caracteres, etc. 

**Exemplo em C:**
int idade;  // Declaração de uma variável do tipo inteiro.
idade = 25; // Atribuição de valor à variável.

**Exemplo em Python:**
idade = 25  // Não é necessário declarar o tipo explicitamente.

## Tipos de Dados

Os tipos de dados definem a natureza dos valores que podem ser armazenados em uma variável. Eles variam de acordo com a linguagem de programação, mas os mais comuns incluem:

1. **Inteiro (int)**: Armazena números inteiros, positivos ou negativos, sem casas decimais.
2. **Ponto Flutuante (float, double)**: Armazena números com casas decimais.
3. **Caractere (char)**: Armazena um único caractere, como letras e símbolos.
4. **Booleano (bool) (char)**: Armazena valores lógicos true (verdadeiro) ou false (falso).
5. **String**: Representa uma sequência de caracteres, como palavras ou frases.

### Tipos de Dados Compostos

São tipos que podem agrupar múltiplos valores.

1. **Array (vetor)**: Coleção de elementos do mesmo tipo.
2. **Objetos (Object)**: Estrutura que pode conter múltiplos tipos de dados.

## Importância e Aplicações

- Armazenamento e Processamento de Dados:
Variáveis permitem que os programas manipulem dados de forma eficiente. Desde simples cálculos até a criação de complexos sistemas de banco de dados, as variáveis são fundamentais.

- Controle de Fluxo:
O uso de variáveis é essencial no controle de decisões dentro de um programa.

- Reutilização e Modularidade:
A capacidade de armazenar informações em variáveis possibilita a reutilização de valores e o aumento da legibilidade e modularidade do código.

- Eficiência e Desempenho:
Escolher o tipo de dado correto é crucial para a eficiência do programa. Por exemplo, usar um tipo int quando se precisa de um valor flutuante pode resultar em erros, enquanto escolher um tipo double para armazenar valores inteiros pode desperdiçar memória desnecessariamente.

## Considerações Finais

O domínio sobre variáveis e tipos de dados é indispensável para qualquer pessoa que deseja aprender a programar. Esses conceitos são a base para tarefas simples e complexas em linguagens de programação modernas. Ao entender como utilizar variáveis corretamente, é possível criar programas mais robustos, eficientes e organizados.

## Referências

Cormen, Thomas H., et al. Introduction to Algorithms. 3ª ed. MIT Press, 2009.
Sweigart, Al. Automate the Boring Stuff with Python: Practical Programming for Total Beginners. 2ª ed. No Starch Press, 2019.
Zelle, John M. Python Programming: An Introduction to Computer Science. Franklin, Beedle & Associates Inc., 2010.
Documentation Python. Tipos de Dados. Disponível em: https://docs.python.org/3/library/stdtypes.html

#### Estruturas de controle (202110049611)

#### Funções (201910402211)

### Referências

## 4. Projetos Práticos com Arduino

### Controle de LED (202310053411)

### Leitura de Sensores (202110048211)

### Controle de Motores (201910351011)

### Referências
