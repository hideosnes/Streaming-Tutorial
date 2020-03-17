# Streaming-Tutorial

Ein Tutorial in dem die Potentiale und technischen Hürden erklärt werden, um einen (Live)Stream zu erstellen.

<h3>Achtung:</h3>

<p>Bei Fragen nutzen Sie bitte entweder die Commit-Funktion von Github, schicken Sie mir eine Twitter-DM via <a href="https://twitter.com/hideosnes/">@hideosnes</a> oder einfach eine Mail. Am Ende dieses Tutorials befindet sich ein FAQ, welches ich laufend erweitern werde. Es gilt: Wenn Sie eine Frage haben ist die Chance hoch, dass sie von weiteren Menschen ebenfalls gestellt wird. :) Fragen, Wünsche, Anregungen und Feedback sind natürlich immer willkommen. </p>

<p>Gerne können Sie das Tutorial mit diesem Link teilen: https://github.com/hideosnes/Streaming-Tutorial/ . Alternativ können Sie auch auf folgenden Thread auf Twitter verlinken, in dem ich nützliche Links für Kulturschaffende und -institutionen sammle.
<blockquote class="twitter-tweet"><p lang="de" dir="ltr">Ein ungemein wichtiger Appell an <a href="https://twitter.com/UlrikeLunacek?ref_src=twsrc%5Etfw">@UlrikeLunacek</a> ! Nicht nur Trägerorganisatioen sind in Gefahr, sondern auch Kunst- und Kultureinrichtungen, und wie es <a href="https://twitter.com/stefansargnagel?ref_src=twsrc%5Etfw">@stefansargnagel</a> ganz richtig anspricht, auch Künstler*innen, deren Einkommen davon abhängt. <a href="https://twitter.com/hashtag/coronavirus?src=hash&amp;ref_src=twsrc%5Etfw">#coronavirus</a> <a href="https://twitter.com/hashtag/COVID19?src=hash&amp;ref_src=twsrc%5Etfw">#COVID19</a> <a href="https://t.co/e5FukuBoQ9">https://t.co/e5FukuBoQ9</a></p>&mdash; Hideó SNES (@hideosnes) <a href="https://twitter.com/hideosnes/status/1237400543120760835?ref_src=twsrc%5Etfw">March 10, 2020</a></blockquote></p>

<!-- Inhalte -->

<h2 id="inhalte">Inhalte</h2>

 <ul>
  <li><a href="#grundlagen">Grundlagen</a></li>
  <li><a href="#hardware">Hardware</a></li>
  <li><a href="#software">Software</a></li>
  <li><a href="#monetarisierung">Monetarisierung</a></li>
  <li><a href="#faq">FAQ</a></li>
  </ul>

<!-- Grundlagen -->

<h2 id="grundlagen">Grundlagen</h2>

<p>Wenn man gemeinhin über einen Stream spricht ist damit im Grunde die Datenübertragung von Audio und Video Daten in Echtzeit gemeint. Daraus ergibt sich, dass es grundsätzlich folgende Formen von Streams gibt:</p>

<ol>
 <li><b>Audio</b> (z.B.: Podcasts, iTunes, ...)</li>
 <li><b>Video</b> (z.B.: Youtube, Netflix, ...)</li>
 <li><b>Live A/V</b> (z.B.: Social Media Liveübertragung, Twitch, ...)</li>
</ol>

<p>Während man manche Formate relativ einfach mit einem Handy einrichten kann, können sich bei zB. Live A/V Streams durchaus Probleme einschleichen, die das Streaming Erlebnis stark beeinträchtigen. Daher sollte man sich vor dem Einrichten eines Streams folgende Fragen stellen:</p>

<ol>
 <li>Welche Contents kann ich produzieren?</li>
 <li>Wie will ich diese Contents publizieren?</li>
 <li>Will ich die Publikation monetarisieren?</li>
</ol>

<p>In den folgenden Kapiteln werde ich nun versuchen diese Fragen möglichst schlüssig zu erklären und nenne bewusst - falls verfügbar - FOSS-Lösungen, welche den Vorteil haben schnell und einfach verfügbar zu sein, da es sich dabei um "Free and/or Open Source Software" handelt. Software von gängigen Anbietern (zB. Adobe) kann natürlich auch problemlos verwendet werden.</p>

<br>
<a href="#inhalte">Zurück nach oben</a>
<br>

<!-- Hardware -->

<h2 id="#hardware">Hardware</h2>
<p>Ich konzentriere mich bei der Hardware darauf, dass die Konfigurationen solide und in Wien(!) möglichst leicht verfügbar sind.</p>

<h3>Audio</h3>

<p>Für einen Podcast genügt meistens sogar die Aufnahmefunktion eines Handys. Im Falle von iPhones ist der eingebaute, aktivierbare "Auto-Equalizer" in der Lage erstaunlich gute Aufnahmen zu produzieren. Equalizer-Software ermöglicht es Usern das Finetuning der Aufnahme vorzunehmen (Lautstärke, Höhe/Tiefen, Bässe, etc.) und ist in den meisten Handys bereits vorinstalliert. Sollten Sie sich dennoch nach einer App-Lösung umsehen wollen, finden Sie mit dem <a href="https://play.google.com/store/apps/details?id=com.andrwq.recorder&hl=de&hl=de">Smart Recorder</a> eine geeignete Lösung.</p>

<p>Mit einem sogenannten <a href="https://www.conrad.com/p/zoom-h1n-portable-audio-recorder-black-1645795">Zoom Recorder</a> können Sie auch mit einfachen Mitteln professionelle Audio Aufnahmen erzeugen. Aufnahmen werden dabei entweder als "wav" oder "mp3" Datei auf einer <a href="https://www.conrad.com/p/sandisk-micro-sd-16-gb-microsdhc-card-16-gb-class-4-incl-sd-adapter-417304">SD-Speicherkarte</a> gespeichert (Achten Sie bei Zoom Recordern auf die SD Kompatibilität in Gigabyte ("GB")). Wenn Sie ein Audiokabel mit einer <a href="https://www.conrad.com/p/clicktronic-jack-audiophono-cable-1x-jack-plug-35-mm-1x-jack-plug-35-mm-100-m-blue-gold-plated-connectors-1171945">3,5 mm Klinke (männlich-männlich)</a> benutzen können Sie das Zoom Gerät gleichzeitig als Mikrophon für Ihren Desktop Computer verwenden. Bei Mobilgeräten müssen Sie einen <a href="https://www.conrad.com/p/irig-mic-handheld-mobile-phone-microphone-transfer-typecorded-incl-clip-312360">3,5 mm TRRS-Plug</a> (<a href="https://www.youtube.com/watch?v=fA7YV8zwr0Y">Videoanleitung</a>) verwenden. Im Kapitel <a href="#software">"Software"</a> finden Sie weitere Tipps und Anleitungen zur Bearbeitung von Audio Dateien.

<p>Da von Gesprächsrunden und RL-Interviews derzeit abzusehen ist werde ich das Setup für mehrere Mikrophone derzeit überspringen. (Kann bei Bedarf aktualisiert werden.) Alternativ können Sie Interviews per <a href="https://www.techworld.com/picture-gallery/apps-wearables/best-free-software-for-video-calling-3685869/">Videochat</a> durchführen oder einen Anruf einfach aufnehmen.</p>

<h3>Video</h3>

<p>Auch bei Videoaufnehmen kann Ihnen ein Mobilgerät gute Dienste erweisen. Besonders gut geeignet sind Geräte von Huawei, da die eingebaute Kamera qualitativ hochwertige Aufnahmen erzeugt. Mit der <a href="https://play.google.com/store/apps/details?id=com.camerasideas.instashot&hl=en">InShot App</a> können Sie Videoaufnahmen direkt am Handy schneiden, editieren und simple Postproduktion vornehmen. Die meisten Mobilgeräte erzeugen im Landscape Modus Videos im Format 16:9 bei 1080p. Das ist mehr als ausreichend, um Videos für Online- und Streaming Plattformen zu erzeugen. Die Aufnahmegrösse lässt sich in der Kamera-App entweder über das Zahnrad-Symbol oder 3-vertikale-Punkte-Symbol ändern. Beachten Sie dabei die Auflösung nicht kleiner als 720p einzustellen!</p>

<p>Sollten Sie es vorziehen mit einer Kamera oder einem Camcorder aufzunehmen, ist die Voreinstellung bei Aufnahmen im Normalfall bereits als 16:9/1080p gesetzt. Bei digitalen Spiegelreflexkameras (zB.: Canon 5d Mark II) hängt das Aktivieren der Videofunktion vom Modell ab. Lesen Sie daher die Anleitung oder googeln Sie "Record Video"+Kameramodell. In jedem Fall werden die Videoaufnahmen auf der SD Karte abgespeichert und können anschliessend auf einen Desktop Computer übertragen und dort bearbeitet werden. Im Kapitel <a href="#software">"Software"</a> finden Sie weitere Tipps und Anleitungen zur Bearbeitung von Video Dateien.

<p>Während die eingebauten Mikrophone in einem Mobilgerät gar nicht schlecht sind, werden Sie jedoch bei Camcordern und Kameras schnell an unschöne Grenzen stossen. Daher sei hier geraten ein externes Mikrophon zu benutzen. Sie können dazu ein Zoom Mikrophon anschliessen oder auf vorgefertigte Lösungen zurück greifen. Empfehlenswert sind die Expert*innen des <a href="https://www.kameraverleih.at/">Kameraverleih</a> in 1050 Wien oder der <a href="https://www.klangfarbe.com/">Klangfarbe</a> u.a. in 1030 Wien.</p>

<p>Da von Gesprächsrunden und RL-Interviews derzeit abzusehen ist werde ich das Setup für mehrere Mikrophone derzeit überspringen. (Kann bei Bedarf aktualisiert werden.) Alternativ können Sie Interviews per <a href="https://www.techworld.com/picture-gallery/apps-wearables/best-free-software-for-video-calling-3685869/">Videochat</a> durchführen oder einen Anruf einfach aufnehmen.</p>

<h3>Live A/V</h3>

<p>Auch bei Live Audio/Video Übertragungen sei zuerst auf Mobilgeräte verwiesen. Moderne Geräte verfügen inzwischen über genug Rechenkapazität um Live Streams problemlos auf einen aufzunehmen und gleichzeitig auf einen Server zu übertragen. Verwenden Sie bei Bedarf einen 3,5mm TRRS-Plug (Hardware > Audio) um ein externes Mikrophon anzuschliessen. Sämtliche Anbieter werden bei Live Streams am Mobiltelefon automatisch auf die eingebaute Kamera des Mobilgerätes zugreifen und Sie müssen sich sonst um nichts mehr kümmern. <a href="https://www.conrad.com/p/mini-incl-mobile-phone-holder-renkforce-black-white-1511438">Tripods</a> für Mobilgerät werden Ihnen hier die Aufnahme sehr erleichtern.</p>

<p>Eine weitere Möglichkeit besteht darin mit einem PC und einer Webcam einen Lifestream anzubieten. 3 Dinge sind dafür notwendig:
 <ol>
  <li>Ein Computer mit leistungsstarkem Prozessor oder Grafikkarte</li>
  <li>Eine Webcam und optional ein (USB) Mikrophon</li>
  <li>Streaming-Software und eine Plattform</li>
 </ol>

<blockquote id="streamingbegriffe">
<p>Beim Streaming werden Sie laufend auf folgende Begriffe treffen, daher möchte ich diese vorab kurz erklären:</p>

<p>Mit <b>Streaming</b> ist in diesem Fall die Aufnahme, (En)Codierung und das Hochladen von Video und Audio Daten ohne Zeitverzögerung (real-time) gemeint.</p>

<p>Das <b>Encoding</b> ist der Prozess rohe ("raw") Video und Audio Daten zu komprimieren ("compression"), damit diese gesendet und angesehen werden kann. Dabei gibt es zwei Möglichkeiten: 1.) Bei <b>Software encoding</b> benutzt eine Software die CPU (Prozessor) des Computers um die A/V Daten zu komprimieren. Das ist sehr resourcen-intensiv erlaubt aber eine bessere Bildqualität. 2.) Im Falle von <b>Hardware encoding</b> wird extra Hardware (Grafikkarte) benutzt, welche die A/V Daten komprimiert.</p>

<p>Die <b>Bitrate</b> beschreibt die Grösse der Datei, welche im Sekundentakt anwächst. Wenn ein Video mit 1,5kbps (Kilobits pro Sekunde) aufgenommen wird, ergibt das eine Datei, die 188 Kilobyte (1 byte = 8 bit) pro Videosekunde gross ist.</p>

<p><b>Frames-per-second (FPS)</b> ist die Anzahl der Bilder, welche ein Computer pro Sekunde berechnen kann, während dieser eine Aufgabe, wie zB. das Streaming, durchführt. Eine geringe FPS Zahl lässt ein Video ruckelig und abgehackt erscheinen.</p>
<br>

<p><b>1080p/720p</b> beschreibt die vertikale Auflösung eines Videobildes bei einem Aspektverhältnis von 16:9 in Pixel. D.h. die Auflösung 1080p entspricht 1920*1080 Pixel und 720p entspricht 1280*720 Pixel. Das "p" steht für "progressive scan" und kann im Zuge dieses Tutorial ignoriert werden.</p>  
</blockquote>

<p>Anders als bei der Aufnahme von Videos für zB. Youtube, wird beim Streamen keine Videodatei auf Ihrer Festplatte abgelegt, die man bearbeiten oder schneiden könnte. Stattdessen wird das Video live von der Kamera auf einen Server gestreamt, worüber andere Menschen das Video ansehen können. Daher wird für das Live A/V Streaming ein guter PC gebraucht, damit alle Daten ordentlich am Server ankommen und die Zuseher*innen flüssige, scharfe Videos zu sehen bekommen.<p>
 
<p>Damit es zu keinen Darstellungs- und Übertragungsproblemen kommt sollten Sie ein Desktop Gerät benutzen, welches mindestens über einen Intel Core i5-4670 Prozessor (oder Equivalent) und 8GB RAM verfügt. (Im Falle von Hardware Encoding mindestens eine Radeon RX570 oder Equivalent). Weiters ist dringend anzuraten den Computer via einem Ethernet Kabel mit dem Internet zu verbinden und eine entsprechend schnelle Verbindung zu wählen. Damit sollte es möglich sein Videos in 1080p, 3000kbps bei guter FPS-Zahl zu encodieren. Pi*Daumen kann gesagt werden, dass ein Stream mit 720p/1500kbps/30+FPS bereits eine durchaus annehmbare Video-Erfahrung liefert. Es ist natürlich möglich mit nicht so leistungsstarker Hardware zu streamen, jedoch kann das je nach Inhalt und Rechenaufwand zu Frame-Drops - das sind ungewollte Sprünge im Video - oder verwaschenen, unscharfen Videobildern führen.</p>

<p>Neben einem PC benötigt man auch eine <a href="https://www.conrad.at/de/p/creative-live-cam-sync-hd-720p-hd-webcam-1280-x-720-pixel-standfuss-klemm-halterung-352288.html">USB Webcam</a>. Beachtenswert ist hier die Maximalauflösung der Kamera. D.h. mit einer 720p Auflösung lassen sich keine 1080p Videos streamen, umgekehrt geht das jedoch problemlos. Um nicht unnötig Encodierungsresourcen zu verschwenden, sollte man darauf achten, dass die Grösse der Aufnahme 1:1 der Grösse des gestreamten Videos - 1080p oder 720p - entspricht. Camcorder lassen sich meist problemlos per <a href="https://www.conrad.at/de/p/speaka-professional-hdmi-anschlusskabel-1x-hdmi-stecker-1x-hdmi-stecker-1-50-m-schwarz-325235.html">HDMI Kabel</a> und iFdF. entsprechendem Adapter an die Grafikkarte anschliessen und via Hardware encoding zum Streamen nutzen. Bei digitalen Spiegelreflexkameras kommt es sehr stark auf das Modell an, ob man die Kamera benutzen kann, oder nicht. Manche Kameras benötigen ein externes Videointerface, um für Livestreams verwendet zu werden, wovon jedoch - bei mangelnder Rechenleistung - abgeraten wird. Mit der Android-App <a href="https://www.dev47apps.com/">DroidCam</a> kann man auch ein Mobilgerät als 720p Wifi oder USB Webcam verwenden.</p>

<p>Bei Streaming-Software handelt es sich um zweckorientierte Software zum Encodieren und Hochladen von Videodaten. <a href="https://obsproject.com/">Open Broadcaster Software</a> und <a href="https://www.xsplit.com/">XSplit</a> sind beliebte Beispiele, die das Encodieren und das Hochladen über einen Social Media oder Streaming Plattform Account fast gänzlich automatisieren. Mehr dazu im <a href="#software">Software Kapitel</a>.</p>

<br>
<a href="#inhalte">Zurück nach oben</a>
<br>

<!-- Software -->

<h2 id="#software">Software</h2>
<p>In diesem Kapitel werde ich mich darauf beschränken getestete FOSS-Produktionspipelines aufzuzählen. Besonders in diesem Kapitel gilt, dass sehr viele Wege nach Rom führen und ich versuche mich daher auf leichte Verfügbarkeit und Automatisierungskapazitäten der Software zu fokussieren.</p>

<h3>Audio/h3>
 
<a href="https://play.google.com/store/apps/details?id=com.andrwq.recorder&hl=de&hl=de">Smart Recorder</a>
Aufnehmen, Bearbeiten und Sharing von Audio am <b>Mobiltelefon</b> - <a href="https://www.youtube.com/watch?v=dW7CdjlfjZE">Video Tutorial</a>

<a href="https://www.audacityteam.org/"><h3>Audacity</h3></a>
Aufnehmen und Bearbeiten von Audio am <b>Desktop PC</b> (Win, MacOs, Linux) - <a href="https://www.youtube.com/watch?v=Vn7HYyopGXk">Video Tutorial</a>



Achten Sie hierbei auf das Vorhandensein der nötigen Recording-Software, wie zB. <a href="https://www.audacityteam.org/">Audacity</a>. Sollten Sie Audio-Samples oder diverse Sounds für Ihren Podcast benötigen sei Ihnen <a href="https://freesound.org/">Freesound</a>.)</p>


