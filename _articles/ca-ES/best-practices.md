---
locale: ca-ES
title: Millors pràctiques per a mantenidors
description: Facilitant la vostra vida com a mantenidor de codi obert, documentant processos per treure profit de la vostra comunitat.
class: millors-practiques
toc:
  what-does-it-mean-to-be-a-maintainer: "Què vol dir ser un mantenidor?"
  documenting-your-processes: "Documentant els vostres processos"
  learning-to-say-no: "Aprenent a dir no"
  leverage-your-community: "Aprofiteu la vostra comunitat"
  bring-in-the-robots: "Porteu als robots"
  its-okay-to-hit-pause: "Està bé fer una pausa"
order: 5
image: /assets/images/cards/best-practices.png
related:
  - metrics
  - leadership
---

## Què vol dir ser un mantenidor?

Si manteniu un projecte de codi obert que utilitza molta gent, és possible que hàgiu notat que escribiu menys codi i que responeu a més problemes.

En les etapes inicials d'un projecte, us trobareu experimentant amb noves idees i prenent decisions basades en el que volgueu. A mesura que el vostre projecte creixi en popularitat, us trobareu treballant més amb els vostres usuaris i contribuïdors.

Mantenir un projecte requereix molt més que codi. Aquestes tasques sovint són inesperades, però són tan o més importants per a un projecte en creixement. Hem recopilat diverses maneres de facilitar-vos la vida, documentant processos per aprofitar la vostra comunitat.

## Documentant els vostres processos

Redactar és una de les coses més importants que podeu fer com a mantenidor.

La documentació no només aclareix el vostre propi pensament, sinó que ajuda a altres persones a comprendre el que necessiteu o espereu, fins i tot abans de preguntar-ho.

Redactar les coses fa que sigui més fàcil dir que no quan alguna cosa no encaixa en el vostre àmbit. També facilita que les persones entrin i ajudin. Mai se sap qui podria estar llegint o fent servir el vostre projecte.

Fins i tot si no feu servir paràgrafs complets, anotar els punts principals és millor que no escriure res.

Recordeu mantenir actualitzada la vostra documentació. Si no podeu fer-ho sempre, suprimiu la vostra documentació obsoleta o indiqueu que està obsoleta, de manera que els contribuïdors sàpiguen que les actualitzacions són benvingudes.

### Anoteu la visió del vostre projecte

Comenceu per anotar els objectius del vostre projecte. Afegiu-los al README o creeu un fitxer separat anomenat VISION. Si hi ha altres artefactes que ajudin, com ara un full de ruta del projecte, feu-los també públics.

Tenir una visió clara i documentada us manté enfocats i us ajuda a evitar l'"àmbit imprevist" de les contribucions dels altres.

Per exemple, @lord va descobrir que tenir una visió de projecte el va ajudar a esbrinar en quines peticions destinar més temps. Com a nou mantenidor, va lamentar no ajustar-se a l'àmbit del seu projecte quan va rebre la primera sol·licitud de característica per a [Slate] (https://github.com/lord/slate).

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/1976330?v=3&s=460" class="pquote-avatar" alt="avatar" alt="avatar d'en @lord">
  Vaig fer-ho bé. No em vaig esforçar per trobar una solució completa. En lloc d'una solució a mig fer, m'agradaria haver dit "Ara no tinc temps per a això, ho afegiré a la llista de coses ideals a tenir a llarg termini."
  <p markdown="1" class="pquote-credit">
— @lord, ["Consells per a nous mantenidors de codi obert"](https://lord.io/blog/2014/oss-tips/)
  </p>
</aside>

### Comuniqueu les vostres expectatives

Les regles poden ser angoixants d'escriure. Sovint pot semblar que esteu vigilant el comportament dels altres o tallant tota la diversió.

Malgrat això, escrites i executades de manera justa, les bones regles capaciten els mantenidors. T'impedeixen ser arrossegat a fer coses que no vols fer.

La majoria de persones que es troben amb el vostre projecte no saben res sobre vosaltres ni sobre les vostres circumstàncies. Poden suposar que cobreu un sou per treballar-hi, especialment si és quelcom que habitualment utilitzen amb certa dependència. Potser, en un moment donat, destineu molt temps al vostre projecte, però ara esteu ocupats amb una nova feina o algun membre de la família.

Tot això és perfectament acceptable! Simplement assegureu-vos de que les altres persones en tenen constància.

Si el manteniment del vostre projecte és a temps parcial o purament voluntari, sigueu honestos sobre la quantitat de temps que disposeu. Això no és el mateix que la quantitat de temps que penseu que el projecte requereix, o que els altres volen que hi destineu.

Heus aquí algunes regles que val la pena anotar:

* Com es revisa i s'accepta una contribució (_Necessiten proves? Una plantilla d'incidència?_)
* Tipus de contribucions que acceptareu (_Voleu només ajuda amb una determinada part del vostre codi?_)
* Quan és adequat el seguiment (_per exemple, "Podeu esperar una resposta d'un mantenidor en un termini de 7 dies. Si no heu sentit res aleshores, no dubteu a fer-lo servir"._)
* Quant de temps es dedica al projecte (_per exemple, "Només dediquem unes 5 hores setmanals a aquest projecte"_)

[Jekyll](https://github.com/jekyll/jekyll/tree/master/docs), [CocoaPods](https://github.com/CocoaPods/CocoaPods/wiki/Communication-&-Design-Rules), i [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Maintainers-Avoiding-Burnout.md) són diversos examples de projectes amb regles bàsiques per als mantenidors i contribuïdors.

### Mantingueu pública la comunicació

No oblideu, també, de documentar les vostres interaccions. Sempre que pugueu, mantingueu pública la comunicació sobre el vostre projecte. Si algú intenta contactar-vos de manera privada per discutir una sol·licitud de funcions o una necessitat de suport, dirigiu-lo educadament a un canal de comunicació pública, com ara una llista de correu o un gestor d'incidències.

Si us reuniu amb altres mantenidors o preneu una decisió important en privat, documenteu aquestes converses en públic, fins i tot si es tracta només de publicar les vostres notes.

D'aquesta manera, qualsevol que s'uneixi a la vostra comunitat tindrà accés a la mateixa informació que algú que hi hagi estat durant anys.

## Aprenent a dir no

Ja heu escrit les coses. L'ideal seria que tothom llegís la vostra documentació, però, en realitat, haureu de recordar als demés que aquest coneixement existeix.

Tanmateix, tenir-ho tot per escrit, contribueix a despersonalitzar situacions quan necessiteu fer complir les normes.

Dir que no, no és pas divertit, però _"La vostra contribució no coincideix amb els criteris d'aquest projecte"_ sona menys personal que _"no m'agrada la vostra contribució"_.

Dir que no es pot aplicar a moltes situacions que us trobareu com a mantenidor: sol·licituds de funcions que no s'ajusten a l'àmbit d'actuació, algú fent descarrilar un debat, donant feina innecessària als demés.

### Mantingueu la conversa amistosa

Un dels llocs més importants on practicareu dient que no és en el vostre problema i a la vostra cua de Sol·licituds d'Extracció (SE). Com a mantenidors del projecte, inevitablement rebreu suggeriments que no voldreu acceptar.

És possible que la contribució canvii l'àmbit del vostre projecte o no coincideixi amb la vostra visió. Pot ser lque a idea sigui bona, però que la implementació sigui deficient.

Independentment del motiu, és possible tractar amb cura aquelles contribucions que no compleixin amb els estàndards del vostre projecte.

Si rebeu una contribució que no voleu acceptar, la vostra primera reacció podria ser ignorar-la o fer veure que no l'heu vist. Si ho feu, podria ferir els sentiments dels altres, o fins i tot desmotivar altres potencials col·laboradors de la vostra comunitat.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/869950?v=3&s=400" class="pquote-avatar" alt="avatar" alt="avatar d'en @KrauseFx">
  La clau per gestionar el suport per a projectes de codi obert a gran escala, és evitar que els problemes es belluguin. Intenteu evitar tenir problemes. Si sou desenvolupador d'iOS, sabreu el frustrant que pot arribar a ser el fet d'enviar radars. És possible que rebeu resposta, 2 anys més tard, i se us demani que torneu a provar amb l'última versió d'iOS.
  <p markdown="1" class="pquote-credit">
— @KrauseFx, ["Escalant comunitats de codi obert"](https://krausefx.com/blog/scaling-open-source-communities)
  </p>
</aside>

No deixeu una contribució no desitjada oberta pel fet de sentir-vos culpables o voler ser amables. Amb el pas del temps, els vostres problemes i SE sense resposta faran que treballar en el vostre projecte resulti molt més estressant i intimidant.

És millor tancar immediatament aquelles contribucions que sabeu per endavant que no voleu acceptar. Si el vostre projecte ja pateix un gran retard, @steveklabnik té suggeriments sobre [com classificar problemes de manera eficient] (http://words.steveklabnik.com/how-to-be-an-open-source-gardener).

En segon lloc, ignorar les contribucions envia un senyal negatiu a la vostra comunitat. Contribuir a un projecte pot ser intimidatori, especialment si és per primera vegada. Fins i tot si no accepteu les contribucions dels altres, mostreu reconeixement per la persona que hi ha al darrera, i agraïu-li el seu interès. És un gran elogi!

Si no voleu acceptar una contribució:

* **Doneu-los les gràcies** per la seva contribució
* **Expliqueu-los per què no encaixa** en l'àmbit del projecte i oferiu suggeriments clars per a la millora, si és possible. Sigueu amable, però ferm.
* **Enllaceu cap la documentació rellevant**, si en disposeu. Si observeu sol·licituds repetides de coses que no voleu acceptar, afegiu-les a la vostra documentació per evitar de repetir-les.
* **Tanqueu la petició**

No haurieu de necessitar més de 1-2 frases per respondre. Per exemple, quan un usuari de [Celery] (https://github.com/cellery/celery/) va informar d'un error relacionat amb Windows, en @berkerpeksag [va respondre amb] (https://github.com/celery/celery/issues/3383):

![Captura de pantalla de Celery](/assets/images/best-practices/celery.png)

Si la idea de dir no us atemoritza, no esteu sol. [Poseu-ho] (https://blog.jessfraz.com/post/the-art-of-closing/) com en @jessfraz:

> He parlat amb els mantenidors de diversos projectes de codi obert, Mesos, Kubernetes, Chromium, i tots estan d'acord en que una de les parts més dures de ser un mantenidor és dir "No" als pedaços que no vulgueu.

No us sentiu culpable de no voler acceptar la contribució d'algú. La primera regla de codi obert, [segons](https://twitter.com/solomonstre/status/715277134978113536) @shykes: _"No és temporal, sí és per sempre."_ Tot i que l'empatia per l'entusiasme d'una altra persona és cosa bona, rebutjar una contribució no és el mateix que rebutjar la persona que hi ha al darrera.

En última instància, si una contribució no és prou bona, no teniu cap obligació d'acceptar-la. Sigueu amable i atent quan la gent contribueixi al vostre projecte, però només accepteu canvis que cregueu realment que faran que el vostre projecte sigui millor. Com més freqüentment practiqueu dir que no, més fàcil serà. En dono fe.

### Sigueu proactius

Per reduir el volum de contribucions no desitjades, expliqueu el procés del vostre projecte per enviar i acceptar contribucions, a la vostra guia sobre contribucions.

Si rebeu massa contribucions de baixa qualitat, demaneu als col·laboradors que facin una mica de feina per endavant, per exemple:

* Empleneu un problema o una plantilla de SE/llista de verificació
* Obriu un problema abans d'enviar una SE

Si no segueixen les vostres regles, tanqueu el problema immediatament i adreceu-los cap a la documentació.

Tot i que aquest enfocament pot semblar desconsiderat al principi, ser proactiu és realment bo per a ambdues parts. Redueix la possibilitat que algú introdueixi moltes hores de treball malgastades en una SE que no penseu acceptar. I fa que la vostra càrrega de treball sigui més fàcil de gestionar.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/125011" class="pquote-avatar" alt="avatar">
  Idealment, expliqueu-los en un fitxer CONTRIBUTING.md com poden obtenir una millor indicació en el futur sobre el que seria o no acceptat abans de començar la feina.
  <p markdown="1" class="pquote-credit">
— @mikemcquaid, ["Tancant Sol·licituds d'Extracció amablement"](https://github.com/blog/2124-kindly-closing-pull-requests)
  </p>
</aside>

De vegades, quan dieu que no, el vostre potencial col·laborador podria molestar-se o criticar la vostra decisió. Si el seu comportament es torna hostil, [prengueu mesures per apaivagar la situació](https://github.com/jonschlinkert/maintainers-guide-to-staying-positive#action-items) o fins i tot elimineu-los de la vostra comunitat, si no estan disposats a col·laborar de forma constructiva.

### Abraceu la tutoria

Sovint pot passar que algú de la vostra comunitat enviï regularment contribucions que no compleixin amb els estàndards del vostre projecte. Pot ser frustrant per ambdues parts rebutjar-se repetidament.

Si veieu que algú està entusiasmat amb el vostre projecte, però necessita polir alguns aspectes, tingueu paciència. Expliqueu-los clarament en cada situació per què les seves contribucions no compleixen amb les expectatives del projecte. Intenteu fer-los referència a una tasca més fàcil o menys ambigua, com ara un problema marcat com a _"primer error,"_ per tal d'iniciar-los en la feina. Si teniu temps, considereu orientar-lo a través de la seva primera contribució, o trobeu a algú més a la vostra comunitat que estigui disposat a fer-ho.

## Aprofiteu la vostra comunitat

No cal fer-ho tot tu mateix. La comunitat del vostre projecte existeix per un motiu! Fins i tot si encara no teniu una comunitat de col·laboradors actius, si teniu molts usuaris, poseu-los a treballar.

### Compartiu la càrrega de treball

Si voleu que tothom participi, comenceu per preguntar al vostre entorn.

Quan trobeu nous contribuïdors fent contribucions repetides, reconeixeu el seu treball oferint-los més responsabilitat. Documenteu com els altres poden créixer en funcions de lideratge, si ho desitgen.

Encoratjar els demés a [compartir la propietat del projecte](../building-community/#share-ownership-of-your-project) pot reduir considerablement la vostra pròpia càrrega de treball, tal i com la @lmccart va descobrir en el seu projecte [p5.js](https://github.com/processing/p5.js?files=1).

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/191056?v=3&s=460" class="pquote-avatar" alt="avatar">
  Jo havia estat dient: "Sí, qualsevol persona pot estar involucrada, no cal que tingui molts coneixements de codi" [...]." Teníem gent inscrita per venir [a un esdeveniment] i aleshores va ser quan em vaig preguntar realment: és cert el què he dit? Hi haurà 40 persones que apareixeran, i no podré assseure'm amb cadascuna d'elles ... Però la gent es va unir, i d'alguna forma va funcionar. Tan aviat com una persona ho va aconseguir, va poder ensenyar al seu veí.
  <p markdown="1" class="pquote-credit">
—  @lmccart, ["Què significa exactament “codi obert”? Edició p5.js"](https://medium.com/@kenjagan/what-does-open-source-even-mean-p5-js-edition-98c02d354b39#.chnjlag7p)
  </p>
</aside>

Si necessiteu allunyar-vos del vostre projecte, ja sigui temporal o permanentment, no us faci vergonya demanar-li a algú que se'n faci càrrec.

Si altres persones estan entusiasmades amb la seva orientació, doneu-los accés per poder cometre (*commit*) o bé doneu-li el control a una altra persona. Si algú va fer un bifurcació (*fork*) del vostre projecte i el manté activament en un altre lloc, considereu enllaçar amb la bifurcació del vostre projecte original. És genial que tantes persones vulguin fer perdurar el vostre projecte!

En @progrium [va descobrir això](http://progrium.com/blog/2015/12/04/leadership-guilt-and-pull-requests/) tot documentant la visió del seu projecte, [Dokku](https://github.com/dokku/dokku), ajudant a viure aquests objectius fins i tot després d'allunyar-se del projecte:

> Vaig escriure una pàgina de wiki que descrivia el que volia i per què ho volia. Per alguna raó, va sorprendre'm que els mantenidors comencèssin a moure el projecte en aquella direcció! Va passar exactament com jo ho faria? No sempre. Però tot i així el projecte va arribar més a prop del que jo vaig anotar.

### Deixeu que els altres construeixin les solucions que necessiten

Si un potencial contribuïdor té una opinió diferent sobre el que hauria de fer el vostre projecte, és possible que vulgueu encoratjar-los a treballar amb la seva pròpia bifurcació.

Bifurcar un projecte no ha de ser una cosa dolenta. Ser capaç de copiar i modificar projectes és una de les millors coses sobre el codi obert. Animar els membres de la comunitat a que treballin en la seva pròpia bifurcació pot donar-los la sortida creativa que necessiten, sense entrar en conflicte amb la vostra visió del projecte.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/481677?v=3&s=400" class="pquote-avatar" alt="avatar">
  Em refereixo al cas d'ús del 80%. Si ets un dels unicornis, si us plau bifurca el meu treball. No m'ofenderé! Els meus projectes públics gairebé sempre estan destinats a resoldre els problemes més comuns; Tracto de que sigui fàcil aprofundir, ja sigui bifurcant el meu treball o estenent-lo.
  <p markdown="1" class="pquote-credit">
— @geerlingguy, ["Per què tanco SEs"](https://www.jeffgeerling.com/blog/2016/why-i-close-prs-oss-project-maintainer-notes)
  </p>
</aside>

El mateix s'aplica a un usuari que realment vol una solució, que simplement no és a la vostra disposició de construir. Oferir APIs i garfis (*hooks*) de personalització pot ajudar els altres a satisfer les seves necessitats, sense haver de modificar la font directament. En @orta [es va trobar que](https://artsy.github.io/blog/2016/07/03/handling-big-projects/) encoratjant complements (*plugins*) per a CocoaPods va provocar "algunes de les idees més interessants":

> És gairebé inevitable que una vegada un projecte esdevé gran, els mantenidors han de ser molt més conservadors en el moment d'introduir codi nou. Et tornes més bo dient "no", però molta gent té necessitats legítimes. Per tant, enlloc d'això, acabeu convertint la vostra eina en una plataforma.

## Porteu als robots

De la mateixa manera que hi ha tasques en que altres persones poden ajudar-vos, també hi ha tasques que cap humà hauria de fer mai. Els robots són els vostres amics. Utilitzeu-los per facilitar-vos la vida com a mantenidors.

### Demaneu proves (*tests*) i altres controls per millorar la qualitat del vostre codi

Una de les maneres més importants per tal d'automatitzar el vostre projecte és afegir proves.

Les proves ajuden els col·laboradors a confiar en que no trencaran res. També fan més fàcil revisar i acceptar contribucions ràpidament. Com més atents sigueu, més compromesa pot arribar a estar la vostra comunitat.

Configureu les proves automàtiques que s'executaran a totes les contribucions entrants, i assegureu-vos que les vostres proves es puguin executar localment pels col·laboradors. Demaneu que totes les contribucions de codi passin les proves abans de poder enviar-les. Ajudareu a establir un nivell mínim de qualitat per a tots els enviaments. Utilitzar [comprovacions d'estat requerides](https://help.github.com/articles/about-required-status-checks/) a GitHub pot ajudar a evitar fusions (*merge*) canvis sense passar les proves.

Si afegiu proves, assegureu-vos d'explicar com funcionen al vostre fitxer CONTRIBUTING.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/812892?v=3&s=460" class="pquote-avatar" alt="avatar">
  Crec que les proves són necessàries per a tot el codi en que les persones treballen. Si el codi era total i perfectament correcte, no necessitaríem canvis; només escrivim codi quan hi ha alguna cosa incorrecta, ja sigui que "falla" o que "no té tal funció". Independentment dels canvis que feu, les proves són imprescindibles per interceptar qualsevol regressió que pugueu introduir accidentalment.
  <p markdown="1" class="pquote-credit">
— @edunham, ["Automatització comunitària de Rust"](https://edunham.net/2016/09/27/rust_s_community_automation.html)
  </p>
</aside>

### Utilitzeu eines per automatitzar tasques bàsiques de manteniment

La bona notícia sobre el manteniment d'un projecte popular és que altres mantenidors probablement han tingut problemes similars i han creat una solució.

Hi ha una [varietat d'eines disponibles](https://github.com/showcases/tools-for-open-source) per ajudar a automatitzar alguns aspectes realcionats amb el treball de manteniment. Alguns exemples:

* [publicació-semàntica](https://github.com/semantic-release/semantic-release) automatitza les vostres publicacions
* [robot-de-mencions](https://github.com/facebook/mention-bot) menciona als revisors potencials per a sol·licituds d'extracció
* [Perill](https://github.com/danger/danger) ajuda a automatitzar la revisió de codi

Per als informes d'errors i altres contribucions comunes, GitHub té [Plantilles de problema i Plantilles de sol·licitud d'extracció](https://github.com/blog/2111-issue-and-pull-request-templates), que podeu crear per a optimitzar la comunicació que rebeu. En @TalAter va fer una [Trieu la vostra pròpia guia d'aventura](https://www.talater.com/open-source-templates/#/) per ajudar-vos a escriure les vostres Plantilles de problema i Plantilles de sol·licitud d'extracció.

Per gestionar les vostres notificacions per correu electrònic, podeu configurar [filtres de correu electrònic](https://github.com/blog/2203-email-updates-about-your-own-activity) per tal d'organitzar-les per prioritat.

Si voleu anar una mica més enllà, les guies d'estil i les lents (*linters*) poden estandarditzar les contribucions del projecte i fer-les més fàcils de revisar i acceptar.

Tanmateix, si els vostres estàndards són massa complicats, poden augmentar les barreres per poder contribuir. Assegureu-vos que només afegiu les regles suficients per facilitar la vida de tots.

Si no esteu segurs de quines eines heu d'utilitzar, consulteu el que fan altres projectes populars, especialment aquells del vostre ecosistema. Per exemple, quin aspecte té el procés de contribució per a altres mòduls de Node? Utilitzar eines i enfocaments similars també farà que el vostre procés sigui més familiar per als vostres col·laboradors objectiu.

## Està bé fer una pausa

Treballar amb codi obert us donarà alegries. Però potser ara us comença a fer-vos sentir evasius o culpables.

Potser us sentiu aclaparats o amb un sentiment creixent de temor quan penseu en els vostres projectes. I mentrestant, els problemes i les peticions d'extracció s'acumulen.

Estar cremat (*burnout*) és un problema real i generalitzat en el treball de codi obert, especialment entre els mantenidors. Com a mantenidor, la vostra felicitat és un requisit no negociable per a la supervivència de qualsevol projecte de codi obert.

Tot i que no calgui recordar-ho, fes un descans! No espereu fins a sentir-vos cremats per prendre unes vacances. En @brettcannon, un desenvolupador del nucli de Python, va decidir prendre [un mes de vacances llarg](https://snarky.ca/why-i-took-october-off-of-oss-volunteering/) després de 14 anys de voluntariat d'OSS.

Com a qualsevol altre tipus de feina, fer pauses regulars us mantindrà fresc, feliç i emocionat pel vostre treball.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/36432?v=3&s=400" class="pquote-avatar" alt="avatar">
  En mantenir WP-CLI, he descobert que primer m'he de fer feliç a mi mateix, i establir límits clars sobre la meva participació. El millor equilibri que he trobat és de 2 a 5 hores setmanals, com a part del meu calendari de treball normal. Això fa que matingui la meva participació com una passió, i de sentir-se massa com treballant. Gràcies al fet de prioritzar els problemes en els que estic treballant, puc fer progressos regulars sobre el que considero més important.
  <p markdown="1" class="pquote-credit">
— @danielbachhuber, ["Us acompanyo en el sentiment, ara sou el mantenidor d'un projecte de codi obert popular"](https://runcommand.io/2016/06/26/my-condolences-youre-now-the-maintainer-of-a-popular-open-source-project/)
  </p>
</aside>

De vegades, pot ser difícil descansar del treball de codi obert, quan sentiu que tothom us necessita. La gent pot, fins i tot, intentar fer-vos sentir culpable de fugir.

Feu el millor que pogueu per trobar suport per als vostres usuaris i per a la vostra comunitat mentre estigueu fora d'un projecte. Si no podeu trobar el suport que necessiteu, preneu-vos un descans de totes formes. Assegureu-vos de comunicar quan no estigueu disponible, per tal que la gent no estigui confosa per la vostra falta de resposta.

Fer pauses s'aplica més enllà de les vacances. Si no voleu fer treballs de codi obert els caps de setmana, o durant l'horari laboral, comuniqueu aquestes expectatives als altres, per tal de no molestar-vos.

## Cuideu-vos primer!

Mantenir un projecte popular requereix diferents habilitats que les primeres etapes de creixement, però no és menys gratificant. Com a mantenidor, practicareu el lideratge i les habilitats personals a un nivell que poques persones poden experimentar. Tot i que no sempre és fàcil de gestionar, establir límits clars i només assumir el que us fa sentir còmodes, us ajudarà a mantenir-vos feliços, frescos i productius.
