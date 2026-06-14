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

Comando executado:

```bash
ping -c 4 8.8.8.8
```

Foram observados pacotes Echo Request e Echo Reply utilizados para validar a conectividade da máquina com a internet.

### ARP

Foram capturadas requisições e respostas ARP utilizadas para resolução de endereços IP em endereços MAC na rede local.

### DNS

Foi realizada uma consulta DNS para observar o processo de resolução de nomes de domínio para endereços IP.

### HTTPS/TLS

Foi acessado um site utilizando HTTPS para observar o estabelecimento de uma conexão segura utilizando TLS.

## 🔍 Principais observações

- O protocolo ARP permite descobrir o endereço MAC associado a um endereço IP.
- O ICMP é utilizado para testes de conectividade.
- O DNS converte nomes de domínio em endereços IP.
- O HTTPS utiliza TLS para proteger a comunicação entre cliente e servidor.

## 🧠 Interpretação SOC

A análise de tráfego é uma atividade essencial em um SOC. A identificação dos protocolos utilizados permite compreender o comportamento da rede e auxiliar na detecção de atividades suspeitas.

## 📸 Evidências

### ICMP

![ICMP](images/icmp.png)

### ARP

![ARP](images/arp.png)

### DNS

![DNS](images/dns.png)

### HTTPS/TLS

![HTTPS](images/https.png)

## 📌 Conclusão

O laboratório permitiu compreender o funcionamento dos principais protocolos observados em redes corporativas e demonstrou a utilização do Wireshark para análise de tráfego.
