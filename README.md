# Codebox
Codebox is a Codesys implementation in a raspberry board

A CodeBox ou CodeRPIBox é uma jiga de teste multiprotocolo que utiliza o Software Codesys embarcado em uma placa Raspberry PI 3. Ela pode ser utilizada como escravo Modbus TCP, escravo Ethernet/IP, escravo Profinet IO ou mestre/escravo OPC-UA. A figura abaixo mostra uma imagem do CodeBox

![alt text](image.png)

O módulo possui quatro botões de entrada digital, quatro leds de saída digital e uma saída relé do tipo triac (contato seco, podendo ligar carga AC somente até 220Vac, a lógica do relé é NF, ou seja, zero liga o relé e 1 desliga). O potenciômetro está ligado em um conversor AD (ADS1115) e se comunica via interface I2C.
Para comunicar o CodeBox na rede, basta ligar um cabo de rede em uma rede DHCP ou configurar o IP localmente.


