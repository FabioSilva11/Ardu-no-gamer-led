# Projeto de Onda de LED com Arduino Nano

Este é um projeto simples para criar uma onda de luz em uma fita de LED RGB utilizando um Arduino Nano e um sensor de som.

![o que estamos construindo](https://exemplo.com/logo.png)


## Materiais Necessários

- 1 Arduino Nano
- 1 Fita de LED RGB WS2812 Endereçável Operação 5v 110v/220v
- 1 Sensor de som (microfone ou módulo sensor de som)
- Jumpers (fios)

## Bibliotecas Utilizadas

- Adafruit NeoPixel: [https://github.com/adafruit/Adafruit_NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel)

Certifique-se de instalar a biblioteca Adafruit NeoPixel em sua Arduino IDE antes de carregar o código.

## Montagem do Circuito

Conecte a fita de LED RGB ao Arduino Nano da seguinte forma:

- Pino de dados da fita de LED -> Pino digital 6 (D6) do Arduino Nano
- Fio positivo (+) da fita de LED -> Pino 5V do Arduino Nano
- Fio negativo (-) da fita de LED -> GND (terra) do Arduino Nano
- Conecte o sensor de som ao Arduino Nano de acordo com suas especificações, e ajuste o pino de entrada no código conforme necessário.

## Como Utilizar

1. Faça a montagem do circuito conforme descrito acima.
2. Abra o código fornecido neste repositório na Arduino IDE.
3. Certifique-se de ter instalado a biblioteca Adafruit NeoPixel.
4. Carregue o código para o Arduino Nano.
5. Bata palmas ou produza algum som próximo ao sensor de som para ver a onda de luz se movendo na fita de LED.

Divirta-se experimentando com diferentes tamanhos de onda, velocidades e efeitos de cor modificando o código conforme desejado!

## Nota

Certifique-se de ajustar os parâmetros do código, como o tamanho da onda (`waveSize`), a velocidade da onda (`waveSpeed`), o pino do sensor de som (`MIC_PIN`), etc., de acordo com suas necessidades e a configuração do seu circuito.
