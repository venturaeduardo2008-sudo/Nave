# Simulação de Telemetria de Nave para Marte

Este projeto contém um notebook (`Nave.ipynb`) que simula e analisa dados de telemetria de uma nave em missão para Marte. O objetivo é explorar, visualizar e interpretar indicadores críticos do funcionamento da nave durante a viagem.

# Objetivo

Simular dados de uma nave espacial e permitir a análise de variáveis essenciais para monitoramento e tomada de decisão durante a missão.

# Dados de Telemetria

O dataset simulado inclui os seguintes parâmetros:

- **Temperatura interna (°C)** → Condições dentro da nave
- **Temperatura externa (°C)** → Ambiente espacial
- **Integridade estrutural (0/1)** → Estado da estrutura da nave
- **Nível de energia (%)** → Capacidade energética restante
- **Pressão dos tanques (bar)** → Estado dos sistemas de combustível/ar
- **Status dos módulos críticos** → Estado operacional (OK, ALERTA, FALHA, etc.)

- # Possíveis Análises

- Detecção de falhas estruturais
- Queda de energia ao longo do tempo

# Execução
foi solicitado ao CHATGPT que criasse a tabela de telemtria

![WhatsApp Image 2026-03-26 at 15 12 41](https://github.com/user-attachments/assets/13f7d876-fe13-4547-8dbb-8b012f6631e7)

Desenvolvimento do algoritmo pós análise de dados

![WhatsApp Image 2026-03-26 at 16 01 07](https://github.com/user-attachments/assets/edc70965-0fb7-478d-a00b-86a31460181c)

Solicitado ao GEMINI por um prompt que desenvolvesse um dataset de comsumo de energia da nave

![WhatsApp Image 2026-03-26 at 16 04 30](https://github.com/user-attachments/assets/2187eafb-634f-4370-a0e7-ab75f30e8f27)

O cálculo utilizado para a energia disponível foi: energy_available_kwh = (battery_voltage_v * battery_capacity_ah * battery_soc_percent/100) / 1000

Com base no dataset de energia, foi solicitado que gerasse anomalias em 3% das linhas

<img width="1460" height="703" alt="imagem_2026-03-26_171121215" src="https://github.com/user-attachments/assets/a2f0891b-4612-4007-b5b3-d5ae17ca26f8" />

Após isso foi analisado os dados de energia

<img width="914" height="257" alt="imagem_2026-03-26_171155246" src="https://github.com/user-attachments/assets/454938f7-e621-4f06-9ec0-e32549bc25e4" />

E então foi realizado a reflexão com base em todas as etapas do processo

<img width="877" height="457" alt="imagem_2026-03-26_171223307" src="https://github.com/user-attachments/assets/e7501e16-5251-4207-bbc3-2ac814052263" />

# Instuções de execução
Analise os valores que constam na nave

Insira-os na etapa 5, nisso será analisado se os valores são os necessários para a decolagem

A partir da etapa 6 até a 8 são as análises de energia do processo 
