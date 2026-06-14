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


🔍 Principais observações
O protocolo ARP opera na rede local para descoberta de endereços MAC.
O ICMP é utilizado para testes de conectividade.
O DNS realiza a tradução de nomes de domínio para endereços IP.
O HTTPS protege os dados transmitidos utilizando criptografia TLS.
🧠 Interpretação SOC

A análise de protocolos de rede é uma atividade fundamental em centros de operações de segurança (SOC). A identificação de consultas DNS, testes ICMP, resolução ARP e conexões HTTPS permite compreender o comportamento normal da rede e detectar atividades suspeitas.

📸 Evidências
ICMP

ARP

DNS

HTTPS

📌 Conclusão

O laboratório permitiu compreender o funcionamento dos principais protocolos observados em redes corporativas e demonstrou como o Wireshark pode ser utilizado para monitoramento e análise de tráfego.
