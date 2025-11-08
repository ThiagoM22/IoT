# 🤖 Projetos IoT — Mazzi

Este repositório reúne todos os meus projetos desenvolvidos na área de **Internet das Coisas (IoT)**.  
Cada projeto é armazenado como um **submódulo Git**, permitindo a manutenção individual e a integração em um ecossistema unificado.

---

## 📘 Sobre o Repositório

A IoT (Internet of Things) tem como objetivo conectar dispositivos físicos à internet, permitindo automação, monitoramento e coleta de dados.  
Aqui, apresento meus experimentos, estudos e aplicações práticas com **ESP32**, **sensores**, **atuadores** e **comunicação MQTT**.

---

## ⚙️ Tecnologias Utilizadas
- **Placas:** ESP32 
- **Linguagem:** C / C++ (Arduino Framework)  
- **Protocolo de Comunicação:** MQTT  
- **Bibliotecas Principais:** PubSubClient, DHT, WiFi, etc.  
- **Plataformas de Desenvolvimento:** Arduino IDE / PlatformIO / Wokwi

---

## 📂 Estrutura dos Projetos

| Projeto | Descrição | Link |
|----------|------------|------|
| **TemperaturaUmidade** | Leitura de dados ambientais via DHT11 e envio MQTT | [Acessar projeto](./TemperaturaUmidade) |
| **casaAutomaticasenai** | Controle remoto de dispositivos via broker MQTT | [Acessar projeto](./casaAutomaticasenai) |
| **Qustionario** | Sistema de perguntas e respostas com Dispkay Lcd e envio MQTT  | [Acessar projeto](./Questionario) |

> ⚠️ *Os links acima apontam para os submódulos deste repositório.*

---

## 🚀 Como Clonar o Repositório

Para clonar o repositório com todos os submódulos, use:

```bash
git clone --recurse-submodules https://github.com/ThiagoM22/IoT.git
