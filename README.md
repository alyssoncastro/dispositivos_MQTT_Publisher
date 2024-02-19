# Simulação de dispositivos MQTT (Publisher)
----
##### ALYSSON C. C. CORDEIRO
##### Engenheiro da Computação - Instituto de Tecnologia e Liderança (INTELI)

---

# Simulador de Dispositivos IoT com MQTT

## Objetivo
Este projeto consiste em um simulador de dispositivos IoT que utiliza o protocolo MQTT para enviar informações relacionadas à detecção de gases. O objetivo é criar uma simulação fidedigna de dispositivos IoT que respeite a taxa de comunicação, unidade e ordem de grandeza das medições, principalmente.

## Enunciado
A implementação visa reproduzir o comportamento de dispositivos de detecção de gases, gerando mensagens MQTT com base em dados simulados. O enunciado orienta a reprodução fiel da taxa de comunicação, unidades de medida e faixa de valores das medições.

## Tecnologias Utilizadas
- Python
- Paho MQTT Library
- Mosquitto

## Dados Tirados daqui:
[https://datasheetspdf.com/pdf/1350171/SGX/MiCS-6814/1]

## Como Executar o Código?

1. **Instalação de Dependências:**
   Certifique-se de ter o Python instalado. Em seguida, instale as dependências usando o seguinte comando:
   ```bash
   pip install paho-mqtt
2. Baixe e instale o Mosquitto [https://mosquitto.org/download/]

3. Vai no reposítório 
    ```bash
    cd dispositivos_MQTT_Publisher
4. Execute em um terminal:
    ```bash
    mosquitto -c mosquitto.conf
5. execute em outro terminal:
    ```bash
    python pub.py

## Demostração:
[https://drive.google.com/file/d/1iFiXn3EMzRY4Syf0xJtDYd94Ret8PbdS/view?usp=sharing]
