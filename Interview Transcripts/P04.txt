I: bist du damit einverstanden, dass du hier aufgezeichnet wirst?

B: ja, ich bin damit einverstanden

I: wie alt bist du?

B: 22

I: wie viele Jahre programmierst du insgesamt schon?

B: seit 2017, das sind 5 jahre

I: wie viele daovn in Ausbildung?

B: 4

I: welche art ausbildung?

B: studium bachelor informatik

I: wie viele jahre hast du für größere softwareprojekte programmiert, zum beispiel in einer firma?

B: da würde ich mal 1 jahr sagen, falls es zählt, dass ich bei der technischen informatik dort ne hardware-ansteuerung für ne drohne entwickelt hab

I: wie groß war das projekt? also unter 900 zeilen, zwischen 900 und 40'000 zeilen oder über 40'000 zeilen?

B: also das waren so um die 30'000 zeilen code, denke ich

I: auf einer skala von 1 bis 10, also 1 sehr unerfahren und 10 sehr erfahren, wie hoch shcätzt du deine eigene programmiererfahrung ein?

B: 9

I: auf einer skala von 1 bis 5, wie hoch schätzt du deine programmiererfahrung im vergleich mit experten mit 20 jahren praktischer erfahrung ein?

B: 2

I: auf einer skala von 1 bis 5, wie hoch schätzt du deine programmiererfahrung im verlgeich mit deinen kollegen, beziehungsweise mit leuten, die ähnliches machen wie du ein?

B: also ich geh jetzt mal vom studium aus, da würde ich sagen 5

I: wie viele programmiersprachen kennst du, bei denen du deine programmiererfahrung bei 3 oder höher einschätzen würdest?

B: 9

I: welche sind das?

B: C, C++, das würde ich als eine nehmen

I: dann sind wir eher bei 10

I2: die würde ich als 2 nehmen, ja

B: dann Rust, Kotlin, Python, Java, JavaScript, TypeScript, Haskell, C# und php

I: (zählt bis 11)

B: oh, dann habe ich mich verzählt

I: dann nehmen wir 11

I: wieder auf einer skala von 1 bis 5, wie erfahren bist du mit den folgenden programmier-paradigmen? funktionale programmierung?

B: 5

I: imperative programmierung?

B: 5

I: logische programmierung?

B: 2

I: und objekt-orientiert?

B: 5

I: dann kommen wir zum zweiten teil. das sind fragen, da geht es um deinen programmier-prozess. und dafür würde ich dich einfach gern bitten, mir etwas über ein aktuelles projekt von dir zu erzählen. kann von der arbeit sein, kann privat sein, kann abgeschlossen sein, kann sich noch in arbeit befinden. einfach so ein bisschen kontext, dass wir wissen, was ist das für ein projekt und dann wie gehst du dabei vor? 

B: aktuell schreibe ich für mich privat eine kleine app, die dafür da sein soll, später so klassische bürokratische (?) daten zu managen. wo man dann am ende sagen kann, man kann einen vertrag einscannen, beziehungsweise daten eingeben und dann hat man da vertragskonto, personennummer, monatliche kosten und kann auch andere monatliche kosten und halt alles mit auflisten. und hätte dann potentiell dabei ansprechpartner, beziehungsweise email, beziehungsweise wo kann man sich einloggen, um das dann auch zu kündigen, dass man solche sachen managen kann. dazu sollen dann am ende auch mietverträge, (?)-verträge und alles mögliche mitreingehören und im idealen fall soll das einfach nur eine scan-funktion und die app soll das dann halt alles automatisch aus dem vertrag auslesen können. wie mache ich das? ist das interessant?

I: ja, das ist interessant

B: okay, wie mache ich das. also ich habe mich in dem kontext jetzt das erste mal wirklich mit app-programmierung auseinandergesetzt. und das mache ich nativ mit kotlin. dafür schreibe ich halt in kotlin das frontend dafür und im backend wollte ich mich schon länger mal mit so containerisierung auseinandersetzen und schreib dementsprechend in / also für docker-container microservices in verschiedenen programmiersprachen. einserseits nutze ich da auch kotlin für so die ganzen klassischen sachen, so die datenbank abfragen. für sachen die so image-processing brauchen, habe ich ein python-microservice. für sachen, die so ein bisschen rechenaufwendig sind und weil ich die sprache sehr mag, habe ich rust genutzt, das heißt die drei sprachen nutze ich im backend.

wie bin ich da vorgegangen? ich habe, weil es ein hobby-projekt ist keine wirklich lange design-phase gehabt, sondern einfach lust drauf gehabt, das zu starten. und hab halt einfach angefangen zu programmieren, indem ich mir angeguckt hab, wie erstellt man ein app-frontend, wie kann man damit was machen. das heißt da habe ich erstmal so ein bisschen geguckt und ein bisschen rumgeklickt, rumgeschaut, bis ich dann irgendwo (?störgeräusche) funktionales, gut aussehendes design-prinzip hatte, also wie es aussah. und hab mich dann halt im hintergrund ein bisschen damit auseinandergesetzt, wie man / also, deployment würde ich das nicht genau bezeichnen, aber wie man das halt dann wirklich alles aufsetzen kann mit den containern im hintergrund. das heißt, damit habe ich mich dann erstmal auseinandergesetzt, bevor ich wirklich in die programmierung reingegangen bin. bei der programmierung dann im hintergrund habe ich bei rust das rocket-framework benutzt, das kannte ich schon aus einem vorherigen projekt, da musste ich also (?) schnell nachschauen. 07:56 hab da halt einfach so ein bisschen hin und her programmiert. bei python, image-processing, hab ich dann sowas wie opencv benutzt und flask für den api zugriff, das kannte ich halt auch schon. und bei php, da schreibt man ja nativ mit apis, da habe ich kein framework benutzt, da habe ich/ äh, nicht php, kotlin. kotlin, da habe ich dann halt spring benutzt. und spring habe ich da auch das erste mal benutzt und musste dementsprechend auch erstmal ein bisschen nachschauen, wie man das überhaupt macht.

08:28 I: um das nochmal so ein bisschen zusammenzufassen, also du hast dich halt in die verschiedenen frameworks undso, die du benutzt, eingelesen und dann/ habe ich das richtig verstanden, du hast gesagt, du hast so ein bisschen "hin und her" programmiert dabei?  

08:48 B: genau. eingelesen trifft es nicht ganz genau, also ab und zu schon in die dokumentation gucken, vor allem bei sachen, wo ich mich gar nicht mit auskenne, schaue ich am anfang immer youtube videos, die so ein bisschen zeigen, wie es geht  

09:09 I: was meinst du mit "hin und her programmieren"?  

09:13 B: also dass ich halt nicht wirklich einen design-prozess durchlebt habe in dem projekt für mich, sondern einfach denke hey, zum beispiel ein authentifikations-service wär jetzt ganz interessant. und dass ich dann halt gucke, ja, wo mache ich das jetzt. authentifikationsservice, habe ich ein bisschen rumgeguckt, was gibt's da alles mögliche und hab dann für mich überlegt, damit ich einfach mal weiß, wie das funktioniert, dann habe ich das von null auf in rust implementiert und mich da halt so ein bisschen stück für stück langgehangelt. also erstmal nach dem prinzip, erstmal halt die api-anfrage, dass man irgendwie nutzer und nen passwort übermittelt. dann auch irgendwie, dass man sich darum kümmert, ja ich brauche eine datenbank, um das zu speichern. dann natürlich japasswörter will man nicht unverschlüsselt in der datenbank haben, das heißt, dann habe ich mich damit auseinandergesetzt. dann habe ich geschaut, wie kann man das im web tatsächlich weitergeben, dass eine person authentifiziert ist. das passiert dann zum beispiel durch cookies. aber bei cookies möchte man dann ja zum beispiel auch nicht den nutzernamen und das passwort drinstehen haben, weil das wäre sicherheitskritisch anfällig, wenn man zum beispiel (?) machen würde. dementsprechend nutzt man sogenannte jwts, json web tokens, da musste ich halt auch erstmal gucken, wie die funktionieren, und hab mich dann auch dort immer so ein bisschen umgeschaut, wie funktionieren die genau. das heißt angefangen mit, wie funktioniert die verschlüsselung davon, welche protokolle gibt es da, um die zu nutzen, wie gibt man das dann von rust im (?) jetzt tatsächlich den cookie als jwt zurück an den browser und solche sachen. und das in ganz ganz vielen bereichen. und dann hatte ich halt den authentifikations-service. und dann habe ich erstmal wieder geguckt, aha, backend, schön und gut, und hab das dann erstmal im frontend implementiert, also in der  app tatsächlich, um zu schauen, geht das auch alles. und dann habe ich ein bisschen weiter im frontend gemacht um zu schauen, was wäre denn cool so zu haben, also wie soll es dann am ende aussehen. 11:10 das heißt nicht, ich würde es jetzt mal als statisch bezeichnen, als die ganze zeit strukturiert am backend zu arbeiten und da erstmal die gesamte struktur aufzubauen mit automatisierten tests und allem möglichen, nein, eher so die ganze zeit probieren und für mich das proof of concept hinzubekommen  

11:27 I: also du fängst einfach so an einem punkt mal so an und guckst, was sich dann daraus entwickelt, was an notwendigkeiten  

B: ja, genau. bei dem projekt auf jeden fall

11:40 I: also entspricht das/ also ist das nicht quasi immer wie du vorgehst?  

11:44 B: das kommt ganz darauf an, jetzt zum beispiel im bereich, was ich halt hier auch für die arbeit mache, das ist ja eher so ein bisschen datenauswertung, data science, da lohnt es sich meiner ansicht nicht, test driven development zu schreiben, weil das eher alles so hoch * volatilen/ mir fällt gerade das deutsche wort nicht ein. und dementsprechend da einen statischen design-prozess durchzugehen, wenn man halt, ich sag jetzt mal in anführungszeichen NUR ein paar skripte schreibt, die daten auswerten, weiß ich nicht, ob sich da ne gesamte infrastruktur für lohnt, die aufzusetzen. also da mache ich dann meistens so/ oder halt mich einfach an irgendwelchen/ an den research questions halt fest und gucke, wie man die halt genau abarbeiten kann. aber das würde ich jetzt auch nicht als struktur für ein software-produkt aufbauen. 12:34 als ich zum beispiel die hardwareansteuerung gemacht hab, da habe ich legacy-code bekommen und um dort reinzukommen habe ich halt erstmal ein UML-diagramm dafür gezeichnet/ klassendiagramm. und habe überlegt, wie tatsächlich diese ganzen klassen miteinander kommunizieren und hab das dann halt weiter ausgebaut, indem ich halt auch weiter mit dem uml erstmal überlegt hab, wie kann ich da konzeptuell arbeiten.   

12:59 I: da habe ich jetzt grade akustisch nicht ganz verstanden, also zu welchem projekt war das mit dem uml?  

13:03 B: das wo ich gesagt hatte bei der technischen informatik, wo ich dieses eine jahr an der hardwareansteuerung für eine drohne gearbeitet habe. also das hängt ganz davon ab, ob es jetzt für mich ein persönliches projekt ist, wo ich sage, hey, da möchte ich für mich einfach nur beweisen oder nur lernen, wie's geht. hängt davon ab, wie/ welche fluktuation oder wie groß das projekt am ende wird, wie jetzt zum beispiel bei datenauswertungen. okay, da steckt schon einiges an skripten hinter, ist jetzt aber keine ganze software-struktur. wenn es jetzt aber ein produkt sein soll, was über längerfristige zeit dokumentiert sein soll und auch wirklich genutzt werden soll in größerem stil und auch von mehreren programmierern, dann arbeite ich alleine aus dokumentationsgründen mit ner design-phase  

14:01 I: also du sagst, die größten kriterien, dass sich das unterscheidet, sind halt ob es privat für dich oder oder für die arbeit, und die größe  

14:13 B: genau  

14:17 I: aber wenn du privat für dich programmierst, dann ähnelt der prozess meistens dem, was du jetzt für die app beschrieben hast  

14:23 B: genau  

14:30 I: wenn wir jetzt beim app-projekt bleiben, oder generell bei den privaten projekten, wenn du das programmierst, wenn du die app schreibst, hast du da wen im kopf? also schreibst du das für jemanden, also irgendwie für einen endnutzer oder so oder nur für dich selbst, oder hast du da irgendwie was im kopf?  

14:49 B: ich schreib ganz ganz viel davon einerseits manchmal um für mich gewisse sachen zu automatisieren, zu vereinfachen. wenn's jetzt gewisse skripte sind, um sachen runterlaufen zu lassen, oder wie jetzt diese app, die soll für mich dann halt auch (?) diese bürokratischen abo-modelle und sowas so ein bisschen auf einen blick haben, weil damit bin ich sehr sehr schlecht persönlich. und um sowas im blick zu behalten und deswegen das irgendwo zentral zu haben wär ganz cool. oder ich mach gewisse sachen einfach nur aus lernzwecken für mich. das heißt, damit ich sehe, aha, dieses teilfeld der informatik, da habe ich noch nie so viel drin gemacht und das interessiert mich jetzt einfach mal, da ein bisschen einblick zu bekommen. das heißt, wenn man zum beispiel compiler/ oder interpreter benutzt man ja eigentlich immer und um ein bisschen genauer zu verstehen, wie funktionieren die, kann man sich auch mal so nen kleinen selbst schreiben. und das finde ich dann halt das interessante, um mehr einblick in die gesamten technologien zu bekommen  

15:58 I: gut, ich glaube, das ist für den teil eigentlich schon gut. dann würd ich zum letzten teil übergehen vom interview. und da geht's um die frage, hast du schonmal eins deiner projekte abgebrochen?  

16:24 B: ja, ich sag jetzt mal nicht aktiv abgebrochen, sondern eher liegen gelassen. also dass ich dann wirklich sag hey, ich hab hier dieses projekt, da hab ich so vielleicht ein paar grundzüge gelernt und jetzt ist es dann halt einfach so, hier interessiert mich erstmal was anderes. obwohl, doch, doch, ein paar projekte hab ich mal abgebrochen. das sind vor allem bereiche in der computergrafik, weil mir das dann an manchen stellen viel zu aufwendig und zu weit weg vom programmieren war und eher die reine mathematische theorie war und die gibt es schon und die hat mich dann nicht so interessiert, die eins zu eins abzuschreiben  

17:11 I: okay, also hauptsächlich dann, wenn entweder das interesse am projekt an sich quasi weg ist oder was anderes halt interessanter ist, oder wenn du feststellst, dass das projekt eigentlich zu weit weg von deinem eigentlichen interessengebiet ist  

17:24 B: genau. wenn ich das gefühl hab, dass es einfach nur stumpfes abtippen oder übersetzen von einer programmiersprache in eine andere oder vom konzeptuell mathematischen in eine programmiersprache ist, das finde ich für meine hobbyprojekte immer sehr sehr eintönig und habe ich meistens keine lust drauf  

17:51 I: gab's schonmal projekte oder momente an denen du einfach länger irgendwie hängen geblieben bist an einer stelle im programm?  

17:59 B: ja, das gab's. sogar häufiger  

18:06 I: häufiger, okay? wann passiert das, hast du da irgendwie ein beispiel im kopf?  

18:11 B: ja. ich kann ein beispiel machen und daraus können wir vielleicht schauen, wann das häufiger passiert. also ich hab jetzt keine regel, wenn ich so überlege, die mir direkt als erster gedanke in den kopf kommt, wann ich solche blockaden direkt hab. zum beispiel bei dieser hardwareansteuerung der drohne hatte ich/ das war eine kleine server-architektur, wo es halt einen server gab und verschiedene clients konnten anfragen an diesen server senden, wie sich die drohen bewegen soll. und es gab da ein problem, dass, wenn der client anfragen zum server gesendet hat, dann hat das funktioniert. aber manchmal gab es dann einen deadlock, wo dieser server komplett blockiert hat. da das gemulti-threaded war, auf ganz vielen ebenen, aber nur ein thread blockiert hat, fand ich es unglaublich schwierig, den fehler tatsächlich zu finden, wo das passiert. und daran saß ich, ich glaube insgesamt drei oder vier wochen. also ich hab in der zeit woanders noch weiterprogrammiert, aber immer, wenn halt dieser fehler aufgetaucht ist, weil der halt nicht jedes mal aufgetaucht ist, konnte ich halt auch nicht wirklich testen, ob er sinnvoll weg ist. das heißt, immer wenn ich dachte, hey, vielleicht habe ich ihn jetzt gelöst, dann habe ich es natürlich 10, 20 mal probiert, ob der jetzt weg ist. es konnte aber sein, dass das durch die nicht-deterministik von solchen mutexes, von den mutexes, die da benutzt werden und von den threads, das einfach zufall war, dass es in den 20 mal nicht passiert.   

19:49 I: okay. also einfach ein sehr schwieriger bug  

19:53 B: genau  

20:01 I: findest du da noch andere beispiele oder ist es meistens sowas?  

20:08 B: also sonst, wo ich mal eine blockade im programmieren selbst hatte, war, wenn ich dann nicht das domänen-wissen habe, wie zum beispiel was wir jetzt am anfang beim eeg hatten. wenn ich da einfach keine ahnung hatte, was man sucht, wie man tatsächlich vorgehen soll. das heißt, da haben wir eeg genutzt/ ich mag das nur nochmal kurz zusammenfassen/ in einer studie, um herauszufinden, welche mentale anstrengung eine person beim codelesen (?). die sache ist die, als wir damit angefangen hatten, ja okay, ich hatte schonmal so ein bisschen in eeg reingeguckt, aber ich hatte noch nie hands on mit dem eeg wirklich dran gearbeitet. ich hab zwar die daten aus gewissen programmen gesehen, ich hab auch mal mit gewissen libraries gearbeitet um zu sehen, he, man kann das eeg so visualisieren und so dies und das machen, aber wirklich dann die ahnung haben, oder das domänen-wissen haben, wie man tatsächlich dann damit umgeht, wenn das nicht da ist, bringt natürlich jede library-dokumentation nichts, wenn man einfach nicht weiß, was man machen möchte.  

21:08 I: also dir fehlt quasi das wissen, um überhaupt ne vorstellung zu entwickeln, wie dieses programm aussehen müsste  

21:15 B: genau  

21:23 I: okay. dann haben wir ja quasi zwei verschiedene sachen. irgendwas, was da noch aus dem rahmen fällt?  

21:30 B: nicht, das sich wüsste, nein  

21:36 I: alles klar. wie hast du die probleme gelöst? also war das dann bei der drohne/ war das einfach weitertesten und irgendwann hat es dann gepasst?  

21:53 B: ne. da war's halt so, ich hab das halt über einen langen zeitraum versucht zu beheben. also wenn ich jetzt so generalisiere bei harten bugs, manchmal schaffe ich es dann den fehler zu finden und zu sehen, aha, dort ist grober unfug passiert, der aber beim überfliegen oder auch beim normalen lesen schon sinn ergibt, aber halt irgendwas außer acht lässt. bei der stelle bei der hardwareansteuerung habe ich den fehler tatsächlich nach wochen nicht gefunden. da habe ich es dann so gemacht, ich hab gesagt, hey, das ist so viel legacy-code, so viel verwurstelung, so viel c++-schwachsinn, der da genutzt worden ist, dass ich da ein zwei nachtschichten gemacht hab und das komplett neu geschrieben habe und dann hat es funktioniert. ich hab diesen fehler auf teufel komm raus einfach nicht gefunden und hab's dementsprechend neu gemacht, von null auf. also nicht alles, aber halt dieses modul, wo der fehler aufgetaucht ist  

22:47 I: okay, und beim eeg, war das da einfach, das fehlende wissen aneignen?  

22:54 B: genau, also einerseits lesen, was man da alles machen kann und andererseits die zusammenarbeit, was eher der größere punkt ist, mit leuten, die davon ahnung haben. das haben wir ja dann mit X gemacht. und da hat mir M von X, mit dem habe ich mich dann mal zusammengesetzt, der hat mir ein bisschen literatur immer geschickt, der hat mir immer mal so ein bisschen gesagt, was es gibt. so wie es für mich wirkte/ also er hat seine masterarbeit über eeg geschrieben/ oder hat immer halt noch, wie es halt in den meisten bereichen ist, immer noch so lücken, wo man sich dann was aneignen kann. und das war gerade in dem feld, was wir gemacht haben, weil er eher so auf pattern-matching mit deep-learning gegangen ist und wir halt auf ne statische analyse, sag ich jetzt mal, über cognitive load. dementsprechend hat es da einfach viel an kommunikation gebraucht, um zu wissen, auf welchem ast sind wir, auf welchem ast sind die anderen, und dass man dann kommuniziert und von den anderen lernen kann. beziehungsweise habe ich dort auch mal eine sache, die ich gebraucht hab, nichts in einem youtube video gefunden, was gar nichts mit eegs eigentlich zu tun hatte. 24:01  da ging es dann wirklich/ dadurch dann, irgendein (?)-video geguckt. wenn ich es genau sagen soll, das war, falls das aus marvel bekannt ist, es gibt da so doctor octo/octorak oder so, der solche mechanisch steuerbare arme hat. und das hat jemand in einem hobby-projekt versucht nachzubauen mit nem eeg, wo es dann darum ging, diese arme irgendwie mit gedanken zu steuern. das war alles sehr stümperhaft gemacht, hat aber so ein paar ideen gebracht, was man machen könnte. das heißt, wie man dann zum beispiel mit den hirnwellen oder mit den einzelnen frequenzbändern agieren könnte, was wir dann auch darüber/ also, dass ich dann eine wesentlich klarere vorstellung hatte, wie das tatsächlich abläuft und dementsprechend intern einfach irgendwie eine bessere repräsentation hatte. wir hatten zu dem zeitpunkt schon ein vorgehen, das hat mir aber nochmal geholfen, das ein bisschen besser zu durchdringen. weil das in dem video einfach ziemlich gut erklärt war. oder ziemlich interessant und dementsprechend war ich da nochmal angefuchst, da nochmal ein bisschen tiefer zu tauchen, um das zu verstehen.  

25:12 I: und hättest du jetzt bei dem eeg/ oder war dein vorgehen da schlussendlich zu vergleichen mit dem jetzt zum beispiel von deiner app? Oder war das anders, weil es ein Arbeitsprojekt war?

25:28 B: also bei meiner app bin ich jetzt selbst noch nicht auf harte bugs gestoßen oder harte fehler oder harte blockaden. weil es da halt so viele baustellen gibt, dass ich, wenn ich mir denke, hey, hier ist grad ein fehler oder eine blockade, dann denke ich mir halt an der stelle okay, dann machst du an einer anderen stelle kurz weiter, weil irgendwann findet sich die motivation schon wieder, an der stelle mehr zu lesen. weil wenn ich jetzt keine ahnung, eine woche lang nur am json web token sitze, warum auch immer, und mir dann denke, hey, ich hab jetzt hier einen fehler, dann brauche ich ab und zu einfach ein bisschen abstand, um da wieder mehr motivation dafür zu bekommen.  

26:06 I: okay, aber beim eeg hätte das nicht geklappt?  

26:12 B: hätte aufgrund der natur des softwareprodukts nicht funktioniert, weil es dort die letzte große baustelle war, die gefehlt hat. dementsprechend saß ich da halt dran und hatte halt nicht die punkte zum hin und her springen. dementsprechend war es da dann halt aktiv irgendwie versuchen, die lösung zu finden und das nicht so passiv auf einen einrieseln zu lassen. und das aktive war halt mit den faktoren, die ich jetzt schon genannt hab.  

26:43 I: dann hast du jetzt noch gesagt, durch dieses video, was du da gesehen hast bei dem eeg, da hat sich dein bild im kopf quasi verbessert  

26:55 B: genau. das habe ich häufiger, dass ich sachen zwar manchmal lese, verstehe und denke, dass ich es verstand, aber irgendwann nochmal eine andere perspektive bekomme und dann wirklich das gefühl habe, das thema durchdringen zu können.  

27:14 I: okay, aber da geht es jetzt mehr um das thema allgemein  

27:18 B: ne, geht auch um ganz verschiedene sachen, das ist jetzt nicht nur bei diesem beispiel so, das war auch mal, wenn ich eine vorlesung als beispiel/ hier hab ich die vorlesung compilerbau eins und zwei, dachte, ja ok, alles verstanden und theoretisch niveau in der prüfung auch alles gut abgeschnitten. und später habe ich mich dann irgendwann wirklich mit compilerbau auseinandergesetzt, über ein buch, wie man das halt wirklich hands on machen würde. und dann hatte ich wirklich das gefühl hey, vieles davon kommt mir bekannt vor aus der vorlesung, aber dass ich das jetzt nochmal auf einem anderen oder auf einem besseren niveau verstehe.  

27:57 I: okay, also es ist jetzt mehr auf einer wissensebene, es ist jetzt nicht quasi auf der coding-ebene  

28:01 B: nenene, das ist nicht auf der coding-ebene, das ist eher wirklich die interne repräsentation, die ich von gewissen dingen hab  

28:16 I: gut, dann wäre der dritte teil des interviews auch vorbei, vielen dank. dann kann ich dir jetzt erzählen, worum's geht. ja du hast das stichwort selber eingeworfen mit den blockaden. weil ich hab mich ja mal vermehrt mit schreibblockaden befasst in meinem bachelor. und die idee von meiner masterarbeit ist, die theorie davon aufs programmieren zu übertragen. und zu gucken, gibt es programmierblockaden und sind die vergleichbar mit schreibblockaden. hattest du das von mir schonmal irgendwie gehört, also dass du vielleicht unbewusst dich daran erinnert hast oder so?

29:21 B: vor anderthalb jahren glaub ich bei J, zur einzugsfeier, hast du glaub ich mit N darüber geredet. vielleicht habe ich das peripher mitbekommen, aber sonst war mir das jetzt nicht bewusst  

29:33 I: okay. ich hoffe, das passt. ja, das ist so die grundidee und deswegen frage ich zu programmierprozessen undso, weil schreibblockadne hängen halt auch viel mit dem schreibprozess zusammen  

29:51 B: okay, also wenn ich jetzt meine antworten reflektiere, dann war es bei mir sehr viel, wo ich sage, das ist eher so wissen und interne repräsentation und nicht eher dieses coding-technische. ist das beim schreiben denn anders?  

30:06 I: also das ding ist/ also das ist jetzt die frage. viele blockaden können quasi auftreten beim schreiben, wenn die gestaltbildung bezogen auf den text quasi fehlschlägt. ist jetzt die frage, ob das beim coding/ also die interne repräsentation damit vergleichbar ist oder ob es sich halt wirklich eher auf diese wissensebene bezieht.

30:39 B: mhm, okay  

30:40 I: weiß nicht, was sagt dein bauchgefühl?   

30:44 B: es ist nicht reine wissens-ebene, es ist auch dann schon/ mit interner repräsentation, ich weiß jetzt nicht, was gestaltbildung genau aussagt im schreibprozess, aber es geht dann halt auch so ein bisschen darum, denke ich, WIE strukturiert man den code. weil wenn ich mir jetzt denke, man kann ihn ja auch nicht komplett unstrukturieren. man kann ja nicht sagen, ich suche zuerst in dem feld und danach sortiere ich es. andersrum macht es natürlich mehr sinn. das kann man jetzt vielleicht auf wissenseben, sagen, dass man halt sagt, hey, sortieren macht als erstes sinn, wenn ich was suchen möchte oder wenn ich mehrfach suchen möchte. beziehungsweise kann das auch als interne abfolge von schritten sein, die/ also wenn ich ganz häufig über algorithmen nachdenke, dann denke ich schon in so einer art pseudocode nach, ganz häufig. wenn ich jetzt sage, hey, ich möchte ein element finden, dann denke ich schon so, sortieren, halbieren, suchen. so nach dem motto. und wenn ich jetzt binäre suche mit einem sortier-algorithmus verknüpfen möchte. ähnlich bei einem dijkstra oder so, wenn man da mal einen komplexeren algorithmus nehmen möchte. dann weiß ich natürlich, wie er funktioniert, aber ich muss das auch irgendwie umsetzen. und da geht's dann bei mir schon darum, welche schritte kommen wann, wie, warum und in welcher reihenfolge. wie sich das dann im code verhält, ist ja dann immer halt programmiersprache zu programmiersprache abhängig. wenn ich jetzt zum beispiel beim dijkstra bin, um das beispiel weiter aufzugreifen, und ich sage hey, ich muss irgendwie wissen, welcher knoten der nächste dran ist, so wäre das halt in meinem kopf. dann kann ich das ja auf coding-ebene auf verschiedene weise machen.32:25 das kann ich ja einerseits mit ner priority-queue machen. an der stelle mit meiner internen repräsentation würde ich da noch nicht so drüber nachdenken, ob das mit ner priority-queue ist oder einfach mit ner liste, die ich immer wieder sortiere. das ist dann ne sache, die hängt dann davon ab, wie die programmiersprache das tatsächlich unterstützt. wenn ich jetzt sage, hey, ich hab jetzt, keine ahnung, ne programmiersprache, die priority-queues direkt unterstützt und es ist einfach convenient, die zu benutzen, dann nutze ich die auf jeden fall. wenn ich jetzt aber sage, hey, keine ahnung, es gibt die skiptsprache von godot, das ist ne game-engine, und da brauchte ich auch eine prioritäts-warteschlange, hatte sie aber nicht, und es war in ner (?), wo es recht schnell gehen sollte, da habe ich dann halt gesagt, hey, okay, dann nutze halt ne liste, die du jedes mal sortierst. ist laufzeittechnisch absolut schrecklich, aber funktioniert vollkommen gleich vom verhalten her  

33:20 I: aber du musst oder willst dir vorher den algorithmus dir vorher schon im kopf irgendwie vorstellen? also du brauchst da ein bild von?  

33:27 B: genau. also das ich nicht einfach drauflos code und zeile für zeile denke, was passiert, das kann auch ab und zu mal sein, aber meistens ist es ja so, dass ich vorher so schon ne schrittabfolge brauche oder mir gedanken machen muss, wie die schrittabfolge sein könnte. es ist jetzt wenn wir auf die programmier-paradigmen eingehen, bei funktionalen nicht so der stil, aber das programmier ich auch nicht jeden tag, sagen wir es mal. bei den klassischen funktionalen programmiersprachen wie haskell ist die ausführungsreihenfolge ja tatsächlich komplett egal. das heißt da kann zeile 3 vor zeile 1 ausgeführt werden. das ist nochmal ein bisschen anders aber meistens programmiert man ja sequentiell oder objekt-orientiert und nur mit einem funktionalen STIL sage ich mal und da ist es halt schon so, dass man, oder dass ich mir schritt für schritt im kopf überlege, wie muss ich was machen. zum beispiel bei dem sortieren weiß ich so ganz grob, ja, sortieren funktioniert schon irgendwie, und mach mir da keine gedanken drum, wie das in der sprache tatsächlich ausgelöst wird. ob das jetzt mit nem .sort() in java ist oder sort und dann den container in die funktion übergeben in python, dann ist es mir auch tatsächlich ziemlich egal, was für ein sortieralgorithmus meistens dahinter ist. es sei denn, ich (?) jetzt in einer programmiersprache, die keinen sortieralgorithmus schön implementiert, wo man jetzt nicht ganz viel umwege nehmen muss, wie c oder sowas.  

35:00 I: und wie verknüpft sich das, diese vorstellung im kopf von der groben struktur, sich das zu machen, wie verknüpft sich das mit dem, was du beschrieben hast am anfang, also dass du halt vom einen punkt zum anderen springt beim programmieren, also was halt grade sich ergibt aus dem, woran du arbeitest?  

35:25 B: da ist es dann halt so nach dem motto wie, wenn ich jetzt mal gucken möchte, ich greif mal das beispiel wieder auf von dem json web token. da muss ich halt auch irgendwie vom ablauf wissen, hey, ich bekomme ne anfrage, ich verarbeite die anfrage, ich geb irgendein cookie zurück. das kann ich grob schonmal implementieren so. das ist ja schonmal so ein grobes top-down verständnis, wo ich sagen kann, hey, ich krieg die anfrage irgendwie, dann habe ich irgendwie ne funktion, die heißt processing oder wie auch immer. und was dann da im detail alles passiert, kann ich ja auch stück für stück dann wieder in dieser funktion klären. das heißt, entschlüsseln, gucken, wann das abgelaufen ist, gucken ob der die rechte hat und so weiter und so fort, das geht ja alles sequentiell. und wenn ich dann denke irgendwann, da fehlt noch ein schritt, dann kann ich den in dieses sequentielle wieder rein. aber wenn ich irgendwann so einen sequentiellen algorithmus hab, so en funktion, die das irgendwie prüft, die gibt's ja an verschiedenen stellen. die gibt's ja jetzt einerseits im authentifizierungs-backend, die gibt's aber auch andererseits dann im daten/ in nem anderen backend, wo es halt nur darum geht, dokumente abzulegen. da geht es dann ja auch darum, dass man sagt, hey, ich bekomm das dokument, ich speicher das mal irgendwie ab, oder ich les irgendwie sachen aus, und ich send irgendwas zurück. das heißt so gewisse/ switche ich dann halt intern, denke ich, rum, zwischen diesen einzelnen domänen. dass ich sage hey, da gibt's dieses sequentielle problem, da gibt's dieses sequentielle problem. und die bearbeite ich dann so als kleine module.