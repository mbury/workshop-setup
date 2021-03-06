# Grupa nr 5: Jak przygotować się do warsztatów?

## Konfiguracja środowiska

1. [Edytor tekstu](/workshop-setup/partials/edytor-tekstu.html)
2. [Przeglądarka](/workshop-setup/partials/przegladarka.html)
3. [Node.js + npm](/workshop-setup/partials/node+npm.html)
4. Git
    + [Instalacja](/workshop-setup/partials/git-instalacja.html)
    + [Integracja z GitHub-em](/workshop-setup/partials/git-integracja-z-github.html)
    + [Konfiguracja użytkownika](/workshop-setup/partials/git-konfiguracja-uzytkownika.html)
    + [Konfiguracja globalna](/workshop-setup/partials/git-konfiguracja-globalna.html)
5. [EditorConfig](/workshop-setup/partials/editorconfig.html)
6. [ESLint](/workshop-setup/partials/eslint.html)
7. [MongoDB](https://docs.mongodb.com/manual/installation/)
    + MongoDB [Compass](https://www.mongodb.com/download-center/compass)
8. (Opcjonalnie) [Docker](/workshop-setup/partials/docker.html)

## Konfiguracja projektu `warsawjs-workshop-31-calendar-client`

* Sklonować projekt <https://github.com/G3F4/warsawjs-workshop-31-calendar-client>
* Zainstalować zależności

## Konfiguracja projektu `warsawjs-workshop-31-calendar`

* Sklonować projekt <https://github.com/piecioshka/warsawjs-workshop-31-calendar>
* Zainstalować zależności

## Weryfikacja

Aby sprawdzić konfigurację systemu, należy uruchomić:

```bash
mkdir -p /tmp/
curl -sSL https://raw.githubusercontent.com/warsawjs/workshop-setup/master/31/.solidarity.json > /tmp/.solidarity.json
npx solidarity -f /tmp/.solidarity.json
rm /tmp/.solidarity.json
```

_Dla Windows: Uruchom powyższe polecania w `Git Bash`._
