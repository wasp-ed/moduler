[![en](https://img.shields.io/badge/lang-sv-yellow.svg)](https://github.com/wasp-ed/moduler/blob/main/modul2.md)
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/wasp-ed/moduler/blob/main/modul2en.md)
# Kompetensutvecklande aktivitet 2 – Praktiskt arbete med AI


Mål:
-   Grundläggande förståelse för hur AI fungerar
-   Begreppsförståelse

Nyckelord:
-   Maskininlärning, djupinlärning, neuronnät/neuralt nätverk, träningsdata

## Information om modulen

Denna modul är tänkt att genomföras i två steg. Deltagarna får inledningsvis ta del av två olika exempel på tillämpningar av AI med tillhörande videointroduktioner. Därefter deltar deltagarna i en gemensam träff där de ska träna ett neuralt nätverk via en onlinetjänst samt hålla en diskussion under ledning av handledare. Aktiviteterna förutsätter tillgång till dator. Total tidsåtgång är beräknat till 2,5-3 h (1,5 h individuellt och 1-1,5 h gemensamt)

## Del 1 - Individuell utforskning av AI-tillämpningar (1 h och 30 min)

### Steg 1, utforska djupinlärning (30 min)

*Deltagare inleder med att se en video som introducerar exemplet i MATLAB som de sedan ska arbeta med. De utforskar därefter miljön och exemplet, till exempel genom att ändra parametrar eller källor. Miljön innehåller instruktioner för att kunna testa på egen hand.*

**Beskrivning till deltagare:**

Denna aktivitet går ut på att utforska djupinlärning med programmeringsmiljön MATLAB, genom enkel, praktisk kod. Exemplet bygger på bildigenkänning. I miljön har du möjlighet att experimentera med att justera såväl kod som källa för analys. Var inte rädd för att experimentera, om något blir tokigt är det bara att ladda om sidan.

- Börja med att ta del av videon [Prova djupinlärning med MATLAB](https://www.youtube.com/watch?v=ELIcLRsX_wQ)
- Gå därefter till programmeringsmiljön MATLAB via [https://se.mathworks.com/campaigns/offers/deep-learning-try-in-browser.html#](https://se.mathworks.com/campaigns/offers/deep-learning-try-in-browser.html#) och klicka Launch the example
- Titta på koden och experimentera genom att till exempel justera källa för bilden som ska analyseras. Gå tillbaka till videon vid behov.
- Ladda om sidan om det blir problem eller om du vill nollställa allt och testa på nytt.


### Steg 2, promptning av språkmodeller (60 min)

*Deltagare inleder med att se en video som introducerar språkmodeller och promptning. De väljer sedan minst en av de specificerade tjänsterna där de sedan ska utforska olika typer av promptning utifrån givna ramar. Detta steg avslutas med en kort gemensam reflektion kring promptning utifrån ett antal frågeställningar.*

**Beskrivning till deltagare:**

I denna aktivitet ska du utforska olika sätt att formulera så kallade prompter (ungefär instruktioner) till en språkmodell. Det finns ett flertal tjänster online som alla går att använda kostnadsfritt, dock med vissa begränsningar. Vissa tjänster kräver dock inloggning. Du inleder med att ta del av videon som kort introducerar språkmodeller och promptning.

Därefter utforskar du minst en av nedanstående chatbottar:

-   ChatGPT ([https://chatgpt.com/](https://chatgpt.com/)), chatbott från OpenAI som använder språkmodellen GPT.
    
-   Copilot ([https://copilot.microsoft.com/](https://copilot.microsoft.com/)), chatbott från Microsoft som använder OpenAI:s språkmodell men som ändå ger delvis annat resultat.
    
-   Claude, ([https://claude.ai/](https://claude.ai/)), chatbott från Anthropic som använder språkmodellen Claude.
    
-   Gemini, ([https://gemini.google.com/](https://gemini.google.com/)), chatbott från Google som använder språkmodellen Gemini.
    

Utforskningen av chatbottarna görs med fördel utifrån nedanstående instruktioner:

-   Inled med att skriva en enkel prompt där du ber chatbotten att formulera en kort text inom ett område som du känner till väl. Be sedan chatbotten att arbeta om texten enligt en specifik instruktion, till exempel när det gäller form eller ton.
    
-   Gör sedan samma förfrågan till chatbotten, men ange redan i den inledande prompten instruktioner om hur du vill att texten ska vara, till exempel i form, ton eller detaljnivå. Gör sedan ytterligare en eller två prompter där du ber om specifika förändringar eller förbättringar av resultatet
    
-   Gör sedan ännu en gång samma förfrågan till chatbotten, men använd den här gången en exempeltext som du anger som mall för hur du vill att resultatet ska utformas.
    
-   Reflektera över varför resultaten varierar och hur det påverkar hur du kan arbeta mot språkmodeller för olika syften.
    
-   Om du har tid över kan du testa att göra om ovanstående i en annan chatbott.
    

Som avslutning ska ni sedan i helgrupp diskutera era erfarenheter från övningen ovan. Reflektera gärna utifrån frågorna nedan:

-   Hur påverkades resultatet av de olika sätten att prompta?
    
-   Varför tror du att resultatet varierar?
    
-   Hur kommer du att behöva variera din promptning utifrån olika syften och behov?

## Del 2 - Gemensam aktivitet, träna ett neuralt nätverk (1-1,5 h)

*Innan träffen förbereder sig deltagarna med att se en introduktion till tjänsten Google Teachable Machine som de sedan ska arbeta med. Vid träffen arbetar de i par med att träna ett neuralt nätverk via tjänsten. Aktiviteten följs sedan upp med en diskussion i helgrupp¬ under ledning av handledare. De frågor som bör beröras finns formulerade i beskrivningen nedan. Begreppen från modul 1 bör användas i diskussionen.*

**Beskrivning till deltagare:**

Denna aktivitet låter dig bygga neurala nätverk med Googles Teachable Machine. Den gör det möjligt att träna ett nätverk för att känna igen olika objekt, olika ljud eller olika kroppspositioner med hjälp av ett relativt enkelt visuellt gränssnitt. När du har skapat en "modell" kan du till och med exportera den och använda den på en webbplats eller på din dator för att utlösa saker som till exempel att spela ett ljud när någon ler på en webbkamera. Aktiviteten genomförs på plats, men du ska förbereda dig innan träffen med att titta på videon nedan.

- Börja med att se videon [Prova Googles Teachable machine](https://www.youtube.com/watch?v=v5SE5_MpBiw) innan du kommer till träffen. 
- Vid träffen delas ni in i par för att genomföra arbetet.
- Gå till Googles Teachable Machine via [https://teachablemachine.withgoogle.com/](https://teachablemachine.withgoogle.com/).
- Testa att träna nätverket med olika saker, till exempel personer, objekt eller liknande.
- Under ledning av handledare ska ni sedan i gruppen fundera över och diskutera kring vad är det som händer i verktyget. Berör frågor som till exempel:
  - Varför blir resultatet som det blir?
  - Varför reagerar verktyget som det gör?
  - Vad lär sig verktyget när det tränas?
  - Använd relevanta begrepp från modul 1 i diskussionen.
