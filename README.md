# Pokemon-GO-Personal-Database
Database of your Pokemon collection
The database is made using SQLite3.

The goal of this projects is to create database template of Pokemon caught in Pokemon GO for player's personal use, holding all Pokemon's data that may be important for the player.

Structure:
The database contains several tables.
First of all is "pokemon" table which holds data about each individual Pokemon the user puts in there. The data it contains is only what's exclusive for the certain Pokemon, like its nickname, combat power, individual values, moves, place of getting caught, tags etc.
Information that's common for whole species is held in "pokedex" table, that would be things like the species name, type(s), base stats, Pokedex number etc.
There are also tables holding information about moves (seprate "fast moves" and "charge moves"), for types (named "types", obviously) to hold data about which is weak or super effective against which and last there's "player" table for data like player's name, team or level.

Purpose:
Main purpose is to allow Pokemon GO players to keep list of their caught Pokemons for sorting and filtering though any criteria they wish, most of all ones that the game don't allow. In Pokemon GO you can sort and filter your monsters by their Pokedex number, name, combat power, type and many other traits, but the game lacks consideration of things like place of catching or individual values. Such values may be important for sentimental reasons (keeping a Pokemon as a souvenir from a certain place or event) but also practical, like knowing the potential of Pokemon's individial values or how many points and candies calculated from the distance compared to another Pokemon it will give through trade.
Such problems might be also dealt with by tagging system. The game only allows tagging Pokemon with a star as favourite (which puts them on top of list if it's sorted by that and keeps them safe from accidental transferring or trading) but it could use something more, like tagging as assigned for trade, of sentimental value but currently useless in game or caught in foreign country. As for now it could be dealth with by giving descriptive nicknames or prefixes, but that's limited by name length and to only one prefix per Pokemon.

Usage:
This database structure has not been used in any application yet and there are no such plans so far.
There's no plan if and how it would interact with Pokemon GO app.
So far there's only plan to write methods for adding Pokemons to list in Java.
In conclusion, this structure is open for ideas on how to apply it for practical use. Feel free to share if you have any!

CURRENT STATUS:
Working on database's basic tables and fields, holding data from the game.
