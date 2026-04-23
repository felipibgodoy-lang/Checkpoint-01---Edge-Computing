# 🍷 Sistema de Monitoramento de Luminosidade

## 📌 Checkpoint 01 - Edge Computing

---

## 👥 Integrantes

* **Arthur Caram Fiorese Herrada** - RM: 569578
* **Felipe Ricardo Moreira Aguiar** - RM: 573410
* **Felipi Bandeira de Godoy** - RM: 573741
* **Gustavo Ferreira Silva** - RM: 571675
* **Matheus Medeiros da Cunha** - RM: 572780

---

## 📖 Descrição do Projeto

Este projeto tem como objetivo desenvolver um sistema de monitoramento de luminosidade para a **Vinheria Agnello**, utilizando Arduino e um sensor LDR (*Light Dependent Resistor*).

A proposta surge da necessidade de manter condições ideais de armazenamento dos vinhos, já que a exposição excessiva à luz pode comprometer sua qualidade, alterando suas propriedades químicas.

---

## 🎯 Estados do Sistema

* 🟢 **Condição adequada**
* 🟡 **Nível de alerta**
* 🔴 **Condição crítica**

---

## ⚙️ Funcionamento

O sensor LDR capta a intensidade luminosa do ambiente e envia um sinal analógico ao Arduino, que interpreta esses valores e aciona os dispositivos de saída conforme os limites definidos:

| Estado      | Ação                         |
| ----------- | ---------------------------- |
| 🟢 Adequado | LED verde aceso              |
| 🟡 Alerta   | LED amarelo aceso            |
| 🔴 Crítico  | LED vermelho + buzzer por 3s |

> ⚠️ Caso a luminosidade permaneça crítica, o buzzer será acionado novamente.

---

## 🧰 Componentes

* 1x Arduino (Uno ou similar)
* 1x Sensor LDR
* 4x Resistores
* 3x LEDs (verde, amarelo e vermelho)
* 1x Buzzer
* 1x Protoboard
* 13x Jumpers

---

## 💻 Simulação

* 🔗 Tinkercad (modo editor): *(https://www.tinkercad.com/things/5vje9jUHpd1-cp1-edge-/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=5w4zcdQE6STZ0iBKhwvKRyUI7zBJMZrZlxJ4tXw8xbo)*

---

## 🚀 Como Executar

1. Monte o circuito (simulação ou físico)
2. Conecte o LDR na entrada analógica
3. Configure LEDs e buzzer nas portas digitais
4. Envie o código para o Arduino
5. Teste variando a luminosidade

---

## 🎥 Vídeo

📹 *Vídeo YouTube: (https://youtu.be/dBjjVYqXtDc?si=SxgaZQPMbuNwQFhK)*

---

## ⚠️ Desafios

* Calibrar níveis de luminosidade
* Interpretar valores analógicos
* Definir limites adequados

✔️ Resolvido com testes práticos e ajustes no código.

---

## 📌 Conclusão

O projeto demonstra a aplicação prática de **Edge Computing**, permitindo decisões em tempo real diretamente no dispositivo.

Além disso, reforça o uso da tecnologia para preservar produtos sensíveis como o vinho.

---
