# Introdução à Robótica: Eletricidade, Eletrônica e Arduino

## Apontamentos Importantes

- Todas as imagens devem ser fotografias tiradas pelos próprios alunos, utilizando os equipamentos disponíveis na Universidade. Isso evitará problemas legais relacionados a direitos autorais.
- Os diagramas devem ser construídos pelos alunos, utilizando ferramentas como Inkscape, Fritzing ou criando GIFs animados.
- Cada seção deve incluir suas próprias referências bibliográficas.

## 1. Fundamentos de Eletricidade

### Conceitos Básicos

#### Carga elétrica (202110272411)

#### Corrente elétrica (202110049611)

Conceito Básico

A corrente elétrica representa o movimento ordenado e direcionado de cargas elétricas, predominantemente elétrons, através de um material condutor. Este fluxo é induzido pela aplicação de uma diferença de potencial (tensão) entre dois pontos, criando um campo elétrico que propulsiona as cargas. A magnitude da corrente é quantificada em amperes (A), calculada pela equação fundamental:

𝐼 = 𝑄 / 𝑡

onde 𝐼 corresponde à corrente elétrica, 𝑄 representa a quantidade de carga em coulombs (C), e 𝑡 indica o intervalo de tempo em segundos (s). Esse princípio fundamental é crucial para a compreensão e modelagem de circuitos elétricos e eletrônicos, permitindo análises precisas do comportamento das cargas em diversos sistemas e dispositivos.

Tipos de Corrente Elétrica

Dois tipos principais de corrente elétrica são fundamentais para entender sua aplicação:

Corrente Contínua (DC): Caracterizada pelo fluxo unidirecional de cargas. Típica de fontes como baterias e painéis solares, a DC é predominante em dispositivos eletrônicos devido à sua estabilidade e previsibilidade.

Corrente Alternada (AC): Apresenta oscilação periódica na direção do fluxo de cargas. Amplamente utilizada em redes de distribuição de energia elétrica, sua eficiência no transporte de energia em longas distâncias a torna essencial para sistemas de transmissão elétrica.

Fatores que Influenciam a Corrente Elétrica

Resistência: De acordo com a Lei de Ohm (𝐼 = 𝑉/𝑅), a corrente mantém relação inversamente proporcional à resistência do circuito. Materiais com menor resistividade facilitam um fluxo mais significativo de corrente.

Tensão: A intensidade da corrente correlaciona-se diretamente com a diferença de potencial aplicada, seguindo princípios eletrodinâmicos fundamentais.

Composição Material: Condutores como cobre e alumínio possibilitam um fluxo de corrente mais expressivo, enquanto isolantes apresentam significativa limitação à passagem de cargas.

Aplicações Práticas
Circuitos Eletrônicos: Em sistemas de baixa potência, como dispositivos móveis, o gerenciamento preciso da corrente elétrica é essencial para garantir funcionalidade e prevenir sobreaquecimento.
Eletrodomésticos: Equipamentos como refrigeradores, máquinas de lavar e ar-condicionados dependem criticamente da corrente elétrica para acionar motores e sistemas mecânicos.
Biomedicina: Aplicações terapêuticas sofisticadas, como eletroestimulação neuromuscular e desfibrilação cardíaca, fundamentam-se no controle refinado da corrente elétrica.

Considerações

A corrente elétrica configura-se como elemento central em praticamente todos os sistemas eletroeletrônicos contemporâneos. Compreender e gerenciar adequadamente seu comportamento constitui requisito fundamental para projetar dispositivos seguros, eficientes e inovadores, desde microcomponentes até complexas infraestruturas de distribuição energética.

Referências:
- Halliday, David, Resnick, Robert, and Walker, Jearl. Fundamentals of Physics. 10ª ed. Wiley, 2013.
- HyperPhysics. Corrente Elétrica. Disponível em: http://hyperphysics.phy-astr.gsu.edu/hbase/electric/elecur.html

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

#### Estruturas de controle (202110049611)

Conceito Básico

As estruturas de controle constituem elementos nucleares da programação, proporcionando aos programas a capacidade de tomar decisões, executar ações repetitivas e processar comandos de forma condicional. No contexto específico da programação para Arduino, essas estruturas são instrumentos fundamentais para definir o comportamento de dispositivos conectados, permitindo respostas dinâmicas a estímulos externos, como sinais de sensores, e a execução de sequências operacionais repetitivas.

Tipos de Estruturas de Controle

Condicionais:
if/else: Mecanismo que permite a execução seletiva de blocos de código com base em condições específicas, possibilitando respostas programáticas a diferentes cenários.

if (sensorValue > 500) {
    digitalWrite(ledPin, HIGH); // Ativa o LED quando o valor do sensor ultrapassa 500
} else {
    digitalWrite(ledPin, LOW);  // Desativa o LED em caso contrário
}

switch/case: Ferramenta avançada para gerenciar múltiplas condições de forma estruturada e legível, ideal para implementar máquinas de estado e seleções múltiplas.

switch (mode) {
    case 1:
        // Processamento específico para Modo 1
        break;
    case 2:
        // Processamento específico para Modo 2
        break;
    default:
        // Comportamento padrão ou tratamento de estados não mapeados
        break;
}

Laços de Repetição:

for: Projetado para executar um bloco de código um número predeterminado de vezes, otimizando processos iterativos e sequenciais.

for (int i = 0; i < 10; i++) {
    digitalWrite(ledPin, HIGH);
    delay(500);
    digitalWrite(ledPin, LOW);
    delay(500);
}

while: Estrutura que repete um bloco de código continuamente enquanto uma condição específica permanece verdadeira, permitindo processamentos dinâmicos.

while (sensorValue < 500) {
    digitalWrite(ledPin, HIGH); // Continuará executando até que o valor do sensor ultrapasse 500
}

do/while: Variação do laço while que garante a execução inicial do bloco de código, mesmo antes da verificação da condição, assegurando pelo menos uma iteração.

do {
    digitalWrite(ledPin, HIGH);
} while (sensorValue < 500);

Aplicações Práticas

Automação Inteligente: Estruturas condicionais viabilizam a criação de sistemas automatizados, como sistemas de iluminação que respondem a detecções de movimento ou variações ambientais.
Robótica Avançada: Laços de repetição possibilitam o controle preciso de movimentos cíclicos, fundamentais para a navegação e execução de tarefas por sistemas robóticos.
Interfaces Interativas: Comandos condicionais permitem a implementação de interfaces responsivas, capazes de interpretar e reagir a diferentes entradas do usuário, como acionamentos de botões ou ajustes de potenciômetros.

Considerações

As estruturas de controle transformam programas em sistemas verdadeiramente dinâmicos e adaptáveis, sendo componentes essenciais na criação de soluções tecnológicas interativas e inteligentes. No ecossistema Arduino, o domínio dessas estruturas é crítico para o desenvolvimento de projetos inovadores, eficientes e com alto grau de flexibilidade comportamental.

Referências:
- Monk, Simon. Programming Arduino: Getting Started with Sketches. McGraw-Hill, 2016.
- Arduino.cc. Control Structures. Disponível em: https://www.arduino.cc/en/Tutorial/BuiltInExamples/ControlStructures

#### Funções (201910402211)

### Referências

## 4. Projetos Práticos com Arduino

### Controle de LED (202310053411)

### Leitura de Sensores (202110048211)

### Controle de Motores (201910351011)

### Referências
