<h1>EniigEpiicFaiil: Sikkerhedsproblemer hos Eniig Fiber</h1>
<p>I 2017 blev der fundet en r&aelig;kke sikkerheds-problemer i fiberboks-ops&aelig;tningen fra Eniig Fiber (de hed Bredb&aring;nd Nord p&aring; tidspunktet). Som gjorde det muligt at hacke sig ind p&aring; 150.000 hjemmenetv&aelig;rk. Problemerne blev reporteret til Eniig igennem en journalist.</p>
<p>Problemerne kunne kort beskrives som:</p>
<ul>
<li>Default ops&aelig;tningen i fiberboksene var kun &aelig;ndret nok til at f&aring; det til at virke. Default koder til konsol, webinterface og GPON var ikke &aelig;ndret. Firewall var ikke sat op i fiberboksen.</li>
<li>Der var et f&aelig;lles login til FTP-serveren hvor alle konfigurationerne var gemt, de indeholdte hver kundes WiFi og SIP kode. Alle konfigurationerne p&aring; FTP-serveren var l&aelig;se- og skive-bare.</li>
<li>Der var ingen firewalls i management netv&aelig;rket, der var f&oslash;rt ud til alle fiberbokse.</li>
<li>Kundenummeret var genbrugt som WiFi navn, og WiFi koden var genbrugt til login i selvbetjening.</li>
<li>Du kunne via selvbetjenings-hjemmeside f&aring; koden til WiFi/selvbetjening ved at kende WiFi navn og adresse.</li>
<li>Der var en fejl der gjorde det muligt at blive root fra konsol og webinterface.</li>
</ul>
<p>De fleste af fejlene blev rettet i l&oslash;bet af 4 uger. Som det ser ud nu, er der ikke nogen m&aring;de at masse-overtage alle fiberboksene p&aring;. Men det er stadig muligt at lave m&aring;lrettet angreb.</p>
<h2><span id="Eget_indhold" class="mw-headline">Eget indhold</span></h2>
<ul>
<li>Videoer p&aring; YouTube
<ul>
<li><a class="external text" href="https://www.youtube.com/watch?v=gf3Unl8L_gc" rel="nofollow">Hvorfor Per pillede ved sin fiberboks</a></li>
<li><a class="external text" href="https://youtu.be/fTj0ngF4OaU" rel="nofollow">Foredrag om sikkerhedsproblemerne</a></li>
</ul>
</li>
<li>Filer p&aring; GitHub
<ul>
<li><a title="Sikkerhedsproblemer i Icotera i5800 fiberboks fra Bredb&aring;nd Nord" href="https://github.com/CableCatDK/EniigEpiicFaiil/blob/master/Teknisk%20gennemgang%20af%20sikkerhedsproblemerne.html">Teknisk gennemgang af sikkerhedsproblemerne</a></li>
</ul>
</li>
</ul>
<h2><span id="Links" class="mw-headline">Links</span></h2>
<ul>
<li>Avisartikeler p&aring; Version2
<ul>
<li><a class="external text" href="https://www.version2.dk/artikel/hittepaasom-v2-laeser-graver-md5-kodeord-ud-fiberboks-saa-fik-udbyder-travlt-med-at-lukke" rel="nofollow"> Sikkerhedsproblemer hos Eniig Fiber</a></li>
<li><a class="external text" href="https://www.version2.dk/artikel/softwareudvikler-er-blevet-tiltalt-hacking-og-haervaerk-mod-it-systemet-i-sin-soens" rel="nofollow"> Tiltalt for hacking for at advare om hul i b&oslash;rnehave system</a></li>
<li><a class="external text" href="https://www.version2.dk/artikel/politianmeldt-at-paapege-svaghed-overfor-kmd-1077571" rel="nofollow">Politianmeldt for at advare om hul i pladsanvisnings-system som giver adgang til alle CPR-numere</a></li>
</ul>
</li>
<li>Videoer p&aring; YouTube
<ul>
<li><a class="external text" href="https://www.youtube.com/watch?v=C2N98HMrFKc" rel="nofollow">Ligende sag fra Tyskland der omhandlede 8 million enheder</a></li>
<li><a class="external text" href="https://www.youtube.com/watch?v=h5PRvBpLuJs" rel="nofollow">Hvordan du f&aring;r konsol adgang til mange forskellige enheder</a></li>
<li><a class="external text" href="https://www.youtube.com/watch?v=rz0SNEFZ8h0" rel="nofollow">TR-069 og de sikkerhedproblemer forkert brug giver</a></li>
</ul>
</li>
<li>Artikler p&aring; Wikipedia
<ul>
<li><a class="external text" href="https://en.wikipedia.org/wiki/Passive_optical_network" rel="nofollow">Passive optical network (PON)</a></li>
<li><a class="external text" href="https://en.wikipedia.org/wiki/TR-069" rel="nofollow">Technical Report 069 (TR-069)</a></li>
</ul>
</li>
<li>Andet
<ul>
<li><a class="external text" href="https://pierrekim.github.io/blog/2016-11-01-gpon-ftth-networks-insecurity.html" rel="nofollow">Ligende sag fra Frankrig</a></li>
<li><a class="external text" href="https://docbox.etsi.org/Workshop/2009/200901_SECURITYWORKSHOP/TELECOMITALIA_DELUTIIS_NextGenerationAccessNetwork(in)Security.pdf" rel="nofollow"> Sikkerhedsanalyse af GPON standarden</a></li>
</ul>
</li>
</ul>
