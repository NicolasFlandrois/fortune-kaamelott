# fortune-kaamelott
[French] Compilation of the best quotes from 'Kaamelott' TV Show ( (c) Alexandre Astier), seet up to use in fortune-mod

==========================

This small project sets to customize a quotes database for the application [fortune-mod (cf wikipage)](https://en.wikipedia.org/wiki/Fortune_%28Unix%29), providing fortune cookies on demand.
Fortune program returns a random quote from a given database, and allows its users to add up new database.

Therefore, I decided to create my own database, with the best 120 quotes from the french comedy TV show "Kaamelott" [(French Wiki page)](https://fr.wikipedia.org/wiki/Kaamelott) [(English Wiki page)](https://en.wikipedia.org/wiki/Kaamelott),  wrote by Alexandre Astier [En wiki](https://en.wikipedia.org/wiki/Alexandre_Astier) [Fr wiki](https://fr.wikipedia.org/wiki/Alexandre_Astier).

-------------------------
## ***Copyghts Diclaimer:***
This project is under MIT Licencing 2020. Non Profits.
This project is intended for personal uses, and shall not be taken responcible for other users use or misbehavior.
This project intend to respect the legal copyrights owners of ***Kaamelott***, and enforce such rights, if need be.
I will delete this project if the copyright's owner, Mr A. Astier, demands so.

==========================
# Installation

1. Clone this repository.
    `git clone https://github.com/NicolasFlandrois/fortunes-kaamelott.git`

2. Paste this 2 files (*kaamelott* and *kaamelott.dat*) in following fortunes directory (Unix/Linux files system here):
    `/usr/share/games/fortunes`

3. Run your fortune application with Kaamelott
    `fortune kaamelott`

============================
# How to customize your own database

1. Create (or modify) your file. a simple file, with or without .txt extension.
    (Unix/Linux)
    `touch my_kaamelott_quotes`

2. Edit this file with your new quotes. Use the text editeur of your choice. Each quotes must be contained in between 2 % symboles.
    %
    PAYS DE GALLE INDÉPENDAAAAAAAAAAAAAAAAAAAANT.

    [ Perceval - Kaamelott - Écrit par: Alexandre Astier ]
    %
    Faut pas respirer la compote, ça fait tousser.

    [ Kadoc - Kaamelott - Écrit par: Alexandre Astier ]
    %
    ...etc

3. Save the edited file.

4. Transform your file into a .dat file
    (Unix/Linux)
    `strfile my_kaamelott_quotes`
    The output file will be *my_kaamelott_quotes.dat*

5. Then repeate steps in installation section.
