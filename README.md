# Converter App

Application Android native développée en Java permettant de convertir :

- les températures entre Celsius et Fahrenheit ;
- les distances entre kilomètres et miles.

L’application utilise des Fragments avec une interface à deux onglets pour une navigation simple et moderne.

---

# Fonctionnalités

## Conversion des températures
- Celsius ➜ Fahrenheit
- Fahrenheit ➜ Celsius

## Conversion des distances
- Kilomètres ➜ Miles
- Miles ➜ Kilomètres

## Interface
- Deux onglets avec Fragments :
  - C ↔ F
  - KM ↔ MILES
- Navigation fluide avec TabLayout et ViewPager2

## Menu d’options
- Option **Quitter** dans le menu

## Confirmation de fermeture
- Confirmation avant fermeture :
  - avec le bouton Retour
  - depuis le menu Quitter

---

# Technologies utilisées

- Java
- Android Studio
- XML
- Fragments
- ViewPager2
- TabLayout
- Material Design

---

# Structure du projet

```text
ConverterApp/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/converterapp/
│   │   │   │   ├── MainActivity.java
│   │   │   │   ├── TemperatureFragment.java
│   │   │   │   ├── DistanceFragment.java
│   │   │   │   ├── ViewPagerAdapter.java
│   │   │   │
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   ├── fragment_temperature.xml
│   │   │   │   │   ├── fragment_distance.xml
│   │   │   │   │
│   │   │   │   ├── menu/
│   │   │   │   │   ├── main_menu.xml
