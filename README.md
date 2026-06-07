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
O hardware é composto por:1x Microcontrolador: Arduino UNO1x Sensor de Temperatura e Umidade: DHT22 (Pino Digital 6)1x Display LCD 16x2 com Módulo I2C: Para exibição de dados (Pinos A4/SDA e A5/SCL)3x LEDs Indicadores (5mm):Verde: Indicador de ambiente seguro (Pino Digital 8)Amarelo: Indicador de estado de atenção (Pino Digital 9)Vermelho: Indicador de perigo iminente (Pino Digital 10)1x Buzzer Piezoelétrico: Para alertas sonoros (Pino Digital 7)3x Resistores de 220 $\Omega$: Para proteção e limitação de corrente dos LEDs1x Protoboard (Breadboard) e Jumpers de conexão
