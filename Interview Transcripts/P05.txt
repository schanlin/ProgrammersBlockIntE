00:06 I: der erste teil des interviews ist einfach ein fragebogen zu deiner programmiererfahrung. erste frage ist, wie alt bist du?  

00:14 B: 28  

00:16 I: wie viele jahre programmierst du insgesamt schon?  

00:22 B: 14  

00:29 I: wie viele davon in irgendeiner förmlichen ausbildung?  

00:35 B: mit 16 jahren bin ich in die ausbildung gegangen, also 12 jahre, würde ich jetzt sagen  

00:40 I: ich glaube, die frage bezieht sich nur darauf, wie viele davon in ausbildung waren  

00:45 B: achso, davon waren's dann 3  

00:51 I: war ne berufsausbildung?  

00:53 B: das war ne berufsausbildung, genau  

00:58 I: seit wie vielen jahren programmierst du für größere software-projekte, also zum beispiel in einer firma?  

01:07 B: seit 12 jahren, also in der ausbildung halt dran gearbeitet mit an den projekten dort. und da auchs erste mal open source code beigesteuert (?und damit) an größeren projekten, also ja, 12 jahre  

01:23 I: wie groß sind deine professionellen projekte üblicherweise? also wir haben klein, mittel, groß die unterscheidung. klein ist unter 900 codezeilen, mittel ist 900 bis 40'000 und groß wäre über 40'000 codezeilen  

01:38 B: jetzt hier in dem aktuellen job sind's vermutlich alles eher mittlere projekte an denen ich hauptsächlich arbeite, aber es ist auch ab und zu mal ein großes projekt dabei. im job vorher waren es auf jeden fall auch große projekte und davor auch. und in meiner freizeit kommen auch einige große projekte zusammen  

02:03 I: ich schreib mal mittel bis groß auf, das wird schon passen. okay. auf einer skala von 1 bis 10, also 1 sehr unerfahren und 10 sehr erfahren, wie hoch schätzt du deine eigene Programmiererfahrung ein?

02:19 B: 8 bis 9  

02:25 I: 9, okay. auf einer skala von 1 bis 5 nur, wie hoch schätzt du deine programmiererfahrung im vergleich mit experten mit, ja, 20 jahren praktischer erfahrung, oder sagen wir mal 20 jahre mehr als du, als deine eigene, ein?  

02:46 B: das hängt jetzt sehr von den experten ab. ich sag mal 4  

02:51 I: auf einer skala von 1 bis 5, wie hoch schätzt du deine programmiererfahrung im vergleich mit deinen kollegen ein? beziehungsweise, leute, die ähnliches machen wie du, falls du keine kollegen direkt hast?  

03:05 B: wäre dabei 3 genauso gut?  

03:09 I: joah  

03:16 B: ja, dann ist es glaube auch ne 4  

03:25 I: wie viele programmiersprachen kennst du//  

03:31 B: (lacht)  

03:31 I: (lacht mit) okay, warum ist das lustig?  

03:34 B: weil ich wusste, dass irgendsoeine frage kommt. und ich schon angefangen habe, nochmal durchzuzählen, weil ich immer welche vergesse. stell die frage erstmal fertig.  

03:40 I: okay, ich stell sie andersrum. welche programmiersprachen kennst du, wo du deine erfahrung bei 3 oder höher einschätzen würdest?  

03:49 B: auf skala bis 5?  

03:54 I: auf skala bis 5, ja genau

03:54 B: okay c, c++, perl, javascript, typescript, java, scala, python, php, assembler in verschiedenen dialekten. aber ja, das sind glaube tatsächlich die mit 3 oder höher. das ist eine gute einschränkung.  

04:46 I: 10 zähle ich jetzt  

04:51 B: das klingt plausibel  

04:52 I: ja vermutlich fällt das eh alles unter VIELE.  

04:58 B: ja. das meinte ich mit, ich könnte an manchen stellen ein bisschen der ausreißer sein.  

05:05 I: dann haben wir noch die letzten fragen. wie erfahren, auf ner skala von 1 wieder bis 5, bist du mit den folgenden programmierparadigmen? das erste, funktionale programmierung?  

05:23 B: das konzept selber oder paradigma selber/ auch wieder skala bis 5?  

05:31 I: ja, genau  

05:32 B: dann ne 3  

05:36 I: imperative programmierung?  

05:38 B: 5  

05:41 I: logische programmierung?  

05:42 B: okay, hab ich unter dem begriff jetzt noch nichts grade verknüpft  

05:49 I: prolog ist wohl so die standardsprache  

05:51 B: ah okay. ne dann muss ich das mit 0 beantworten. ah ne, 1 bis 5\. 1? keine ahnung  

06:00 I: und objekt-orientiert?  

06:01 B: ja, 5  

06:41 I: dann kommen wir zum zweiten teil. da geht es um deinen persönlichen programmierprozess. und zwar wollte ich dich dazu gern bitten, mir einfach was über ein aktuelles programmier-projekt von dir zu erzählen. von der arbeit oder privat, je nachdem, worüber du reden kannst und willst. kann abgeschlossen sein, kann sich noch in arbeit befinden, irgendwas, wo du gerne drüber reden würdest.  

07:06 B: okay, irgendwelche punkte, die dir da besonders wichtig sind?  

07:10 I: nö, also, kannst mir einfach kurz erklären, damit es ein bisschen eingeordnet werden kann, worum's geht und wie du dabei vorgehst  

07:22 B: okay. dann nehme ich jetzt mal ein projekt oder ein ticket, was ich vor kurzem auf arbeit hatte. da ging es darum in einer bestehenden software in neues feature einzubauen. konkret, die software provisioniert virtuelle maschinen bei uns und die kennt bisher die größe einer festplatte, die dabei provisioniert werden soll und das neue feature, was dazukommen sollte, ist, dass es auch/ dass man eine performance-klasse angeben kann. also wir bieten halt/ die virtuellen festplatten bieten performanceklassen an, verschiedene geschwindigkeiten undso. und dass man das halt mit angeben kann, war das neue geplante feature.08:04 einfachste wäre dann an der stelle gewesen, einfach das neue attribut der konfig hinzufügen 'performance-klasse'. aber ich wusste, dass an der stelle auch noch ein anderes feature geplant ist, was noch nicht dringend genug ist, wo man dann mehrere platten angeben kann, also habe ich die/ das komplette konfig-format an dieser stelle ein bisschen umgebaut und hab halt jetzt ein array von festplatten, wo man zu jedem dann die größe und performance-klasse angeben kann. 08:36 und zuerst habe ich halt die relevanten stellen im code dafür rausgesucht. nochmal die richtigen stellen in unserer rest-api zusammengesucht dafür. meinen neuen code geschrieben oder die neuen konfig-optionen halt eingefügt an der richtigen stelle. dann das parsing für diese konfiguration eingebaut und dabei dann auch test geschrieben, damit es auch mit der alten option, die weiter vorhanden sein musste, immer noch funktioniert. dass es auch die richten fehler wirft, wenn das alte und neue gesetzt ist und so weiter. genau und als die tests funktioniert haben, dann noch rund rum noch ein bisschen was geschrieben, doku geschrieben. wobei die allermeiste doku direkt an den attributen dran war und daraus zum glück dann die doku generiert wird letztlich, die kundendoku. und ja. insgesamt sind es drei git-commits geworden. und wurde dann halt nen pull-request gegen ein open source projekt, wo halt der code von uns mit drin ist. insgesamt waren das anderthalb tage oder so. zwischendurch halt noch einige meetings gehabt. okay, allein da dran 6 stunden oder so.  

10:01 I: okay. und das ist bei der arbeit so relativ üblich dein vorgehen?  

10:06 B: wenn das so kleinere dinge sind ist es immer ziemlich genau so in der richtung. bei größeren änderungen ist es dann öfter ein bisschen anders. dann splitte ich das halt in teilbereiche auf, wo dann halt auch mehrere commits entstehen, die halt immer nen teilbereich machen, wo ich dann auch schon jemanden drüberschauen lassen kann. da sind auch öfter noch mehr absprachen drin, weil dann mehr komponenten miteinander interagieren und wenn ich was in einer komponente anpasse, muss auch auch jemand anderes in einer anderen anpassen. das macht das dann halt sehr viel komplizierter, länger. aber prinzipiell läuft es darauf hinaus, irgendwo code dazu, tests dazu, joah. und jemanden reviewen lassen.  

11:00 I: wenn wir jetzt ein bisschen mehr in die teilprozesse reingucken, beim code schreiben, kannst du da dein vorgehen beschreiben? also machst du dir da erst irgendwie nen plan, denkst du dir das im kopf?

11:23 B: meistens mache ich mir den plan halt schon, während ich das ticket ausarbeite, an dem ich halt meistens mit mit beteiligt. und ich krieg halt die tickets auch immer erst zugewiesen, wenn ich halt schon weiß, wie ich das dann machen würde. also, der ganz grobe plan, wie ist das zu machen, steht schon an der stelle, wo ich damit anfange, es umzusetzen. womit's dann halt unterm strich halt bei der umsetzung wirklich nur noch das reine, okay, ich muss an der stelle ein bisschen code hinschreiben, ich muss dort ein bisschen code schreiben, mehr ist es dann halt schon nicht mehr. um auf diesen plan erstmal zu kommen, ist es halt ziemlich viel code lesen, eventuell die autoren des ursprünglichen codes fragen. wobei das in letzter zeit eher selten möglich war, weil irgendwie sind die alle weg (lacht). ich weiß grad nicht, was ich da noch mehr erzählen kann  

12:24 I: ist okay, wenn du nicht weißt, dann war das alles, dann ist das okay. also du sagst viel code lesen und daraus entsteht dann die vorstellung, wie der neue code aussehen muss  

12:43 B: ja. für die meisten änderungen  

12:46 I: was sind die ausnahmen?  

12:49 B: kann ich von einem anderen erzählen?  

12:51 I: ja klar  

12:53 B: gab halt nen ticket, da ging's eigentlich darum, auch wieder über unsere rest-api nen bestimtmes feld an nem objekt zu setzen. die halt ursprünglich von diesem code wurden diese ganzen objekte angelegt und es musste jetzt noch ein feld gesetzt werden. das wurde halt in dem ursprünglichen vergessen. und urspünglich hat das jemand anderes geschrieben, ich hab diesen code dann quasi geerbt und der code sah aus wie kraut und rüben. und da ist unterm strich halt ein ziemlich großes refactoring entstanden, wo dann halt sehr sehr viel neuer code entstanden ist, wo es auch vorher nicht wirklich den plan gab, wie es aussehen soll, wo es halt wirklich stück für stück entstanden ist. vorher gab es halt irgendwie sehr viel code, der fünfmal dupliziert war, nur halt einmal für das eine art objekt, dann nochmal für ne andere art objekt, dann nochmal für ne andere art objekt, aber unterm strich der gleiche code. und der neue code generiert sich halt im speicher die ganzen objekte, die entstehen sollen, und gleicht dann ab, was schon existiert und was er noch anlegen muss und was davon in abhängigkeit steht und angelegt werden muss. und da habe ich tatsächlich ziemlich lang dran gesessen, weil es halt vorher den plan noch nicht gab. der ist dann halt stück für stück entstanden. also ich hab halt zu einem teilbereich den code geschrieben, so wie ich es im kopf halt für mich sofort schlüssig war. und hab dann geschaut, wie ich das nächste stückchen, was dazu muss, wie ich das dort reinintegriert bekomme oder drübergesetzt bekomme. dadurch ist dann halt der ursprünglich geschriebene code nochmal ein paarmal umsortiert worden und von dem allerersten geschriebenen code ist auch nichts mehr übrig. ist halt sehr viel dabei umsortiert worden. aber da bin ich dann halt so schritt für schritt vorgegangen, code geschrieben, im nächsten schritt geguckt, was von dem, was ich jetzt habe, ist nutzbar, wie kann ich das umsortieren, damit es nutzbar wird. und so ist dann halt ein sehr komplexer code entstanden an der stelle.  

15:20 I: okay und wenn du jetzt vergleichst/ also das ist auf der arbeit/ wenn du privat projekte hast, gehst du da genauso vor?  

15:31 B: oft, je nach projekt, aber oft ein bisschen unsauberer. weniger commits zwischendurch, auch mal so nen unfertigen stand schon in den hauptentwicklungszweig reinpushen. aber prinzipiell so von der herangehensweise ist schon sehr ähnlich, wenn nicht sogar gleich.  

15:57 I: also du, um das nochmal zusammenzufassen, dass ichs richtig verstanden hab, also dass du an irgendeinem teilbereich anfängst und das dann nach und nach da aufbaust?  

16:08 B: ja, genau, das ist da trotzdem größtenteils so. aber auf arbeit habe ich zum beispiel immer irgendeinen git-branch, auf dem ich arbeite, auf dem ich ein neues feature baue, meine commits mache und das dann jemandem zum review gebe. und erst wenn es durchs review durch ist, kommen diese commits, die vielleicht auch nochmal umsortiert und aufgeräumt wurden, auf den hauptentwicklungszweig. und das mache ich halt privat eher selten, weil ich hab da niemanden zum reviewen und da kommt das halt immer alles direkt auf den hauptentwicklungszweig. das ist da so der unterschied. die herangehensweise ist die gleiche.  

16:50 I: also hauptsächlich in der organisation  

16:53 B: ja, das kann man so sagen  

17:01 I: wenn du an nem code von nem projekt arbeitest, für wen schreibst du den? also, hast du da beim programmieren wen im kopf? nen kunden, oder nächsten kollegen kollegin, die's bekommt?  

17:22 B: meistens schreibe ich den code so, dass ihn auch hinterher noch jemand lesen kann. also viel habe ich dabei im kopf, dass ich ihn auch in der zukunft lesen kann, weil ich in sechs monaten ist genauso gut wie irgendjemand, der den code noch nie gesehen hat. weil ich sechs monaten ist es, als hätte ich den code noch nie gesehen. und versuche deswegen immer eine struktur im code zu haben, die logisch ist, die nachvollziehbar ist. ich mache dabei nicht allzu viel über kommentare, meistens strukturiere ich den code selber so, dass er nicht viele kommentare benötigt, zumindest hoffe ich das. aber manchmal für so ganz grobe abläufe oder komplexere dinge steht dann halt auch nen großer kommentar drüber, der die ganze logik erstmal beschreibt. halt auch wieder so, dass ich das in nem halben jahr verstehen würde oder auch irgendjemand, der den code noch nie gesehen hat. kunden sehen den code eher nicht, bei dem, wo ich jetzt arbeite. bei vielem könnten sie den code sehen, vieles ist open source, aber ich glaube, das interessiert unsere kunden nicht wirklich.  

18:34 I: okay. ja ich glaube, das reicht für den teil auch schon. dann gibt es noch einen dritten und letzten teil. jetzt geht's um probleme. erste frage ist, hast du schonmal irgendwie ein programmier-projekt abgebrochen, an das du dich erinnerst?

19:01 B: ja, definitiv. lass mich ein gutes beispiel finden. weil kommt dann ja bestimmt auch die frage warum.  

19:08 I: ja, das ist die folgefrage  

19:13 B: zählt auch sowas wie abgebrochen, indem ich den job gekündigt hab?  

19:19 I: ich nehm an, dass da eher so äußere umstände dazu geführt haben?  

19:25 B: naja, jain, also das projekt war ein guter grund mit, warum ich da weg bin  

19:32 I: okay, dann bin ich neugierig, wenn du das erzählen darfst und willst  

19:48 B: es war ein ziemlich komplexes projekt. schön nach wasserfall geplant. vorher gabs halt ein angebot, das wurde dem kunden geschickt. der kunde hat nach nem dreivierteljahr gesagt, jo, ok, ich beauftrage das jetzt. da waren schon ein paar von den leuten, die während der angebotserstellung geplant waren, das umzusetzen, nicht mehr in der firma. und ich war in der zwischenzeit neu dazugekommen. und ursprünglich hieß es, dass ich/ also das ganze projekt war eine webanwendung für einen industriekunden zur planung der produktion. also interne webanwendung. urpsrünglich hieß es, dass ich dafür das frontend bauen soll. was ich auch auf grundlage der wenigen informationen, die ich hatte, gemacht habe. und mit dem frontend waren die auch soweit zufrieden. es gab ein paar dinge, die bei mir nicht richtig ankamen, weil es fehlten halt informationen. aber prinzipiell das frontend war ok. ich hab dann ne ganze weile darauf gewaret, dass halt jemand das backend schreibt, um halt auch mein frontend gegen irgendwas testen zu können, es hatte halt nur testdaten. und dann hieß es halt irgendwann, ja, wir sind alle ein bisschen swamped, magst du auch das backend schreiben? okay, ja, kann ich machen. an der stelle kam dann aber das problem, dass die nen ziemlich veralteten technologie-stack hatten. auf dem testsystem lief java 6\. und das war übrigens alles so 2018, 19\. da war java 6 schon ne weile alt. und deswegen habe ich das halt, um einfach effizienter zu sein, in scala geschrieben. das was ich an code hatte, funktionierte auch gut. im gegensatz zu dem allermeisten code dort, hatte ich dann auch eine authentifizierung und autorisierung drin, also es konnte nicht einfach jeder im netzwerk alles. und ja, was da war, war gut. problem, der kunde hatte am laufenden band ändernde anforderungen. es gibt mehrere commits in dem repo, wo ich irgendwas endlich fertig hatte und dann committed habe mit, ja, jetzt ist es endlich fertig, aber der kunde hat wohl heute im meeting gesagt, dass er es jetzt anders will. nur damit der code noch hier ist, einmal ins repo. das ist irgendwie so zwei drei mal passiert, dass ich halt zwei drei wochen arbeit versenkt habe und der kunde dann sagte, ne, eigentlich will ich das doch anders. und letztlich bin ich darüber in nen burnout gerannt und hab letzten endes die firma verlassen, weil mir vorgeworfen wurde, dass ich das projekt an die wand gefahren hätte  

22:45 I: ach schön  

22:49 B: ja. und es gibt eine entscheidung in dem projekt, die ich gemacht habe, die nicht ideal war. scala zu nehmen. weil, konnte halt nur ich. aber alle anderen probleme darin, waren management-probleme. also die leute für das projekt beim kunden, waren keine mehr von denen, die es ursprünglich haben wollten. die bei uns, die sich darum gekümmert haben, waren keine mehr von denen, die es ursprünglich mal geplant haben. die kommunikation war unter aller sau. und mir wird vorgeworfen, ich hätte es gegen die wand gefahren. kurz gesagt also aus organisatorischen gründen abgebrochen  

25:30 I: im gegensatz zu so einem beispiel jetzt, gibt es projekte, an denen du auch einfach länger gehangen hast? also einfach nicht voran, nicht weitergekommen bist an einer stelle?  

25:44 B: oh ja. privates projekt. und zwar eins, was ich schon sehr sehr lange habe. ich glaube, als ich angefangen hab, war ich 15\. zwischendurch auch mal neu angefangen, auch, weil ich einfach mehr gelernt habe und was ich hatte, war einfach rotz, wie ich dann später gelernt hab. die aktuelle version davon habe ich irgendwie 2016 oder 17 angefangen und an der schreibe ich jetzt immer noch. und zwar ist das mein eigenes betriebssystem. und ja, aktuell hänge ich da seit einer ganzen weile rum. fragen warum oder was willst du wissen?  

26:28 I: ja, warum?  

26:30 B: es ist an der stelle einfach technisch ein bisschen schwierig. ich hab probleme, mit irgendeinem code, der auf echter hardware crasht, aber im emulator weder mit noch ohne hardwarebeschleunigung, wobei halt emulator mit aktivierter beschleunigung, die sich allergrößtenteils genauso verhält, wie es auf echter hardware laufen zu lassen, aber dort funktioniert alles super. es ist halt wirklich nur auf echter hardware. und das zu debuggen ist sehr schwierig, wenn das genau in der phase des boot-prozesses ist, wo du grade schon nichts mehr von der (?firmware) hast, aber auch noch keinen (?treiber). und ja, da bin ich einfach blockiert, weil ich einfach keine idee hab, wie ich da irgendwie sinnvoll rankomme um rauszufinden, was da schief geht.  

27:24 I: okay, also einfach ein sehr schwieriger bug  

27:30 B: ne sammlung von bugs sogar. es gibt verschiedene verhaltensweisen, die (?sich hier zeigen) und die auf verschiedene bugs hinweisen. macht das ganze nicht einfacher.  

27:42 I: das kann ich mir vorstellen. irgendwelche anderen beispiele noch?  

28:14 B: ja auch in dem projekt eben, was ich ja abgebrochen hab, gab es momente, in denen ich länger gehangen hab, weil einfach die anforderungen nicht klar waren. oder es zu große brocken waren. bei den zu großen brocken ist halt, wenn dann ganz kurz geschrieben ist, mach, dass wir dieses und jenes machen können. das aber noch 20'000 weitere informationen braucht und du einfach niemanden greifen kannst, der sie dir sagt oder auch einfach nicht klar ist, welche informationen du noch brauchst. das macht es immer sehr schwer.   

28:51 I: wie würdest du in so einem fall anfangen, das runterzubrechen? also falls es möglich ist  

28:56 B: normalerweise würde ich an der stelle versuchen, irgendwie nen kunden dranzukriegen mit, hey, hier, dieser teilbereich, da müssen wir nochmal drüber reden, es ist noch nicht ganz klar, was da jetzt gemacht werden soll. aber in dem fall hatte ich halt keinen draht zum kunden und konnte das dann nur an kollegen sagen, die das dann halt irgendwie zum kunden bringen und in erfahrung bringen, die es halt aber einfach nicht gemacht haben. also ja, normalerweise, würden an dem projekt mehr kollegen von uns arbeiten, dann hätte ich kollegen gefragt. aber ich war halt alleine auf weiter flur und hätte halt nur kunden fragen können. und auch ansonsten, wenn ich blockiert bin, frage ich gern in irgendwelchen allgemeineren kommunikationskanälen dazu nach, also irgendwas privates sind es meistens irgendwelche irc channels, die irgendwie darauf spezialisiert sind. oder auf twitter, mastodon. da gibt es auch öfter mal leute, die ahnung haben, dann mein zeug lesen und ne idee haben, was ich machen kann. bei arbeitsprojekten halt kollegen. schreibe ich dann halt, wenn's irgendwas ist, was mit der sprache zu tun hat, halt in irgendeinen sprachspezifischen channel in mattermost. oder wenn's zu irgendeinem projekt ist, zieh ich mir halt irgendeinen kollegen mit, hey, ich brauch mal ne gummiente

30:40 I: okay. wir hatten's heute früh grad irgendwie/ ich hab dazu noch keine gescheite frage formuliert, also die frage klingt jetzt doof. es kam quasi die frage auf, ob compiler-fehlermeldungen hilfreich sind  

31:05 B: das hängt sehr von der sprache ab. also die letzten, die ich hatte, waren hilfreich. das waren heute ein paar in go/ hatte ich go eben mitgesagt?  

31:18 I: nein, hast du nicht gesagt  

31:18 B: ich habe go vergessen! alter schwede. ich arbeite grade fast komplett mit go. ja, heute hatte ich ein paar fehler in go, die waren sehr hilfreich. gestern hatte ich was in c und wenn ich sie einmal gefunden hatte, waren auch die hilfreich. typescript habe ich eigentlich auch immer als hilfreich in erinnerung, javascript ist immer ein bisschen naja, nciht so hilfreich. c++ kann unhilfreich sein, wenn es sehr templatelastiger code ist, aber meistens gehts. perl schwankt, kommt sehr auf den code an, den er zu meckern hat. scala meistens hilfreich.

32:16 I: du kennst dich in vielen sprachen sehr gut aus undso, hast du da auf syntatkischer ebene manchmal noch probleme? also, außer semikolon vergessen  

32:29 B: ja, wenn ich zwischen einer sprache auf eine andere switche, passiert das immer mal. dass ich irgendwie code schreibe, der in einer sprache gültig ist und in der anderen nicht, oder irgendein lustiger mischmasch ist. allerschönstes beispiel sind da halt c-ähnliche sprachen und go. bei c-ähnlichen sprachen hast du ja datentyp und danach den namen der variable in der deklaration. bei go hast du variablenname, datentyp. das ist was, was mir immer mal wieder passiert, wenn ich irgendwie am wochenende wieder viel an meinem betriebssystem geschrieben habe. und komm montag wieder auf arbeit, direkt nach dem daily irgendwas in go schreiben und dann ist alles erstmal halb c halb go. auch so dinge wie, in c schreibe ich oft code mit sehr vielen pointern. in go passiert das seltener. aber wenn ich wieder sehr viel c geschrieben hab, kann es mal sein, dass mein go-code plötzlich etwas pointerlastiger ist als normal. so wirklich große probleme allerdings nicht. der erste compile-durchgang sagt mir dann, ach, ja, klar. dann sortier ich das fix um und dann ist wieder ein tag gegessen

34:44 I: da du den begriff vorhin schon selber eingebracht hast, erübrigt sich die frage eigentlich auch, ob du denkst, dass du schonmal ne programmierblockade hattest  

34:55 B: ja, durchaus. manchmal gibt es einfach probleme, wo einfach nicht klar ist, wie löse ich das jetzt, oder auch einfach nur, wie komme ich auch nur einen schritt weiter in die richtung. manchmal ist es einfach zu unklar, was das problem ist

35:30 I: ja dann sind wir mit meinem fragen tatsächlich durch, vielen dank. jetzt darfst du, wenn du magst, erfahren, worum es geht  

35:33 B: ja gern  

35:36 I: also ich komm ja vom schreiben. und ich hab mich in meinem bachelor mit schreibprozessforschung und schreibblockaden auch auseinandergesetzt und will jetzt die theorie davon aufs programmieren übertragen und gucken, ob dabei was rauskommt  

35:50 B: spannend. ein kreativer prozess zum anderen  

35:53 I: genau. das ist so der gedanke  

36:00 B: das klingt spannend  

36:03 I: fällt dir unter dem gesichtspunkt/ willst du noch irgendwas hinzufügen einfach?  

36:11 B: nichts, das mir grade einfällt. also mir fallen ein paar unterschiede zwischen schreiben und programmieren ein, glaub ich. zum beispiel dass du halt beim programmieren für teilbereiche zum beispiel öfter mal tickets hast und das beim schreiben mir zumindest nicht bekannt wäre  

36:28 I: ist die frage, wenn man im team schreibt, who knows?  

36:31 B: ja, ja stimmt. schreiben ist nicht nur fantasy-romane, sondern auch manchmal technisches schreiben oder so  

36:38 I: ja, da fehlt mir auch die erfahrung, aber der größte unterschied, der mir so einfällt, ist einfach immediate feedback durch den compiler  

36:50 B: ja, das stimmt. und dass wortwahl auch nicht so sein problem ist, weil, du hast nicht so viele wörter zur auswahl, um eine schleife zu machen  

37:04 I: das ist ist richtig. also man könnte vielleicht argumentieren variablenbenennung, clean code undso  

37:10 B: ja, genau. aber durch die syntax davon, kann die sprache/ sind halt sehr viele wörter schon eingegrenzt  

37:21 I: aber du würdest jetzt schon sagen, dass schreibprozess und programmierprozess würdest du schon vergleichbar finden?  

37:29 B: ja, das klingt nicht so abwegig. wär ich jetzt nicht drauf gekommen, das zu vergleichen, aber es klingt nicht abwegig tatsächlich  

37:36 I: okay, das beruhigt mich  

37:40 B: es sind beides kreative prozesse, bei beiden geht es darum, dinge runterzuschreiben. ja und wie du sagtest, schreibblockade versus programmierblockade, ja, das kann durchaus sehr ähnlich sein tatsächlich  

37:53 I: schreibst du?  

37:56 B: ne. also ich hatte mal die idee zu schreiben, ich hab mal angefangen, ich hab ne seite geschafft und dann hab ichs wieder vergessen