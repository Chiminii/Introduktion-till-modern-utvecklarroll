# Introduktion till modern utvecklarroll
## Praktisk Verktygsuppgift

Syftet med denna uppgiften är att se till att man har koll på grundläggande utvecklingsverktyg och arbetsflöden. Uppgiften fokuserar på *fyra huvudområden* istället för svår programmering:

* **Filsystemet:** kunna orientera sig där, t.ex. hitta, skapa och flytta filer och mappar på sin dator.

* **Terminalen:** att man kan styra datorn med textkommandon.

* **Utvecklingsmiljön:** att man kan öppna och arbeta med filer i kodredigeraren (VS Code).

* **Git & Repository-samarbete:** att man förstår grunderna i hur man kan spara sin kod med Git och hur man kan samarbeta kring kodprojekt.


## Git och versionhantering
* Inne i min projektmapp *Praktisk verktygsuppgift* skrev jag kommandot **git init** för att göra om mappen till ett Git-repository.

* Jag skrev sedan **git status** för att kolla läget i projektet.

* Skrev sedan **git add mina-bash-kommandon.txt** för att köa filen och förbereda den för nästa versionssparning.

* Skrev sedan **git commit -m "ett beskrivande meddelande på vad jag gjort"** för att spara den förberedda filen som en permanent version i projektets loka historik på datorn.

* Skrev sedan **git branch -M main** för att ändra om namnet på den nuvarande utvecklingsgrenen till "main".

* Skrev sedan **git remote add origin git@github.com:Chiminii/Introduktion-till-modern-utvecklarroll.git** för att koppla ihop min lokala projektmapp med mitt tomma repository på GitHub.

* Skrev sedan **git push -u origin main** för att ladda upp min lokala versionshistorik till GitHub och samtidigt sätta "main" som min standardgren för framtida uppladdningar.

* För att spara min första version av README.md och ladda upp den till GitHub använde jag kommandona **git add README.md**,för att köa filen, **git commit -m "mitt meddelande"**, för att spara den lokalt och sedan **git push** för att skicka upp den till GitHub.

* Ett **repository** är en digital lagringsplats eller mapp för ett projekt. Där sparar Git filerna, all versionshistorik och ändringar.

* En **commit** är som en sparad version av projektets filer i versionshistoriken, där varje commit fungerar som en "timestamp" på hur koden såg ut vid ett visst specifikt tillfälle.

* **Versionshistorik** är som en tidslinje över alla sparade ändringar (commits). Där visar den t.ex. vad som har ändrats i filerna över tid, när den gjordes och av vem.