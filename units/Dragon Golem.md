---
title: "Golem draconico"
permalink: /units/Dragon Golem/
excerpt: "Era of Chaos Unità. Unità. Era of Chaos L'apice della tecnologia degli Gnomi. Ogni singola parte di questa fusione tra macchina e magia trabocca di un potere inesauribile."
unitID: 609
last_modified_at: 2021-04-14
locale: it
ref: "Golem draconico"
toc: true
---
**Warning** This unit is not released yet, provided information can be changed later or may contain inconsistency!
{: .notice--danger}

## General information
 **Descrizione:** L'apice della tecnologia degli Gnomi. Ogni singola parte di questa fusione tra macchina e magia trabocca di un potere inesauribile.

 **Classe:** [Difesa](/it/units/Unit Class Defense/)

 **Classe Descrizione:** Le unità di difesa possono sopravvivere a più attacchi grazie alla riduzione dei danni subiti.

 **Fazione:** [Torre](/it/units/Faction Tower/)

 **Race:** Drago

 **Members:** [x1](/it/units/Unit Member x1/)

 **Rank:** [Comandante](/it/units/Unit Rank Commander/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/it/units/Star 3/)

 **Unit Soul:** [Golem draconico](/it/Items/unt_243/)

 **Short description:** Difesa suprema.

 **Position :** Protezione ad area all'inizio della battaglia, che riduce i danni subiti. L'unità di difesa definitiva per le retrovie. Controllo a distanza, intimidisce tutte le unità in campo.

## Statistiche base
 **Base HP: 9616.7**

 **Base ATK: 396.0**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Verde | 198.0 | 16.5 | 7212.525 |
  | Blu | 396.0 | 33.0 | 14425.05 |
  | Blu +1 | 594.0 | 49.5 | 21637.575 |
  | Blu +2 | 831.6 | 69.3 | 30292.605 |
  | Viola | 1069.2 | 89.1 | 38947.635 |
  | Viola +1 | 1306.8 | 108.9 | 47602.665 |
  | Viola +2 | 1584.0 | 132.0 | 57700.2 |
  | Viola +3 | 1861.2 | 155.1 | 67797.735 |
  | Arancione | 2138.4 | 178.2 | 77895.27 |
  | Arancione +1 | 2455.2 | 204.6 | 89435.31 |
  | Arancione +2 | 2772.0 | 231.0 | 100975.35 |
  | Arancione +3 | 3088.8 | 257.4 | 112515.39 |
  | Arancione +4 | 3405.6 | 283.8 | 124055.43 |
  | Arancione +5 | 3880.8 | 323.4 | 141365.49 |
  | Rosso | 4514.4 | 376.2 | 164445.57 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 55.44 | 0.44 | 8.26 | 1346.338 |
  | **4x** <i class="fas fa-star"/> | 63.36 | 0.46 | 9.09 | 1538.672 |
  | **5x** <i class="fas fa-star"/> | 71.28 | 0.48 | 9.92 | 1731.006 |
  | **6x** <i class="fas fa-star"/> | 79.2 | 0.5 | 10.75 | 1923.34 |

## Equipaggiamento

  | I | Equipaggiamento  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Artiglio in lega](/images/e/e_6091.png) | [Artiglio in lega](/it/equipment/Alloy Claw/) | **ATT** | **DIF** | 
  | ![Testa di Drago di titanio](/images/e/e_6092.png) | [Testa di Drago di titanio](/it/equipment/Titanium Dragon Head/) | **PF** | **DIF** | 
  | ![Leva di comando principale](/images/e/e_6093.png) | [Leva di comando principale](/it/equipment/Main Control Stick/) | **ATT** | **DIF** | 
  | ![Armatura in lega](/images/e/e_6094.png) | [Armatura in lega](/it/equipment/Alloy Armor/) | **PF** | **DIF** | 

## Esclusivo


## Emblemi sacri consigliati

* [Segreto eterno](/it/Emblem/Everlasting Secret/) (Ordine)
* [Ira](/it/Emblem/Anger/) (Caos)
* [Avarizia](/it/Emblem/Greed/) (Caos)

## Informazioni combinazione

* [Stordimento](/combination/Stordimento/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Tecnica suprema: Impulso disorientante
 **Descrizione:** <span style="color: #645252;font-size:20px">Il Golem draconico emette un &lt;Impulso disorientante&gt; ogni 15 secondi, infliggendo </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> DAN a tutte le unità da mischia nemiche, <span style="color: #48b946;font-size:20px">&lt;stordendole&gt;</span><span style="color: black"> per 2 secondi e applicando 5 secondi di <span style="color: #48b946;font-size:20px">&lt;Paralisi&gt;</span><span style="color: black">.</span><span style="color: black">

### Tecnica normale 1 : Palazzo di ferro
 **Descrizione:** <span style="color: #645252;font-size:20px">Il Golem draconico gode di PF aumentati (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">), Tenacia aumentata (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">) e Rid DAN aumentata (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">). Danno aumentato del 100% contro le unità Dungeon. All'inizio della battaglia, il Golem draconico lancia <span style="color: #F0F000;font-size:20px">&lt;Palazzo di ferro&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Tecnica normale 2 : Risveglio magico
 **Descrizione:** <span style="color: #645252;font-size:20px">Quando viene risvegliato dall'incantesimo di supporto di un eroe alleato, lancia &lt;Tempesta magica&gt;, che causa &lt;Silenzio&gt; per 2 secondi alle unità nemiche nell'area e le </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;paralizza&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> per 5 secondi. Inoltre, ottiene DIF aumentata (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">) e Rid DAN aumentata (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">). Il bonus è cumulabile fino a 3 volte e dura fino al termine della battaglia. Il Golem draconico si risveglia ogni 25 secondi.</span><span style="color: black">

### Tecnica normale 3 : Ritorno magico
 **Descrizione:** <span style="color: #645252;font-size:20px">Quando i suoi PF scendono al 40% e al 20%, il Golem draconico evoca un campo rigenerante della durata di </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> secondi. Finché il campo rimane attivo, tutti i danni subiti dal Golem draconico vengono convertiti in PF. Quando il Golem draconico viene sconfitto, l'energia temporale che emana infligge danni pari al 30% dei PF massimi alle unità nemiche in un'ampia area e infligge </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Blocco temporale&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> ai bersagli per 5 secondi.</span><span style="color: black">

### Tecnica speciale fazione I : Mente lucida
 **Descrizione:** <span style="color: #645252;font-size:20px">Le unità Torre resistono con maggiore efficacia al &lt;Silenzio&gt;. La durata del &lt;Silenzio&gt; inflitto su di loro è ridotta (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black">

### Tecnica speciale fazione II : Esplosione di Energia
 **Descrizione:** <span style="color: #645252;font-size:20px">Le unità Torre sono esperte nella conversione dell'energia. Il loro DAN CRIT aumenta (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str9"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black">

### Tecnica normale 6 : Ruota del tempo
 **Descrizione:** <span style="color: #645252;font-size:20px">Il Golem draconico gode di Rid DAN aumentata (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str10"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">) e Tenacia aumentata (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str11"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">) quando vengono schierate 3 unità Torre. Quando il Golem draconico attiva il &lt;Risveglio magico&gt;, può evocare un'</span><span style="color: black"><span style="color: #F0F000;font-size:20px">&lt;Aura temporale&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> di dimensioni crescenti in base al livello. L'Aura ha una durata di 15 secondi. Recupero: 30 secondi.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*0.2+2.8)"
    let str8 = "(LEVEL*2+10)"
    let str5 = "(LEVEL*0.1+14.9)"
    let str6 = "(LEVEL*0.1+9.9)"
    let str3 = "(LEVEL*10+150)"
    let str4 = "(LEVEL*1+10)"
    let str1 = "(LEVEL*5+25)"
    let str2 = "(LEVEL*5+25)"
    let str10 = "(LEVEL*2+5)"
    let str11 = "(LEVEL*20+100)"
    let str9 = "(LEVEL*1.5+4)"
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
     res = eval(str10); document.getElementById('str10').textContent = res;
     res = eval(str11); document.getElementById('str11').textContent = res;
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

* **Torre**  (Roster Torre)
* **Difesa**  (Roster unità di difesa)
* **Comandante**  (Comandante)

### Bonus eroe
* [Mephala](/it/heroes/Mephala/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Astral](/it/heroes/Astral/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talento

* Attacco
* PF
* Riduzione danno unità
* Resistenza magica

 **:** [Pozione di Talento Difesa](/it/Items/con_787/)


## Awaking
### Awaking Dettagli
 **Is it possible right now?** NO

 **Awaking Name:** null

 **Awaking Descrizione:** Con le armature ben temprate e le lame affilate, i Paladini Supremi e i loro seguaci non si fermeranno dinanzi a nulla, guidati dalla luce sacra del loro credo.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Schiera un Paladino e un minimo di </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unità Castello e supera il livello Campione (o superiore) dell'Utopia dei dragoni almeno una volta.</span>

 2. <span style="color: #3c2a1e;font-size:18px">Ottieni </span><span style="color: #1ca216;font-size:18px">2</span><span style="color: #3c2a1e;font-size:18px"> pezzi di equipaggiamento nell'Avventura della Gilda.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Ottieni </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> anime di Paladino Supremo nei livelli del Sottosuolo 17-2 e 17-4.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Schiera un Paladino e un minimo di </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unità Castello e vinci 1 battaglia del Duello dei Campioni.</span>

## Awaken Skills

### 1st Skill (or 2nd): Eliminazione temeraria
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Rinforzi del valoroso&gt;</span><span style="color: #645252;font-size:18px">: i Seguaci del Santuario vengono promossi a Custodi del Santuario. Per ogni Custode del Santuario presente sul campo di battaglia, la DIF del Paladino Supremo aumenta del 15%. Il Paladino Supremo recupera il 10% dei PF per le prime 3 evocazioni.</span>

### 2nd Skill (or 1st): Gloria del Santuario
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Rinforzi del valoroso&gt;</span><span style="color: #645252;font-size:18px">: i Seguaci del Santuario vengono promossi a Custodi del Santuario. Le prime 3 evocazioni aumentano del 10% DAN e Rid DAN delle tue unità per 30 secondi. Quando entra in battaglia, il Paladino Supremo evoca un Custode del Santuario.</span>

### 3rd Skill (or 4th): Fede e lealtà
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Comando&gt;</span><span style="color: #645252;font-size:18px">: Rid DAN del Paladino aumentata del 22%. Il &lt;Morale alto&gt; non modifica questo effetto.</span>

### 4th Skill (or 3rd): Fede incrollabile
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Comando&gt;</span><span style="color: #645252;font-size:20px">: Rid DAN del Paladino aumentata di un ulteriore 15%</span><span style="color: #645252;font-size:20px">. Effetto raddoppiato con </span><span style="color: #48b946;font-size:20px">&lt;Morale alto&gt;</span><span style="color: #645252;font-size:20px">.</span>

### 5th Skill (or 6th): Perseveranza
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Incentivo&gt;</span><span style="color: #645252;font-size:18px">: si applica a tutte le unità alleate. Aumenta il DAN CRIT del 50% e la Tenacia di 150. Durata di &lt;Morale alto&gt; aumentata di 10 secondi.</span>

### 6th Skill (or 5th): Contrattacco agile
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Incentivo&gt;</span><span style="color: #645252;font-size:18px">: si applica a tutte le unità alleate. Aumenta il DAN del 15% e la Tenacia di 150 per tutte le unità nell'area. Durata di &lt;Morale alto&gt; aumentata di 10 secondi.</span>

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 9.0

 **Rush:** 1

 **Speedattack:** 160

 **Attack Show:** 7.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 6.0

 **Defense Show:** 9.0

 **Score:** 1630

 **HP Show:** 7

 **disrdcvol:** -2147483648

 **Dead Type:** 1

 **s:** 4

 **label1:** 2

 **speedmove:** 120

 **posclass:** 2

 **talk1:** Torna alla vita, mio Catafratto!

 **talk2:** La Sacra Luce ci purificherà tutti!

 **talk3:** Gli eretici fuggiranno di fronte al mio potere!

