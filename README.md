# Zajecia1

Link do meetingu:

https://teams.microsoft.com/l/meetup-join/19%3ameeting_Mzk4ZGUxZWUtMGYyMC00NDJiLWIxZDItMGY0ZDNkOWMwNTNj%40thread.v2/0?context=%7b%22Tid%22%3a%2280b1033f-21e0-4a82-bbc0-f05fdccd3bc8%22%2c%22Oid%22%3a%22331e097f-9d0e-4021-9227-f8fce0d4797c%22%7d

Termin realizacji:

Do 19.03.2021

## Wstęp
Skoro chcemy mówić o "technikach internetowych" koniecznym jest poznanie technologii wersjonowania plików git.<br/>
Utworzone konto na github będzie wykorzystywane na każdych kolejnych zajęciach.

### Informacje ogólne:
https://guides.github.com/

### Ciekawe informacje o technologii git można przeczytać na stronie:
https://guides.github.com/introduction/git-handbook/

### "Hello world" w serwisie github:
https://guides.github.com/activities/hello-world/

## Przydatne materiały

Github: https://docs.github.com/en/github/getting-started-with-github<br/>
Materiały do git'a: http://letmegooglethat.com/?q=git+commands<br/>
Materiały do css: http://letmegooglethat.com/?q=css<br/>
Github Pages Hello world: https://pages.github.com/<br/>

# Zadanie (przygotowanie środowiska):

1. Należy wejść na stronę: https://github.com/
2. Zarejestrować się w serwisie **github** o ile nie ma się wcześniej utworzonego konta które posiada niewykorzystane Github Pages
    1. Wysłać nick z rejestracji (nazwę użytkownika) na adres e-mail: wdlubacz@zarz.agh.edu.pl przy czym: 
    2. Mail ten najlepiej wysłać z adresu z którego będzie się dana osoba chciała kontaktować ze mną w ramach wytłumaczenia jakiegoś zadania poza zajęciami
3. Należy wygenerować oraz podpiąć **klucze SSH** do konta Github:
    1. https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account
5. Należy mieć klienta **git** na swoim systemie operacyjnym:
    1. Dla systemu Windows zalecam skorzystać z: https://git-scm.com/downloads
    2. 64-bit Git for Windows Portable. -> rozpakować i powinno działać pod "git-bash.exe"
6. Należy zapoznać się z komendami **git**:
    1. `init`, `add`, `commit`, `push`, `pull`, `merge`, `clone`, `branch`, `checkout`
7. Należy pobrać VSCode: https://code.visualstudio.com/
8. W serwisie **github** należy utworzyć *repozytorium* o nazwie: *NAZWA_UŻYTKOWNIKA.github.io*
    1. Zgodnie z tutorialem na stronie: https://guides.github.com/features/pages/ dotyczącym tzw **Github Pages**
9. Repozytorium to należy *sklonować* lokalnie na własny komputer poleceniem `git clone git@github.com:NAZWA_UŻYTKOWNIKA/NAZWA_REPOZYTORIUM.git`
    1. Istotne jest aby używać `git@github.com` a nie `https://github.com/` - w ten sposób autoryzacja następuje poprzez wcześniej wygenerowane **klucze SSH**
10. W repozytorium tym należy utworzyć plik index.html
11. Plik index.html należy wypełnić tekstem "Hello world" przy użyciu HTML oraz nałożyć na ten tekst style CSS
    1. Wygląd ostateczny, końcowy może być dowolny byle był tekst "Hello world"
12. Następnie należy wewnątrz folderu z *repozytorium* wykonać komendy:
    1. `git add .` - dowiązanie nowych plików
    2. `git commit -m "Index.html initial commit"` - utworzenie *commit* lokalnie
    3. `git push` - wrzucenie zmian publicznie (na serwery github)
13. Jeżeli wszystko zostało wykonane poprawnie, na stronie internetowej *https://NAZWA_UŻYTKOWNIKA.github.io* powinien się pojawić napis Hello World wcześniej utworzony w pliku index.html

## Dodatkowe informacje:

Istnieje prawdopodobieństwo, że z wymienionych komend **git** będzie kolokwium
