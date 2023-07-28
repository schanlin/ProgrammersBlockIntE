00:21 I: wie alt bist du?  

00:23 B: 25  

00:28 I: wie viele jahre programmierst du insgesamt? also auch hobbymäßig, alles  

00:31 B: sechs, sieben jahre ungefähr  

00:42 I: wie viele jahre davon in ausbildung, also uni oder berufsausbildung?  

00:49 B: die sieben jahre (lacht)  

00:54 I: welche art von ausbildung?  

01:00 B: beides  

01:11 I: seit wie vielen jahren programmierst du für größere softwareprojekte, zum beispiel in einer firma?  

01:20 B: zweieinhalb  

01:25 I: wie groß sind diese professionellen projekte üblicherweise? wir unterscheiden da in klein, mittel und groß, klein ist unter 900 codezeilen, mittel ist zwischen 900 und 40'000 codezeilen, groß ist über 40'000 codezeilen  

01:46 B: (lacht) irgendjemand hatte das letztens noch gesagt, wie viele codezeilen wir im projekt haben. das waren schon einige. ich glaube, ich würde grade so sagen mittel. aber es wird ja neu gemacht, also weiß ich gerade nicht genau, wie viele das sind  

02:05 I: auf einer skala von 1 bis 10, also 1 entspricht sehr unerfahren, 10 entspricht sehr erfahren, wie hoch schätzt du deine eigne programmiererfahrung ein?  

02:17 B: ne solide fünf? vier? das ist schwer zu sagen

02:31 I: ja du kannst das begründen oder auch nicht, wie du willst. einfach bauchgefühl ist auch fine

02:36 B: ja, die basis ist ja sozusagen da, ne, würde ich schon sagen. fünf, ja.  

02:46 I: auf einer skala von eins bis fünf, wie hoch schätzt du deine programmiererfahrung im vergleich mit experten mit 20 jahren praktischer erfahrung ein?  

03:01 B: puh, ne eins? obwohl, also wenn ich das manchmal sehe, denke ich schon fast ne zwei. je nachdem, kommt draufan, wer das halt macht

03:19 I: auf einer skala von 1 bis 5, wie hoch schätzt du deine programmiererfahrung im vergleich mit deinen kollegen ein? oder mit leuten, die ähnliches machen, wie du  

03:37 B: die in meiner firma? die sind auch noch alle sehr jung. deswegen würde ich sagen ne drei  

03:51 I: wie viele programmiersprachen kennst du, bei denen du deine programmiererfahrung bei drei oder höher einschätzen würdest?  

04:08 B: zwei bis drei  

04:11 I: welche sind das?  

04:14 B: golang, javascript und java. * aber auch nur weil das in der schule und der uni die ganze zeit gelernt wird

05:05 I: auch wieder auf einer skala von 1 bis 5, wie erfahren bist du mit den folgenden programmierparadigmen? erstens funktionale programmierung * haskell und sowas ist das  

05:15 B: nicht so. also ne 1  

05:46 I: imperative programmierung? sagt dir das was?  

05:51 B: nein  

05:52 I: das ist C  

05:54 B: C? ja, so ein bisschen.   

06:01 I: also so eine 2?   

06:02 B: ja  

06:08 I: logische programmierung? falls du davon schonmal gehört hast  

06:14 B: (tippen) nein  

06:20 I: und objekt-orientierte programmierung?  

06:22 B: ja, das wird einem die ganze zeit beigebracht, das kann ich schon.  

06:38 I: und bei welcher zahl würdet du es so schätzen, 1 bis 5?  

06:43 B: 3, 4, so um den dreh  

06:47 I: sagen wir mal/ wir runden mal auf, 4  

06:49 B: das wird einem die ganze zeit eingetrichtert, ja  

07:16 I: nächster teil sind fragen zu deinem programmierprozess, also wie du da so rangehst. und zwar würde ich das gern machen, indem ich dich gern bitten würde, mir als erstes was über ein einigermaßen aktuelles projekt, also kann kürzlich abgeschlossen oder noch in arbeit sein, privat oder von der arbeit, wie du willst/ mir einfach mal darüber so ein bisschen zu erzählen. kontext, was ist das, was machst du da, wie gehst du dabei vor  

07:50 B: wie ich dabei vorgehe?  

07:50 I: erstmal einfach anfangen erzählen, was du erzählen willst und dann kann ich fragen  

07:55 B: okay, also. wir bieten eine monitoring-software an. und die wurde/ also es gibt momentan die version 3, und die wollten wir eigentlich weiterentwickeln und hat sich halt dazu entschieden, die komplett nochmal neu zu entwickeln, mit anderen programmiersprachen, alles anders, alles auf neu. das läuft halt momentan seit drei jahren, dreieinhalb jahren.

08:29 I: okay?  

08:29 B: das ist halt das große projekt, in dem ich drinstecke. * und dann gibt es halt so größere blöcke, was jetzt das nächste ziel ist, und daraus kommen dann halt die ganzen tickets und anforderungen undso. und dann wird halt gesagt "mach das mal". so im groben.  

09:07 I: also du bekommst dann so ein ticket zugeteilt und machst dann mal, okay. was machst du da?  

09:09 B: nicht unbedingt zugeteilt, man nimmt sich natürlich auch welche, aber ja. was ich dann mache? kommt darauf an, was für ein ticket das natürlich ist, ne. ob das ein bug ist, dann (?) muss ich natürlich erstmal nachstellen, was da passiert. und dann werden ganz viele logs erstmal reingehauen, bis man rausfindet, wo das problem liegt. und dann versucht man das ganze zu fixen. und wenn ich jetzt n feature habe *09:52  je nachdem, da unsere objekte immer gleich aussehen, ist dieser teil immer ziemlich einfach. da hat man halt seine felder, die dieses objekt hat, und die funktionen sind halt meistens immer gleich und dann ist das eigentlich immer einfach. und dann kommt halt die logik, tja und dann ist halt/ ich denk mir halt meinen teil im kopf, wie das aussehen könnte und dann probier ich das halt aus. und dann programmier das, wie ich das denke, wie es auszusehen hätte * von der logik her. ja und teste dann halt die ganze zeit nebenbei. über/ wir schicken halt die ganze zeit abfragen an den server, an die endpunkte. und gucken halt, ob das passt, und guck ich halt, ob das passiert, was passieren sollte. und auch auf die weise, wie es passieren sollte. das ist mein grober ablauf, würde ich sagen.

10:57 I: gut, dann gehen wir nochmal von vorne. also du kriegst das ticket und du musst ja erstmal rausfinden, was das für ein ticket ist. was gibt es da zu tun, also was musst du da alles beachten?  

11:15 B: was ich da beachten muss?  

11:16 I: ja, oder * du kriegst das ticket, was machst du dann?  

11:26 B: ich lese mir das ticket durch. je nachdem sind da halt anforderungen drin, oder fehlermeldungen oder halt sonstige sachen, die beachtet werden müssen  

11:42 I: und je nachdem, was da drin steht, also es gibt unterschiedliche sachen, ist dann auch dein vorgehen anders?  

11:50 B: ja. wenn ich schon weiß, wo das problem, oder wo irgendwas fehlt, ist, ist es natürlich/ oder wenn da schon code ist, der nur überarbeitet werden muss, ist es natürlich einfacher da hinzukommen und nur so ein bisschen diese logik umzudenken anstatt sich was ganz neues zu erfinden, zu erdenken, wie das aussehen soll, als wenn es das halt schon gibt und nur etwas falsch ist  

12:32 I: und dann hast du gesagt, wenn du an der logik was machen musst, dann denkst du dir deinen teil im kopf. ist das sowohl bei bugfixes, also wenn du nur überarbeiten musst und wenn du code von vorn schreiben musst, ist das gleich? also machst du das auch im kopf?  

12:54 B: meistens ja. manchmal, wenn es wirklich komplizierter ist, mit so fällen so, wenn das, dann das, wenn das, dann das, wenn das, dann das und dann kommt das und das, dann mal man sich halt schon mal so ein bisschen so STIEFmütterlich so auf, dann das und dann das und dann sollte das passierten. kommt halt immer draufan, wie komplex das thema ist  

13:23 I: okay, je komplexer, desto eher greifst du zu irgendeinem planungstool  

13:29 B: ja  

13:31 I: wenn du das im kopf machst, kannst du so einigermaßen rekonstruieren, wie das so/ was du dir so denkst?  

13:50 B: was ich mir dabei so denke * erstmal natürlich "wer hat das denn angestellt" je nachdem (lacht). Ne, was ich mir dabei denke * halt meistens so/ erstmal so grob halt, wie das aussehen soll, oder wie es passieren könnte. da spiel ich halt so manchmal die szenarien halt so durch, wie dann sollte das passieren, dann müsste dann da das stehen und dann müsste das passieren, dazu müsste ich dann so ne funktion haben und so weiter. so halt wie dieser generell ablauf halt irgendwie laufen sollte.  

14:57 I: gut und dann beim übertragen in code, also läuft das dann relativ flüssig, so quasi du denkst//  

15:12 B: ich denke und ich schreibs auf, ja. weil da würd ichs sonst wieder verlieren  

15:22 I: also das kommt vor, dass du das wieder verlierst?  

15:23 B: ja wenn man halt so am späten nachmittag darüber nachdenkt, was man am nächsten tag denn noch machen soll, wenn man sich's nicht aufschreibt, kann man das mal/ halt man kriegt's wieder, aber man kann's halt ein bisschen verlieren, oder halt bruchstücke davon verlieren  

15:49 I: und läuft das in der regel relativ flüssig oder sitzt du auch manchmal vor dem code und weißt jetzt nicht, was du schreiben sollst?  

15:54 B: kommt vor, ja. je nachdem, wie viel logik gefragt ist. wenn es halt irgendwas komplexes ist und man halt viel gehirnschmalz reinstecken muss, dann muss man da halt auch mal ziemlich lange vor undso. das beste beispiel war, es ist halt nicht viel code insgesamt gewesen, das kann man auf einer seite, also einem bildschirm darstellen. ich und ein kollege saßen da zwei bis drei wochen dran, weil es halt einfach das gehirn schon krass gefordert hat, bis wir da auf eine vernünftige lösung und eine zufriedenstellende lösung gekommen sind. und da für das ergebnis sieht man halt nicht viel. aber es muss dann funktionieren. da war halt auch viel mit rumprobieren und an die tafel halt irgendwie malen, an so'n whiteboard, irgendwo so muss das aussehen und dann hat man's getestet und dann war's doch nicht wie man sich es gedacht hat und so weiter und so fort.

17:18 I: aber du würdest sagen es ist relativ viel rumprobieren involviert?  

17:24 B: ja. eigentlich immer. man schreibt irgendwo immer logs hin, was passiert, was ausgegeben werden sollte und so weiter  

17:37 I: und wenn du da mal nicht weiter weißt, dann hilft da auch einfach was ausprobieren?  

17:46 B: ja. dann schreibt man halt auch mal auch irgendwas da hin, was man denkt, was (?nicht) passieren/ funktionieren sollte und es funktioniert auch irgendwie trotzdem und das kann auch schon weiterhelfen  

18:14 I: wenn du am programmieren bist, oder an einem projekt arbeitest, hast du da wen im kopf, für den du das programmierst, also entweder kunden oder der nächste mitarbeiter, der's kriegen muss, hast du da irgendwie/ für wen programmierst du das?  

B: für wen ich das programmiere?  

I: oder für wen du den code schreibst  

18:36 B: für den kunden halt. da das momentan noch nicht wirklich draußen ist, kann man sich da halt/ gibt es halt noch nicht viele leute, die das benutzen. Dann ist das halt eher ein "ich denke, die kunden würden das so wollen" ding. nicht so ein "der kunde will das so" sondern kunden könnten das so haben wollen. und dann bespricht man sich halt auch so mit den anderen leuten, wie die das sehen, ob das dem kunden so gefallen könnte oder nicht.  

19:19 I: und das macht es schwerer? also, nicht zu wissen, was der kunde potentiell will oder ist das halt so?  

19:27 B: ja das kommt so/ im frontend ist das halt schwer. sich zu überlegen, ist das so richtig, ist dieser button da wirklich an der richtigen stelle, macht dieser workflow so sinn.  

20:03 I: also was du jetzt so beschrieben hast, die prozesse, ist das der übliche prozess bei deinen projekten?  

20:17 B: es ist halt eigentlich auch mein einziges projekt. also ich halt am anfang so ein bisschen/ halt am anfang der ausbildung so ein bisschen was selber gemacht, (?aber das war) für die anfänge, da weiß man ja noch nicht so was. aber momentan schon, ja.

20:36 I: man kann ja auch sagen, man kann jedes einzelne ticket, was du bearbeitest, quasi als kleines projekt sehen  

20:42 B: ja könnte man, aber ich seh das so nicht. weil's halt immer etwas von etwas größerem ist. außer es ist halt ein großer unterpunkt von irgendwas, aber wenn's halt nur ein kleines ticket ist, dann eher nicht

21:03 I: was sind die unterschiede zwischen großen und kleinen tickets für dich? also abgesehen vom aufwand  

21:15 B: gibt es irgendwas anderes als den aufwand? (lacht) es ist halt/ hat auch viel mit der planung zu tun, wie viel man dafür geplant hat (?oder) wie viel man dafür planen muss. darauf kommt es halt auch immer an.  

21:43 I: und beim planen reden wir jetzt wieder hauptsächlich vom planen im kopf?  

21:52 B: ne? die größeren sachen bei uns werden halt erstmal im team besprochen. welche anforderungen wir haben. was es dann können soll. das umsetzen, das muss man halt selber/ das plan ICH selber im kopf. aber halt wie's aussehen soll und was passieren soll und wir für neue objekte oder so brauchen, das wird meistens, wenn's was größeres ist, vorher wirklich geplant und aufgeschrieben, damit man nicht sagen kann "ne, das aber aber so nicht besprochen" "doch, doch"

22:55 I: gut, das war der zweite teil. beim dritten teil geht es jetzt um probleme, die auftreten können. erste frage/ für den sinn und zweck der frage sehen wir jetzt projekt mal nicht als das ganze/ also nicht als die ganze software sondern als entweder teile davon oder du kannst über private sachen, die du geschrieben hast, reden. hast du schonmal etwas abgebrochen? oder an wen anders weitergegeben und selber nicht mehr weitergemacht oder so?

23:39 B: weitergegeben glaube ich nicht. kann ich mich jetzt nicht so daran erinnern. ich glaub, abgebrochen schon. weil da haben wir uns halt beraten und dann ging's halt irgendwann so, ja es glaube ich macht keinen sinn mehr, das zu machen oder so. oder es macht keinen sinn, noch weiter darin zu/ zeit zu investieren, weil die zeit halt anders sinnvoller genutzt werden kann. oder es wird dann halt zurückgestellt erstmal. das passiert schon mal.

24:23 I: wann macht es denn zum beispiel keinen sinn mehr/ also wie kommt man an diesen punkt?  

24:36 B: wenn es zum beispiel irgendein kleines projekt ist, was mit ein bis zwei tagen eigentlich nur eingeplant war, aber sich daraus halt viel mehr entwickelt, als man angenommen hat. dann wird halt schonmal gesagt, das lassen wir erstmal so, das müssen wir nochmal neu einplanen, überdenken, und so weiter  

25:16 I: wie macht man denn normalerweise die zeitliche planung? wie schätzt du ein, wie lange du für etwas brauchst?  

25:26 B: wie ich das einschätze? also zeiten schätzen wir meistens gemeinsam im team. und dann wird halt meistens/ ungefähr sind wir halt gleich und dann denkt man sich halt so, ich muss da nur einen kleinen button einbauen, dafür brauche ich ne stunde, wenn überhaupt, oder/ das sind halt die einfachen sachen. aber wenn man etwas neues machen muss, dann muss man/ man beruft sich halt auf seine vorherigen erfahrungen so ungefähr. ich hab für das so und solange gebraucht und das dürfte im aufwand ungefähr dasselbe sein wie das jetzt, dann müsste das auch ungefähr so lange dauern.

26:18 I: und wie kommt's dann dazu, dass man sich verschätzt? also, was verzögert die projekte, wenn das vorkommt?  

26:28 B: sachen, die man nicht bedacht hat. sachen, die/ wo man geplant hat, es könnte so aussehen, und im nachhinein merkt man halt, dass es halt doch nicht so aussehen muss, weil es doch eigentlich komplett nicht dem entspricht, was man sich dabei gedacht hat. oder halt sachen auftreten, die, wenn man halt an etwas sitzt, es bearbeitet und dann dadurch sachen wieder auftreten, von denen man vorher nicht wusste, dass die dadurch dann auftreten, wenn man etwas verändert  

27:16 I: lustige seiteneffekte zum beispiel?  

27:18 B: genau  

27:23 I: gibt es da irgendein beispiel, von dem du erzählen kannst?  

27:33 B: also meine kollegen sprechen immer wieder gerne über die vorherige version der software. da habe ich nie dran gearbeitet und ich weiß auch nicht, wie der code aussieht, aber da gibt's halt so sachen so * ja * das fassen wir lieber nicht an, es funktioniert grade so. wenn wir das machen würden, dann wüssten wir nicht, was danach passiert. das gibt's da anscheinend noch sehr viel. und dann haben die wohl schon an einigen sachen gearbeitet und dann, tja, fällt einem dann auf, das funktioniert so nicht, weil wir daran irgendwas anderes wieder verändern müssten  

28:33 I: habt ihr deadlines, außer die geschätzten, wie lange was dauert?  

28:41 B: ja, schon  

28:41 I: ist es schonmal passiert, dass ihr eine nicht einhalten konntet?  

28:45 B: ja, das auch.  

28:48 I: warum?  

28:50 B: warum. tja. es hat halt einfach ein bisschen länger gedauert als angenommen. es war halt ziemlich straff geplant. eigentlich mit dem/ so wir programmieren das so, dass es beim ersten mal funktioniert, wenn etwas fehlschlägt * ja. war dann halt ein bisschen zu wenig zeit.  

29:18 I: okay. also keine fehlschläge einzuplanen ist nicht optimal  

29:22 B: kann man so sagen, ja  

30:09 I: gab's momente, wo du bei einem projekt einfach nicht voran gekommen bist, obwohl du nicht durch irgendwelche äußeren umstände, keine ahnung internet kaputt, gehindert wurdest?  

30:24 B: ja  

30:27 I: okay? wie sehen die aus?  

30:32 B: dass ich nicht weiterkomme an einem projekt?  

30:35 I: ja genau

30:50 B: (denkt nach) wenn man sich so denkt, wie man halt irgendwas macht und dann halt an einen punkt kommt, wo man denkt, dass dann so zu machen und dann muss man das wieder umdenken und dann wieder umdenken und dann wieder neu versuchen und wieder neu versuchen, da kommt man halt nicht vorwärts  

31:12 I: und wie/ also dann machst du's einfach, bis irgendwas funktioniert oder wie durchbrichst du das?  

31:27 B: schon, ja. vielleicht muss man sich da ein bisschen mal kurz mit was anderem beschäftigen, das hilft auch sehr häufig. bis man vielleicht mal irgendwann einen geistesblitz hat. vielleicht auch mal nachts kurz vorm schlafen (lacht). hatte ich auch schon. dass man dann so denkt "ach das könnte ich morgen auch mal so probieren"  

31:57 I: weißt du's dann am morgen noch?  

31:59 B: meistens ja  

32:09 I: gibt es da für dich nen unterschied beim code verstehen und beim code produzieren? also, kannst du bei beidem hängenbleiben?

32:31 B: bestimmt. kommt auf den code draufan, wie einfach der zu verstehen ist und wie der geschrieben ist, wenn er nicht von mir selber geschrieben wurde. wobei sogar da ist man bestimmt, wenn man sich nach nem jahr was anguckt, was man gemacht hat, das erstmal wieder zu verstehen (lacht). kommt halt auf die qualität das codes auch draufan.  

33:11 I: denkst du, du hattest schonmal sowas wie eine programmierblockade? analog zum beispiel zu einer schreibblockade  

33:29 B: eine programmierblockade? das würde ich nicht sagen. man versucht halt die ganze zeit trotzdem was zu machen. ob's sinnvoll ist, ist dann halt die andere frage. ob es zielführend ist. aber, nicht wissen, was ich zu schreiben/ was ich programmieren möchte, ja, irgendwie versuchen kann man es meistens immer  

34:01 I: möchtest du an der stelle noch irgendwas hinzufügen?  

34:15 B: ich glaube nicht