# Estação de Trem em Miniatura em Assembly AVR com ATmega328P

Este é o código fonte e o circuito de um projeto de automação desenvolvido como trabalho das minhas aulas de engenharia da computação, desenvolvido em AVR ASSEMBLY  para o microcontrolador ATMEGA328P.
Ele simula e controla uma estação de trem em miniatura, com dois trens, desvios de trilho e paradas automáticas nas estações.

---
  - Driver ponte H de motor para controlar dois trens individualmente.

  - A energia é transmitida pela placa para os trens em movimento por meio de um Slip Ring.

  - Quando um trem passa sobre um LDR, o servo motor correspondente gira, redirecionando automaticamente os trilhos.

  - Outros 2 sensores LDR adicionais detectam quando um trem chega à estação, parando o trem correspondente até que o outro se aproxime.

  - 4 servo motores controlados via PWM gerado por software.

  - Velocidade totalmente controlável e reversão completa por meio de um potenciômetro.
    
---

🎥 Vídeo do projeto: https://youtu.be/FEgj6yQy-WY
<img width="899" height="589" alt="image" src="https://github.com/user-attachments/assets/c859b046-7d3f-4a7f-8568-5ca56e0f3855" />
