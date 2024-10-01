# Simulador de Robôs em Área

## Estrutura do Código:

### Classes:

- **Area:** Define os limites da área em que os robôs podem se mover, com métodos para obter as coordenadas máximas (maxX e maxY).
- **Robot:** Classe abstrata que encapsula a lógica básica para robôs, incluindo suas posições (posX e posY) e métodos abstratos para movimentos em quatro direções (norte, sul, leste, oeste).
- **RoboSimples:** Implementação da classe Robot, permitindo apenas o movimento para o norte.
- **App:** Classe principal que cria uma área e um robô, e executa um movimento.

## Técnicas Utilizadas:

- **Programação Orientada a Objetos (POO):** Utilização de herança e encapsulamento para definir robôs e áreas.
- **Controle de Fluxo:** O método moverNorte verifica se o deslocamento não ultrapassa os limites definidos pela classe Area.
- **Estruturas Abstratas:** Uso de classes abstratas para permitir que diferentes tipos de robôs sejam implementados com funcionalidades específicas.
