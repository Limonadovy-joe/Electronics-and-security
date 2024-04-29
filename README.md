# Electronics-and-security

- [Definition of basic quantities](#definition-of-basic-quantities)
  - [Voltage](#voltage)
  - [Current](#current)
  - [Resistance](#resistance)
  - [Power](#power)
  - [Capacitance](#capacitance)
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

