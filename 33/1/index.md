# Grupa Piotra Kowalskiego: Jak przygotować się do warsztatów?

## Konfiguracja środowiska

1. [Edytor tekstu](/workshop-setup/partials/edytor-tekstu.html)
2. [Przeglądarka](/workshop-setup/partials/przegladarka.html)
3. [Node.js + npm](/workshop-setup/partials/node+npm.html)
4. Git
    + [Instalacja](/workshop-setup/partials/git-instalacja.html)
    + [Integracja z GitHub-em](/workshop-setup/partials/git-integracja-z-github.html)
    + [Konfiguracja użytkownika](/workshop-setup/partials/git-konfiguracja-uzytkownika.html)
    + [Konfiguracja globalna](/workshop-setup/partials/git-konfiguracja-globalna.html)

## Konfiguracja projektu `warsawjs-workshop-33-twitter`

```bash
git clone git@github.com:piecioshka/warsawjs-workshop-33-twitter
cd warsawjs-workshop-33-twitter
npm install # lub yarn
```

## Dodatkowo

* Zainstalować plugin do `Visual Studio Code`:
    + `Vetur`
* Zainstalować plugin do `Google Chrome`:
    + `Vue.js devtools`

## Weryfikacja

Aby sprawdzić konfigurację systemu, należy uruchomić:

```bash
mkdir -p /tmp/
curl -sSL https://raw.githubusercontent.com/warsawjs/workshop-setup/master/33/.solidarity.json > /tmp/.solidarity.json
npx solidarity -f /tmp/.solidarity.json
rm /tmp/.solidarity.json
```

_Dla Windows: Uruchom powyższe polecania w `Git Bash`._
