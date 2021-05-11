---
title: "Sirena"
permalink: /units/Mermaid/
excerpt: "Era of Chaos Sirena. Sirena Unità. null. Era of Chaos Figlia e protetta del mare, è in grado di sfruttare il potere delle acque per lanciare incantesimi di guarigione."
unitID: 9905
last_modified_at: 2021-05-11
locale: it
ref: "Sirena"
toc: true
---
  ![Sirena](/images/u/ti_meirenyu.jpg)

## General information
 **Descrizione:** Figlia e protetta del mare, è in grado di sfruttare il potere delle acque per lanciare incantesimi di guarigione.

 **Classe:** [Incantatore](/it/units/Unit Class Caster/)

 **Classe Descrizione:** Grazie alla completa padronanza delle arti magiche, gli incantatori sono più resistenti agli incantesimi.

 **Fazione:** [Baia](/it/units/Faction Cove/)

 **Race:** Terre sommerse

 **Members:** [x4](/it/units/Unit Member x4/)

 **Rango:** [SR](/it/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/it/units/Star 3/)

 **Unit Soul:** [Sirena](/ItemsIT/unt_277/)

 **Short description:** Guarigione ad area. Buff potenti.

 **Position :** Guaritore eccezionale. Applica potenti buff a inizio battaglia.

## Statistiche base
 **Base HP: 1648.0**

 **Base ATK: 185.0**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Verde | 92.5 | 3.5 | 1236.0 |
  | Blu | 185.0 | 7.0 | 2472.0 |
  | Blu +1 | 277.5 | 10.5 | 3708.0 |
  | Blu +2 | 388.5 | 14.7 | 5191.2 |
  | Viola | 499.5 | 18.9 | 6674.4 |
  | Viola +1 | 610.5 | 23.1 | 8157.6 |
  | Viola +2 | 740.0 | 28.0 | 9888.0 |
  | Viola +3 | 869.5 | 32.9 | 11618.4 |
  | Arancione | 999.0 | 37.8 | 13348.8 |
  | Arancione +1 | 1147.0 | 43.4 | 15326.4 |
  | Arancione +2 | 1295.0 | 49.0 | 17304.0 |
  | Arancione +3 | 1443.0 | 54.6 | 19281.6 |
  | Arancione +4 | 1591.0 | 60.2 | 21259.2 |
  | Arancione +5 | 1813.0 | 68.6 | 24225.6 |
  | Rosso | 2109.0 | 79.8 | 28180.8 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 25.9 | 0.56 | 2.54 | 230.72 |
  | **4x** <i class="fas fa-star"/> | 29.6 | 0.59 | 3.11 | 263.68 |
  | **5x** <i class="fas fa-star"/> | 33.3 | 0.61 | 3.68 | 296.64 |
  | **6x** <i class="fas fa-star"/> | 37.0 | 0.64 | 4.25 | 329.6 |

## Equipaggiamento

  | I | Equipaggiamento  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Organo marino](/images/e/e_99051.png) | [Organo marino](/it/equipment/Sea Organ/) | **ATT** | **DIF** | 
  | ![Orecchini da Tritone](/images/e/e_99052.png) | [Orecchini da Tritone](/it/equipment/Merman Earrings/) | **PF** | **DIF** | 
  | ![Coda di pesce flessibile](/images/e/e_99053.png) | [Coda di pesce flessibile](/it/equipment/Flexible Fishtail/) | **ATT** | **DIF** | 
  | ![Protezione dell'oceano](/images/e/e_99054.png) | [Protezione dell'oceano](/it/equipment/Ocean's Protection/) | **PF** | **DIF** | 

## Esclusivo

 **Nome:** [Maree notturne](/it/Exclusive/Mermaid Night Tides/) 

 **Is Open:** - 

 **Item to Rango ↑:** [Token Maree notturne](/ItemsIT/con_1004/)

 **Skin:** [Skin speciale Maree notturne](/ItemsIT/con_672/)


## Emblemi sacri consigliati

* [Colpevolezza di Tarnum](/it/Emblem/Tarnum's Culpability/) (Neutrale)
* [Principi legali dei successori](/it/Emblem/Successors' Legal Principles/) (Neutrale)

## Informazioni combinazione

  none

## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Tecnica suprema: Accordo di Re
 **Descrizione:** <span style="color: #645252;font-size:20px">L'attacco della Sirena ha effetti curativi: cura l'unità alleata con la percentuale di PF più bassa di una quantità di PF pari a </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> dell'ATT della Sirena. Inoltre, cura 1 unità casuale. L'effetto aggiuntivo può essere attivato 3 volte. L'effetto di cura è pari a </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">/</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">/</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> dell'ATT della Sirena.</span><span style="color: black">

### Tecnica normale 1 : Canto imperituro
 **Descrizione:** <span style="color: #645252;font-size:20px">All'inizio della battaglia, la Sirena aumenta DAN (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">) e CRIT (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">) di tutte le unità alleate. Ogni 2 secondi, il DAN si riduce del 2% e il CRIT di 50, fino a un massimo di 10 volte. L'effetto dura 20 secondi. Durata raddoppiata e riduzione dimezzata per le unità Baia.</span><span style="color: black">

### Tecnica normale 2 : null
 **Descrizione:** 

### Tecnica normale 3 : Canto ceruleo
 **Descrizione:** <span style="color: #645252;font-size:20px">Guarigione della Sirena aumentata (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">). Quando la Sirena emette un &lt;Accordo di Re&gt;, rimuove tutti i debuff dall'unità alleata con la percentuale di PF minore.</span><span style="color: black">

### Tecnica speciale fazione I : Pace interiore
 **Descrizione:** <span style="color: #645252;font-size:20px">Le unità Baia sanno come muoversi all'interno delle tempeste. Se equipaggiate con un Emblema sacro, i loro PF aumentano (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">) e hanno una probabilità del 40% di resistere allo &lt;Stordimento&gt;.</span><span style="color: black">

### Tecnica speciale fazione II : Conflitto piratesco
 **Descrizione:** <span style="color: #645252;font-size:20px">Le unità Baia sono esperte negli scontri navali. Quando affrontano unità non Baia, il loro danno aumenta (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str9"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*1+5)"
    let str8 = "(LEVEL*1+5)"
    let str5 = "(LEVEL*1+9)"
    let str6 = "(LEVEL*20+280)"
    let str3 = "(LEVEL*1+9)"
    let str4 = "(LEVEL*0.5+4.5)"
    let str1 = "(LEVEL*4+36)"
    let str2 = "(LEVEL*2+18)"
    let str9 = "(LEVEL*1+5)"
    let res="ERR";
    try {
     res = eval(str7); document.getElementById('str7').textContent = res;
     res = eval(str8); document.getElementById('str8').textContent = res;
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
     res = eval(str9); document.getElementById('str9').textContent = res;
    } catch (e) { log.textContent = "Issue with calculation!";}
    if (event!=null)
      event.preventDefault();
  }
  const form = document.getElementById('form');
  const log = document.getElementById('log');
  form.addEventListener('submit', skillCalc);
  window.onload = skillCalc;
  </script>
## Connessione
### Connessione roster

* **Baia**  (Roster Baia)
* **Incantatore**  (Roster incantatori)
* **SR**  (SR)

### Bonus eroe
* [Dracon](/it/heroes/Dracon/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Cassanbel](/it/heroes/Cassanbel/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talento

* Attacco
* PF
* Velocità d'attacco
* Guarigione

 **:** [Pozione di Talento Incantatori](/ItemsIT/con_790/)


## Awaking

  ![null](/images/u/tia_meirenyu.jpg)

### Awaking Dettagli
 **Is it possible right now?** NO

 **Awaking Name:** null

 **Awaking Descrizione:** 

### Awaking Tasks
 1. 

 2. 

 3. 

 4. 

## Awaken Skills

### 1st Skill (or 2nd): null
 **Descrizione:** 

### 2nd Skill (or 1st): null
 **Descrizione:** 

### 3rd Skill (or 4th): null
 **Descrizione:** 

### 4th Skill (or 3rd): null
 **Descrizione:** 

### 5th Skill (or 6th): null
 **Descrizione:** 

### 6th Skill (or 5th): null
 **Descrizione:** 

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 4.0

 **Rush:** 3

 **Speedattack:** 60

 **Attack Show:** 5.5

 **Attack Area:** 280

 **Attack Range:** 300

 **Attack Speed Show:** 4.0

 **Defense Show:** 4.0

 **Score:** 1405

 **HP Show:** 5

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 2

 **label1:** 13

 **speedmove:** 90

 **posclass:** 5

 **talk1:** La mia lancia è infrangibile!

 **talk2:** Ovunque vado, la morte mi segue!

 **talk3:** Non cederò! Per la mia casa e la mia patria!

