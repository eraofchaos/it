---
title: "Troll"
permalink: /units/Troll/
excerpt: "Era of Chaos Unità. Unità. Era of Chaos I Troll sono creature estremamente intelligenti che combattono usando pesanti massi. Preferiscono occupare la prima fila, per spazzare via i nemici con possenti attacchi."
unitID: 409
last_modified_at: 2021-03-18
locale: it
ref: "Troll"
toc: true
---
## General information
 **Descrizione:** I Troll sono creature estremamente intelligenti che combattono usando pesanti massi. Preferiscono occupare la prima fila, per spazzare via i nemici con possenti attacchi.

 **Classe:** [A distanza](/it/units/Unit Class Ranged/)

 **Classe Descrizione:** Maggiore è la distanza tra un'unità a distanza e il suo bersaglio, più efficaci sono i suoi attacchi.

 **Fazione:** [Roccaforte](/it/units/Faction Stronghold/)

 **Race:** Domatore

 **Members:** [x1](/it/units/Unit Member x1/)

 **Rank:** [Comandante](/it/units/Unit Rank Commander/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/it/units/Star 3/)

 **Unit Soul:** [Troll](/it/Items/unt_225/)

 **Short description:** Attacca bersagli singoli. Danni istantanei.

 **Position :** Attacca bersagli singoli. Danni istantanei.

## Statistiche base
 **Base HP: 9051.0**

 **Base ATK: 1018.3**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Verde | 509.15 | 7.5 | 6788.25 |
  | Blu | 1018.3 | 15.0 | 13576.5 |
  | Blu +1 | 1527.45 | 22.5 | 20364.75 |
  | Blu +2 | 2138.43 | 31.5 | 28510.65 |
  | Viola | 2749.41 | 40.5 | 36656.55 |
  | Viola +1 | 3360.39 | 49.5 | 44802.45 |
  | Viola +2 | 4073.2 | 60.0 | 54306.0 |
  | Viola +3 | 4786.01 | 70.5 | 63809.55 |
  | Arancione | 5498.82 | 81.0 | 73313.1 |
  | Arancione +1 | 6313.46 | 93.0 | 84174.3 |
  | Arancione +2 | 7128.1 | 105.0 | 95035.5 |
  | Arancione +3 | 7942.74 | 117.0 | 105896.7 |
  | Arancione +4 | 8757.38 | 129.0 | 116757.9 |
  | Arancione +5 | 9979.34 | 147.0 | 133049.7 |
  | Rosso | 11608.62 | 171.0 | 154772.1 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 142.562 | 0.24 | 4.3 | 1267.14 |
  | **4x** <i class="fas fa-star"/> | 162.928 | 0.25 | 4.95 | 1448.16 |
  | **5x** <i class="fas fa-star"/> | 183.294 | 0.26 | 5.6 | 1629.18 |
  | **6x** <i class="fas fa-star"/> | 203.66 | 0.28 | 6.25 | 1810.2 |

## Equipaggiamento

  |  Equipaggiamento  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Cascata di massi](/it/equipment/Cascata di massi/) | **ATT** | **DIF** | 
  | [Potenza dei Signori](/it/equipment/Potenza dei Signori/) | **PF** | **DIF** | 
  | [Sfonda-corazza](/it/equipment/Sfonda-corazza/) | **ATT** | **DIF** | 
  | [Stivali della guarnigione](/it/equipment/Stivali della guarnigione/) | **PF** | **DIF** | 

## Esclusivo


## Emblemi sacri consigliati

* [Giudizio degli antenati](/it/Emblem/The Judgment of Fathers/) (Neutrale)
* [Superbia](/it/Emblem/Arrogance/) (Caos)
* [Calamità del Re](/it/Emblem/King's Calamity/) (Malvagio)

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
### Tecnica suprema: Potere meteorico
 **Descrizione:** <span style="color: #645252;font-size:20px">Quando il Troll attacca, lancia un masso verso l'unità bersaglio: </span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Infligge danni pari a </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> del proprio ATT, più </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> dei PF massimi dell'unità bersaglio.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Applica </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Rallentamento&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> per 3 secondi a tutte le unità non volanti avversarie in un'area molto grande.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Riduce del 20% la DIF e la RID DAN delle unità nemiche </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;stordite&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> in un'ampia area per 5 secondi.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Le unità nemiche in un'ampia area affette da </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Impedimento&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> subiscono danni pari a </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> dell'ATT del Troll.</span><span style="color: black">

### Tecnica normale 1 : Antica stirpe
 **Descrizione:** <span style="color: #645252;font-size:20px">Il Troll diventa immune a </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Impedimento&gt;, &lt;Spossatezza&gt; e &lt;Morale basso&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> e gode di PF aumentati (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">) e Rid DAN aumentata (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Le cure ricevute dal Troll sono ridotte del 100%, ma il Troll recupera </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> dei propri PF massimi ogni 2 secondi.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Le unità da mischia nemiche che attaccano il Troll diventano </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;affaticate&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> per 2 secondi. L'</span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Affaticamento&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> può essere attivato una volta ogni 7 secondi.</span><span style="color: black">

### Tecnica normale 2 : Raptus
 **Descrizione:** <span style="color: #645252;font-size:20px">Il Troll gode di CRIT aumentato di </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">; l'effetto raddoppia quando i suoi PF scendono sotto il 50%. &lt;Raptus&gt; si attiva la prima volta che i PF del Troll scendono sotto il 60%, o quando 4 unità alleate vengono sconfitte. Terminato il &lt;Raptus&gt;, il Troll diventa Troll condottiero e &lt;Potere meteorico&gt; diventa &lt;Esplosione meteorica&gt;.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">&lt;Esplosione meteorica&gt;: </span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Infligge danni pari a </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> del proprio ATT, più </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str9"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> dei PF massimi dell'unità bersaglio.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Infligge danni pari al 15% del proprio ATT a 3 unità nemiche casuali.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">&lt;Esplosione meteorica&gt; viene lanciata regolarmente una volta al secondo e non è influenzata dai bonus alla Vel ATT, dalle abilità di controllo di gruppo e dalla portata.</span><span style="color: black">

### Tecnica normale 3 : Dio della Guerra invincibile
 **Descrizione:** <span style="color: #645252;font-size:20px">Il Troll gode di ATT aumentato (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str10"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">) e DAN aumentato (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str11"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">). Se il bersaglio è </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;affaticato&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">, aumenta ulteriormente il DAN (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str12"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">) e il DAN CRIT (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str13"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Quando il Troll attacca, ha una probabilità di </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;pietrificare&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> il bersaglio per 0,1 secondi e i suoi attacchi ignorano </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str14"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> della DIF dell'unità nemica.</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">Per ogni unità Roccaforte schierata, il Troll gode di DAN aumentato (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str15"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black">

### Tecnica speciale fazione I : Combattenti devoti
 **Descrizione:** <span style="color: #645252;font-size:20px">Le unità Roccaforte sono a proprio agio nelle battaglie più estenuanti. Per ogni 15% dei PF che perdono, la loro Vel ATT aumenta (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str16"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black">

### Tecnica speciale fazione II : Vitalità aumentata
 **Descrizione:** <span style="color: #645252;font-size:20px">Le unità Roccaforte conoscono i segreti delle tecniche di guarigione e godono di rigenerazione dei PF aumentata (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str17"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> PF recuperati ogni 3 secondi) e ottengono </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str18"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> di assorbimento.</span><span style="color: black">

### Tecnica normale 6 : Signore della natura
 **Descrizione:** <span style="color: #645252;font-size:20px">Se sono presenti in campo 3 unità Roccaforte, gode di DAN aumentato (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str19"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">) e DAN CRIT aumentato (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str20"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black"><br/><span style="color: #ffffff;font-size:6px">　</span><span style="color: black"><br/><span style="color: #645252;font-size:20px">A 6 secondi dall'inizio della battaglia, il Troll evoca un'aura </span><span style="color: black"><span style="color: #F0F000;font-size:20px">&lt;Trappola mortale&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px">, la cui portata aumenta al crescere del livello. L'Aura ha una durata di 15 secondi. In seguito, l'Aura si forma nuovamente ogni 30 secondi.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str20 = "LEVEL*2+30"
    let str7 = "LEVEL*40+160"
    let str8 = "LEVEL*10+120"
    let str5 = "LEVEL*2+8"
    let str18 = "(LEVEL*0.3+1)"
    let str6 = "LEVEL*0.3+1.2"
    let str19 = "LEVEL*1+15"
    let str3 = "LEVEL*0.5+2.5"
    let str4 = "LEVEL*5+25"
    let str1 = "LEVEL*5+120"
    let str2 = "LEVEL*0.2+1"
    let str12 = "LEVEL*1+15"
    let str13 = "LEVEL*3+5"
    let str10 = "LEVEL*5+25"
    let str11 = "LEVEL*2+10"
    let str16 = "(LEVEL*0.3+0.5)"
    let str17 = "(LEVEL*300+1200)"
    let str9 = "LEVEL*0.2+1"
    let str14 = "LEVEL*2+10"
    let str15 = "LEVEL*0.3+1.5"
    let res="ERR";
    try {
     res = eval(str20); document.getElementById('str20').textContent = res;
     res = eval(str7); document.getElementById('str7').textContent = res;
     res = eval(str8); document.getElementById('str8').textContent = res;
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str18); document.getElementById('str18').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str19); document.getElementById('str19').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
     res = eval(str12); document.getElementById('str12').textContent = res;
     res = eval(str13); document.getElementById('str13').textContent = res;
     res = eval(str10); document.getElementById('str10').textContent = res;
     res = eval(str11); document.getElementById('str11').textContent = res;
     res = eval(str16); document.getElementById('str16').textContent = res;
     res = eval(str17); document.getElementById('str17').textContent = res;
     res = eval(str9); document.getElementById('str9').textContent = res;
     res = eval(str14); document.getElementById('str14').textContent = res;
     res = eval(str15); document.getElementById('str15').textContent = res;
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

* **Roccaforte**  (Roster Roccaforte)
* **A distanza**  (Roster unità a distanza)
* **Comandante**  (Comandante)

### Bonus eroe
* [Kilgor](/it/heroes/Kilgor/)  ->   Specialità: <i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Gelu](/it/heroes/Gelu/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Crag Hack](/it/heroes/Crag Hack/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talento

* Attacco
* PF
* Colpo critico unità
* Danno unità

 **:** [Pozione di Talento A distanza](/it/Items/con_789/)


## Awaking
### Awaking Dettagli
 **Is it possible right now?** NO

 **Awaking Name:** null

 **Awaking Descrizione:** null

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 7.0

 **fly:** jushi

 **flyspeed:** 350

 **atkfly:** 5

 **Rush:** 3

 **Speedattack:** 120

 **Attack Show:** 9.0

 **Attack Area:** 420

 **Attack Range:** 460

 **Attack Speed Show:** 4.0

 **Defense Show:** 7.0

 **Score:** 1630

 **HP Show:** 9

 **disrdcvol:** 70

 **Dead Type:** 1

 **s:** 4

 **label1:** 5

 **speedmove:** 90

 **posclass:** 4

 **talk1:** Non siete altro che formiche!

 **talk2:** Mi credi cieco, per caso?

 **talk3:** Indovina quanto lontano riesco a lanciarla!

