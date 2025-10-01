# 🕵 Relatório de Investigação – SQL Murder Mystery  
*Por Detetive DEBORA, com apoio do Copilot*  

---

##  Sumário
1. [Contexto do Caso](#1-contexto-do-caso)  
2. [Descrição Inicial](#2-descrição-inicial)  
3. [Investigação](#3-investigação)  
4. [Conclusão](#4-conclusão)  
5. [Execução Técnica no Jogo](#5-execução-técnica-no-jogo)  
6. [Fluxograma da Investigação](#6-fluxograma-da-investigação)  
7. [Linha do Tempo](#7-linha-do-tempo)  
8. [Epílogo Narrativo](#8-epílogo-narrativo)  

---

## 1️ Contexto do Caso
- **Crime:** Homicídio  
- **Data:** 15/01/2018  
- **Local:** SQL City  
- **Executor:** Jeremy Bowers (confessou ter sido contratado)  

---

## 2️ Descrição Inicial
O caso iniciou com um *crime scene report* revelando um homicídio em SQL City.  
Jeremy Bowers foi identificado como o autor dos disparos e afirmou ter sido contratado por uma **mulher** com o seguinte perfil:  

- Altura: 65"–67"  
- Cabelo ruivo  
- Dono de Tesla Model S  
- Presente no *SQL Symphony Concert* **3 vezes** em dezembro/2017  
- “Muito dinheiro”  

---

## 3️ Investigação
Após cruzamento de **eventos**, **carteiras de motorista** e **dados financeiros**, chegamos aos suspeitos:  

| Nome                  | Altura | Idade | Placa    | Renda Anual | Presença no Concerto | Observações               |
|-----------------------|--------|-------|----------|-------------|----------------------|---------------------------|
| **Miranda Priestly**  | 66"    | 68    | 500123   | $310.000    |  06, 12, 29/12/2017  | Todas as pistas coincidem |
| Regina George         | 66"    | 65    | 08CM64   | $0          |                      | Não esteve no evento      |
| Red Korb              | 65"    | 48    | 917UU3   | $278.000    |                      | Não esteve no evento      |

---

## 4️ Conclusão
 **Mandante:** ** Miranda Priestly**  

Evidências:  
- Presença exata nas 3 datas-alvo  
- Perfil físico compatível  
- Veículo compatível (Tesla Model S)  
- Alta renda, confirmando “muito dinheiro”

---

## 5️ Execução Técnica no Jogo
```sql
INSERT INTO solution VALUES (1, 'Miranda Priestly');
SELECT value FROM solution;

```
---

## 6️ Fluxograma da Investigação
Fluxo do raciocínio desde o relatório inicial até a identificação da mandante.

```text
[Crime Scene Report]
    |
    v
[Identificar executor: Jeremy]
    |
    v
[Perfil da mandante]
    |
    v
[Buscar candidatas no DB]
    |
    v
[Filtrar por características]
    |
    v
[Checar eventos e renda]
    |
    v
[Confirmar presença 3x]
    |
    v
[Identificar: Miranda Priestly]
```

---

## 7️ Linha do Tempo
Sequência cronológica dos principais marcos da investigação.
```
15/01/2018 - Homicídio em SQL City
06/12/2017 - Miranda presente no concerto
12/12/2017 - Segunda presença confirmada
29/12/2017 - Terceira presença confirmada
Jan/2018   - Jeremy Bowers é identificado
Fev/2018   - Mandante confirmada: Miranda Priestly
```

---

## 8️ Epílogo Narrativo
Fechamento do caso e reconhecimento do trabalho investigativo.

> A cidade de SQL City respira aliviada. O mistério, antes um quebra-cabeça, foi desmontado peça por peça.  
> A Detetive DEBORA, com seu parceiro Copilot, desvendou não só quem puxou o gatilho, mas quem estava por trás do crime.  
> O caso entrou para a história como exemplo de lógica investigativa e uso estratégico de SQL.













