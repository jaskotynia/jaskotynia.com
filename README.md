# html-css2 - kurs dla Jasia cześć 2

- docelowy url  https://jaskotynia.com
- Github https://github.com/jaskotynia/jaskotynia.com
- Publiczna tymczasowa https://jaskotynia.github.io/jaskotynia.com/

## 1. narzedzia  

- **https://git-scm.com/** - trzeba zainstalowac- GIT system kontroli kodu zrodlowego

- **https://github.com** - repozytorium kodu i mozliwosc opublikowania strony

  - zalogowanie do github `sign in`
  - stworzenie nowego repozytorium `new` repository
  - klonowanie do komputera 
  - wysylanie do repozytorium
  
```bash
#trzeba uruchamiac w folderze z linii komend cmd 

#klonowanie
git clone adresurl-repozytorium

#zapisywanie pracy 
git commit -m komunikat

#wysylanie do serviera github
git push
```

- **visual studio code**  - program do edycji kodu
  - extension (rozszerzenie) **live server** - mozliwosc podgladu wyniku 


```  
Slownik EN

extension - rozszerzenie
signin - logowanie
create - tworzenie
```

### Visual Studio Code

- `File > New File`   nowy plik
- `File > Save (ctrl+s)` zapisanie pliku

## 2. budowa html  znaczniki `html`,`head`,`title`,`body`  https://www.w3schools.com/html/html_intro.asp

- [x] ZADANIE utworzyc plik **index.html**  z podstawowa struktura strony- strona hello world!
- [x] ZADANIE udostepnienie strony publicznie > https://jaskotynia.github.io/jaskotynia.com/

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>tytul strony</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
	<script src="index.js"></script>
  </body>
</html>
```


## 3. podstawowe znaczniki `div` ,`span`,`h1` , `h2` ,`h3`,`h4`,`p`,`ul`>`li`

- https://www.w3schools.com/html/html_basic.asp 
- https://www.w3schools.com/html/html_elements.asp
- https://www.w3schools.com/tags/tag_ul.asp

## 4. podstawowe znaczniki formatowania `b`,`strong`,`i`,`mark`,`small`,`del`,`ins` - https://www.w3schools.com/html/html_formatting.asp

- [x] ZADANIE eksperymenty z roznymi znacznikami, uzyc kazdego znacznika na stronie, opublikować strone girhub


## 5. linki i obrazki  `a`  , `img` https://www.w3schools.com/html/html_attributes.asp 

- img https://www.w3schools.com/html/html_images.asp
- a https://www.w3schools.com/html/html_links.asp
- [ ] ZADANIE stworzyc strukture strony patrz punkt Struktura strony i nawigacje z pukntu 20
- [x] ZADANIE wkleic obrazek na stronie glownej


## 6. atrybuty

- `class` - `<div class=""></div>`
- `href` - `<a href="">nazwa linku</a>`
- `style` - `<div style=""></div>`
## 7. wyglad elementow atrybut, style ( konfiguracja wygladu) przykłady

 - `background-color:blue` - 
 - `color:red` - kolor tekstu 
 - `font-size:15px` - wielkosci
 - `text-align:left` - wyrownanie

## 8. strona `plan-lekcji.html` znacznik `table` https://www.w3schools.com/html/html_tables.asp

- [x] ZADANIE przeniesc plan lekcji 


## 9. stylowanie atrybut `<style>` https://www.w3schools.com/html/html_css.asp

### 9.1 podstawowe selektory 
   - `.nazwaclass`  
   - `nazwa elementu` np `div {  }`  
### 9.2 podstawowe jednostki 
   - `em` 
   - `px` 
### 9.3 podstawowe style służace do formatowania
   - `border` - brzeg, przykłąd `border: solid 1px red`
   - `padding` -  odstęp, przykład `padding:10px`
   - `margin` - margines, przykład `margin :10px`
   - `width`
   - `height`
   - `float`
   - `line-height`
   - `display`- sposób prezentacji przykłady:
     - `display: inline-block`
     - `display: block`




## 10. Nawigacja strony cz1.

- [ ] framewrok css https://www.w3schools.com/w3css/w3css_downloads.asp
- [ ] dolaczenie do strony stylów, pobranie i dołaczenie zgodnie z przykłądem
- [ ] przygotowanie nawigaji  podobna do  https://www.saradietschy.com/
- [ ] zalaczenie ikon  np do strony o zwierzetach jakies zwierze

- `index.html` strona startowa
- `sprzet.html` :  Sprzęt komputer,kamera, 
- `zwierzeta.html` : Zwierzęta strona ze zdjeciami i video swinkia
- `plan-lekcji.html` Plan lekcji strona z planem lekcji ( cel jest taki zeby sie ladnie drukowala)
- `projekty.html`  gdzie bedziemy umieszczac projekty np ger python
  - `jak-powstala-strona.html`
  - `python-gra1.html`


## 11. video format mp4 - https://www.w3schools.com/html/html5_video.asp

- [ ] ZADANIE nagranie video, na kamerze
- [ ] upload i prosty montaz (kolory) do formatu mp4

### Strona sprzet

- [ ] ZADANIE zobic Zdjecia opisac

## 12. konfiguracja domeny jaskotynia.com

- konfiguracja publikacji github
- obsługa konsoli Amazon Route 53 - https://console.aws.amazon.com/route53
- [ ] ZADANIE zakup domeny

```
Słownik EN

- register - rejestracja
- available - dostepna
- domain - domena np jaskotynia.com
```



