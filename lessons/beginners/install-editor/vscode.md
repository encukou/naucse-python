{% set editor_name = 'Visual Studio Code' %} {% set editor_url = 'https://code.visualstudio.com' %} 
{% extends lesson.slug + '/_base.md' %}

{% block name_gen %}Visual Studio Code{% endblock %}

{% block install %}
## Stažení a instalace 

Editor si můžeš stáhnout z jeho [domovské stránky](https://code.visualstudio.com/).
Vyber na ní zelené tlačítko Download a vyber instalátor pro svůj systém.
Dále se řiď instrukcemi instalátoru jako u každého jiného programu.
{% endblock %}

{% block setup %}
Ve Visual Studio Code se nemusí nic nastavovat, funguje „od výroby“ tak, jak má.

Editor VSCode or Microsoftu podobně jako Atom funguje ihned po instalaci bez těžkého nastavování
Pokud ale chceš v editoru psát Python kód (nebo obecně každý jazyk) nainstaluj si rozšíření pro daný jazyk. 

## Jak na to:

1. Otevři si VSCode editor.
2. V sloupci úpně na levo(šedý) klikni na ikonku rozšíření. Ve výchozí pozici
třetí od shora. Vypadá jako čtverec, který má v sobe ještě jeden.
3. Do vyhledávacího boxu zadej "Python".
4. Zvol první výsledek (v rohu je označen hvězdičkou).
5. V nově otevřeném okně klikni na modré tlačítko "Install".
6. Vyčkej, než se rozšíření nainstaluje. Editor se restartuje a zobrazí se ti okno nápovědy rozšíření.

## Spuštění kódu

V editoru nenajdeš tlačtko spusit kód. Pokud tak chceš učinit naistaluj si toto [Rozšíření](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner).
Kód se dá spustit i v terminálu. Co to je a jak na to se dozvíš v dalších lekcích.

### Odesílání telemetrických dat

Tento textový editor ale odesílá data o tvém používání ([nejspíš včetně např.
obsahu otevřených souborů][privacy]).
Pokud si nepřeješ aby se data odesílala, můžeš odesílání zrušit:

* Otevři **File** > **Preferences** > **Settings** (macOS: **Code** > **Preferences** > **Settings**).
* Vyhledej `telemetry.enableTelemetry` a odškrtni tento záznam.

Viz též [původni postup v angličtině](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).

[privacy]: https://privacy.microsoft.com/en-us/privacystatement


## A to je vše!
Vše ostatní je již nainstalováno. Teď se jen pusť do samotného programování!

{% endblock %}
