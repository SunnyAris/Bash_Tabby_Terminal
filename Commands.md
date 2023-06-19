`pwd`- wskazanie mojej aktualnej ścieżki gdzie jestem 

`cd` - wędrowanie po plikach 
np. `cd home` - zabiera mnie do pliku home 

`tab` - uzupełnia nazwę jak nie wiemy co wpisać 

`touch` - tworzy plik np `touch x.txt` lub `touch .x.txt` 

`mkdir dokumenty` - tworzy folder dokumenty 

`cd dokumenty` wchodzi do folderu dokumenty 


`ls -al `
listowanie plikow w katalogu
 

`cd .. `
powrót do poprzednego katalogu 

`cd path/to/directory`
przejscie do innego katalogu - tutaj przyklad `path/to/directory`
 

`mv` cos gdzies
przenoszenie pliku


zmiana nazwy to też mv 
np. 
mv .x.txt x.txt 

zmieniło nazwę i odkryło ukryty plik tu już nie ma kropki 
przenosi w to samo miejsce zmieniając nazwę i rozszerzenie np z txt na jpg jeśli potrzeba 



`cp cos gdzies`
kopiowanie pliku
jeśli w tym samym folderze cp nazwa pliku nazwa pliku po zmianie

`cp nazwa pliku  ~/dokumenty` czyli nazwa folderu do którego ma przenieść 


`cp *.txt cukier/ `  przenosi wszystkie txt do folderu 



`touch plik.txt`
tworzenie pliku


`mkdir nazwa_folderu`
tworzenie folderu


`rm  usuwa plik  rm -rf cos `
usuwanie plikow/folderow 


### opcja `-r` rekurencja : kasowanie plikow oraz pliki ktore sa w srodku `-f` force wymuszenie kasowania



`less plik.txt`
czytanie/ otwarcie pliku calego


`tail plik.txt`
przejście do zawartości pliku koncowki pliku


`head plik.txt`
poczatku pliku



`cat plik.txt`
### wywalenie calej zawartosci plikow do terminala - moze powodowac crashe systemu jezeli plik jest duzy - lepiej uzywac less



`ource .bashrc`
przeladowanie pliku konfiguracyjnego


`history`
sprawdzenie histori komend



`pwgen -s 32`
tworzy randomowe "haslo" tutaj skladajace sie z 32 znakow




`sudo -i`
sudo zrob cos jako root // sudo -i przeloguj sie jako root



`apt`
w Ubuntu instalacja paczek/aplikacji/narzedzi




`grep -i x plik.txt `
wyszukaj slowa `x` w `plik.txt` opcja `-i` sprawia ze szuka konkretne slowo nie zaleznie od wielkosci liter uzyte w pliku


`history | grep mv  `
wyszukuje w historii polecenia z małym mv jak wpisze duże MV wyszuka duże jak wpiszę history | grep -i mv pokaże wszystkie 



`man ls` instrukcja 
 man mv itd.



`diff nazwa pliku nazwa pliku `
pokazuje różnicę mniędzy plikami 


l`s -al nazwafoldru/` sprawdza zawartość jakiegoś folderu w którym się nie jest 


`np. cat .bash `- wyświetla zawartość pliku 
.bash - ukryty plik kropka przed nazwą oznacza ukryty plik 

`ctrl d `- wylogowanie 

`ctrl c `ubija proces 


`cd .. `cofnij się 

`cd - `cofa do poprzedniego katalogu z którego wyszliśmy
