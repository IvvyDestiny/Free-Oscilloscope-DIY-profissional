# Manual de Operação

## Início Rápido
1. Conecte o ESP32 ao módulo base.
2. Acesse o Wi-Fi gerado pelo dispositivo: `Oscilloscope-ESP32`.
3. Acesse via navegador `http://192.168.4.1`.
4. Use os botões laterais ou encoder físico para navegar.

## Controles Manuais
- Encoder rotativo: ajuste de escala vertical
- Botões físicos: troca de canal e congelamento

## Proteções
O sistema realiza testes automáticos de sondas e ignora leituras falsas. Módulos devem ser protegidos contra sobrecorrente e má conexão.














/Plataforma-Medicao-Modular
├── README.md                # Visão geral completa do projeto
├── LICENSE.txt              # Licença técnica de uso não-comercial
├── .gitignore               # Arquivos/pastas a excluir do Git
│
├── /docs                    # Documentação técnica e explicações
│   ├── estrutura_rede.md    # Arquitetura de rede e distribuição dos módulos
│   ├── interface_web.md     # Funcionalidades e layout da interface web
│   ├── sensores.md          # Tipos, funções e calibração de sensores
│   ├── operacao_campo.md    # Missão tática e uso em zonas de risco
│   └── ficha_tecnica.md     # Dados técnicos do robô e módulos
│
├── /assets                  # Imagens, infográficos e protótipos visuais
│   ├── robô_explorador.png
│   ├── interface_web.png
│   ├── cientista_missao.jpg
│   └── cena_tatica_bo.jpg
│
├── /firmware                # Código para ESP32 e Uno
│   ├── esp32_main.ino       # Firmware principal
│   ├── uno_expansao.ino     # Módulo auxiliar para sensores
│   ├── config_wifi.h        # Configuração da rede local
│   └── sensores_config.h    # Setup de leitura dos sensores
│
├── /web_interface           # Interface Web completa
│   ├── index.html           # Página principal
│   ├── style.css            # Estilo visual
│   ├── script.js            # Funções interativas
│   ├── socket.js            # Comunicação WebSocket
│   └── simulador_sensores.js# Testes offline com dados simulados
│
├── /simulacoes              # Testes de campo e exemplos funcionais
│   ├── campanha_aula.md     # Simulação educacional em laboratório
│   ├── missao_vulcao.md     # Estudo técnico em campo
│   └── teste_mult_host.md   # Uso simultâneo em displays variados