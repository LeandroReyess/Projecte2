# ⚡ T02: Informe tècnic — Estudi i selecció d’un SAI per a TecnoGestió S.L.

**Nom:** Leandro Linares de los Reyes  
**Data:** 02/10/2025  
**Curs:** SMX2 B  
**Mòdul:** Seguretat  
**Enllaç complet:** [Informe tècnic a Google Docs](https://docs.google.com/document/d/17Y95xV2tYxh0UTtLyEXzIkPZsqqKKUPNeSlX8CMuJZQ/edit?usp=sharing)

---

## 📑 Índex
1. [Descripció del cas](#1-descripció-del-cas)  
2. [Càlculs](#2-càlculs)  
3. [Temps d’autonomia](#3-temps-dautonomia)  
4. [Simulació al proveïdor](#4-simulació-al-proveïdor)  
5. [Solució justificada](#5-solució-justificada)  
6. [Conclusions](#6-conclusions)

---

## 1️⃣ Descripció del cas

L’empresa **TecnoGestió S.L.** disposa de:
- 4 ordinadors de sobretaula  
- 4 monitors  
- 1 impressora multifunció  
- 1 router d’accés a Internet  

Com que hi ha **talls elèctrics freqüents**, es vol instal·lar un **SAI (Sistema d’Alimentació Ininterrompuda)** per protegir els equips i garantir la continuïtat del servei.

**Equips a connectar:**
- 💻 Ordinadors i monitors → *Sí, per evitar pèrdua de dades*  
- 🌐 Router → *Sí, per mantenir connexió bàsica*  
- 🖨️ Impressora → *No, pel consum elevat i baixa prioritat*

---

## 2️⃣ Càlculs

| Dispositiu | Quantitat | Consum (W) | Consum (VA) |
|-------------|------------|-------------|--------------|
| PC sobretaula | 4 | 250 W | 312 VA |
| Monitor LED 24” | 4 | 30 W | 38 VA |
| Router | 1 | 15 W | 19 VA |
| **Total parcial** | — | **1.075 W** | **1.365 VA** |

> 🔹 Amb un 20% de reserva → **1.290 W / 1.638 VA**

👉 El SAI ha de tenir una **capacitat mínima de 1.300 W / 1.650 VA**.

---

## 3️⃣ Temps d’autonomia

Objectiu: mantenir els equips actius durant **mínim 10 minuts** per guardar la feina i apagar amb seguretat.

---

## 4️⃣ Simulació al proveïdor

| Model | Potència (W/VA) | Autonomia (50%) | Sortides | Preu |
|--------|------------------|------------------|-----------|-------|
| **APC Smart-UPS 2200VA** | 1980W / 2200VA | ~12 min | 8 Schuko | ~900 € |
| **Eaton 5PX 2200i RT2U** | 1980W / 2200VA | 9–11 min | 8 IEC | ~950 € |
| **Riello Vision Dual 2200** | 1760W / 2200VA | ~10 min | Schuko + IEC | ~750 € |

---

## 5️⃣ Solució justificada

✅ **Model recomanat:** *APC Smart-UPS 2200VA (SMT2200I)*  
**Motivació:**
- Potència sobrada: 1980 W vs 1290 W requerits  
- Autonomia superior als 10 minuts  
- Marca fiable i amb servei tècnic  
- Sortides Schuko adequades per a oficina  

---

## 6️⃣ Conclusions

Amb la implantació del **SAI APC Smart-UPS 2200VA**, TecnoGestió S.L. obtindrà:

- 🔒 Protecció davant talls elèctrics  
- ⚙️ Continuïtat del servei durant incidències breus  
- 💾 Apagat segur dels sistemes  
- 💰 Solució professional amb cost raonable (~900 €)

> En resum: el SAI proposat garanteix seguretat, estabilitat i eficiència energètica dins d’un entorn d’oficina professional.

---

## 📄 Contingut

- **[solució.md](./solució.md)** — Documentació completa de la tasca.
- **Carpeta [IMG/](./IMG/)** — Imatges i captures de pantalla utilitzades a la documentació.

---

> 🖇️ [Fes clic aquí per accedir directament a la solució](./solució.md)

