# GS-EDGE-Computer

# LiveOnSpace: Monitor de Temperatura e Umidade com Alertas

## Integrantes do Grupo
[Pedro Feltrin] - RM: [569038]

[Kaick Lima Silva] - RM: [574060]

[Gustavo Basso] - RM: [572623]

[Guilherme Sales] - RM: [572933]

[Guilherme Failla] - RM: [571611]

## Descrição do Projeto
O LiveOnSpace é um sistema desenvolvido na plataforma Arduino para o monitoramento contínuo das condições climáticas de um ambiente. Focado em segurança ou otimização de ambientes controlados, o dispositivo lê dados de temperatura e umidade em tempo real e fornece avisos visual e sonoro imediato, dependendo da severidade do clima detectado.

## Objetivo da Solução
Garantir a segurança de riscos climáticos que afetem o ambiente, mitigando riscos causados pelo calor excessivo ou baixa umidade. A solução automatiza a leitura de riscos em três níveis operacionais (OK, Alerta e Crítico), permitindo tomadas de decisão rápidas antes que falhas estruturais ou de hardware aconteçam.

## Componentes Utilizados
| Ícone | Componente | Quantidade| Função Principal no Circuito| 
| :--- | :---: | :---: | :--- |
| 🧠 | Arduino UNO R3 | 1 un. | Microcontrolador central; processa a lógica dos sensores e controla as saídas. |
| 🌡️ | Sensor DHT22 | 1 un. | Sensor digital de alta precisão para medição de Temperatura e Umidade relativa. | 
| 📺 | Display LCD 16x2 (I2C) | 1 un. | Interface visual para exibição em tempo real dos dados climáticos e status. | 
| 🚨 | Buzzer Piezoelétrico | 1 un. | Alarme sonoro intermitente ativado apenas em condições de risco crítico. | 
| 🔴 | LED Difuso Vermelho | 1 un. | Indicador visual para o Nível 3: Risco Crítico no ambiente. | 
| 🟡 | LED Difuso Amarelo | 1 un.| Indicador visual para o Nível 2: Estado de Alerta. |
| 🟢 | LED Difuso Verde| 1 un. | Indicador visual para o Nível 1: Ambiente Seguro (OK). |
| ⚡ | Resistores de 220 $\Omega$ | 3 un. | Limitadores de corrente para proteção dos LEDs (Verde, Amarelo e Vermelho). |
| 🔌 | Protoboard & Jumpers | 1 kit | Base de ensaios e cabos de conexão para a interligação dos componentes. |
