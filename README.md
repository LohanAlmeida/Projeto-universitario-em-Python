Sistema de Pedágio em Python

Este projeto é um sistema simples de pedágio desenvolvido em Python, que permite calcular automaticamente o valor a ser pago com base no tipo de veículo e no horário de passagem.

📌 Funcionalidades
Seleção de tipo de veículo
Cálculo automático de tarifas
Adicional de 20% em horários de pico
Tratamento de erros de entrada do usuário
Cálculo especial para caminhões (por quantidade de eixos)

🧠 Lógica do Sistema

O sistema funciona em três etapas principais:

Escolha do veículo
O usuário seleciona o tipo de automóvel
Caso seja caminhão, informa a quantidade de eixos
Horário de passagem
O sistema verifica se está em horário de pico:
06h às 08h
17h às 20h
Cálculo da taxa
Horário normal → valor padrão
Horário de pico → acréscimo de 20%
