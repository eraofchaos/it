---
title: "Driade"
permalink: /units/Sprite/
excerpt: "Era of Chaos Unità. Unità. Era of Chaos Innumerevoli favole e leggende narrano delle bellissime Driadi. Chiunque osi maltrattarle si attira il disprezzo dei lettori... e di conseguenza fa una fine decisamente poco lieta."
unitID: 901
last_modified_at: 2021-04-01
locale: it
ref: "Driade"
toc: true
---
## General information
 **Descrizione:** Innumerevoli favole e leggende narrano delle bellissime Driadi. Chiunque osi maltrattarle si attira il disprezzo dei lettori... e di conseguenza fa una fine decisamente poco lieta.

 **Classe:** [Incursione](/it/units/Unit Class Charging/)

 **Classe Descrizione:** Incursione: Le unità d'incursione attaccano le retrovie nemiche e godono di DAN CRIT aumentato contro le unità a distanza e gli incantatori.

 **Fazione:** [Confluenza](/it/units/Faction Conflux/)

 **Race:** Domatore

 **Members:** [x4](/it/units/Unit Member x4/)

 **Rank:** [R](/it/units/Unit Rank R/)

 **Starts:** [<i class="fas fa-star"/>](/it/units/Star 1/)

 **Unit Soul:** [Driade](/it/Items/unt_262/)

 **Short description:** Ammutolisce. Incantesimo iniziale potenziato.

 **Position :** Esplode quando muore, causa <Silenzio> e aumenta il mana iniziale degli eroi.

## Statistiche base
 **Base HP: 993.0**

 **Base ATK: 69.5**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Verde | 34.75 | 3.75 | 744.75 |
  | Blu | 69.5 | 7.5 | 1489.5 |
  | Blu +1 | 104.25 | 11.25 | 2234.25 |
  | Blu +2 | 145.95 | 15.75 | 3127.95 |
  | Viola | 187.65 | 20.25 | 4021.65 |
  | Viola +1 | 229.35 | 24.75 | 4915.35 |
  | Viola +2 | 278.0 | 30.0 | 5958.0 |
  | Viola +3 | 326.65 | 35.25 | 7000.65 |
  | Arancione | 375.3 | 40.5 | 8043.3 |
  | Arancione +1 | 430.9 | 46.5 | 9234.9 |
  | Arancione +2 | 486.5 | 52.5 | 10426.5 |
  | Arancione +3 | 542.1 | 58.5 | 11618.1 |
  | Arancione +4 | 597.7 | 64.5 | 12809.7 |
  | Arancione +5 | 681.1 | 73.5 | 14597.1 |
  | Rosso | 792.3 | 85.5 | 16980.3 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **1x** <i class="fas fa-star"/> | 6.95 | 0.48 | 1.5 | 99.3 |
  | **2x** <i class="fas fa-star"/> | 8.34 | 0.5 | 2.08 | 119.16 |
  | **3x** <i class="fas fa-star"/> | 9.73 | 0.53 | 2.65 | 139.02 |
  | **4x** <i class="fas fa-star"/> | 11.12 | 0.55 | 3.23 | 158.88 |
  | **5x** <i class="fas fa-star"/> | 12.51 | 0.58 | 3.8 | 178.74 |
  | **6x** <i class="fas fa-star"/> | 13.9 | 0.6 | 4.38 | 198.6 |

## Equipaggiamento

  | I | Equipaggiamento  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Ghirlanda profumata](/images/e/e_9011.png) | [Ghirlanda profumata](/it/equipment/Fragrant Wreath/) | **ATT** | **DIF** | 
  | ![Abito della Luna e delle Stelle](/images/e/e_9012.png) | [Abito della Luna e delle Stelle](/it/equipment/Gown of Moon and Stars/) | **PF** | **DIF** | 
  | ![Ali di farfalla luminescenti](/images/e/e_9013.png) | [Ali di farfalla luminescenti](/it/equipment/Phosphorus Butterfly Wings/) | **ATT** | **DIF** | 
  | ![Fascia di smeraldo](/images/e/e_9014.png) | [Fascia di smeraldo](/it/equipment/Emerald Arm Ring/) | **PF** | **DIF** | 

## Esclusivo

 **Nome:** [Carica impetuosa](/it/Exclusive/Sprite Knight Pike/) 

 **Is Open:** - 

 **Item to Rango ↑:** [Token Carica impetuosa](/it/Items/con_916/)

 **Skin:** -


## Emblemi sacri consigliati

* [Fuoco antico](/it/Emblem/Ancient Fire/) (Ordine)
* [Segreto eterno](/it/Emblem/Everlasting Secret/) (Ordine)
* [Ira](/it/Emblem/Anger/) (Caos)

## Informazioni combinazione

* [Silenzio](/combination/Silenzio/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Tecnica suprema: Frammentazione energetica
 **Descrizione:** <span style="color: #645252;font-size:20px">Quando una Driade viene abbattuta, infligge danni pari a </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> dei PF massimi del bersaglio (fino a un massimo del 1000% del suo ATT).</span><span style="color: black">

### Tecnica normale 1 : Benedizione della Driade
 **Descrizione:** <span style="color: #645252;font-size:20px">All'inizio della battaglia, la Driade aumenta la resistenza magica di tutte le unità alleate davanti a sé (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">). Effetto raddoppiato per la Driade stessa.</span><span style="color: black">

### Tecnica normale 2 : Ispirazione
 **Descrizione:** <span style="color: #645252;font-size:20px">Se la Driade è sul campo di battaglia, aumenta il mana base degli eroi alleati di </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Tecnica normale 3 : Dedizione
 **Descrizione:** <span style="color: #645252;font-size:20px">Quando una Driade viene abbattuta, infligge </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Silenzio&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> all'unità bersaglio </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> sec.</span><span style="color: black">

### Tecnica speciale fazione I : Affinità elementale
 **Descrizione:** <span style="color: #645252;font-size:20px">Le unità Confluenza sono esperte nell'utilizzo della magia della Confluenza. La resistenza magica degli eroi aumenta (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black">

### Tecnica speciale fazione II : Conflitto elementale
 **Descrizione:** <span style="color: #645252;font-size:20px">Le unità Confluenza infliggono ingenti danni da Confluenza. Quando affrontano unità non Confluenza, il loro danno aumenta (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str5 = "(LEVEL*3+15)"
    let str6 = "(LEVEL*1+5)"
    let str3 = "LEVEL*1.5+0.2"
    let str4 = "LEVEL*0.15+1.85"
    let str1 = "LEVEL*0.25+2.75"
    let str2 = "(LEVEL*0.5+2.5)"
    let res="ERR";
    try {
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
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

* **Confluenza**  (Roster Confluenza)
* **Incursione**  (Roster unità di incursione)
* **R**  (R)

### Bonus eroe
* [Mullich](/it/heroes/Mullich/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Ciele](/it/heroes/Ciele/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talento

* Attacco
* PF
* Danno unità
* Resistenza magica

 **:** [Pozione di Talento Incursione](/it/Items/con_788/)


## Awaking
### Awaking Dettagli
 **Is it possible right now?** NO

 **Awaking Name:** 

 **Awaking Descrizione:** null

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Schiera i Picchieri e un minimo di </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unità Castello e uccidi </span><span style="color: #1ca216;font-size:18px">1000</span><span style="color: #3c2a1e;font-size:18px"> Gnomi in un singolo attacco alla Tesoreria degli gnomi. (I raid non sono considerati nel conteggio della missione.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Uccidi </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> mostri durante un'Avventura della Gilda.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Ottieni </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> anime di Alabardiere nei livelli del Sottosuolo 14-2 e 14-4.</span>

 4. null

## Awaken Skills

### 1st Skill (or 2nd): Spazzata Muro di lance
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Muro di lance&gt;</span><span style="color: #645252;font-size:18px"> ora colpisce le unità più grandi</span>

### 2nd Skill (or 1st): Colpo Muro di lance
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Muro di lance&gt;</span><span style="color: #645252;font-size:18px">: DAN aumentato al 150%, durata &lt;Stordimento&gt; aumentata a 4,5 secondi</span>

### 3rd Skill (or 4th): Muro impenetrabile
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Comando&gt;</span><span style="color: #645252;font-size:18px">: con &lt;Morale alto&gt;, la Rid DAN delle unità aumenta del 30% per 10 secondi</span>

### 4th Skill (or 3rd): Muro cavo
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Comando&gt;</span><span style="color: #645252;font-size:18px">: con &lt;Morale alto&gt;, la resistenza magica aumenta del 30% per 10 secondi</span>

### 5th Skill (or 6th): Infiltrazione
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Caccia al Drago&gt;</span><span style="color: #645252;font-size:18px">: contro unità da 1 o 4 membri, causa &lt;Impedimento&gt; al bersaglio. &lt;Impedimento&gt;: riduce il CRIT del bersaglio di 300.</span>

### 6th Skill (or 5th): Assalto estenuante
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Caccia al Drago&gt;</span><span style="color: #645252;font-size:18px">: contro unità da 1 o 4 membri, riduce la Schivata del bersaglio di 300.</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 1.0

 **Rush:** 2

 **Speedattack:** 160

 **Attack Show:** 1.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 546

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 11

 **speedmove:** 120

 **posclass:** 3

 **talk1:** La mia lancia è infrangibile!

 **talk2:** Ovunque vado, la morte mi segue!

 **talk3:** Non cederò! Per la mia casa e la mia patria!

