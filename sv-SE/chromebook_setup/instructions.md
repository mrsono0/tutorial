Du kan [hoppa över denna sektion](http://tutorial.djangogirls.org/en/installation/#install-python) om du inte använder en Chromebook. Om det är så att du använder en Chromebook kommer din installation se lite annorlunda ut. Du kan ignorera resten av installations instruktionerna.

### Cloud 9

Cloud 9 är ett verktyg som ger användaren en kod-editor och tillgång till en sorts dator som man kör i webbläsaren. Denna dator kan man installera, skriva och köra mjukvara. Under denna introduktion kommer Clod 9 vara din *lokala maskin*. Du kommer fortfarande att köra din kommandon i terminalen, precis som dina klasskamrater som sitter på OS X, Ubuntu eller Windows, men din terminal kommer vara kopplat till en dator som Cloud 9 har satt upp till dig.

1. Installera Clound 9 från [Chrome webshop](https://chrome.google.com/webstore/detail/cloud9/nbdmccoknlfggadpfkmcpnamfnbkmkcp)
2. Gå till [c9.io](https://c9.io)
3. Registrera ett konto
4. Klicka på *Create a New Workspace*
5. Döpt den till *django-girls*
6. Välj *Blank* (Näst längst till höger på nedersta raden med orange logotyp)

Nu kan du se ett interface med en navigation vid sidan, ett stort huvud-fönster med någon text och ett litet fönster nertill som ser ut typ så här:

{% filename %}Cloud 9{% endfilename %}

    yourusername:~/workspace $
    

Den nedersta delen är din *terminal*, här kommer du ge din Cloud 9 dator instruktioner. Du kan ändra storleken på ditt fönster och göra det större.

### Virtuell miljö

En virtuell miljö (också kallad virtualenv) är som en typ av privat dator som man kan använda för att spara data och program som man använder i sitt projekt. Vi kommer använda den för att spara olika bitar av kod som tillhör olika projekt. På detta sätt kommer koden till projekten hållas separat från varandra så att vi inte blandar ihop de olika projekt-koden.

I din terminal, placerad längst ned i Cloud 9 rutan, kör följande kommando:

{% filename %}Cloud 9{% endfilename %}

    sudo apt update
    sudo apt install python3.6-venv
    

Om detta kommando inte fungerar, fråga din lärare om hjälp.

Nästa steg, kör:

{% filename %}Cloud 9{% endfilename %}

    mkdir djangogirls
    cd djangogirls
    python3.6 -mvenv myvenv
    source myvenv/bin/activate
    pip install django~=1.11.0
    

(Notera att den sista raden var det en tilde följt efter ett vanligt likhets-tecken).

### GitHub

Skapa ett [Github](https://github.com) konto.

### PythonAnywhere

Django Girls introduktion innehåller en sektion på vad som kallas Deployment, vilket menas med processen av att ta koden för din nya applikation och flyttar den till en publik server så att andra personer kan se applikationen.

Denna biten av introduktionen är lite annorlunda för dig som sitter på en Chromebook. Eftersom din dator redan utgår ifrån internet (inte som en vanlig laptop som är en dator i sig). Men Cloud 9 är fortfarande användbart för dig. Eftersom vi kan tänka att vår Cloud 9 workspace är ett ställe för vårt "pågående" arbete och då är Python Anywhere ett ställe där vi kan visa upp vårt arbete som är mer klart.

Således, registrera dig på Python Anywhere på [www.pythonanywhere.com](https://www.pythonanywhere.com).