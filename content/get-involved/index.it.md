---
title: "Contribute to the Protocol"
date: 2018-03-20T07:41:22+13:00
draft: false
type: "default"
description: "There are several ways to contribute to the NavCoin protocol - so if you’d like to support the project, here’s some of the best ways to get involved"
---
{{< hero_section
titleText="Partecipa attivamente"
paragraphText="Ci sono molti modi per contribuire allo svilupo del protocollo di NavCoin, e non tutti questi metodi richiedono una elevata preparazione in programmazione. Se volessi supportare il progetto NavCoin di seguito trovi l'elenco di alcune modalità con cui potrai&nbsp;contribuire."
imgSrc="/images/get-involved/con-hero.svg"
>}}
{{< zig_section
titleText="Traduzioni"
imgSrc="/images/get-involved/con-translate.svg"
  buttonText="Crea un account Transifex"
  buttonUrl="https://www.transifex.com/signup/"
  buttonImgSrc="/images/icons/rightward-arrow.svg"
    reversed="true"
    newTab="true"
>}}
NavCoin Core è stato tradotto in oltre 25 lingue e molte altre sono ancora in fase di traduzione e sono parzilmente complete — l'aiuto è quindi è sempre ben accetto. NavCoin Utilizza Transifex per le traduzioni e per partecipare hai bisogno di un&nbsp;account.<br><br>Per contribuire alle traduzioni visita il link del progetto NavCoin su Transifex: <br><a href="https://www.transifex.com/navcoin/navcoin-core" style="text-decoration:underline;">https://www.transifex.com/navcoin/navcoin-core</a><br><br>Clicca su 'Join Team', facci sapere quale lingua sei in grado di tradurre ed inizia in poco tempo a&nbsp;tradurre!
{{< /zig_section>}}

{{< zig_section
  titleText="Documentazione"
  imgSrc="/images/get-involved/con-doc.svg"
  buttonText="Contribuisci ai documenti di sviluppo"
  buttonUrl="https://github.com/NAVCoin/navcoin-dev-docs"
  buttonImgSrc="/images/icons/rightward-arrow.svg"
  bgPurple="true"
  newTab="true"
>}}
Stiamo lavorando per portare online la documentazione di sviluppo open-source di NavCoin Core. Se desideri aiutarci ad avviare questa parte del progetto visita GitHub e verifica come puoi supportare. Assicurati di seguire le modalità di utilizzo di GitHub descritte di seguito per evitare di richiedere un eccessivo sforzo sulla documentazione che stai&nbsp;producendo.
{{< /zig_section>}}

{{< zig_section
titleText="Invia una segnalazione"
imgSrc="/images/get-involved/con-issue.svg"
buttonText="Invia una segnalazione"
buttonUrl="https://github.com/NAVCoin/navcoin-core/issues"
buttonImgSrc="/images/icons/rightward-arrow.svg"
reversed="true"
newTab="true"
>}}
Per tutti i problemi non-critici che impattano NavCoin Core ti preghiamo di cercare prima l'eventuale presenza di altre segnalazioni o problemi, se non trovi nulla invia una nuova segnalazione fornendo le indicazioni riportate di&nbsp;seguito.
<br>
<ul class="article-ul" style="color: rgba(0, 0, 0, 0.55);">
  <li>Chiara descrizione del problema e i passi da compiere per riprodurre fedelmente il&nbsp;problema.</li>
  <li>Quale versione di NavCoin Core stai utilizzando.</li><li>Tutte le informazioni rilevanti presenti nel tuo file debug.log. Ricordati di eliminare preliminarmente ogni informazione sensibile che ti riguarda prima di pubblicare tale&nbsp;file.</li>
</ul>
<p class="paragraph-text">La miglior strategia per risolvere velocemente gli errori che segnali è di rendere facile la vita degli svilupatori affinchè comprendano correttamente il problema e gestiscano la soluzione. Più informazioni fornirai ed organizzandole in modo logico e coerente aiuterà questo lavoro in modo&nbsp;significativo.</p>
{{< /zig_section>}}

{{< zig_section
  titleText="Risolvere un problema"
  imgSrc="/images/get-involved/con-resolve.svg"
  buttonText="Leggi il readme"
  buttonUrl="https://github.com/navcoin/navcoin-core/blob/master/CONTRIBUTING.md"
  buttonImgSrc="/images/icons/rightward-arrow.svg"
  bgPurple="true"
  newTab="true"
>}}
L'issue tracker è il posto migliore nel quale trovare il modo giusto di collaborare allo sviluppo di NavCoin&nbsp;Core. Prima di cominciare a scrivere qualsiasi patche per gli errori trovati dovresti scrivere un commento per quell'errore per essere sicuro che nessuno stia lavorando allo sesso problema. Ricordati comunque che anche se stai risolvendo un errore che hai trovato, devi in ogni caso riportarlo nel issue&nbsp;tracker.
<br><br>
Per risolvere un problema segui questi passi:
<br>
<ul class="article-ul" style="color: rgba(255,255,255,0.55);">
  <li>Forka NavCoin/navcoin-core su tuo account&nbsp;GitHub.</li>
  <li>Crea un branch per lavorare alla soluzione del problema poi lavora sul problema&nbsp;stesso.</li>
  <li>Write or update unit and integration tests to cover any changes you’ve&nbsp;made.</li>
  <li>Make a pull request from your branch back into the main NavCoin Core repository with the issue type and number in the title (eg. Trivial: fixes spelling mistake #145).</li>
  <li>Talk with other NavCoin Core contributors on Discord or through GitHub to alert them to the pending Pull Request and they will review it as soon as&nbsp;possible.</li>
</ul>
<p class="paragraph-text">For the full contribution workflow details, please see the readme on&nbsp;GitHub.</p>
{{< /zig_section>}}

{{< zig_section
titleText="Write tests"
imgSrc="/images/get-involved/con-test.svg"
reversed="true"
newTab="true"
>}}
NavCoin Core is covered by many tests, but patches that improve test coverage are always welcome and are a great way to build familiarity with the codebase.
<br><br>
Developers are strongly encouraged to write <a href="https://github.com/NAVCoin/navcoin-core/blob/master/doc/unit-tests.md" target="e" style="text-decoration:underline;">unit tests</a> for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: make&nbsp;check.
<br><br>
There are also <a href="https://github.com/NAVCoin/navcoin-core/tree/master/qa" target="e" style="text-decoration:underline;">regression and integration tests</a>, written in Python, that are run automatically on the build&nbsp;server.
{{< /zig_section>}}

{{< zig_section
  titleText="Review the code"
  imgSrc="/images/get-involved/con-bug.svg"
    buttonText="Review pull requests"
  buttonUrl="https://github.com/navcoin/navcoin-core/pulls"
  buttonImgSrc="/images/icons/rightward-arrow.svg"
  bgPurple="true"
  newTab="true"
>}}
NavCoin Core is security software that helps protect assets worth millions of dollars, so every code change needs to be reviewed by experienced&nbsp;developers.<br><br>It can take a long time for other developers to review your pull requests. Remember that all reviewers are taking time away from their own projects to review your pull requests, so be patient and respectful of their&nbsp;time.<br><br>Please also consider helping to review other people’s pull requests. You don’t need to be an expert in NavCoin, the NavCoin Core codebase, or C++ (although all these things help). There are almost always open pull requests that any programmer can&nbsp;review.
{{< /zig_section>}}

{{< zig_section
titleText="Suggest a protocol improvement"
imgSrc="/images/get-involved/con-npips.svg"
buttonText="View NPIP's"
buttonUrl="https://github.com/NAVCoin/npips"
buttonImgSrc="/images/icons/rightward-arrow.svg"
reversed="true"
newTab="true"
>}}
NavCoin Core strives to continually improve the underlying protocol of NavCoin. Our aim is always to improve security, privacy and efficiency while encouraging decentralisation, uptake and usability. If you want to help us improve the NavCoin protocol, the best place to document your suggestion is on the NPIPs (NavCoin Protocol Improvement Proposals) GitHub&nbsp;repository.<br><br>People wishing to submit NPIPs, first should propose their idea or document to the NavCoin Core development community through Discord or IRC (irc.freenode.net #navcoin). After discussion, please open a PR to the NPIPs repository. After copy-editing and acceptance, it will be published&nbsp;there.<br><br>We are fairly liberal with approving NPIPs, and try not to be too involved in decision making on behalf of the community. The exception is in very rare cases of dispute resolution when a decision is contentious and cannot be agreed upon. In those cases, the conservative option will always be&nbsp;preferred.<br><br>Having a NPIP here does not make it a formally accepted standard until its status becomes Final or Active.<br><br>Those proposing changes should consider that ultimately consent may rest with the consensus of the NavCoin&nbsp;users.
{{< /zig_section>}}

{{< zig_section
  titleText="Disclose a security vulnerability"
  imgSrc="/images/get-involved/con-disclosure.svg"
  paragraphText="NavCoin is experimental technology and sometimes critical bugs are found. If you’re a researcher and you’ve found a security vulnerability head over to the Responsible Disclosure page to see how you can report&nbsp;it."
    buttonText="Responsible disclosure"
  buttonUrl="/responsible-disclosure/"
  buttonImgSrc="/images/icons/rightward-arrow.svg"
  bgPurple="true"
  newTab="true"
>}}
{{< /zig_section>}}

<style>
.article-ul>li{
    margin-bottom: 8px;
    font-size: 16px;
    font-family: roboto;
    line-height: 25px;
    text-align: justify;
    margin-top: 0;
    margin-bottom: 10px;
}
</style>
