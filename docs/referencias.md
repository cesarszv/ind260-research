---
author: Cesar Sebastian Zambrana Ventura
name: Referencias
description: Estado de cada fuente y dónde buscar las que faltan
date: 2026-09-16
---

# Referencias

Tres estados:

- **Verificada**: confirmé los datos bibliográficos contra la fuente o su registro oficial.
- **Por leer**: la fuente existe pero todavía no la abrí. No la cito para afirmar contenido.
- **Falta**: hueco abierto. Todavía no hay fuente.

| # | Fuente | Estado | Para qué la uso |
| ---: | --- | --- | --- |
| [1] | OMS, *WHO Guidelines on Physical Activity and Sedentary Behaviour*, 2020 | Verificada, por leer | Recomendación de 150 a 300 min/semana y riesgos de estar sentado |
| [2] | Tremblay *et al.*, SBRN Terminology Consensus Project, *IJBNPA* 14:75, 2017 | Verificada, por leer | Definición de comportamiento sedentario |
| [3] | Craig *et al.*, IPAQ 12-country reliability and validity, *MSSE* 35(8), 2003 | Verificada, por leer | Validez del cuestionario y protocolo de puntuación |
| [4] | Validez del IPAQ corto en español, universitarios | **Falta** | Limitación: el autorreporte sobreestima |
| [5] | OMS, *Obesity: Preventing and Managing the Global Epidemic*, TRS 894, 2000 | Por leer | Cortes del IMC |
| [6] | Hernández Sampieri *et al.*, 6.ª ed., 2014 | En el repositorio de la materia | Estructura del planteamiento cuantitativo |
| [7] | Vargas Beal, 2011 | En el repositorio de la materia | Métodos y técnicas para la tabla de metodología |
| [8] | Sobrepeso y obesidad en adultos, Bolivia y Santa Cruz | **Falta** | Contexto del planteamiento y relevancia social |
| [9] | Estudios de actividad física en universitarios | **Falta** | Antecedentes y comparación del objetivo 5 |

Datos de verificación, por si tengo que rastrearlos: [1] repositorio IRIS de la OMS y PubMed
33239350, ISBN 978-92-4-001512-8. [2] PubMed 28599680, doi 10.1186/s12966-017-0525-8. [3] PubMed
12900695, doi 10.1249/01.MSS.0000078924.61453.FB.

## Dónde buscar las que faltan

### [4] IPAQ en español

Hay dos líneas publicadas: un estudio de validez de constructo en universitarios españoles
(Redalyc y repositorio de la Universidad de Vigo) y uno de fiabilidad en universitarios chilenos.
Cualquiera sirve; elijo la que pueda abrir completa.

```
("IPAQ" OR "Cuestionario Internacional de Actividad Física") AND (validez OR fiabilidad) AND universitarios
```

Buscar también el protocolo oficial de puntuación del IPAQ, que es un documento aparte del
artículo de Craig y es lo que realmente necesito para calcular MET-min/semana.

### [8] Bolivia y Santa Cruz

En este orden: INE Bolivia (Encuesta de Demografía y Salud, módulo de salud), Ministerio de Salud
y Deportes, OMS/OPS Global Health Observatory, y SciELO Bolivia para ubicar fuentes nacionales.

No citar prensa. Los medios reportan cifras de la EDSA y del World Obesity Atlas; si la cifra me
sirve, voy al documento original.

```
site:ine.gob.bo obesidad sobrepeso adultos
Bolivia prevalencia obesidad adultos departamento Santa Cruz encuesta demografía salud
```

### [9] Antecedentes

Hay bastante con IPAQ en universitarios (Alemania, Reino Unido, comparaciones multinacionales). Lo
escaso es el corte por carrera de computación o ingeniería, y eso mismo es mi vacío: si no
encuentro un estudio específico, lo digo así en los antecedentes en lugar de forzar una fuente.

```
IPAQ "university students" "sedentary behaviour" prevalence cross-sectional
("engineering students" OR "computer science students") AND ("physical activity" OR "sedentary")
estudiantes universitarios sedentarismo actividad física IPAQ Latinoamérica
```

PubMed y Google Scholar primero, SciELO para América Latina.

## Reparto para la matriz (Tarea #4)

La tarea pide 4 o 5 fuentes. Así cubro el perfil completo sin repetir:

| Para qué | Fuente |
| --- | --- |
| Umbral de actividad física | [1] |
| Definición de comportamiento sedentario | [2] |
| Instrumento | [3] o [4] |
| Contexto local | [8] |
| Antecedente comparable | [9] |
