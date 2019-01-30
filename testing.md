### 2.	Hvað er leikjavél? Berðu saman tvær leikjavélar, t.d. Unity og Unreal (1%)

Munurinn á milli Unity og Unreal:
Unity notar C#  Unreal notar C++ og skriptar með Lua

Unity er betra fyrir einn mann og unreal er betra fyrir lið af fólki.
Það þýðir ekki að þú getur ekki unnið einn í unreal eða með lið af fólki í unity.

Unreal er open source og er frítt Meðan Unity vélinn er meira lokuð og getur breytt minna í vélinni sjálfri.

Unreal er betra fyrir leikjatölvur, meðan Unity er betra fyrir snjall síma.

### 1.	Útskýrðu vel e. GameLoop í leikjagerð og í Unity. (1%)
Gameloop er forritunar kóði sem keyrir sig aftur og aftur, svo að leikurinn fer keyrir áfram.
Ýmindaðu þér gamla myndavél sem tekur 20 myndir á sekúndu og setur það á filmu, svo spilaru filmuna eins og í bíó.
Gameloop keyrir hvern einasta ramma í leiknum

### 3. Útskýrðu hvernig árekstur (e. collision detection) gæti verið útfærður í leik með
### sýnidæmi (kóði, skýringamynd, stærðfræði osfrv.).
Árekstur er þegar tveir hlutir snerta saman og það verða viðbrögð t.d. eins og sprengjing eða endurskot eða snjarri.
![mynd!](https://uploads.toptal.io/blog/image/924/toptal-blog-image-1425298886178.jpg)
# dæmi um collision


### 4. Hvað er asset?
Asset eru hlutir eins og módel, hljóð og texture.

### 5. Hvað er e. game object og hvernig tengist það e. components í e. Inspector?
Gameobject eru hlutir í leiknum sem þú getur sett components í. Sem dæmi, getur þú búið til lampa "gameobject" og sett ljós "component" í lampann. Inspector leyfir þér að skoða gameobject og components til að stilla það.

### 6. Hvað er líkt og ólíkt með game object og prefab?
Prefab er tilbúið game object sem er með tilbúin components sem þú getur sett inn í svæðið í leiknum.
Gameobject er eins og autt blað sem þú getur sett components inní það.
Bæði eru mjög svipuð en ekki alveg eins.

### 7. Hvert er samband þríhyrnings og e. mesh í 3D umhverfi? 
Mesh er búð til úr þríhyrningum í 3D umhverfi til að búa til hlut. Þríhyrningur hefur þrjá punkta sem mesh getur notað til að gera hluti.

### 8. Hvað er tags og layers?
Tags er notað til að nefna ákveðna hluti eins og "óvini". Notar það til að flokka hópa.
Layer er aðalega notað af myndavélinni til að render'a umhverfi. Getur líka notað það fyrir eitthvað sem heitir "raycasting"

### 9. Útskýrðu stuttlega hlutverk eftirfarandi glugga/svæði í Unity:
## a) Scene view: Notar það til að vinna með gameobjects eins og módel, ljós colliders til að búa til "scenes".
## b) Game view: er notað til að spila leikinn. Sýnir þér hvernig leikurinn lítur út í spilun.
## c) Project: Það geymir alla vinnu þína sem þú ert búinn að gera í leiknum. Heldur utan um allt.
## d) Hierarchy: Heldur utan um öll gameobjects og assets og prefabs
## e) Inspector: Notar það til að breyta gameobject. Getur sett inn "scripts" og breytt hlutum á gameobject, td. skugga,stærð og staðsetningu.

### 10. 
