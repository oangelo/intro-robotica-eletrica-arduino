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

# Lei de Ohm

A **Lei de Ohm** é um princípio fundamental na eletricidade que descreve a relação entre **tensão elétrica (V)**, **corrente elétrica (I)** e **resistência elétrica (R)**. Este documento apresenta os conceitos básicos, fórmulas principais e exemplos práticos para entender melhor essa lei.

---

## 📖 O que é a Lei de Ohm?

A Lei de Ohm afirma que:

> A corrente elétrica que flui através de um condutor entre dois pontos é diretamente proporcional à diferença de potencial (tensão) aplicada e inversamente proporcional à resistência do condutor.

Matematicamente, a fórmula é:

\[
V = I \cdot R
\]

Onde:
- **\( V \)**: Tensão elétrica (Volts, V)
- **\( I \)**: Corrente elétrica (Ampères, A)
- **\( R \)**: Resistência elétrica (Ohms, Ω)

---

## 🔍 Conceitos Principais

### 1. **Tensão (V)**

- É a "força" que empurra os elétrons através de um condutor.
- Medida em **volts (V)**.
- Representa a energia elétrica por unidade de carga.

### 2. **Corrente (I)**

- É o fluxo de carga elétrica através de um condutor.
- Medida em **ampères (A)**.
- Determina a quantidade de carga elétrica que passa por um ponto do circuito em um segundo.

### 3. **Resistência (R)**

- É a oposição ao fluxo de corrente elétrica.
- Medida em **ohms (Ω)**.
- Depende do material, comprimento e área da seção transversal do condutor.

---

## 📊 Fórmulas Derivadas

A partir da equação principal (\( V = I \cdot R \)), podemos derivar outras fórmulas:

1. Para calcular a corrente:
   \[
   I = \frac{V}{R}
   \]

2. Para calcular a resistência:
   \[
   R = \frac{V}{I}
   \]

---

## ⚡ Exemplos Práticos

### Exemplo 1: Calcular a Tensão
Se a corrente em um circuito é de \( 2A \) e a resistência é de \( 5Ω \):
\[
V = I \cdot R = 2 \cdot 5 = 10V
\]

### Exemplo 2: Calcular a Corrente
Dada uma tensão de \( 12V \) e uma resistência de \( 4Ω \):
\[
I = \frac{V}{R} = \frac{12}{4} = 3A
\]

---

## 🖼️ Diagramas e Imagens

### Circuito Simples Representando a Lei de Ohm
![Circuito Simples](https://www.electronica-pt.com/imagens/lei-ohm.png)

---

## 🌟 Importância da Lei de Ohm

A Lei de Ohm é essencial para:
- Dimensionar circuitos elétricos corretamente.
- Projetar sistemas elétricos e eletrônicos.
- Entender como os materiais afetam a resistência elétrica.

---

## 📚 Referências

- "Fundamentos de Eletricidade e Magnetismo" - Autor Desconhecido.
- [Artigo da Wikipedia sobre a Lei de Ohm](https://pt.wikipedia.org/wiki/Lei_de_Ohm)

---

> Desenvolvido para fins educativos.


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
# Leitura de Sensores

A leitura de sensores é um processo essencial em sistemas embarcados, automação e IoT. Sensores permitem capturar grandezas físicas e transformá-las em informações que podem ser processadas por microcontroladores ou computadores.

---

## 📖 O que é um Sensor?

Um **sensor** é um dispositivo que detecta uma grandeza física ou química (como temperatura, luz ou pressão) e a converte em um sinal elétrico utilizável. 

Exemplos de grandezas detectadas:
- **Temperatura**
- **Luminosidade**
- **Pressão**
- **Umidade**
- **Movimento**
- **Aceleração**

Sensores são fundamentais para transformar fenômenos do mundo real em dados digitais ou analógicos que possam ser utilizados em sistemas inteligentes.

---

## 🛠️ Componentes Envolvidos na Leitura

### Principais etapas no processo de leitura:
1. **Sensor**: Captura a grandeza física.
2. **Conversor Analógico-Digital (ADC)**: Converte o sinal analógico em digital.
3. **Microcontrolador**: Interpreta os sinais para tomada de decisão.
4. **Fonte de Alimentação**: Mantém o sistema estável.
5. **Interface de Comunicação**: Protocolos como GPIO, I2C, SPI ou UART.

---

## 🔍 Classificação dos Sensores

### 1. **Sensores Analógicos**
- Geram sinais contínuos (geralmente tensão ou corrente).
- Exemplo: Sensor de temperatura **LM35**.

### 2. **Sensores Digitais**
- Transmitem informações em forma de dados binários.
- Exemplo: Sensor de umidade e temperatura **DHT11**.

### 3. **Sensores Ativos**
- Precisam de fonte de energia para operar.
- Exemplo: Sensor ultrassônico **HC-SR04**.

### 4. **Sensores Passivos**
- Utilizam a energia do ambiente para funcionar.
- Exemplo: **Fotodiodos**.

---

## 📋 Processo de Leitura de Sensores

### **Passo 1: Conexão Física**
- Verifique o **datasheet** do sensor.
- Conecte os pinos ao microcontrolador.
- Exemplo: 
  - Pino de sinal → Entrada analógica/digital.
  - Pino de energia → VCC (3.3V ou 5V).
  - Pino GND → Terra.

### **Passo 2: Configuração do Microcontrolador**
- Configure os pinos e o protocolo de comunicação (I2C, SPI, UART ou GPIO).

### **Passo 3: Captura de Dados**
- Leia os sinais em intervalos regulares.
- Use filtros para reduzir ruídos.

### **Passo 4: Processamento**
- Converta os dados para uma unidade compreensível (ex.: Celsius, Lux, etc.).

---

## 🌟 Exemplos de Sensores e Aplicações

### **1. Sensor de Temperatura - LM35**
- Sinal analógico proporcional à temperatura.
- Aplicações: Termômetros digitais, climatização.

![Diagrama de Ligação do LM35](https://www.usinainfo.com.br/blog/wp-content/uploads/2020/04/esquema_lm35.jpg)

---

### **2. Sensor de Luminosidade - LDR**
- A resistência do LDR varia com a intensidade de luz.
- Aplicações: Controle de luminárias, sensores automáticos.

![Funcionamento do LDR](https://i0.wp.com/elcereza.com/wp-content/uploads/2021/10/LDR-composicao.jpg?resize=532%2C361&ssl=1)

---

### **3. Sensor Ultrassônico - HC-SR04**
- Mede distância usando pulsos ultrassônicos.
- Aplicações: Robótica, controle de estacionamento.

![Exemplo de Uso do HC-SR04](https://www.makerhero.com/wp-content/uploads/2011/07/Ajuste2.png)

---

## 📊 Protocolos de Comunicação Comuns

### **1. GPIO (Pino Digital ou Analógico)**
- Comunicação básica e direta.
- Exemplo: LDR.

### **2. I2C (Inter-Integrated Circuit)**
- Protocolo de barramento serial.
- Exemplo: Sensor MPU6050.

### **3. SPI (Serial Peripheral Interface)**
- Comunicação síncrona e rápida.
- Exemplo: Sensor de pressão BMP280.

### **4. UART (Universal Asynchronous Receiver-Transmitter)**
- Comunicação assíncrona.
- Exemplo: Sensor GPS.

---

## 🛠️ Exemplo Prático: Leitura de um LDR com Arduino

### Circuito:
1. Conecte o LDR e um resistor de 10kΩ em série.
2. Conecte a junção ao pino analógico do Arduino.

### Código:

const int ldrPin = A0; // Pino analógico conectado ao LDR

void setup() {
  Serial.begin(9600); // Inicializa a comunicação serial
}

void loop() {
  int ldrValue = analogRead(ldrPin); // Lê o valor do LDR
  Serial.println(ldrValue); // Exibe o valor no monitor serial
  delay(500); // Aguarda 500 ms
} 
# Leitura de Sensores

## Resultado
Os valores exibidos no monitor serial variam com a luz incidente.

---

## 📷 Galeria de Imagens

1. **Leitura de Sinal Analógico:**

![Leitura Analógica](https://i0.wp.com/alfacomp.net/wp-content/uploads/2021/03/Conversor-de-sinais-analogicos-4.jpg?resize=579%2C321&ssl=1)

2. **Sensor DHT11:**

![DHT11](https://cdn.awsli.com.br/78/78150/produto/3440956/modulo_umidade_temperatura_dht11-z97e6uxojd.png)

3. **Diagrama de Comunicação SPI:**

![SPI Diagram](https://embarcados.com.br/wp-content/uploads/2014/04/cpol_2.jpg)

---

## 🌟 Desafios Comuns e Soluções

1. **Ruído no Sinal:**
   - Use filtros passa-baixa ou médias móveis.

2. **Calibração Incorreta:**
   - Consulte o datasheet para ajustar corretamente.

3. **Conexão Física:**
   - Certifique-se de que os pinos estão conectados corretamente.

---

## 📚 Referências

- [Arduino Reference](https://www.arduino.cc/reference/en/)
- [Wikipedia sobre Sensores](https://pt.wikipedia.org/wiki/Sensor)
- Datasheets de sensores específicos.

---

### Controle de Motores (201910351011)

### Referências
