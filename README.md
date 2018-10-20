  <h1>EniigEpiicFaiil: Sikkerhedsproblemer hos Eniig Fiber</h1>

  <p>I 2017 blev der fundet en r&aelig;kke sikkerheds-problemer i
  fiberboks-ops&aelig;tningen fra Eniig Fiber (de hed Bredb&aring;nd Nord p&aring;
  tidspunktet). Problemerne blev reporteret til Eniig igennem en journalist. De fleste af
  fejlene blev rettet i l&oslash;bet af 4 uger.</p>

  <p class="c1">Problemerne kunne kort beskrives som</p>

  <ul>
    <li>Default ops&aelig;tningen i fiberboksen var kun &aelig;ndret nok til at f&aring;
    det til at virke. Default koder til konsol, webinterface og GPON var ikke
    &aelig;ndret. Firewall var ikke sat op i fiberboksen.</li>

    <li>Der var et f&aelig;lles login til FTP-serveren hvor alle konfigurationerne var
    gemt, de indeholdte hver kundes WiFi og SIP kode. Med det login var alle
    konfigurationerne l&aelig;se- og skive-bare.</li>

    <li>Der var ingen firewalls i management netv&aelig;rket, der var f&oslash;rt ud til
    alle fiberbokse.</li>

    <li>Kundenummeret var genbrugt som WiFi navn, og WiFi koden var genbrugt til login i
    selvbetjening.</li>

    <li>Der var en fejl der gjorde det muligt at blive root fra konsol og
    webinterface.</li>
  </ul>

  <p class="c1">Problemer der ikke er l&oslash;st</p>

  <ul>
    <li>Default koder til webinterface og GPON er ikke &aelig;ndret. Koden til konsol er
    den samme p&aring; alle bokse.</li>

    <li>Kundenummeret er genbrugt som WiFi navn, og WiFi koden er genbrugt til login i
    selvbetjening.</li>
  </ul>

  <p class="c1">Eksempel p&aring; hvordan ul&oslash;ste problemer kan udnyttes</p>

  <ol>
    <li>Ring til Eniigs telefonsupport.

      <ol>
        <li>Sig du gerne vil kunne logge ind p&aring; selvbetjening hjemmesiden
        mit.eniig.dk.</li>

        <li>Oplys naboens kundenummer og adresse. Du kender hendes kundenummeret, da det
        er genbrugt som WiFi navn.</li>

        <li>Koden du f&aring;r til mit.eniig.dk, er den samme som til naboens WiFi.<br />
        (Alternativ kan du sp&oslash;rger direkte efter WiFi koden. Hvilket sandsynligvis
        ogs&aring; er muligt hos andre ISP'er)</li>
      </ol>
    </li>

    <li>Login ind p&aring; naboens WiFi.

      <ol>
        <li>Gratis internet, uden ansvar. Alt hvad du laver af ulykker vil blive sporret
        tilbage til hende.</li>

        <li>Login p&aring; fiberboksen med standard koden, og skift DNS serveren til din
        egen. Du kan nu f&oslash;lge med i hvikle sider hun bes&oslash;ger.</li>

        <li>Brug <a rel="nofollow" class="external text" href=
        "https://en.wikipedia.org/wiki/ARP_spoofing">ARP spoofing</a> til at aflytte
        trafikken til internettet, hendes printer, netv&aelig;rks-harddisk og
        overv&aring;gnings-kamera.</li>
      </ol>
    </li>
  </ol>

  <h2><span class="mw-headline" id="Eget_indhold">Eget indhold</span><span class=
  "mw-editsection"><span class="mw-editsection-bracket">[</span><a href=
  "/w/index.php?title=Sikkerhedsproblemer_hos_Eniig_Fiber&amp;action=edit&amp;section=1"
  title="Redig&eacute;r afsnit: Eget indhold">redig&eacute;r</a><span class=
  "mw-editsection-bracket">]</span></span></h2>

  <ul>
    <li>Videoer p&aring; YouTube

      <ul>
        <li><a rel="nofollow" class="external text" href=
        "https://www.youtube.com/watch?v=gf3Unl8L_gc">Hvorfor Per pillede ved sin
        fiberboks</a></li>

        <li><a rel="nofollow" class="external text" href=
        "https://youtu.be/fTj0ngF4OaU">Foredrag om sikkerhedsproblemerne</a></li>
      </ul>
    </li>

    <li>Artikler p&aring; denne wiki

      <ul>
        <li><a href=
        "/Sikkerhedsproblemer_i_Icotera_i5800_fiberboks_fra_Bredb%C3%A5nd_Nord" title=
        "Sikkerhedsproblemer i Icotera i5800 fiberboks fra Bredb&aring;nd Nord">Teknisk
        gennemgang af sikkerhedsproblemerne</a></li>

        <li><a href="/Fiber_setup_hos_Eniig_i_Aalborg" title=
        "Fiber setup hos Eniig i Aalborg">Fiber setup hos Eniig i Aalborg</a></li>

        <li><a href="/Sikker_anonym_email" title="Sikker anonym email">Sikker anonym
        email</a></li>
      </ul>
    </li>
  </ul>

  <h2><span class="mw-headline" id="Links">Links</span><span class=
  "mw-editsection"><span class="mw-editsection-bracket">[</span><a href=
  "/w/index.php?title=Sikkerhedsproblemer_hos_Eniig_Fiber&amp;action=edit&amp;section=2"
  title="Redig&eacute;r afsnit: Links">redig&eacute;r</a><span class=
  "mw-editsection-bracket">]</span></span></h2>

  <ul>
    <li>Avisartikeler p&aring; Version2

      <ul>
        <li><a rel="nofollow" class="external text" href=
        "https://www.version2.dk/artikel/hittepaasom-v2-laeser-graver-md5-kodeord-ud-fiberboks-saa-fik-udbyder-travlt-med-at-lukke">
        Sikkerhedsproblemer hos Eniig Fiber</a></li>

        <li><a rel="nofollow" class="external text" href=
        "https://www.version2.dk/artikel/softwareudvikler-er-blevet-tiltalt-hacking-og-haervaerk-mod-it-systemet-i-sin-soens">
        Tiltalt for hacking for at advare om hul i b&oslash;rnehave system</a></li>

        <li><a rel="nofollow" class="external text" href=
        "https://www.version2.dk/artikel/politianmeldt-at-paapege-svaghed-overfor-kmd-1077571">
        Politianmeldt for at advare om hul i pladsanvisnings-system som giver adgang til
        alle CPR-numere</a></li>
      </ul>
    </li>

    <li>Videoer p&aring; YouTube

      <ul>
        <li><a rel="nofollow" class="external text" href=
        "https://www.youtube.com/watch?v=C2N98HMrFKc">Ligende sag fra Tyskland der
        omhandlede 8 million enheder</a></li>

        <li><a rel="nofollow" class="external text" href=
        "https://www.youtube.com/watch?v=h5PRvBpLuJs">Hvordan du f&aring;r konsol adgang
        til mange forskellige enheder</a></li>

        <li><a rel="nofollow" class="external text" href=
        "https://www.youtube.com/watch?v=rz0SNEFZ8h0">TR-069 og de sikkerhedproblemer
        forkert brug giver</a></li>
      </ul>
    </li>

    <li>Artikler p&aring; Wikipedia

      <ul>
        <li><a rel="nofollow" class="external text" href=
        "https://en.wikipedia.org/wiki/Passive_optical_network">Passive optical network
        (PON)</a></li>

        <li><a rel="nofollow" class="external text" href=
        "https://en.wikipedia.org/wiki/TR-069">Technical Report 069 (TR-069)</a></li>
      </ul>
    </li>

    <li>Andet

      <ul>
        <li><a rel="nofollow" class="external text" href=
        "https://pierrekim.github.io/blog/2016-11-01-gpon-ftth-networks-insecurity.html">Ligende
        sag fra Frankrig</a></li>

        <li><a rel="nofollow" class="external text" href=
        "https://docbox.etsi.org/Workshop/2009/200901_SECURITYWORKSHOP/TELECOMITALIA_DELUTIIS_NextGenerationAccessNetwork(in)Security.pdf">
        Sikkerhedsanalyse af GPON standarden</a></li>
      </ul>
    </li>
  </ul>
