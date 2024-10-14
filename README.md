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
#### 1. Sensores de Temperatura
Os sensores de temperatura permitem medir a temperatura ambiente ou de objetos específicos. Existem diversos tipos compatíveis com o Arduino, cada um com características e aplicações particulares.

a) Termistores (NTC e PTC)
- Funcionamento: Termistores são resistores cuja resistência varia com a temperatura.
  
  - NTC (Coeficiente de Temperatura Negativo): Resistência diminui com o aumento da temperatura.
    
  - PTC (Coeficiente de Temperatura Positivo): Resistência aumenta com o aumento da temperatura.
    
- Integração com Arduino: Conectados em um divisor de tensão, permitem ao Arduino ler a variação de tensão correlacionada à temperatura.

- Aplicações: Controle de temperatura em sistemas de aquecimento, monitoramento ambiental.

b) Sensores Analógicos (LM35, TMP36)
- Funcionamento: Produzem uma tensão de saída proporcional à temperatura medida, geralmente em mV/°C.
  
- Integração com Arduino: A saída analógica é conectada a uma entrada analógica do Arduino, permitindo a leitura direta da temperatura após conversão.
  
- Aplicações: Termômetros digitais, sistemas de climatização.

c) Sensores Digitais (DS18B20, DHT11, DHT22)
- Funcionamento: Fornecem dados de temperatura em formato digital, eliminando a necessidade de conversão analógica-digital.
  
- Integração com Arduino: Utilizam protocolos de comunicação como One-Wire (DS18B20) ou proprietários (DHT11/DHT22), necessitando de bibliotecas específicas.
  
- Aplicações: Monitoramento climático, automação residencial.

#### Considerações Importantes
- Precisão e Faixa de Medição: Escolha o sensor adequado com base na precisão necessária e na faixa de temperatura a ser medida.
- Calibração: Alguns sensores podem requerer calibração para garantir medições precisas.
- Bibliotecas e Suporte: Verifique a disponibilidade de bibliotecas para facilitar a integração com o Arduino.

#### 2. Sensores de Luz
Sensores de luz permitem que o Arduino detecte e meça a intensidade luminosa do ambiente, sendo úteis em aplicações que requerem resposta às mudanças de iluminação.

a) Fotoresistores (LDR - Light Dependent Resistor)
- Funcionamento: A resistência elétrica varia inversamente com a intensidade da luz incidente.

- Integração com Arduino: Conectados em um divisor de tensão, a variação na resistência resulta em uma mudança na tensão lida pelo Arduino.

- Aplicações: Sistemas de iluminação automática, detectores de dia/noite.

b) Fotodiodos e Fototransistores
- Funcionamento:
  
  - Fotodiodos: Convertem luz em corrente elétrica.
   
  - Fototransistores: Amplificam a corrente em resposta à luz.

- Integração com Arduino: Podem ser utilizados em modo fotovoltaico ou fotocondutor, conectados a entradas analógicas ou digitais.

- Aplicações: Sensores de chama, comunicação óptica.

c) Sensores de Luz Digitais (BH1750, TSL2561)
- Funcionamento: Medem a intensidade luminosa e fornecem os dados via interfaces digitais como I2C.

- Integração com Arduino: Necessitam de bibliotecas específicas para comunicação via I2C.

- Aplicações: Medições precisas de iluminação, sistemas de controle de brilho.

#### Considerações Importantes
- Sensibilidade Espectral: Verifique a faixa espectral de sensibilidade do sensor (luz visível, infravermelho, ultravioleta).
- Interferências Ambientais: Proteja o sensor de fontes de luz indesejadas que possam afetar a leitura.
- Resposta Temporal: Considere a velocidade de resposta do sensor para aplicações que requerem detecção rápida.

#### 3. Sensores de Proximidade
Sensores de proximidade detectam a presença ou ausência de objetos próximos sem contato físico, sendo amplamente utilizados em automação e robótica.

a) Sensores Ultrassônicos (HC-SR04)
- Funcionamento: Emitem pulsos ultrassônicos e medem o tempo de retorno do eco para calcular a distância até um objeto.

- Integração com Arduino: Utilizam pinos digitais para trigger e echo, e requerem cálculo do tempo de viagem do som.

- Aplicações: Sistemas de estacionamento, robôs evitadores de obstáculos.

b) Sensores Infravermelhos (Sharp GP2Y0A21YK0F)
- Funcionamento: Medem a reflexão de um feixe de luz infravermelha para determinar a distância.

- Integração com Arduino: Fornecem uma saída analógica proporcional à distância do objeto.

- Aplicações: Detecção de presença, contagem de objetos.

c) Sensores Indutivos e Capacitivos
- Funcionamento:
  
  - Indutivos: Detectam objetos metálicos através da alteração do campo magnético.
    
  - Capacitivos: Detectam materiais dielétricos alterando o campo elétrico.

- Integração com Arduino: Fornecem uma saída digital indicando a presença ou ausência de um objeto.

- Aplicações: Detecção de peças em linhas de montagem, sensores de nível.

d) Sensores de Toque (TTP223)
- Funcionamento: Detectam a mudança na capacitância quando tocados pelo usuário.

- Integração com Arduino: Saída digital conectada a um pino de entrada do Arduino.

- Aplicações: Botões touch, interfaces homem-máquina.

### Considerações Importantes
- Alcance e Precisão: Selecione o sensor com base na distância máxima de detecção e precisão necessária.
- Ambiente de Operação: Condições como poeira, umidade e interferências eletromagnéticas podem afetar o desempenho.
- Ângulo de Detecção: Considere o ângulo de abertura do sensor para garantir a detecção adequada.

#### Dicas Adicionais
Leitura de Datasheets: Sempre consulte o datasheet do sensor para entender suas especificações e requisitos.
Bibliotecas Disponíveis: Aproveite as bibliotecas disponíveis na comunidade para facilitar a programação e integração.
Protoboard e Shields: Utilize protoboards ou shields para facilitar as conexões durante o desenvolvimento.

#### Atuadores (201910072711)
Motores DC, servomotores, motores de passo

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
