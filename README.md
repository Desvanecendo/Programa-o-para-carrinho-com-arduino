# Programação para carrinho com Arduino

Projeto de um carrinho robótico desenvolvido na disciplina de Eletrônica Aplicada, utilizando Arduino Uno, ponte H L298N, dois motores DC e sensor ultrassônico HC-SR04.

## Componentes utilizados

 - 1 Arduino Uno;
 - 01 Ponte H L298N;
 - 02 Motores DC com caixa de redução;
 - 02 Rodas para motores DC;
 - 01 Roda boba (caster);
 - 01 Chassi em MDF para carrinho robótico;
 - 01 Sensor ultrassônico HC-SR04;
 - 01 Protoboard;
 - 01 Suporte para 6 pilhas AA;
 - 06 Pilhas AA recarregáveis;
 - 01 Chave liga/desliga;
 - Cabos jumper (macho-macho e macho-fêmea);
 - Parafusos, porcas e espaçadores para fixação dos componentes;
 - Cola quente (utilizada para auxiliar na fixação de alguns componentes).

## Funcionamento

O Arduino Uno é responsável pelo controle do carrinho, enviando sinais para a ponte H L298N, que realiza o acionamento dos motores DC.

O sensor ultrassônico HC-SR04 é utilizado para identificar obstáculos à frente do carrinho. A partir da distância medida pelo sensor, o Arduino executa a lógica programada para realizar o desvio.

## Limitações

Durante os testes, o carrinho conseguiu realizar o movimento de desvio diante de obstáculos, porém apresentou dificuldades para retornar de forma precisa à trajetória e à direção anteriores. Foram necessários testes e ajustes na programação para tentar melhorar esse comportamento.

## Disciplina

**Eletrônica Aplicada**
