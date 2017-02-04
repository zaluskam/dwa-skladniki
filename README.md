Dwa-skladniki
=================

Lista stron działających w Polsce z określeniem czy akceptuja lub nie dwuskładnikowe uwierzytelnianie. Poprzez strony działające w Polsce należy rozumieć strony, które posiadają co najmniej wersje polskojęzyczną interfejsu użytkownika.

Jest to fork projektu repozytorium [twofactorauth](https://github.com/2factorauth/twofactorauth) odpowiedzialnego za [TwoFactorAuth.org](https://twofactorauth.org) dostosowanego do krajowej specyfiki. Regularnie pozyskiwane są zmiany z [nadrzędnego repozytorium](https://github.com/ad-m/dwa-skladniki/compare/master...2factorauth:master).

## Cel

Celem jest stworzenie strony zapełniającej obszerny wykaz stron, które wspierają dwuskładnikowe uwierzytelnianie, a także metod, które one wspierają w celu promocji dwuskładnikowego uwierzytelniania. Po pierwsze, poprzez promocję wśród konsumentów witryn internetowych, które wspierają takie formy uwierzytelniania. Po drugie, chcemy wywierać presję na dostawców usług internetowych, aby wdrożyli oni w optymalny sposób bezpieczne formy uwierzytelniania.

## Rozwój

Jeżeli chcesz pomóc wprowadzić zmiany, przeczytaj całe wytyczne w [podręczniku](CONTRIBUTING.md).

## Uruchomienie lokalne

Dwa-skladniki jest zbudowany na [Jekyll](https://jekyllrb.com/) z użyciem gemu [GitHub-pages](https://github.com/github/pages-gem).
W celu uruchomienia storny lokalnie, konieczne jest zainstalowanie ``bundler`` i wszystkich zależności, a następnie użycie Jekyll, aby dostarczać stronę. Jeśli komenda `gem` nie jest dostępna, konieczne jest zainstalowanie Ruby z RubyGems.
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
