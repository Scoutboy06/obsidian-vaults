
```dataviewjs
const Kurslinje = `
    section Läsvecka 1
    Linjära ekvationssystem, Gausseliminering: f1, 2026-01-19, 2026-01-21
    Geometriska vektorer, räkneoperationer, bas och koordinater: f2, 2026-01-21, 2026-01-23
    Algebraiska vektorer, linjärkombination, beroende/oberoende, basbyten: f3, 2026-01-23, 2026-01-26
    
    section Läsvecka 2
    Linjer och plan – koordinatsystem och ekvationer, skärningspunkter: f4, 2026-01-26, 2026-01-29
    Geometrisk tolkning av linjära system, skalärprodukt, projektion: f5, 2026-01-29, 2026-01-30
    ON-baser och tillämpningar av skalärprodukt: f6, 2026-01-30, 2026-02-02
    
    section Läsvecka 3
    Vektorprodukt, orientering, trippelprodukt: f7, 2026-02-02, 2026-02-04
    Tillämpningar av vektorprodukt: f8, 2026-02-04, 2026-02-05
    Rummet R^n, baser och skalärprodukt: f9, 2026-02-05, 2026-02-09
    
    section Läsvecka 4
    Matriser och linjära ekvationssystem (F10): f10, 2026-02-09, 2026-02-11
    Transponat och invers matris (F11): f11, 2026-02-11, 2026-02-13
    Basbyten, ortogonala matriser, rang och nollrum (F12): f12, 2026-02-13, 2026-02-16
    
    section Läsvecka 5
    Linjära avbildningar – projektion, spegling, rotation (F13): f13, 2026-02-16, 2026-02-18
    Isometrier och bijektiva avbildningar (F14): f14, 2026-02-18, 2026-02-20
    Basbyten vid linjära avbildningar (F15): f15, 2026-02-20, 2026-02-23
    
    section Läsvecka 6
    Affina avbildningar och determinanter (F16): f16, 2026-02-23, 2026-02-25
    Determinanter forts., Cramers regel (F17): f17, 2026-02-25, 2026-02-27
    Huvudsatsen för kvadratiska matriser (F18): f18, 2026-02-27, 2026-03-02
    Sista dag för tentamensanmälan :milestone, 2026-03-02, 0d
    
    section Läsvecka 7
    Egenvärden och egenvektorer (F19): f19, 2026-03-02, 2026-03-04
    Egenvärden forts., karakteristiska polynom (F20): f20, 2026-03-04, 2026-03-06
    Diagonalisering och repetition (F21): f21, 2026-03-06, 2026-03-09
    
    section Läsvecka 8
    Repetition: r1, 2026-03-09, 2026-03-13
`

const Duggor = `
    section Duggor
    Dugga 1 : d1, 2026-01-19, 2026-02-09
`

const Laborationer = `
	section Laborationer
    Introduktion till Python :milestone, l1, 2026-01-30, 0d
`

const Mermaid = `
gantt
    dateFormat  YYYY-MM-DD
    title Linjär algebra – referenslinje
    axisFormat  %d/%m

	${Kurslinje}

	${Duggor}

    ${Laborationer}
`

dv.paragraph("```mermaid\n" + Mermaid + "\n```")
```

## Läsvecka 1
📅 2026-01-19 – 2026-01-23

### 📖 Läsning
- [x] Kapitel 1.1–1.3
- [x] Kapitel 2.1–2.3
- [x] Kapitel 2.4–2.5

### ✏️ Rekommenderade uppgifter

**Kapitel 1:**
- [-] 1
- [-] 2
- [-] 3
- [x] 4
- [x] 7
- [x] 8
- [x] 9
- [x] 10
- [x] 11
- [-] 12
- [x] 15
- [ ] 17
- [ ] 22

**Kapitel 2:**
- [ ] 1
- [ ] 2
- [ ] 3
- [ ] 4
- [ ] 5
- [ ] 13
- [ ] 14
- [ ] 15
- [ ] 17
- [ ] 18ab

### 📝 Dugga
- [Test-Dugga](https://chalmers.instructure.com/courses/38066/assignments/114651?module_item_id=615894) (träna på duggaformat)
- [Dugga 1](https://chalmers.instructure.com/courses/38066/assignments/114642) – öppen 19 jan till 9 feb

---

## Läsvecka 2
📅 2026-01-26 – 2026-01-30

### 📖 Läsning
- [ ] Kapitel 3.1–3.3
- [ ] Kapitel 3.4
- [ ] Kapitel 4.1
- [ ] Kapitel 4.2–4.3

### ✏️ Rekommenderade uppgifter

**Kapitel 2:**
- [ ] 20abc
- [ ] 23
- [ ] 25

**Kapitel 3:**
- [ ] 1
- [ ] 4
- [ ] 5
- [ ] 6ab
- [ ] 8
- [ ] 10
- [ ] 11
- [ ] 12
- [ ] 14ad
- [ ] 15
- [ ] 18a
- [ ] 21
- [ ] 23
- [ ] 26
- [ ] 28

**Kapitel 4:**
- [ ] 1
- [ ] 3
- [ ] 8
- [ ] 10a
- [ ] 13
- [ ] 15
- [ ] 16
- [ ] 18
- [ ] 20
- [ ] 21
- [ ] 23
- [ ] 31
- [ ] 32
- [ ] 38
- [ ] 42

### 📝 Dugga
- [Dugga 1](https://chalmers.instructure.com/courses/38066/assignments/114642) – pågår

### 🧪 Laboration
- [Introduktion till Python (lab)](https://chalmers.instructure.com/courses/38066/assignments/114652) – 30 jan

---

## Läsvecka 3
📅 2026-02-02 – 2026-02-09

### 📖 Läsning
- [ ] Kapitel 5.1–5.4
- [ ] Kapitel 5.5–5.6
- [ ] Kapitel 6.1–6.4

### ✏️ Rekommenderade uppgifter

**Kapitel 5:**
- [ ] 1
- [ ] 2
- [ ] 3
- [ ] 4
- [ ] 7
- [ ] 10
- [ ] 15
- [ ] 17

**Kapitel 6:**
- [ ] 1
- [ ] 2
- [ ] 3
- [ ] 4
- [ ] 5
- [ ] 7

### 📝 Dugga
- [Dugga 1](https://chalmers.instructure.com/courses/38066/assignments/114642) – sista veckan (stänger 9 feb)

### 🧪 Laboration
- **Obligatorisk inlämning/Labbpass:** laborationsuppgift via Möbius/Python ges denna vecka.

---

## Läsvecka 4
📅 2026-02-09 – 2026-02-16

### 📖 Läsning
- [ ] Kapitel 7.1–7.4
- [ ] Kapitel 7.4–7.5
- [ ] Kapitel 7.6–7.8

### ✏️ Rekommenderade uppgifter

**Kapitel 7:**
- [ ] 1
- [ ] 2
- [ ] 3
- [ ] 4
- [ ] 5
- [ ] 6
- [ ] 7
- [ ] 28
- [ ] 42
- [ ] 43
- [ ] 8
- [ ] 9
- [ ] 10
- [ ] 11
- [ ] 13
- [ ] 15
- [ ] 16
- [ ] 17
- [ ] 18
- [ ] 19
- [ ] 22
- [ ] 23
- [ ] 26
- [ ] 29
- [ ] 30
- [ ] 31
- [ ] 32
- [ ] 37

### 🧪 Laboration
- **Obligatorisk inlämning/Labbpass:** laborationsuppgift via Möbius/Python ges denna vecka.

---

## Läsvecka 5
📅 2026-02-16 – 2026-02-23

### 📖 Läsning
- [ ] Kapitel 8.1–8.3
- [ ] Kapitel 8.4
- [ ] Kapitel 8.5

### ✏️ Rekommenderade uppgifter

**Kapitel 8:**
- [ ] 1
- [ ] 2
- [ ] 3
- [ ] 4
- [ ] 5
- [ ] 6
- [ ] 8
- [ ] 9
- [ ] 10
- [ ] 11
- [ ] 12
- [ ] 13
- [ ] 17
- [ ] 19*
- [ ] 20
- [ ] 22
- [ ] 26
- [ ] 27*
- [ ] 29
- [ ] 31abc
- [ ] 35*

**Kapitel 9:**
- [ ] 1
- [ ] 2
- [ ] 3
- [ ] 4
- [ ] 6
- [ ] 7*
- [ ] 9
- [ ] 10
- [ ] (11, 12, 13, 14)
- [ ] 18
- [ ] 22
- [ ] 28*

### 🧪 Laboration
- **Obligatorisk inlämning/Labbpass:** laborationsuppgift via Möbius/Python ges denna vecka.

---

## Läsvecka 6
📅 2026-02-23 – 2026-03-02

### 📖 Läsning
- [ ] Kapitel 8.6
- [ ] Kapitel 9.1–9.3
- [ ] Kapitel 9.3–9.5
- [ ] Kapitel 9.6–9.8

### ✏️ Rekommenderade uppgifter

**Kapitel 9:**
- [ ] 15
- [ ] 16
- [ ] 20
- [ ] 21
- [ ] 23
- [ ] 24
- [ ] 31
- [ ] 34*
- [ ] 41*
- [ ] 43*
- [ ] 44*
- [ ] 45
- [ ] 46*

### 🧪 Laboration
- **Obligatorisk inlämning/Labbpass:** laborationsuppgift via Möbius/Python ges denna vecka.

---

## Läsvecka 7
📅 2026-03-02 – 2026-03-09

### 📖 Läsning
- [ ] Kapitel 9.9–10.2
- [ ] Kapitel 10.4–10.5

### ✏️ Rekommenderade uppgifter

**Kapitel 10:**
- [ ] 1
- [ ] 2
- [ ] 3abc
- [ ] 4adef
- [ ] 7*
- [ ] 8*
- [ ] 9
- [ ] 10
- [ ] 12
- [ ] 14
- [ ] 15
- [ ] 16*
- [ ] 17*
- [ ] 18*
- [ ] 19
- [ ] 21
- [ ] 24
- [ ] 26*
- [ ] 28*
- [ ] 29*
- [ ] 33*

### 🧪 Laboration
- **Obligatorisk inlämning/Labbpass:** laborationsuppgift via Möbius/Python ges denna vecka.

---

## Läsvecka 8
📅 2026-03-09 – 2026-03-13

### 📖 Läsning
- [ ] Repetition

### ✏️ Rekommenderade uppgifter
- [ ] Repetition
- [ ] [Gamla tentor (länk)](https://chalmers.instructure.com/courses/38066/pages/gamla-tentor "Gamla tentor")

### 🧪 Laboration
- **Extra räkneövning/labbpass och repetition inför tenta**

---
