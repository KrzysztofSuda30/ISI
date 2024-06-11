odcinek 2:

uruchomienie nowego kontenera:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/df96cf8d-16b3-4e04-b2be-33634c1e4d28)

Wyświetlenie wersji jądra systemowego: 
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/b88cc0a0-5d10-4525-8424-b78f80e35903)

Wnętrze kontenera:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/dc155c2e-2e37-4322-ad19-72fd421760a1)

Tworzenie nowego pliku oraz wyświetlenie jego zawartości:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d73d6998-07f6-47ba-9dd5-8e515703b04f)

Wyświetlenie wszystkich posiadanych kontenerów:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/8895acf3-627b-4132-8fcf-e1c6fc7f04cc)
Przy samym docker container ls wyświetlają się tylko te które obecnie działają
docker ps(wyświetla procesy) działa dokładnie jak docker ls

Uruchamianie kontenerów:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/4ae04683-6789-48b7-af6d-2d190bd36e35)

Wykonywanie poleceń wewnątrz kontenera(np odczytywanie pliku):
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/8b297792-6a75-4b97-b892-a3e2e26929bf)

odcinek3
struktura działania obrazu z kontenerem(w kontenerze):
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/12dbae13-acdd-4d37-bf16-883d1704493a)

Tworzenie obrazu na podstawie zawartości konntenera:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a88a7350-f5f2-4cc1-b865-37f7be138674)

Wyświetlenie wszystkich obrazów w systemie:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/addd2f3a-7618-4eaf-bc27-183343c23fc5)

Wyświetlenie wszystkich warstw obrazu:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/22c0754d-c7fb-47eb-8d73-2bad8907c114)

Wyświetlenie warstw ubuntu:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d4f7f203-cb1b-4ffb-b480-842718a9a2bf)

Tworzenie kontenera na bazie obrazu:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/027f2208-53d2-4c96-a6be-642efe51e166)

Instalacja programów w kontenerze:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/55cd30d5-2b01-46cc-b114-6872708b851d)

Tworzenie obrazu z obrazu z dodatkiem instalacji: 
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0388b24e-6f52-46e5-bab0-0026c8349241)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/71db92df-b0c7-402e-8e8d-5759b1186403)

Odcinek4:

DockerHub
pobiera automatycznie obrazy z dockerhub, jeśli próbujemy uruchomić kontener który u nas nie istnieje
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/c89720d3-441d-43f5-8e80-e103e221520e)

Zmiana nazwy obrazu:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/48ce1a1b-f10d-4375-b4c8-390866d97381)

Wgrywanie obrazów na dockerhub(wymaga bycia zalogowanym):
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/54c5b983-ab48-41ab-a22f-c34736a31e35)

Odcinek5:

Kopiowanie z kontenerów do pc i z pc do kontenera:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/7908c121-1ed8-495a-bfa8-42661ad26ae5)

Do kontenera:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f152839b-ac62-401b-9b58-9fba47f7ffcd)

Odcinek6:

Pierwsze dockerfile:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/65989b52-0af0-4f40-9dc9-0c251ba1d0f2)

Docker build:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/3cdfc023-83d2-4916-a4bd-c6212c6a6643)

Sprawdzenie czy docker build zadziałał:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f5bb218c-c955-454d-bdcc-f0307285d762)

Odcinek7:

Dodawanie nazw:
Przy użyciu ---tag
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/820f4da7-050d-4900-8f54-c29383c9e139)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d79e9b8e-a650-42ce-b34e-3538519b73e1)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f0200ba4-573f-4c25-89bf-ca0659cd77e1)

Odcinek8:

Budowaniu przy użyciu Dockerfile z innego folderu
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/8b28061c-5832-4c47-b6b1-5cd8f29a9311)

Można wykożystywać tylko pliki z tego samego katalogu albo niższych w Dockerfile
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a21a42ec-3b0d-4dff-be7a-349c8c46e995)
Budując można wybraać dowolny Dockerfile używając --file "katalog w którym jest Dockerfile"


Odcinek9:

Dodawanie aplikacji do kontenera:
Budowanie dockerfile do aplikacji:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/45fb8eca-1393-4c79-a67a-71d7f06d6512)

Następnie docker build:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ae3e517c-966d-4b7f-bac5-344273f94d3f)

Uruchomienie aplikacji mając jej obraz:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/e60c6e8f-5b99-4714-bbb9-d365831ebd5c)

Zmiana na aplikacje webową:
Zmiana w dockerfile:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/b3c13f61-9f9e-4129-ab92-6cbe28eac0b5)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/553c8abd-2a0e-4efb-855c-a23ac4be0318)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/6cd2625e-a277-4a45-8a39-63ed3d91740f)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/8b184aba-336b-44cb-9aac-3533949c7915)

Dzięki docker publish jesteśmy w stanie podłączyć się do aplikacji webowej działającej na kontenerze:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/70a4f77b-49d6-4e89-af7e-343517d9ed29)

Dzięki takiemu poleceniu jesteśmy w stanie użyć wybranego przez nas portu:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d622f8c8-d729-44da-ba60-e0aeb1cacd7f)
W powyższym wypadku aplikacja działać będzie na porcie 5123

Odcinek10:

Różnica między copy i add
ADD działa jak copy, z tą różnicą że ADD może pobierać pliki z internetu za pośrednictwem URL. Można również w poleceniu ADD użyć plik tarowy
Copy używa tylko plików lokalnych
Polecenie WORKDIR -tworzy katalog jeśli nie istnieje, oraz ustawi katalog jako domyślny dla wszystkich następnych poleceń
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/aa15e55e-6191-445e-af75-e8daf439134f)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/3a00d39e-d510-4ef9-8554-491f0b100d3f)

Odcinek11:

Polecenie CMD w dockerfile automatycznie uruchamia polecenie w cmd, można zrobić również listę, za pośrednictwem której można uruchomić pojedyńczy program.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a561e7cb-4132-4a5e-adc9-ae222238860c)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/419b43cf-3fde-41ab-aad0-da33e786e2e5)

Użycie entrypoint:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/e64bedb0-50a4-4831-8d24-1124d9d11cc2)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/b561c602-1bd5-4ffb-a1ee-e4a0ccac8634)
W tym wypadku użycie /nazwa na końcu zostaje uznane jako dodatkowy parametr, podczas gdy w cmd tak nie działało

Jeli doda się cmd przed entrypoint , zostanie on wykorzystany jako domyślny parametr: 
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/90d91cc8-28e1-4d48-9718-978e86883ccd)

Jednak dodanie w konsoli ręcznie dodatkowego parametru nadpisuje polecenie cmd :
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/84687969-eaab-4ffd-8a6a-c824666a3ccf)

Odcinek12:

W kontenerze dane można zapisać w formie obrazu lub w VOLUMES
Dzielą się one na: 
Zarządzane przez dockera
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/246128d3-c13c-4996-88eb-62eecea9b925)

Pokazywanie wszystkich volumes:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/2c88f5f5-8e84-4ac0-a111-3e909280c5a4)

Kasowanie: 
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/875bf462-dfc9-40e3-ac7d-1fe63b0b16ac)

Testowanie Volumes:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/c9a0148e-4d78-4a97-8b10-fa779ad4296f)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/48b1fa0b-3191-48e4-8830-2293490532e2)

jak widzimy, rzy każdym odpaleniu file.txt postaje na nowo
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/7cc50485-1c40-48f0-81ed-0f62322e6059)
Przy użyciu volumes dane zostają zachowane nie tak jak poprzednio

Nawet po usunięciu kontenerów na których działał volumes: 
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a355ce5d-f9bb-470b-b404-d3e84565c3db)

Volumes nadal działa, i przechowuje dane: 
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/c47db878-176f-49bf-84aa-6e98c4d55628)

Można stworzyć volumes aby zrobić backup:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ee296987-5f9c-48de-b088-ac4328f36723)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/10457447-b918-41a7-b863-15028b8fcd33)

Podpinanie katalogu pod volumes:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/b83bf2b1-0744-4128-98fb-a8f1db7b7250)

przed:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/3fbbf972-de5a-436a-8bce-b6e80e68d8e9)

po:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/65e06346-62f0-4257-839f-01329f1d8dc2)

Odcinek13:

Użycie zmiennych środowiskowych:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/1f2d71c6-7e3e-4bf9-9110-a125a76db20d)

Można dodać dodatkową zmienną w następujący sposób:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/92f2d4f3-f8d6-4107-8db2-31852c870438)

Użycie postgres:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/5a7d7aed-577f-44f5-92e7-55d70b1ff457)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ba9da369-d968-4b5d-ab01-187aa195f18d)

Stworzenie katalogu zapisującego baze:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/e0fad077-7767-4f22-be21-c9f490179848)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/1d9353dc-f8b1-4f5d-b85a-fe1bcbb6f333)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a682d93c-4ca7-4dca-8be0-31baddf3b524)

Uruchomienie bazy danych webowe:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/fe491a98-01e5-4475-ac57-d23298c143db)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f2400c1d-54d7-4a5d-8580-84de961c4430)


Odcinek14:

Docker inspect:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/29582075-19bd-41f5-ad31-fc40d7833993)

Pokazuje najważniejsze informacje o kontenerze:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/35543d35-32bc-4e1c-9127-85eb49984da1)

Odcinek15:

Wypisywanie sieci:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/63bc4e37-faf4-4b71-9159-4acde7ee2413)

Uruchomienie dwóch kontenerów:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/53a2a283-d7b9-48ff-b0ca-6e9ec62310cc)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/4373b294-45d6-401b-9183-9ad0fe52ccbf)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d8ea2b9f-4417-4f39-b1f7-f5ff9508a155)

Kontenery zostały domyślnie podłączone:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0d0293a9-6590-4733-a5ec-839bf988beb8)

Sprawdzenie czy internet działa w kontenerach:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/84c87f8c-b85d-4bb4-9e1e-914ecf38f824)
działają pingi, lecz kontenery nie mogą pingować się nawzajem

Tworzenie własnej sieci:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/1282888f-81c3-4f3f-b13e-238dfa99351f)

Podłączenie do sieci:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/31c80e4e-01aa-4a67-86a4-ddcc3dfce7f3)
Po podłączeniu obu kontenerów do sieci własnej mogą one pingować sie wzajemnie


Odcinek17:

Docker-compose:
Tworzenie pliku compose:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0831ec6b-44c2-4ca5-b1ae-6db6546ed4ef)
Uruchomienie:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f84ad5b6-f58a-4030-a83a-e60d1cf42771)


Odcinek18:

Wyłączanie docker compose:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/80ed7b09-4ef3-44a0-8284-10e9d5fc8845)

Tworzenie aplikacji django:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d319bdc9-74f8-4166-b6ae-cf693479ab38)

Aktualizacja compose pliku:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a9f74bdb-f50d-4d65-9a0b-2c0446957749)

Po przebudowaniu podstawowej aplikacji uruchamiamy docker-compose:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/244aea17-f9c2-4256-9dae-dbbf5753948a)


Odcinek19:

Dodanie nginx do pliku compose:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ed1a87a9-8f69-4a67-90d4-e0c9e3167c45)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f2b13767-1560-4bfb-b42c-b57b04e75a4f)

Konfiguracja nginx
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/21a58629-c672-4f0e-bc80-e5a452f2e3ff)

Uruchomienie compose:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/6dfd9757-781b-41bc-80b6-6f42d5e1f42f)


Odcinek20:

Tworzymy pustą aplikację reactową: 
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0836947b-cf61-4342-9797-bed567010872)

Tworzymy dockerfile:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/17cc4d84-aef5-457c-a521-e8b123b39476)

Uruchomienie docker run:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/eb3082f8-e6f9-4d04-958b-b6394e853230)

Odcinek21:

Tworzenie prostej aplikacji C:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d6a93476-ee55-4133-be3f-eb7bcfc8b77f)

Tworzenie dockerfile:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/448472a6-b458-4bda-8dce-c57d324bbe63)

Uruchomienie:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/55de7d50-8514-4a43-b2e5-2a6bf4601f7c)

Odcinek22:

Porady jak tworzyć obrazy, kontenery oraz Dockerfile w tym łączenie poleceń aby uwydajnić kod.
