# Zadanie2_pfwcho
Zadanie 2 z przedmiotu Programowanie Fullstack w Chmurze Obliczeniowej

Link do aplikacji na AWS:
http://mskrzypczynskizad2-env.eba-mfa7wmmz.us-east-1.elasticbeanstalk.com/

Link do repozytorium dockerhub:
https://hub.docker.com/repository/docker/mikczynski/zadanie2_pfwcho

### CZĘŚĆ OBOWIĄZKOWA

1. Proszę uruchomić przygotowaną aplikację na platformie AWS, usługa EBS. W tym celu należy
wykorzystać przykład przedstawiony na laboratorium nr 3 (pliki: Lab3_AWS.pdf oraz
Lab3_AWS_sources.zip).
Wdrożenie aplikacji ma byż zrealizowane w oparciu o GitHub Action i załączony przykład pliku
konfiguracyjnego, który jest dostępny na moodle w katalogu Zadanie 2 (plik: zad2_GHActions.zip)

1. Utworzono konto na https:/travis-ci.com , połączono je z github, dodano secrets do repozytorium
  ![image](https://user-images.githubusercontent.com/49763989/174075379-9b7633fb-3e86-40d3-a554-8027829569a7.png)

2. Założono konto na AWS
3. Utworzono Aplikację i Środowisko w Elastic Beanstal na AWS
    ![image](https://user-images.githubusercontent.com/49763989/174075645-eab4fef8-b7cf-4972-8fc4-bd54b405e73e.png)

4. Założono użytkownika w IAM 
    ![image](https://user-images.githubusercontent.com/49763989/174075899-f2fdc79d-f352-4223-935d-e2d96725f5e9.png)

5. Został utworzony Bucket w S3
![image](https://user-images.githubusercontent.com/49763989/174076277-fce18802-193e-48c5-878b-a3b2b042a42f.png)

![image](https://user-images.githubusercontent.com/49763989/174076909-1aab76a8-a05e-4678-adb4-d522edf2bd1e.png)

![image](https://user-images.githubusercontent.com/49763989/174086923-9f6f9815-0acf-42b6-9ec4-3a973ad7357d.png)

![image](https://user-images.githubusercontent.com/49763989/174086982-8dd4fc27-cac6-48ef-8d0b-9c4ba1f7cd9b.png)


### CZĘŚĆ DODATKOWA

Zadanie w tej części polega na rozbudowaniu pliku wdrożenia w GitHub Action. W ramach tego rozszerzenia:

- a. GitHub Ations ma zbudować obraz aplikacji i przesłać go na repozytorium DockerHub. Proszę w tym celu wykorzystać wiedzę i konfigurację przygotowaną w ramach zadania nr 1.

Do pliku .yml w katalogu workflows dodano actions pozwalające na autoryzację i przesłanie obrazu do repozytoirum DockerHub.
![image](https://user-images.githubusercontent.com/49763989/174086735-4db665c9-3687-42b4-8f1a-51015323c187.png)

![image](https://user-images.githubusercontent.com/49763989/174086379-fa9933bc-ba10-427b-ab4d-8c9a352efe12.png)
