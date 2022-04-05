# Obecny stan polskich odcinków anime
Większość osób ogląda odcinki anime wrzucane na serwisy hostingowe przez różnorodne grupy tworzące fanowskie napisy anime.

Najpopularniejszym i najczęściej wykorzystywanym serwisem jest CDA. Jest prostym wyborem ze wględu na łatwość wrzucania odcinków oraz brak limitów, lecz szczególną wadą tego serwisu jest obniżona jakość wideo.

![image](https://user-images.githubusercontent.com/43544435/159976188-cf9f5579-f2fa-4d37-b69e-e3a005e0cd8b.png)
> Lewo: Odcinek na CDA
> Środek: Odcinek z blu-ray reenkodowany do HEVC
> Prawo: Ten sam odcinek co na CDA ale wrzucony na MEGA

Kolejną ważną rzeczą do uwzględnienia jest to, że odcinki wrzucane na serwisy hostingowe muszą przejść proces hardsubbingu (proces polegający na wyrenderowaniu sciężki napisów wprost do sciężki wideo). 

Taki proces wymaga ponownego enkodowania powodując straty w jakości.

Zaletą takiego procesu jest to, że napisy będą zawsze i wszędzie działać niezależnie od odtwarzacza, ale wadą jest to, że nie można wyłączyć napisów ani ich zmienić.

# Jak oglądać odcinki anime w wysokiej jakości?

Niestety będzie trzeba wtedy zrezygnować z polskich napisów. Chociaż niektóre grupy fansubowe wrzucają swoje napisy na http://animesub.info/, napotkałem się na dużą ilość failsubbingu - czyli niepoprawnego, nie mającego sensu tłumaczenia, głupie wstawki tłumaczów oraz niepasujące linie z nawiązaniami do polskiej kultury. Kolejnym problemem jest to, że zazwyczaj te napisy mają synchronizacje do tylko jednej wersji odcinka, trzeba pobrać odpowiedni odcinek by napisy pokrywały się scieżką dzwiękową.

# Skąd brać odcinki?

Rekomendowanym sposobem na pozyskiwanie odcinków jest strona https://nyaa.si/ - to największy tracker torrentów z odcinkami anime. Żeby móc pobrać odcinki anime trzeba mieć zainstalowany klient torrentów.

![image](https://user-images.githubusercontent.com/43544435/161136464-c1ad29bc-bd81-417f-88d6-9c7d133442b4.png)


### Zalecany klient torrentów - [qBittorrent](https://www.qbittorrent.org/download.php)

![image](https://user-images.githubusercontent.com/43544435/161136221-e44d309d-d7fd-4d02-9a24-6bb539b82dcc.png)


Jest to darmowy, otwartoźródłowy - nieposiadający żadnych reklam klient torrentów. Jest najlepszą alternatywą dla klienta uTorrent. Odradzam używanie uTorrent, jest to adware oraz płatne oprogramowanie wzbudzające wiele kontrowersji.

### Jak wyszukiwać odcinki oraz jakie pobierać?

Rekomendowanym sposobem jest wyszukiwanie poprzez wyszukiwarke: 

![image](https://user-images.githubusercontent.com/43544435/161136567-1449a2a3-9792-4a58-a3f1-4bb33b390014.png)
> [Tytył anime po angielsku] BD HEVC

BD oznacza wydanie blu-ray, a HEVC to kodek cechujący się wspaniałą kompresją wideo z zachowaniem wysokiej jakości. Takie wydania zapewniają najwyższą jakość z najmniejszym rozmiarem pliku.

![image](https://user-images.githubusercontent.com/43544435/161138947-6e233617-80a5-4e7f-81d8-ce8966bcf680.png)

Wybór torrenta należy rozważyć poprzez liczbę seedów oraz komentarze.

W przypadku gdy seria nie doczekała się jeszcze wydania blu-ray, trzeba skorzystać z web-ripów. Web-ripy dostępne są zazwyczaj w kodeku x264, który zajmuje sporo miejsca na dysku, najpopularniejszą grupą web-ripującą jest [Subsplease](https://subsplease.org/). Jeżeli wielkość pliku jest zbyt duża, niektóre grupy reenkodują odcinki w HEVC.

# Jak oglądać odcinki?

Zalecanym odtwarzaczem jest [mpv](https://mpv.io/) - jest to prosty, ale bardzo wydajny odtwarzacz multimedialny z szeroką możliwością konfiguracji. 

![image](https://user-images.githubusercontent.com/43544435/161136682-85823805-48fc-49f9-b544-b30c242718a0.png)

Dostępna jest konfiguracja specjalnie stworzona do oglądania anime: https://github.com/Tsubajashi/mpv-settings
Jest także łatwiejsza wersja tego odtwarzacza z dodanym dodatkowym interfejsem użytkownika [mpv.net](https://mpv-net.github.io/mpv.net-web-site/)

Jeżeli mpv jest dla ciebie za trudnym w obsłudze odtwarzaczem, można skorzystać z [VLC](https://www.videolan.org/vlc/) który jest bardziej rozbudowany lecz posiada niższej jakości dekoder.

![image](https://user-images.githubusercontent.com/43544435/161136709-c2f0d2d4-ecea-45b0-87d1-93a8fc2d76be.png)

# Zalecana lista anime
Podczas oglądania dużej ilości anime, warto posiadać swoją własną listę anime w celu zaznaczania obejrzanych anime, planowanych oraz dzielenia się nią z innymi.

Zalecane listy anime to [Lista MAL](https://myanimelist.net) 

![image](https://user-images.githubusercontent.com/43544435/161136790-0a01b29b-1ab9-4dd2-a731-8e6c375c1af6.png)

oraz [Lista Anilist](https://anilist.co). 

![image](https://user-images.githubusercontent.com/43544435/161137150-40444bf4-8e86-411f-b9d7-8504a648d766.png)

Oba serwisy zawierają doskonałą bazę anime, w łatwy sposób można wyszukać dowolne anime oraż znależć odpowiednie dla siebie według gatunków i tagów.

Jeżeli posiadasz listę anime na shinden, zalecam przenieś ją na dowolny z tych serwisów. Napisałem program który ułatwia ten proces tworząc gotowy plik z listą anime którą można zaimportować do tych serwisów [ShindenToAnilist](https://github.com/Kacper-Kondracki/ShindenToAnilist)

# Pomocnicze oprogramowanie

### [Taiga](https://taiga.moe/) - oprogramowanie do przeglądania listy anime oraz automatycznego jej aktualizowania

![image](https://user-images.githubusercontent.com/43544435/161137776-4219fde2-a00c-4ce3-b7d1-73debc425875.png)

Taiga pozwala połączyć się z listą MAL albo Anilist. Program wykrywa to, gdy oglądamy anime za pomocą odtwarzacza multimedialnego i automatycznie aktualizuje listę.
Zawiera także wbudowaną przeglądarke torrentów oraz powiadamia o nowych odcinkach do pobrania.
