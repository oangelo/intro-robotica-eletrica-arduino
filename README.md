# Introdução à Robótica: Eletricidade, Eletrônica e Arduino

## Apontamentos Importantes

- Todas as imagens devem ser fotografias tiradas pelos próprios alunos, utilizando os equipamentos disponíveis na Universidade. Isso evitará problemas legais relacionados a direitos autorais.
- Os diagramas devem ser construídos pelos alunos, utilizando ferramentas como Inkscape, Fritzing ou criando GIFs animados.
- Cada seção deve incluir suas próprias referências bibliográficas.

## 1. Fundamentos de Eletricidade

### Conceitos Básicos

#### Carga elétrica (202110272411)

#### Corrente elétrica (202110049611)

#### Tensão (201910402211)

#### Resistência (202310053411)

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

#### Funções (201910402211)

### Referências

## 4. Projetos Práticos com Arduino

### Controle de LED (202310053411)

### Leitura de Sensores (202110048211)

### Controle de Motores (201910351011)

### Referências
