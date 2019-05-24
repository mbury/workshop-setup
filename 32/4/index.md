# Grupa nr. 5: Jak przygotować się do warsztatów?

## Konfiguracja środowiska

1. [Edytor tekstu](/workshop-setup/partials/edytor-tekstu.html)
2. [Przeglądarka](/workshop-setup/partials/przegladarka.html)

   Zainstalować następujące pluginy w przeglądarce:

   - Redux DevTools
   - React DevTools

3. [Node.js + npm](/workshop-setup/partials/node+npm.html)
4. Git
   - [Instalacja](/workshop-setup/partials/git-instalacja.html)
   - [Integracja z GitHub-em](/workshop-setup/partials/git-integracja-z-github.html)
   - [Konfiguracja użytkownika](/workshop-setup/partials/git-konfiguracja-uzytkownika.html)
   - [Konfiguracja globalna](/workshop-setup/partials/git-konfiguracja-globalna.html)

## Konfiguracja projektu `warsawjs-workshop-32-book-it`

- Sklonować projekt z GitHuba i zainstalować zależności `npm install`:
  <https://github.com/mbury/warsawjs-workshop-32-book-it>
- Postępuj zgodnie z instrukcjami w repozytorium

## Weryfikacja

Aby sprawdzić konfigurację systemu, należy uruchomić:

```bash
mkdir -p /tmp/
curl -sSL https://raw.githubusercontent.com/warsawjs/workshop-setup/master/32/.solidarity.json > /tmp/.solidarity.json
npx solidarity -f /tmp/.solidarity.json
rm /tmp/.solidarity.json
```

_Dla Windows: Uruchom powyższe polecania w `Git Bash`._
