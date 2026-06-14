# 🧪 LAB 01 – Network Basics

## 🎯 Objetivo

Compreender conceitos básicos de rede em Linux e validar a conectividade da máquina.

## 🛠️ Ferramentas utilizadas

* Terminal Linux

## 💻 Comandos executados

```bash
ip a
arp -a
ping -c 4 8.8.8.8
ip route
```

## 🔍 Resultados Obtidos

### ip a

Identificação do endereço IP da máquina virtual e da interface de rede ativa.

### arp -a

Verificação da tabela ARP para identificar o gateway da rede.

### ping -c 4 8.8.8.8

Teste de conectividade com a internet utilizando o DNS público do Google.

### ip route

Análise da rota padrão utilizada para comunicação externa.

## 🧠 Análise

A máquina recebeu o endereço IP 10.0.2.15 e utiliza o gateway 10.0.2.2 para acessar redes externas. O teste de conectividade foi concluído com sucesso, sem perda de pacotes, demonstrando comunicação funcional com a internet.

## 📌 Conclusão

O laboratório permitiu validar conceitos fundamentais de redes, incluindo endereçamento IP, resolução ARP, conectividade ICMP e roteamento básico.


