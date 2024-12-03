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

<img src="https://cdn.dooca.store/102441/products/ntc-200r_200X200.jpg?v=1678215097" alt="Logo" width="300"> <img src="https://cdn.dooca.store/102441/products/ptc-2_200X200.jpg?v=1677881391" alt="Logo" width="300">


b) Sensores Analógicos (LM35, TMP36)
- Funcionamento: Produzem uma tensão de saída proporcional à temperatura medida, geralmente em mV/°C.
  
- Integração com Arduino: A saída analógica é conectada a uma entrada analógica do Arduino, permitindo a leitura direta da temperatura após conversão.
  
- Aplicações: Termômetros digitais, sistemas de climatização.

<img src="https://www.vidadesilicio.com.br/wp-content/uploads/2021/09/1899-jpg.webp" alt="Logo" width="300">

c) Sensores Digitais (DS18B20, DHT11, DHT22)
- Funcionamento: Fornecem dados de temperatura em formato digital, eliminando a necessidade de conversão analógica-digital.
  
- Integração com Arduino: Utilizam protocolos de comunicação como One-Wire (DS18B20) ou proprietários (DHT11/DHT22), necessitando de bibliotecas específicas.
  
- Aplicações: Monitoramento climático, automação residencial.

<img src="https://d229kd5ey79jzj.cloudfront.net/791/images/791_1_H.png?20241025120208" alt="Logo" width="300">

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

<img src="https://images.tcdn.com.br/img/img_prod/557243/sensor_de_luminosidade_ldr_5mm_224_1_a0f45d5f99af0e11fcfe040a57fb9c7f.png" alt="Logo" width="300">

b) Fotodiodos e Fototransistores
- Funcionamento:
  
  - Fotodiodos: Convertem luz em corrente elétrica.
   
  - Fototransistores: Amplificam a corrente em resposta à luz.

- Integração com Arduino: Podem ser utilizados em modo fotovoltaico ou fotocondutor, conectados a entradas analógicas ou digitais.

- Aplicações: Sensores de chama, comunicação óptica.
  
<img src="http://viverdeeletrica.com/wp-content/uploads/2022/09/o-que-e-fotodiodo-3-1024x576.jpg.webp" alt="Logo" width="300">

c) Sensores de Luz Digitais (BH1750, TSL2561)
- Funcionamento: Medem a intensidade luminosa e fornecem os dados via interfaces digitais como I2C.

- Integração com Arduino: Necessitam de bibliotecas específicas para comunicação via I2C.

- Aplicações: Medições precisas de iluminação, sistemas de controle de brilho.

<img src="https://acdn.mitiendanube.com/stores/975/836/products/120705-mla25066650087_092016-o-882932d634876c681615565096166664-640-0.webp" alt="Logo" width="300">

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

<img src="https://d229kd5ey79jzj.cloudfront.net/620/images/620_1_H.png?20241016112135" alt="Logo" width="300">

b) Sensores Infravermelhos (Sharp GP2Y0A21YK0F)
- Funcionamento: Medem a reflexão de um feixe de luz infravermelha para determinar a distância.

- Integração com Arduino: Fornecem uma saída analógica proporcional à distância do objeto.

- Aplicações: Detecção de presença, contagem de objetos.

<img src="https://curtocircuito.com.br/pub/media/catalog/product/cache/ebf77fb58d795a2dbe3218c301c821c6/s/e/sensor_de_dist_ncia_-_sharp_gp2y0a21yk0f_-_10_80_cm_1.jpg" alt="Logo" width="300">

c) Sensores Indutivos e Capacitivos
- Funcionamento:
  
  - Indutivos: Detectam objetos metálicos através da alteração do campo magnético.
    
  - Capacitivos: Detectam materiais dielétricos alterando o campo elétrico.

- Integração com Arduino: Fornecem uma saída digital indicando a presença ou ausência de um objeto.

- Aplicações: Detecção de peças em linhas de montagem, sensores de nível.

<img src="https://cdn.brasiltec.ind.br/products/9f8c0481d77887e77b105130fbf1443f_wm.png" alt="Logo" width="300">

d) Sensores de Toque (TTP223)
- Funcionamento: Detectam a mudança na capacitância quando tocados pelo usuário.

- Integração com Arduino: Saída digital conectada a um pino de entrada do Arduino.

- Aplicações: Botões touch, interfaces homem-máquina.

<img src="https://d229kd5ey79jzj.cloudfront.net/830/images/830_1_H.png?20240103131628" alt="Logo" width="300">

### Considerações Importantes
- Alcance e Precisão: Selecione o sensor com base na distância máxima de detecção e precisão necessária.
- Ambiente de Operação: Condições como poeira, umidade e interferências eletromagnéticas podem afetar o desempenho.
- Ângulo de Detecção: Considere o ângulo de abertura do sensor para garantir a detecção adequada.

#### Dicas Adicionais
Leitura de Datasheets: Sempre consulte o datasheet do sensor para entender suas especificações e requisitos.
Bibliotecas Disponíveis: Aproveite as bibliotecas disponíveis na comunidade para facilitar a programação e integração.
Protoboard e Shields: Utilize protoboards ou shields para facilitar as conexões durante o desenvolvimento.

### Referências 

MARGOLIS, Michael. Arduino cookbook: recipes to begin, expand, and enhance your projects. 2. ed. Sebastopol: O'Reilly Media, 2020.
ARDUINO. Arduino documentation. Disponível em: https://www.arduino.cc/reference/en/. Acesso em: 3 dez. 2024.
STACK OVERFLOW. Discussões e soluções para sensores Arduino. Disponível em: https://stackoverflow.com. Acesso em: 3 dez. 2024.

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
