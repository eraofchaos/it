---
title: "Osservatore"
permalink: /units/Beholder/
excerpt: "Era of Chaos Osservatore. Osservatore Unità. Occhio del Diavolo. Era of Chaos Intelligentissimi mostri dai numerosi occhi. Per loro, ogni essere vivente è un potenziale schiavo."
unitID: 703
last_modified_at: 2021-05-18
locale: it
ref: "Osservatore"
toc: true
---
  ![Osservatore](/images/u/ti_xieyan.jpg)

## General information
 **Descrizione:** Intelligentissimi mostri dai numerosi occhi. Per loro, ogni essere vivente è un potenziale schiavo.

 **Classe:** [Incantatore](/it/units/Unit Class Caster/)

 **Classe Descrizione:** Grazie alla completa padronanza delle arti magiche, gli incantatori sono più resistenti agli incantesimi.

 **Fazione:** [Dungeon](/it/units/Faction Dungeon/)

 **Race:** Spirito maligno

 **Members:** [x9](/it/units/Unit Member x9/)

 **Rango:** [SR](/it/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/it/units/Star 3/)

 **Unit Soul:** [Osservatore](/ItemsIT/unt_246/)

 **Unit description:** Controllo mentale: immobilizza i nemici, che perdono PF col tempo.

 **Short description:** Danno iniziale elevato. Controllo mentale.

 **Position :** Eccellente a inizio battaglia. Indebolisce i nemici per facilitare la tua vittoria.

 **Recommend:** Creature con PF ridotti e ATT elevato. Ricorda di guarirle per approfittare del loro potere offensivo.

## Statistiche base
 **Base HP: 744.0**

 **Base ATK: 115.8**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Verde | 57.9 | 3.75 | 558.0 |
  | Blu | 115.8 | 7.5 | 1116.0 |
  | Blu +1 | 173.7 | 11.25 | 1674.0 |
  | Blu +2 | 243.18 | 15.75 | 2343.6 |
  | Viola | 312.66 | 20.25 | 3013.2 |
  | Viola +1 | 382.14 | 24.75 | 3682.8 |
  | Viola +2 | 463.2 | 30.0 | 4464.0 |
  | Viola +3 | 544.26 | 35.25 | 5245.2 |
  | Arancione | 625.32 | 40.5 | 6026.4 |
  | Arancione +1 | 717.96 | 46.5 | 6919.2 |
  | Arancione +2 | 810.6 | 52.5 | 7812.0 |
  | Arancione +3 | 903.24 | 58.5 | 8704.8 |
  | Arancione +4 | 995.88 | 64.5 | 9597.6 |
  | Arancione +5 | 1134.84 | 73.5 | 10936.8 |
  | Rosso | 1320.12 | 85.5 | 12722.4 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 16.212 | 0.45 | 2.65 | 104.16 |
  | **4x** <i class="fas fa-star"/> | 18.528 | 0.47 | 3.23 | 119.04 |
  | **5x** <i class="fas fa-star"/> | 20.844 | 0.49 | 3.8 | 133.92 |
  | **6x** <i class="fas fa-star"/> | 23.16 | 0.51 | 4.38 | 148.8 |

## Equipaggiamento

  | I | Equipaggiamento  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Occhio della blasfemia](/images/e/e_7031.png) | [Occhio della blasfemia](/it/equipment/Eye of Blasphemy/) | **ATT** | **DIF** | 
  | ![Pupilla della morte](/images/e/e_7032.png) | [Pupilla della morte](/it/equipment/Pupil of Death/) | **PF** | **DIF** | 
  | ![Zanna maligna](/images/e/e_7033.png) | [Zanna maligna](/it/equipment/Evil Tusk/) | **ATT** | **DIF** | 
  | ![Tentacoli abissali](/images/e/e_7034.png) | [Tentacoli abissali](/it/equipment/Tentacles from the Abyss/) | **PF** | **DIF** | 

## Esclusivo

 **Nome:** [Sguardo oscuro](/it/Exclusive/Beholder Dark Gaze/) 

 **Is Open:** - 

 **Item to Rango ↑:** [Token Sguardo oscuro](/ItemsIT/con_990/)

 **Skin:** [Skin speciale Sguardo oscuro](/ItemsIT/con_658/)


## Emblemi sacri consigliati

* [Fuoco antico](/it/Emblem/Ancient Fire/) (Ordine)
* [Segreto eterno](/it/Emblem/Everlasting Secret/) (Ordine)
* [Ira](/it/Emblem/Anger/) (Caos)

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
### Tecnica suprema: Controllo mentale
 **Descrizione:** <span style="color: #645252;font-size:20px">L'Osservatore prende il controllo di 1 unità nemica casuale. Il bersaglio subisce danni pari a </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> dei suoi PF massimi al secondo per 8 secondi. Finché dura &lt;Controllo mentale&gt;, il bersaglio non può attaccare, muoversi o usare tecniche.</span><span style="color: black">

### Tecnica normale 1 : Incantesimo perforante
 **Descrizione:** <span style="color: #645252;font-size:20px">Quando l'Osservatore entra in battaglia, apre i propri 4 Occhi della morte. Ogni Occhio ne aumenta il danno (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">). Per ogni bersaglio ucciso, l'Osservatore chiude 1 Occhio. L'Osservatore può chiudere un massimo di 3 Occhi.</span><span style="color: black">

### Tecnica normale 2 : Debilitazione
 **Descrizione:** <span style="color: #645252;font-size:20px">Quando l'Osservatore è sul campo di battaglia, il mana iniziale degli eroi nemici è ridotto di </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">. Quando un'unità nemica muore, riduce di 10 il mana degli eroi nemici.</span><span style="color: black">

### Tecnica normale 3 : Raccolta di energia
 **Descrizione:** <span style="color: #645252;font-size:20px">All'inizio della battaglia, l'Osservatore aumenta i PF (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">) di tutte le tue unità in un'ampia area. L'effetto dura fino al termine della battaglia.</span><span style="color: black">

### Tecnica speciale fazione : Conflitto oscuro
 **Descrizione:** <span style="color: #645252;font-size:20px">Le unità Dungeon piegano l'ambiente circostante alla propria volontà. Quando affrontano unità non Dungeon, il loro danno aumenta (</span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">).</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str5 = "(LEVEL*1+5)"
    let str3 = "LEVEL*1.5+8.5"
    let str4 = "LEVEL*2+8"
    let str1 = "LEVEL*0.2+0.8"
    let str2 = "LEVEL*1+4"
    let res="ERR";
    try {
     res = eval(str5); document.getElementById('str5').textContent = res;
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

* **Dungeon**  (Roster Dungeon)
* **Incantatore**  (Roster incantatori)
* **SR**  (SR)

### Bonus eroe
* [Dracon](/it/heroes/Dracon/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Mutare](/it/heroes/Mutare/)  ->   Specialità: <i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Mutare (drago)](/it/heroes/Dragon Mutare/)  ->   Specialità: <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talento

* Attacco
* PF
* Danno unità
* Resistenza magica

 **:** [Pozione di Talento Incantatori](/ItemsIT/con_790/)


## Awaking

  ![Occhio del Diavolo](/images/u/tia_xieyan.jpg)

### Awaking Dettagli
 **Is it possible right now?** YES

 **Awaking Name:** Occhio del Diavolo

 **Awaking Descrizione:** Malvagia entità dalle origini ignote, incute terrore con il solo sguardo. I suoi occhi, portatori di morte, scrutano le debolezze del nemico e ne assorbono la forza.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Schiera un Osservatore e un minimo di </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unità Dungeon e supera il livello Campione (o superiore) dell'Utopia dei dragoni almeno una volta. (I raid non sono considerati nel conteggio della missione.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Ottieni </span><span style="color: #1ca216;font-size:18px">2</span><span style="color: #3c2a1e;font-size:18px"> pezzi di equipaggiamento nell'Avventura della Gilda.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Ottieni </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> anime di Occhio del Diavolo nei livelli del Sottosuolo 17-2 e 17-4.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Schiera un Osservatore e un minimo di </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unità Dungeon e vinci 1 battaglia del Duello dei Campioni. (I raid non sono considerati nel conteggio della missione.)</span>

## Awaken Skills

### 1st Skill (or 2nd): Colpo del mana
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Comando&gt;</span><span style="color: #645252;font-size:18px">: l'Osservatore apre 4 Occhi aggiuntivi. Quando uccide 1 unità bersaglio, ne chiude 2. Può chiudere un massimo di 6 Occhi.</span>

### 2nd Skill (or 1st): Nell'abisso
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Incantesimo perforante&gt;</span><span style="color: #645252;font-size:18px">: ciascun Occhio aumenta del 3% il DAN e la Rid DAN delle unità Dungeon alleate. Effetto raddoppiato per l'Osservatore.</span>

### 3rd Skill (or 4th): Implosione magica
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Debilitazione&gt;</span><span style="color: #645252;font-size:18px">: la rigenerazione del mana degli eroi nemici è ridotta di 1 per ciascuna unità nemica che viene sconfitta. L'effetto può essere attivato 2 volte.</span>

### 4th Skill (or 3rd): Saccheggio magico
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Debilitazione&gt;</span><span style="color: #645252;font-size:18px">: il mana degli eroi nemici è ridotto di 10 per ciascuna unità nemica che viene sconfitta.</span>

### 5th Skill (or 6th): Scudo dello Spezzaincantesimi
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Raccolta di energia&gt;</span><span style="color: #645252;font-size:18px">: effetto aumentato a 150% del valore della tecnica originale. Aumenta la Rid DAN del 10%. Quando un eroe nemico lancia un incantesimo, aumenta del 10% resistenza magica e Rid DAN dell'Osservatore.</span>

### 6th Skill (or 5th): Esorcismo echeggiante
 **Descrizione:** <span style="color: #48b946;font-size:18px">&lt;Raccolta di energia&gt;</span><span style="color: #645252;font-size:18px">: effetto della tecnica aumentato a 150%. Il buff di &lt;Raccolta di energia&gt; si applica a tutte le unità alleate. Quando un eroe nemico lancia un incantesimo, aumenta del 10% resistenza magica e Rid DAN dell'Osservatore</span>

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 1.0

 **Rush:** 3

 **Speedattack:** 60

 **Attack Show:** 1.0

 **Attack Area:** 230

 **Attack Range:** 300

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 1236

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 2

 **label1:** 7

 **speedmove:** 80

 **posclass:** 5

 **talk1:** La mia lancia è infrangibile!

 **talk2:** Ovunque vado, la morte mi segue!

 **talk3:** Non cederò! Per la mia casa e la mia patria!

