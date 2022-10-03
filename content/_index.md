+++
title = "Simualazione di evacuazione di folle con micro-interazioni fisiche ed elementi cognitivi"
outputs = ["Reveal"]
+++

# Agenti cognitivi in Alchemist per la simulazione di evacuazioni di folle

# **Stato dell'arte**

---

# OVERVIEW

1. Modello del pedone cognitivo
    - Modello IMPACT
    - Il pedone cognitivo
    - Movimento del pedone cognitivo

2. Modello di mappa mentale per l'orientamento dei pedoni cognitivi
    - Grafo dell'ambiente e mappa cognitiva
    - Pedoni con capacità di orientamento
    - Comportamento dei pedoni

3. Modello fisico del movimento del pedone cognitivo
    - Il modello HiDAC
    - Forze di evitamento e repulsione
    - Cadute e spinte

4. Simulazione Evacuazione di folla in Piazza San Carlo, Torino

---

# Modello del pedone cognitivo

---

## Il modello IMPACT

Nasce con l'obiettivo di non limitarsi alle sole leggi fisiche nella modellazione
di agenti ma considerare le caratteristiche socio-culturali nonche una component emotiva
fortemente infuenzabile.


Ogni agente e contraddistinto da:
- età (bambino, adulto, anziano); 
- sesso (uomo, donna).

---

## Il modello IMPACT

Le combinazioni di questi due attributi determinano un insieme di caratteristiche statiche e dinamiche.

Le prime si mantengono tali per la durata della simulazione mentre le altre evolvono seguendo i principi del 
Network Oriented Modelling

<table>
    <tr>
        <th colspan="2">Caratteristiche</th>
    </tr>
    <tr>
        <td>STATICHE</td>
        <td>ATTIVE</td>
    </tr>
    <tr>
        <td>
            <ul>
                <li>Velocità</li>
                <li>Conformità alle regole</li>
                <li>Attidudine ad aituare</li>
            </ul>
        </td>
        <td>
            <ul>
                <li>Sensazione di pericolo</li>
                <li>Paura</li>
                <li>Desiderio/Intenzione di fuggire</li>
                <li>Desiderio/Intenzione di non fuggire</li>
            </ul>
        </td>
    </tr>
</table>

--- 

## Il pedone cognitivo

Esistono tre livelli di dettaglio nella rappresentazione di un pedone:

* **Pedone omogeneo**: pedone con una velocita predefinita di camminata e di corsa uguale per tutti;
* **Pedone eterogeneo**: pedone con un sesso e un eta assegnati, dai quali saranno determinate velocita, conformita alle regole e
attitudine ad aiutare;
* **Pedone cognitivo**: pedone eterogeneo con delle emozioni, capace di influenzare e farsi influenzare dagli altri.

---

## Movimento del pedone cognitivo

I movimenti del pedone cognitivo in Alchemist seguono i comportamenti di steering introdotti da Reynolds.
Hanno la funzione di muovere in maniera autonoma e realistica gli agenti sui quali non si possiede controllo.
I comportamenti di steering sono basati sulla semplice formula:

steering = desired_velocity - current_velocity

---

# Modello di mappa mentale per l'orientamento dei pedoni cognitivi

---

## Grafo dell'ambiente
## Pedoni con capacità di orientamento
## Comportamento dei pedoni

---

# Modello fisico del movimento del pedone cognitivo

---

## Il modello HiDAC
## Forze di evitamento e di repulsione
## Cadute e spinte

--- 

# Simulazione
## Evacuazione di folla in Piazza San Carlo, Torino

---

## Descrizione

---

## Risultati

---
