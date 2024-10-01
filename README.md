# Simulador de Robôs em Área

Este projeto simula o movimento de robôs em uma área bidimensional definida. A classe **Area** estabelece os limites do espaço onde os robôs podem operar. A classe abstrata **Robot** define a estrutura básica dos robôs, incluindo suas posições e métodos de movimento. A implementação na classe **RoboSimples** permite que o robô se mova apenas para o norte. O aplicativo principal cria uma instância da área, inicializa um robô e tenta movê-lo, demonstrando a lógica de movimentação dentro dos limites da área.

## Estrutura do Código:

### Classes:

- **Area:** Define os limites da área em que os robôs podem se mover.
- **Robot:** Classe abstrata que encapsula a lógica básica para robôs, incluindo suas posições e métodos abstratos para movimentos.
- **RoboSimples:** Implementação da classe Robot, permitindo apenas o movimento para o norte.
- **App:** Classe principal que cria uma área e um robô, e executa um movimento.

## Técnicas Utilizadas:

- **Programação Orientada a Objetos (POO):** Utilização de herança e encapsulamento.
- **Controle de Fluxo:** Verifica se o deslocamento não ultrapassa os limites definidos.
- **Estruturas Abstratas:** Permite a implementação de diferentes tipos de robôs.
