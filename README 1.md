# Free Oscilloscope DIY Profissional

Este projeto visa criar um osciloscópio digital de alta precisão e baixo custo, usando ESP32, Arduinos e sucata eletrônica. A interface web permite visualização em tempo real, controle remoto e suporte a múltiplos sensores e canais.

## Principais Características
- 8 canais analógicos com alta taxa de amostragem
- Interface web responsiva baseada em WebSocket
- Modularidade com ESP32, Arduino Uno/Nano, Digispark
- Armazenamento local e remoto (pendrive/SD)
- Comunicação via Wi-Fi, Bluetooth e USB
- Modo campo: operação offline com controles físicos

---

## 🌐 Visão Geral

Este projeto apresenta um sistema completo de medição e monitoramento técnico, para projetos simples, para escolas ou instituições de pesquisa que desejam uma solução acessível e eficiente para coleta de dados remotos. A plataforma combina um robô equipado com múltiplos recursos e para ambientes extremos — como zonas de desastre, cenários de risco químico/biológico ou aplicações educacionais nessse aspecto . A unidade embarcada realiza leituras multissensoriais e transmite dados em tempo real para múltiplos dispositivos conectados via rede local e capacidade de automonitoramento registro de capacidades e expansão.

---

## 🤖 Componentes Principais

- ESP32 (núcleo inteligente de aquisição e transmissão web - opcional)
- uno nano ou Arduino Uno (controlador principal ou unidade de expansão)
- Sensores químicos, climáticos, térmicos e radioativos (opcional)
- Módulo de osciloscópio analógico via WebSocket (site e host local)
- Interface Web responsiva com gráficos e dados simultâneos, com simuladores para testes.
- Robô explorador com braços e sensores acoplados (opcional)
- Comunicação redundante (Wi-Fi, BNC, fibra óptica - opcional)
- Displays reciclados (mobile, pc, tablets etc - opcional )
- host USB para analise no PC (opcional)

---

## 🔍 Aplicações

- 📚 Ensino técnico em salas de aula ou laboratório 
- 🌋 Missões em campo (zonas de risco)
- 🧪 Diagnósticos remotos em ambiente hostil
- 🔐 Situações táticas (análise de explosivos, gases, radiação, etc)
- 🛰️ Monitoramento ambiental distribuído
- etc

---

## 🧰 Recursos da Interface Web

- Gráfico em tempo real estilo osciloscópio
- Leitura simultânea de múltiplos sensores
- Transmissão simultâneo para diversos displays web
- Painel químico com alertas críticos
- Painel de meteorologia local
- Painel de visualização de sensores I\O
- painel de gráficos osciloscópio 
- Visualização térmica com vídeo infravermelho
- Controle remoto da unidade via browser
- Acesso mult-host e sincronização de dados

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| ESP32       | Microcontrolador principal |
| Uno nano.   | Módulos de expansão.       |
| HTML/CSS/JS | Interface Web.             |
| WebSocket   | Comunicação em tempo real  |
| SPIFFS      | Armazenamento local.       |
| Chart.js    | Gráficos dinâmicos.        |
| Sensores.   | Captação física            |

---

## 📦 Instalação e Execução

```bash
# Clone o projeto
git clone https://github.com/seu-usuario/seu-repositorio.git

# Instale a IDE Arduino + bibliotecas necessárias

# Faça o upload do firmware para o ESP32

# Acesse a interface web pelo navegador:
http://ip-do-esp32.local