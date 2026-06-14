### ICMP

Comando executado:

```bash
ping -c 4 8.8.8.8
```

Foram observados pacotes Echo Request e Echo Reply utilizados para validar a conectividade.

![ICMP](images/icmp-capture.png)

---

### ARP

Foram capturadas requisições e respostas ARP utilizadas para resolução de endereços IP em endereços MAC.

![ARP](images/arp-capture.png)

---

### DNS

Foi realizada uma consulta DNS para observar a resolução de nomes de domínio.

![DNS](images/dns-capture.png)

---

### HTTPS/TLS

Foi acessado um site utilizando HTTPS para observar o estabelecimento de uma conexão segura utilizando TLS.

![HTTPS](images/https-capture.png)

O laboratório permitiu compreender o funcionamento dos principais protocolos observados em redes corporativas e demonstrou a utilização do Wireshark para análise de tráfego.
