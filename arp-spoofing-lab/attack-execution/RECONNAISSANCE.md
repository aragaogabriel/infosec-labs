# FASE DE RECONHECIMENTO

**A máquina atacante está conectada na mesma rede das vítimas e com isso é possível realizar um escaneamento de rede para identificar hosts**
1. Identificar hosts ativos:
    ```bash
   sudo arp-scan -localnet
   
![Escaneamento de Rede](/arp-spoofing-lab/evidence/screenshots/reconhecimentodarede.png)

*É possível identificar dois dispositivos conectados na rede com seus endereços de IP e respectivo MAC*

2. Identificar o gateway:
    ```bash
    ip route

![Identificando Gateway](/arp-spoofing-lab/evidence/screenshots/reconhecimentodarede2.png)

**Temos todas as informações para executar um ataque MITM**