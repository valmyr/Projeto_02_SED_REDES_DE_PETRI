# Sistemas à Eventos Discretos - Aplicação de Redes de Petri Coloridas 
# Contribuidores

- José Hélio de Araújo Júnior - 124212317
- Valmir Ferreira da Silva          - 119211110

# Vídeo de Demonstração
Para uma explicação detalhada do funcionamento do sistema e uma demonstração da simulação,
[Vídeo de Demonstração do Funcionamento](https://www.youtube.com/watch?v=Dyq_ksFtxUk)

## Descrição Geral do Projeto
Implementar uma sistema que representa uma fábrica com quatro células de manufatura usando redes de Petri coloridas e a ferramenta CPN Tools. As celulas  possuem um depósito de entrada, um depósito de saída, três máquinas e três robôs. Cada uma das máquinas possui um depósito de
entrada e um depósito de saída. Os robôs são responsáveis por movem itens entre os diversos depósitos conforme a figura abaixo.
<img title="Diagrama de alto nível da célula" alt="Alt text" src="images/diagrama_em_alto_nivel.png">

Na célula existem duas rotas de produção: 𝑖 e 𝑗. O robô 1 transporta itens entre o
depósito de entrada da célula para o depósito de entrada da máquina 1. O robô 2
transporta itens do depósito de saída da máquina 1 para os depósitos de entrada
das máquinas 2 e 3. Por fim, o robô 3 transporta itens dos depósitos de saída das
máquinas 2 e 3 para o depósito de saída da célula de manufatura.

### Rede de Petri Máquina 0x
<img title="Rede de Petri Máquina Modelo Base" alt="Alt text" src="images/rede_maquina_base.png">

### Rede de Petri Rôbo 1
<img title="Rede de Petri Robô 1 Modelo Base" alt="Alt text" src="images/rede_robo_1_base.png">

### Rede de Petri Rôbo 2
<img title="Rede de Petri Robô 2 Modelo Base" alt="Alt text" src="images/rede_robo_2_base.png">

### Rede de Petri Rôbo 3
<img title="Rede de Petri Robô 3 Modelo Base" alt="Alt text" src="images/rede_robo_3_base.png">

### Rede de Petri Célula Base 0x
<img title="Rede de Petri Célula Modelo Base" alt="Alt text" src="images/rede_celula_base.png">

### Rede de Petri Fábrica 
<img title="Rede de Petri  Fábrica Modelo" alt="Alt text" src="images/rede_fabrica.png">


