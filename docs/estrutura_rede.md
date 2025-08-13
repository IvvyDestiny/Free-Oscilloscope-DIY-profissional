# Estrutura de Rede

A rede do sistema é montada em topologia estrela com o ESP32 como nó mestre. Arduinos comunicam-se com o mestre via I2C, enquanto a interface web é hospedada diretamente via SPIFFS.

- Host: ESP32 (AP Mode)
- Sub-módulos: Arduinos (I2C)
- WebSocket para interface
- Log remoto via UDP (opcional)