https://esphome.io/components/pipsolar/
https://github.com/syssi/esphome-pipsolar
https://github.com/syssi/esphome-pipsolar

 

1️⃣ Compilar o firmware
esphome compile VoltronicEspHome.yaml
________________________________________
2️⃣ Compilar e gravar no ESP (USB)
esphome run VoltronicEspHome.yaml
Esse comando:
1.	compila o firmware 
2.	conecta na porta serial 
3.	grava no ESP 
4.	abre os logs
python -m esphome run VoltronicEspHomeESP32.yaml
python -m esphome clean VoltronicEspHomeESP32.yaml

Função	Pino
Axpert TX	GPIO17
Axpert RX	GPIO16
SDM630 TX	GPIO25
SDM630 RX	GPIO26
