Simulador de Semáforo com Raspberry Pi Pico 🚦
Este código implementa um simulador de semáforo utilizando um Raspberry Pi Pico e três LEDs para representar as cores vermelho, amarelo e verde. O sistema troca os LEDs em um ciclo de 3 segundos para cada cor. Vamos aprender a rodar e entender esse código! 👇

💡 O que esse código faz?
Ele simula o funcionamento de um semáforo real:

Começa com o LED vermelho aceso.
Após 3 segundos, acende o LED amarelo.
Depois de mais 3 segundos, acende o LED verde.
Continua alternando nesse ciclo indefinidamente. 🔄
Além disso, a cada segundo ele imprime no terminal qual LED está ligado no momento. 🖥️

🛠️ O que você precisa?
✔ Raspberry Pi Pico
✔ 3 LEDs (vermelho, amarelo e verde)
✔ 3 resistores (330Ω a 1kΩ)
✔ Jumpers
✔ Protoboard
✔ Cabo USB para conectar ao PC

🔌 Conectando os LEDs ao Raspberry Pi Pico
LED	Pino GPIO
Vermelho	GPIO 11
Amarelo	GPIO 12
Verde	GPIO 13
