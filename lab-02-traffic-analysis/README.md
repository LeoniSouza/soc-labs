# 🧪 LAB 02 – Traffic Analysis with Wireshark

## 🎯 Objetivo

Capturar e analisar tráfego de rede utilizando o Wireshark para identificar protocolos essenciais utilizados na comunicação entre dispositivos.

## 🛠️ Ferramentas utilizadas

- Wireshark
- Linux

## 📡 Protocolos analisados

- ICMP
- ARP
- DNS
- HTTPS/TLS
  
## 💻 Atividades realizadas

### ICMP

Comando executado prompt comando:

```bash
ping -c 4 8.8.8.8
```

A captura permitiu observar mensagens Echo Request e Echo Reply, utilizadas para verificar conectividade entre hosts.
![ICMP](images/icmp.png)

---

### ARP
```bash
arp -a
```
Foram analisadas requisições e respostas ARP utilizadas para resolver endereços IP em endereços MAC dentro da rede local.

![ARP](images/arp.png)

---

### DNS
```bash
nslookup google.com
host google.com
```
Foi realizada uma consulta DNS para resolução de nomes de domínio.

A captura demonstrou o processo de consulta e resposta entre cliente e servidor DNS.

![DNS](images/dns.png)

---

### HTTPS/TLS
```bash
https://www.cisco.com
```
Foi acessado um site utilizando HTTPS para observar o estabelecimento de uma conexão segura utilizando TLS.

![HTTPS](images/https.png)

A captura mostrou o estabelecimento da conexão segura através do protocolo TLS, incluindo a negociação inicial entre cliente e servidor.
