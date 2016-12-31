Dwa-skladniki
=================

Lista stron działających w Polsce z określeniem czy akceptuja lub nie dwuskładnikowe uwierzytelnianie. Jest to fork projektu repozytorium [twofactorauth](https://github.com/2factorauth/twofactorauth) odpowiedzialnego za [TwoFactorAuth.org](https://twofactorauth.org) dostosowanego do krajowej specyfiki.

Poprzez strony działające w Polsce należy rozumieć strony, które posiadają co najmniej wersje polskojęzyczną interfejsu użytkownika.

## Cel

Celem jest stworzenie strony zapełniającej obszerny wykaz stron, które wspierają dwuskładnikowe uwierzytelnianie, a także metod, które one wspierają.

Mamy nadzieje, że pomoże to dokonać użytkownikom wyboru pomiędzy alternatywnymi usługami w oparciu o ich bezpieczeństwo, które
one oferują dla swoich klientów. Warto zaznaczyc, że może to stanowić wskaźnik nakładu pracy jaki został włożony w bezpieczeństwa w ogóle.

## Rozwój

Jeżeli chcesz pomóc wprowadzić zmiany, przeczytaj całe wytyczne w 
[CONTRIBUTING.md][podręczniku].

## Uruchomienie lokalne


Dwa-skladniki jest zbudowany na [Jekyll](https://jekyllrb.com/) z użyciem gemu [GitHub-pages](https://github.com/github/pages-gem).
W celu uruchomienia storny lokalnie, konieczne jest zainstalowanie ``bundler`` i wszystkich zależności, a następnie użycie jekyll, aby dostarczać stronę. Jeśli komenda `gem` nie jest dostępna, konieczne jest zainstalowanie Ruby z RubyGems.
Gdy Ruby i RubyGems są zainstalowane i dostępne z poziomu wiersza poleceń, dwa-skladniki można ustawić za pomocą następujących poleceń.

```
gem install bundler
cd ~/dwa-skladniki
bundle install
jekyll serve
```

Strona powinna być następnie dostępna z `http://localhost:4000`.

## Licencja

Kod źródłowy jest dostepny na licencji MIT. Aby uzyskać więcej informacji, przeczytaj [plik licencji][LICENSE] dostępny wraz z kodem źródłowym. Jest to fork projektu [twofactorauth](https://github.com/2factorauth/twofactorauth) odpowiedzialnego za [TwoFactorAuth.org](https://twofactorauth.org) dostosowanego do krajowej specyfiki.

[contrib]: /CONTRIBUTING.md
[license]: /LICENSE
