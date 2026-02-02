# 📡 Monitoramento Ambiental com ESP8266 + BME280 + ThingSpeak

Projeto de monitoramento ambiental IoT utilizando o ESP8266 e o sensor BME280 para leitura de temperatura, umidade e pressão atmosférica, com envio dos dados para a plataforma ThingSpeak via Wi-Fi.

---

## 🧠 Descrição do Projeto

Este projeto tem como objetivo demonstrar a integração entre um microcontrolador ESP8266, um sensor ambiental BME280 e a plataforma ThingSpeak. Os dados coletados são enviados periodicamente para a nuvem, permitindo a visualização remota por meio de gráficos.

As credenciais de Wi-Fi e do ThingSpeak presentes no código são **apenas exemplos** e **não são válidas**, devendo ser substituídas pelos dados reais do usuário.

---

## 🧰 Componentes Utilizados

- ESP8266 (NodeMCU ou compatível)
- Sensor BME280 (comunicação I²C)
- Rede Wi-Fi
- Plataforma ThingSpeak

---

## 🔌 Esquema do Circuito

A comunicação entre o ESP8266 e o sensor BME280 é feita via barramento I²C.

| Função | Pino no ESP8266 |
|------|----------------|
| SDA  | GPIO 0 |
| SCL  | GPIO 2 |

Imagem ilustrativa do circuito:

![Circuito do projeto](Circuito.jpg)

---

## 📚 Bibliotecas Utilizadas

Para o funcionamento do projeto, são necessárias as seguintes bibliotecas na Arduino IDE:

- Adafruit BME280 Library  
- Adafruit Unified Sensor  
- ESP8266WiFi  
- ThingSpeak  
- Wire  

---

## ⚙️ Configuração do Sistema

No código-fonte, devem ser configurados os dados da rede Wi-Fi e do canal ThingSpeak.  
Os valores abaixo são **fictícios e apenas demonstrativos**:


