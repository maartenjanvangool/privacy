# Privacy en Cyberveiligheid
Documentje om mijn gedachtes op papier te zetten voor iets dat me bezighoudt de laatste tijd: privacy en security thuis. 

## Uitgangspunten privacy

1. Privacy is belangrijk, maar gebruikersvriendelijkheid ook.
2. We proberen zo goed mogelijke keuzes te maken, maar we weten ook niet alles, en uiteindelijk moeten we (tot op zekere hoogte) bepaalde partijen vertrouwen met onze data.
3. Als richtlijn voor wanneer een partij of een stuk software te vertrouwen is gebruiken we de volgende criteria:
  1. Wat is het verdienmodel van deze partij?
     - Partijen zonder winstoogemerk die leunen op donaties en/of abbonnementen met een privacydoelstelling zijn in beginsel te vertrouwen. 
     - Als de partij geld verdient met advertenties is deze op geen enkele manier te vertrouwen.
  2. Europese organisaties vertrouwen we meer dan Amerikaanse organisaties.
  3. Open source software vertrouwen we meer dan closed source software. 
4. We kunnen niet alles in 1 keer veranderen. Focus op privacy en cyberveiligheid is belangrijk, maar is ook een werkje. 
5. We hebben een specifiek wantrouwen richting Microsoft, Google, Meta (Facebook), Amazon en Apple.
6. We hebben een specifiek wantrouwen richting de meeste AI tools. 

## Apparaten (makkelijk)

Maak een lijst van alle apparaten die je gebruikt en verbonden zijn met het internet. Denk aan telefoons, tablets en computers, maar ook Smart tv's, slimme stofzuigers, etc. 
- Voor Tablets, telefoons en Computers: Welk besturingssysteem staat erop? Tot wanneer worden daar nog patches voor gemaakt? Maak een lijstje; en weet welke apparaten je als eerst moet vervangen. Gebruik geen apparaat waarvan het besturingssysteem end of life is: Dit is echt heel erg onveilig. 
  - Handige website: https://endoflife.date/tags/device
    - iPhone: https://endoflife.date/iphone
    - MacOs: https://endoflife.date/macos
    - Windows: https://endoflife.date/windows (let op: Windows 10 is volgend jaar!)
- Voor alle andere apparaten:
  - Is het echt nodig dat deze met het internet verbonden zijn?
  - Zo ja, kan het informatie verzamelen over mij die ik niet wil? 
  - Zo ja, is het apparaat goedkoop te vervangen als de fabrikant het op afstand kapot maakt?  

## Domotica
Elk apparaat dat met een app bediend moet worden is een (potentieel) privacyprobleem en kan leiden tot onverwachte situaties. 
- Fabrikanten kunnen het apparaat per ongeluk kapot maken door per ongeluk op afstand foutieve softwareupdates op het apparaat te installeren.
- Fabrikanten kunnen doelbewust updates op het apparaat installeren die bepaalde functionaliteiten 'ineens' betaald maken.
- Ga er vanuit dat alle informatie die het betreffende apparaat kan verzamelen verzameld wordt om onder andere te gebruiken gerichtere advertenties te tonen.

Ik heb een slimme stofzuiger die in 2026 niet meer werkt omdat de fabrikant de ondersteuning stopt. Er bestaan koelkasten met een schermpje die je reclame laten zien op basis van wat je erin zet. Er zijn wifi-zendmasten die bijhouden waar je je bevindt in huis. Smart TV's met microfoons worden gebruikt om mensen af te luisteren. Dit is niet verzonnen allemaal. 

Tips: 
- Als het niet nodig is het apparaat te verbinden met het internet: DOE HET NIET.
- Wees extra waakzaam bij camera's en microfoons (ook smart tv's kunnen microfoons bevatten).
- Er zijn privacyvriendelijke alternatieven, zoals Home Asisstant. Maar dit is vooralsnog best veel werk en ingewikkeld... 

## Browsen (makkelijk)

Voor computer, tablet en telefoon:
- Installeer en gebruik de browser Firefox. [Firefox](https://www.firefox.com/nl/browsers/desktop/) is een browser gemaakt door de Mozilla Foundation, en niet geinteresseerd in je data (itt bijvoorbeeld Chrome of Edge). 
- Installeer de plugin [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) in je browser. Deze plugin blokkeert advertenties. Advertenties zijn niet alleen irritant, maar ze verzamelen ook informatie over je.
- Installeer zo min mogelijk plugins verder. Wantrouw plugins tot in het extreme. Plugins kunnen vaak alles zien wat je browst.
- Installeer geen AI tools in je browser. De AI (en dus het bedrijf erachter) kan niet alleen zien wat je doet, maar kan ook vaak acties uitvoeren in je browser. Dit is supergevaarlijk. 
- Stel [DuckDuckGo](https://duckduckgo.com/) in als zoekmachine. DuckDuckGo is een privacyvriendelijker alternatief voor Google. 

## Apps op telefoon of Tablet (makkelijk)
- Firefox boven Chrome of Safari
- Signal boven Whatsapp
- TomTom boven google (of apple) maps
- CleanTube boven YouTube

## Wachtwoorden en tweefactor (beetje moeilijk)

- Installeer een password manager die te vertrouwen in (bijvoorbeeld van [Proton](https://proton.me/pass) (is een Zwitsers bedrijf dat als verdienmodel privacy heeft. Ik vertrouw ze)).
- Bewaar al je wachtwoorden in deze password manager (en niet meer elders).
- Verander je belangrijkste wachtwoorden en stel tweefactor authenticatie in. Doe dit in ieder geval voor:
  - e-mailaccounts
  - Social media accounts (linkedin, Facebook, ...)
  - Belangrijke andere accounts (Apple, Google, Microsoft, etc).
 
## Backups en bestanden (beetje moeilijk)

Bewaar je belangrijke bestanden op 3 plekken: 
1. Op je computer
2. In een (veilige) cloud backup (aanrader: [TransIP stack storage](https://www.transip.nl/stack/) of [Proton Drive](https://proton.me/drive)). Synchroniseer deze constant. 
3. Op een losse externe harde schijf (maak een backup elke 2 of 3 maanden). Bewaar ook als het even kan meerdere oudere backups. 

## Verander van e-mailaccount naar een privacyvriendelijk alternatief (veel werk)

[Proton Mail](https://mail.proton.me/) biedt superveilige end-to-end encryptie voor je e-mail. Nadeel is dat je e-mailadres verandert. In de overgang kan je je oude e-mail wel doorgestuurd worden naar je nieuwe account. 

## Installeer Linux (heel moeilijk)

Microsoft en Apple verzamelen steeds meer informaite over het gebruik van je computer. Daarnaast dwingen deze organisaties je nieuwe computers te kopen omdat ze geen support meer leveren op oude versies van software. Een open source alternatief neemt dit weg. Maar een ander besturingssysteem beteknet ook andere software en erg wennen. Ik gebruik al jaren [Ubuntu](https://ubuntu.com), een relatief eenvoudig te installeren besturingssysteem, ook voor relatieve leken (maar nog steeds veel werk). Kies altijd voor de LTS-versie (long term support). 


