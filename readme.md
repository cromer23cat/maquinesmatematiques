# 🤖 La Màquina de Funcions Matemàtiques

Una aplicació web educativa, interactiva i gamificada dissenyada per a l'alumnat de **Educació Primària** per treballar el pensament algebraic, el reconeixement de patrons i les funcions matemàtiques bàsiques de forma visual i intuïtiva.

![Matemàtiques Primària](https://img.shields.io/badge/Matem%C3%A0tiques-Prim%C3%A0ria-amber)
![HTML5](https://img.shields.io/badge/HTML5-E65100?logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?logo=tailwindcss&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 🌟 Sobre el Projecte

**La Màquina de Funcions** transforma el concepte abstracte de funció matemàtica ($f(x)$) en un joc mecànic i divertit:
* Un número **ENTRA** a la màquina per la canonada superior.
* La màquina aplica una **Norma Secreta** (suma, resta, multiplicació, divisió o operació combinada).
* El número transformat **SURT** per la canonada inferior.

L'objectiu de l'estudiant és analitzar la taula de dades d'entrada i sortida, descobrir el patró o regla matemàtica amagada i deduir el valor correcte de l'última casella marcada amb el signe d'interrogació (`?`).

---

## 🕹️ Funcionalitats i Modes de Joc

* ⚙️ **Animacions i Simulació Visual:** Canonades d'entrada i sortida amb animació de caiguda de boles i engranatges en moviment que reaccionen quan la màquina s'activa.
* 🧪 **Provador / Laboratori de Proves:** Permet a l'estudiant introduir qualsevol número manualment per veure com el transforma la màquina abans de donar la resposta definitiva.
* 🤖 **Assistència en Temps Real (Robo-Codi):** Un robot assistent virtual orienta l'alumnat i dona pistes o feedback educatiu segons els encerts i els intents restants.
* 🔊 **Efectes de So (Web Audio API):** Somatització d'accions amb efectes de so sintetitzats (sons de processament mecànic, encerts i errors) sense dependre d'arxius externs.
* 📊 **Sistema de Puntuació i Vides:** Comptador de punts acumulats, indicador de progrés d'exercicis (5 per ronda) i sistema de cors/intents.
* 🎉 **Feedback Dinàmic:** Animacions de celebració amb confeti (`canvas-confetti`) i revelació de la norma secreta (en text i en notació matemàtica) en completar cada repte.

---

## 🎓 Nivells de Dificultat

L'aplicació compta amb un selector de nivells adaptable a diferents cursos i ritmes d'aprenentatge:

1. 🟢 **Nivell Inicial (Suma / Resta Simple):** 
   * Sumar o restar un número constant a l'entrada (ex: `SURT = ENTRA + 6`, `SURT = ENTRA - 7`).
2. 🔵 **Nivell Intermedi (Multiplicació / Divisió):**
   * Multiplicar o dividir per un factor fix (ex: `SURT = ENTRA × 5`, `SURT = ENTRA / 3`).
3. 🟡 **Nivell Alt (Operacions Combinades):**
   * Processament en dos passos combinats (ex: `SURT = (ENTRA × 2) + 1`, `SURT = (ENTRA × 3) - 2`).
4. 🟣 **Nivell Desafiament (Reptes Avançats):**
   * Nombres més grans, restes inverses (ex: `SURT = 100 - ENTRA`) i divisions combinades.

---

## 🛠️ Tecnologies Utilitzades

* **HTML5 & CSS3:** Estructura semàntica i estils adaptatius.
* **Tailwind CSS (CDN):** Disseny visual modern, paleta de colors espacial/infantil i interfície totalment *responsive* (adaptada a tauletes i pantalles digitals d'aula).
* **JavaScript (Vanilla ES6+):** Lògica del joc, generació d'exercicis, gestió de l'estat i manipulació del DOM.
* **Web Audio API:** Generació de sons i freqüències en temps real.
* **Font Awesome 6 & Google Fonts (Fredoka & Outfit):** Iconografia atractiva i tipografia llegible per a infants.
* **Canvas Confetti:** Efectes visuals de celebració en superar els reptes.

---

## 🚀 Com Executar-ho

No requereix cap instal·lació ni servidor intern. 

1. Clona aquest repositori o descarrega els arxius.
2. Obre el fitxer `index.html` en qualsevol navegador web actualitzat (Chrome, Firefox, Safari, Edge).
3. O bé accedeix directament a través de **GitHub Pages**.

---

## 🏫 Ús Didàctic a l'Aula

Aquesta eina està especialment pensada per a:
* **Treballar l'àlgebra primerenca:** Introduir el concepte de variable i funció sense utilitzar notacions complexes.
* **Fomentar el raonament lògic:** Desenvolupar l'esperit d'investigació a través de la comprovació d'hipòtesis (amb el provador).
* **Ús en Pantalla Digital Interactiva (PDI) o tauletes:** Ideal per a dinàmiques de grup classe o treball autònom.