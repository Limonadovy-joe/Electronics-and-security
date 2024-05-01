# Electronics-and-security

- [Definition of basic quantities](#definition-of-basic-quantities)
  - [Voltage](#voltage)
  - [Current](#current)
  - [Resistance](#resistance)
  - [Eletric Power](#eletric-power)
  - [Eletric Capacitance](#eletric-capacitance)
  - [Inductance](#inductance)
  - [Frequency](#frequency)   
- [Notes](#notes)
 
# Definition of basic quantities

## Voltage
-  Definuje se jako **rozdíl potenciálů <sup>[1](#notes)</sup> mezi dvěma body elektrického pole <sup>[2](#notes)</sup>**, tj. práce, potřebná k přenesení jednotkového náboje mezi těmito body.
-  Napětí představuje **tlak z napájecího zdroje <sup>[3](#notes)</sup> elektrického obvodu**, který tlačí **nabité elektrony (proud)** skrz vodivou smyčku a umožňuje jim vykonávat práci, například rozsvícení světla.
-  Ve zkratce, **napětí = tlak a měří se ve voltech (V)**
<br/><br/>
- Napětí je buď **střídavé napětí (AC - Alternating)** nebo **stejnosměrné napětí (DC - direct)**.
  - **střídavé napětí (AC)**
    - Na rozdíl od stejnosměrného, **v čase mění svou polaritu**
    - Polarita se odkazuje **na směr nebo znaménko napětí v daném čase.** Střídavé napětí se **periodicky mění mezi kladnou a zápornou polaritou v čase.**
![Circuit](https://image2.slideserve.com/4247144/vlastnosti-st-dav-ho-proudu3-n.jpg)
    - Tvar průběhu může být různý. Nejčastěji se setkáváme s tzv. **harmonickým sinusovým průběhem**
    - Teče v **rovnoměrných sinusových vlnách**
    - Běžně produkováno **elektrárnami prostřednictvím generátorů**, kde je mechanická energie – otáčení poháněné tekoucí vodou, párou, větrem nebo teplem – převedena na elektrickou energii.
    - Běžnější než stejnosměrné napětí. Rozvodné podniky dodávají **střídavé napětí domácnostem a společnostem.**
    - Některá zařízení v domácnostech(tv,pc), využívají **stejnosměrné napětí.** **K převedení střídavého napětí a proudu na stejnosměrné používají usměrňovače** (například černé kvádry u napájecích šňůr notebooků).
    - elektronické obvody ke své činnosti obvykle potřebují stejnosměrný proud a k distribuci elektrické energie se využívá proud střídavý
  -  **stejnosměrné napětí (DC)**
     - typ elektrického napětí, u kterého **hodnota a směr zůstávají konstantní v čase, polarita se nemění.**
     - Běžně vzniká prostřednictvím zdrojů uskladněné energie, například baterií.
     - Zdroje stejnosměrného napětí mají **kladné a záporné svorky.** Svorky určují polaritu v obvodu a polaritu lze využít k určení, zda je okruh stejnosměrný nebo střídavý.
     - **směr proudu záleží na tom**, které náboje, zda kladné nebo záporné, zprostředkovávají vedení el. proudu. **V kovových vodičích obstarávají transport el. proudu elektrony**, které mají **záporný náboj (–)**, a proto je skutečný směr proudu od záporného pólu (–) ke kladnému pólu (+)
 
-  Vztah mezi napětím a proudem ve vodiči s elektrickým odporem vyjadřuje Ohmův zákon.

## Current
- uspořádaný pohyb **nosičů elektrického náboje<sup>[3](#notes)</sup> prošlého za jednotku času** daným průřezem elektrického vodiče.
- Elektrický proud je roven **elektrickému náboji q  procházejícím průřezem vodiče S za jednotku času**
![current](https://wikimedia.org/api/rest_v1/media/math/render/svg/2a74ff85e689463ce65dd41728ed6a457a538fd5)
- resp. **plošnému integrálu** přes hustotu elektrického proudu **j** procházejícího plochou **S** </br>
![current 2](https://wikimedia.org/api/rest_v1/media/math/render/svg/8d294937a92d9dd9d99f5fed8f465af3b2baa273) 

- **Stacionární** a **nestacionární** elektrický proud
- Jako stacionární se označuje elektrický proud, který je v **čase konstantní, tj. má časově neměnnou velikost i směr toku.** Stacionárním proudem je generováno **stacionární magnetické pole**. Jako nestacionární se označuje elektrický proud, který v čase mění velikost nebo směr toku. 
  - **Stacionární - setrvaly,nemenny**
    - Prochází-li elektrický náboj průřezem vodiče **rovnoměrně**, definuje se stacionární proud jako množství náboje **ΔQ**  prošlého průřezem vodiče za čas **Δt**:
    - ![current 3](https://wikimedia.org/api/rest_v1/media/math/render/svg/d0f976999deb0e68b22eae985f690603bde3d84a)
  - **nestacionární**
    - Okamžitá hodnota proudu je **limitním případem stacionárního proudu**, definuje se jako množství náboje **q**, prošlého průřezem vodiče za infinitesimální (nekonečně krátký) čas **t**:
    - ![current 4](https://wikimedia.org/api/rest_v1/media/math/render/svg/4cebfbaf05dc3713efa9bd771fceb9870bbc3205)


## Resistance
-  je reálnou částí **komplexní impedance elektrického obvodu**, bránící průchodu elektrického proudu.
   -  **Impedance** je komplexní veličina **elektrického obvodu vyjádřená reálnou rezistancí a imaginární reaktancí**, bránící průchodu elektrického proudu.
      -  **R** je rezistance (odporová složka), **X** je reaktance (složka **závislá na změnách napětí a proudu způsobených kapacitami a induktancemi v obvodu**), j je **imaginární jednotka (sqrt(-1))**, používaná pro vyjádření **fázového posunu mezi proudem a napětím.<sup>[4](#notes)</sup>**
      -    ![current 5](https://wikimedia.org/api/rest_v1/media/math/render/svg/65e7b1fe3101d47d559007af1409b65b9eaf0ebf)
      -  Zatímco elektrický odpor charakterizuje pouze schopnost materiálu  **bránit průchodu stejnosměrného elektrického proudu (DC)**, **impedance** zahrnuje jak **odpor, tak fázi proudu ve vztahu k napětí**(fázového posunu mezi proudem a napětím)  v střídavých obvodech.
      -  **Reaktance (jalový odpor)** je imaginární částí komplexní impedance elektrického obvodu. **Reaktance indukčního charakteru se též nazývala induktance (indukční odpor)**, reaktance kapacitního charakteru se též nazývala **kapacitance (kapacitní odpor).**
      -  Impedance tedy vyjadřuje **celkový odpor obvodu proti průchodu střídavého proudu** a je obecně frekvenčně závislá.
      -  Jako impedanci v obecném slova smyslu označujeme **poměr napětí a proudu**. **Je-li fázový posuv mezi proudem a napětím nulový**, mluvíme o odporu činném. Je-li **posuv +90°, jde o jalový odpor (reaktanci) indukční**. **Jeli posuv -90°, jde o jalový odpor (reaktanci) kapacitní.**

- Hodnota elektrického odporu závisí na **materiálu, průřezu, délce i teplotě vodiče.**
- Odpor **vodičů se vzrůstající teplotou stoupá** (kladný teplotní součinitel elektrického odporu), kdežto **odpor polovodičů se vzrůstající teplotou klesá** (záporný teplotní součinitel elektrického odporu).
- Teplotní součinitel odporu  je fyz. veličina vyjadřující **závislost odporu (rezistivity) vodiče (polovodiče) na teplotě.**, **kolikrát se zvětší odpor při zahřátí vodiče o 1°C**
- **Čím delší je vodič, tím větší je jeho odpor; čím je jeho průřez větší, tím menší je odpor**

- **Závislost na teplotě**
  - Závislost el. odporu vodičů na teplotě je ve **velkém teplotním intervalu prakticky lineární**
  - S **rostoucí teplotou roste odpor**
  - Při velmi nízkých teplotách klesá **měrný odpor na neměřitelnou hodnotu**. Tento jev se nazývá **supravodivost** – očekávání vynálezu pro budoucnost, nyní je nutno chladit kap. Dusíkem, což je neekonomické, měl by přijít nový materiál, **který nebude potřeboval tak nízkou teplotu.**

- **Ztráty**
  - Teče-li vodičem s odporem **R** proud **I** dochází k přeměně **elektrické energie na teplo** a tím k **výkonovým ztrátám**, které lze vyjádřit vztahem:
  -  ![current 6](https://wikimedia.org/api/rest_v1/media/math/render/svg/e436cb13eae078de979968b97d3155ca2a84c93e)
  -  Tento jev se využívá u zařízení jako žárovka **(emituje světlo žhavící spirály)** nebo elektrické topení (emituje teplo žhavící spirály), nicméně je nežádoucí při přenosu energie. 

## Eletric Power
-  vyjadřuje vykonanou **elektrickou práci konanou elektrickou silou za jednotku času.** Pro harmonický průběh napětí a proudu se kromě **činného výkonu P** definuje dále **jalový a zdánlivý výkon Q a S.**
-  je míra, kterou **elektrická soustava přeměňuje elektrickou energii na jiné formy energie (například světlo, teplo, mechanickou energii atd.)**
-  jedna se o časově měřenou veličinu, která udává, **jak rychle se energie spotřebovává nebo dodává.**

- Činný proud s napětím vytváří **činný výkon P [W - watt]**. Činný výkon je užitečný výkon zdroje nebo spotřebiče, který koná práci. **Vyjadřuje skutečnou spotřebovanou el. energii, která se mění na jiný druh energie.**
- 
- Jalový proud s napětím vytváří **jalový výkon Q [Var - voltampér reaktanční]**. Jalový výkon je nepotřebný a neužitečný výkon, který nekoná žádnou práci. **Je způsobený fázovým posunem mezi napětím a proudem.**

- Celkový proud s napětím vytváří **zdánlivý výkon S [VA - voltampér].** **Zdánlivý výkon je celkový výkon dodávaný zdrojem do střídavých obvodů.** Je tvořen celkovým proudem, který zdroj dodává do obvodu, **nezávislým na fázovém posunu mezi napětím a proudem.** Zdánlivý výkon slouží k určení výkonu zdroje, transformátoru atd.




## Eletric Capacitance
- vyjadřující **schopnost vodiče uchovat elektrický náboj**. Čím větší kapacita, tím větší množství náboje může být ve vodiči.
- Elektrický náboj je fyzikální veličina a vlastnost hmoty. **Hmota nesoucí elektrický náboj je zdrojem elektromagnetického pole.**
- Přestože je elektrická kapacita obecně vlastností každého vodiče, využívá se především u **kondenzátorů**, pro něž je kapacita definována jako **množství náboje mezi deskami kondenzátoru o jednotkovém elektrickém napětí (1 V).**
- Kapacity kondenzátorů dosahují běžně hodnot v **pF**, proto je možné setkat se s hodnotami např. 3k3 = 3300 pF = 3,3 nF. 
-  jednotka: **farad, značka F**
-  Elektrická kapacita je závislá **na tvaru a velikosti a materiálu (dielektrika) tělesa.**
-  Dielektrikum je látka (izolant), která má schopnost **polarizace** (tedy být polarizována).

## Inductance
- indukčnost
- vyjadřující schopnost dané konfigurace **elektricky vodivých těles protékaných elektrickým proudem vytvářet ve svém okolí magnetické pole.**
- Magnetické pole je fyzikální pole, **jehož zdrojem je pohybující se elektrický náboj, tj. elektrický proud.**
- Jednotka SI: **henry, značka H**



# Notes
- **Napájecí zdroje**
  - **Síťový adaptér** - transformuje vysoké napětí z elektrické sítě na nižší napětí,
  - **Generátor** - ktery konvertuje mechanickou energii na elektrickou energii,
  - **Transformátor** - zařízení používané ke **změně napětí na jinou hodnotu.** Používán v distribučních sítích elektřiny k **úpravě napětí** a k jeho přizpůsobení různým elektrickým zařízením - trafostanice.
- **Rozdíl potenciálů**
  - definován jako rozdíl potenciální energie mezi dvěma body v obvodu.
  - Výše rozdílu (vyjádřená ve voltech) určuje velikost existující potenciální energie k přesunu elektronů z jednoho místa na druhé.
  - Tato veličina určuje **množství práce, kterou lze potenciálně vykonat prostřednictvím obvodu.**
  - Domácí alkalická baterie typu AA například poskytuje 1,5 V. Běžná domácí zásuvka má 230 V. **Čím vyšší napětí je v obvodu, tím větší je jeho schopnost „protlačit“ více elektronů a vykonat více práce.**
- **Nosič náboje**
  -  volná částice přenášející elektrický náboj, zejména částice nesoucí elektrický proud v elektrických vodičích. Příkladem jsou **elektrony a ionty.**
- **fázovy posun mezi proudem a napětím**
  -  pouziva se k **analýze střídavých (AC) elektrických obvodů.**
  -  Vyjadřuje míru, o **kterou jsou fáze proudového a napěťového signálu posunuty vůči sobě.** Tento posun ovlivňuje, **jak proud a napětí vzájemně interagují** a je důležitý pro chápání výkonu obvodu.
  -  Střídavý proud a napětí se mohou pohybovat sinusovým nebo kosinusovým vzorem, který se opakuje každý cyklus.
  -  V ideálním případě, **kdy jsou proud a napětí ve fázi, dosahují svých maximálních a minimálních hodnot ve stejný okamžik.** Fázový posun mezi proudem a napětím se měří ve stupních (°) nebo radiánech a obvykle se uvádí v rozmezí od -180° do +180°.
  -  Fázový posun 0°: **Proud a napětí jsou ve fázi**, což znamená, **že maximální a minimální hodnoty obou signálů nastávají ve stejný čas.**
  -  V obvodech, kde jsou přítomny **induktory (cívky) nebo kondenzátory**, dochází ke změně fázového posunu mezi proudem a napětím, protože tyto komponenty **ukládají a uvolňují energii, což způsobuje, že proud "zaostává" nebo "předbíhá" napětí.**
  
  -  Fázový posun mezi **napětím a proudem v elektrickém obvodu** může být způsoben několika faktory:
     -  **Induktance a kapacitance:** Přítomnost **induktivních (cívkových)** a **kapacitních (kondenzačních) prvků** v obvodu může způsobit fázový posun mezi napětím a proudem. Například **induktory** mají tendenci vytvářet fázový posun, přičemž **proud zaostává za napětím**, zatímco **kondenzátory** mohou způsobit posun, kde **napětí zaostává za proudem.**
     -  V obvodu střídavého proudu **se kondenzátor opakovaně nabíjí a vybíjí**, což má za následek **předbíhání elektrického proudu před napětím (fázový posun)** a vznik **kapacitance (kapacitní reaktance)**, tj. zdánlivého odporu proti průchodu střídavého proudu.
     - Induktory - cívka - (pusobi zde **Indukční odpor**, **induktance**)  v obvodu se střídavým proudem působí jako odpor, který je tím větší, čím větší je indukčnost cívky a frekvence proudu.
  - Fázový posun má zásadní dopad na elektrický výkon v obvodu. 
