Sistema Biométrico em VHDL – ModelSim 20.1.1

Projeto desenvolvido em VHDL para simulação de um sistema biométrico de controle de acesso utilizando Máquina de Estados Finitos (FSM).

Funcionalidades
- Autenticação biométrica;
- Liberação de acesso;
- Negação de acesso;
- LEDs indicadores;
- Simulação de FSM.

Arquivos
- `sensor_biometrico.vhd` → código principal do sistema;
- `tb_sensor_biometrico.vhd` → TestBench para simulação.

Software utilizado
- ModelSim Intel FPGA Edition 20.1.1

Como executar:

Compilar
Compile → Compile All

Iniciar simulação
Simulate → Start Simulation

Selecionar:
tb_sensor_biometrico

Adicionar waves
Add → To Wave → All items in region

Rodar simulação
No Transcript:
run 500ns

Resultados esperados

Acesso liberado
- digital_in = 1
- led_verde = 1
- acesso_liberado = 1

Acesso negado
- digital_in = 0
- led_vermelho = 1
- acesso_negado = 1
