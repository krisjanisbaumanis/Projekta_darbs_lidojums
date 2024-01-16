# Projekta_darbs_lidojums
Lidojuma cenas no Rīgas uz Trapani-Marsala un atpakaļ:

DARBA UZDEVUMS

Projekta uzdevums bija manis paša izvēlēts, taču šis izvēlētais projekta uzdevums nebija mana pirmā izvēle, sākumā domāju par pavisam citām tēmām, taču beigās izlēmu par labu šai tēmai.
Manis izvēlētais uzdevums bija sekojošs: par cik es esmu gribējis jau labu laiku aizbraukt uz Itālijas lielāko salu Sicīliju, es izdomāju, ka vienā konkrētā nedēļā (kad man ir vārda diena un draudzenei ir dzimšanas diena), varētu izdomāt kā šīs iegūtās zināšanas un projekta darbu varētu apvienot un izveidot kaut ko ļoti noderīgu.  Par cik lidmašīnas biļetes aizņem vienu lielu daļu no ceļojuma budžeta es varētu katru dienu iegūt informāciju, cik maksā divas biļetes turp un divas biļetes atpakaļ. Sāku ar to, ka iegāju “Rayan-air” mājaslapā un izpētīju, kura ir tuvākā lidosta Sicīlijai un kuros datumos šī kompānija lido turp un atpakaļ. Tuvākā lidosta Sicīlijai ir Trapani-Marsala, savukārt lidmašīna uz Trapani-Marsala no Rīgas izlido 13.maijā, un no Trapani-Marsala lido uz Rīgu 18.maijā.


SAITE UZ VIDEO (VAJAG NOKOPĒT VISU SAITI):

https://youtu.be/zQh7UGaNuog


KODA PASKAIDROJUMS

Sākumā es izdomāju, ka varētu mēģināt ar “Webdrivera” palīdzību atvērt Chrome pārlūkprogrammu un mēģināt ar klikšķiem aizklikšķināt līdz vēlamajam saturam meklējot pēc ID, vai Class, taču man tas neizdevās, tāpēc, es pirmo reizi izmēģināju jaunu pieeju sameklēt vēlamo saturu meklējot pēc “CSS_Selector”, es sev dzīvi nedaudz atviegloju ar to ka "webdriveris" nekur daudz neklikšķina, jo es uzreiz programmas sākumā ielieku nepieciešamo url linku, lai palaižot programmu uzreiz ieietu vajadzīgajā sadaļā. Tālāk kopēju “path”, lai nolasītu info no atvērtās sadaļas, šādi viss man izdevās un tiku līdz vajadzīgajai informācijai, šo informāciju es sadalīju un izsijāju vajadzīgo, izprintēju uz ekrāna un tad man radās doma, ka varētu nedaudz sarežģīt uzdevumu un ierakstīt to excelī, lai būtu viss pārskatāmi un varētu apskatīties tendenci šīm biļešu cenām, vai ir lētākas nekā vakar, aizvakar, vai pirms kaut kāda x laika, kad es biju palaidis programmu. To es arī izdarīju un radās vēlviena papildus doma, es varētu vēl šo informāciju un excel failu aizsūtīt uz vienu no saviem gmail kontiem-šis bija, manuprāt, grūtākais un nezināmākais no visa šī projekta, daudz informāciju es meklēju un skatījos “Youtube” platformā un saskāros ar lielāko problēmu projektā, ka es nevarēju ielogoties automātiski ar koda palīdzību savā gmail kontā. Risinot šo problēmu es patērēju ļoti daudz laika, jo man nebija, kam pajautāt, kā arī visi “Youtube” video bija salīdzinoši veci un man nestrādāja tie risinājumi. Tā nu es kaut kā es “izmuļļājos” un man sanāca ielogoties un aizsūtīt sev info no sava gmail uz savu kontu, izrādās, ka pie vainas bija atstarpes, kas tika nokopētas kopā ar to vajadzīgo kodu un tādējādi arī nestrādāja programma, tālākais es izmantoju vienu no “Youtube” video kā paraugu, lai uzrakstīto nepieciešamo e-pastu ar struktūru un excel failu, kuru pēctam automātiski aizsūtu pats sev. Tagad katru dienu, kad es ieeju savā datorā palaižu kodu un man atsūta uz gmail excel failu kopā ar tekstu par to kādas cenas dotajā brīdī ir Rayanair mājaslapā manam lidojumam. 

IZMANTOTĀS BIBLIOTĒKAS

Pirmā un pati galvenā bibliotēka ir selenium, no kuras es importēju webdriveri, lai piekļūtu informācijai internetā, es apzinos, ka es varēju arī to aizstāt vienkārši ar kādu webscraper bibliotēku, taču man iepatikās kontrolēt un spiest pogas ar webdrivera palīdzību, kā arī vienreiz kodā arī tiek spiests uz pogas apstriprināt saites "cookies" neesmu drošs vai var tikt garām šim uzaicinājuma  tikai ar "pliku scraper". Nākamais, ko es importēju no selenium webdriver chrome service sadaļas bija pats Service-pamat bibliotēka, lai skripts strādātu. Tālāk no tās pašas bibliotēkas importēju By, lai vieglāk meklētu sev vajadzīgo informāciju. Pēctam es importēju bibliotēku time, kas ir atbildīga par to, lai manā skriptā webdriveris gaida kaut kādu konkrētu laiku pirms nākamās darbības un nenoslogo serveri, vai pašu datoru. Tālāk no openpyxl bibliotēkas es importēju Workbook un to arī uzreiz ielādēju. Smtplib bibliotēka, lai ar python vidi piekļūtu gmailam. MIMEText, lai nosūtītu texta emailus. MimeMultipart tiek izmanots, lai definētu vairāku daļu gmailu. MIMEAplication izmantota, lai pievienotu aplikāciju failus gmailā. Pati pēdējā tāda reālā bibliotēka, neskaitot to, ka es esmu vienā citā failā ierakstījis to piekļuves kodu gmailam, kā rezultātā, tad es pievienoju mainīgo no tā faila, šī bibliotēka ir os.path no kuras importēju basename, kas tehniski vienkārši ir domāta, lai izgūtu nosaukumu failam pēc dotā path, tādējādi pievienojot excel failu gmailam.













