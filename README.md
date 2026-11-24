# Mòdul Odoo: School Plus

![CFGS DAM](https://img.shields.io/badge/CFGS-Desenvolupament%20d%27Aplicacions%20Multiplataforma%20%28DAM%29-green?style=for-the-badge)
![SGE](https://img.shields.io/badge/assignatura-Sistemes%20de%20Gesti%C3%B3%20Empresarial-purple?style=for-the-badge)

Ampliació del mòdul [`school`](https://github.com/sarapratsm/SGE_P1_Odoo_modul_school) per gestionar l'alumnat i les seves matriculacions. Pràctica 2 de l'assignatura de Sistemes de Gestió Empresarial (SGE) del CFGS de Desenvolupament d'Aplicacions Multiplataforma (Institut Milà i Fontanals, Igualada).

## Models

| Model | Descripció |
|---|---|
| `school.student` | Alumnat (nom, cognoms, país i província). |
| `school.enrollment` | Matrícula d'un alumne en una edició d'un curs. |
| `school.enrollment.subject` | Qualificació de cada assignatura dins d'una matrícula. |
| `res.partner` (ampliat) | Relaciona els contactes amb l'alumnat. |

## Funcionalitats

- Assistent *Edition enrollment* que, per a una edició, mostra quants alumnes hi estan matriculats, quants han aprovat (nota >= 5) i quants han suspès.
- Informe PDF d'alumne.
- Vistes, accions, menús i permisos propis.

## Instal·lació

1. Instal·la primer el mòdul `school` (pràctica 1), ubicat en una carpeta anomenada `school`.
2. Copia aquest mòdul al directori `addons`, reinicia Odoo i actualitza la llista d'aplicacions.
3. Instal·la **school_plus**. Dependències: `base`, `account` i `school`.

## Autoria

Sara Prats Morales · Llicència LGPL-3
