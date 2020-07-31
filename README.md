# Créer un bot discord

Pour créer un bot discord, il faudras commencer par aller sur https://discord.com/developers/applications et créer une "Nouvelle Application".
Ensuite, allez dans "BOT" et "Build Bot". Et pour inviter votre bot dans votre serveur discord, allez dans https://discord.com/developers/applications/738304437151596554/oauth2 et cochez "boot" et "administrateur" puis rendez-vous sur le site.

Après avoir installer discord.py et python, allez dans votre éditeur de code  ( PyCharm est le plus adapté ) et écrivez :

import discord \n
import discord.ext from commands

Ce code permet d'importer les librairies.
Pour créer le bot, saisissez :

bot = commands.Bot(command_prefix"!")

Le prefix du bot est changable bien sûr !
Enfin pour lancer le bot sur discord, il vous suffit d'écrire :

bot.run("votre tocken")

Pour récupérer votre tocken, allez dans l'espace développeur de discord ( https://discord.com/developers/applications/738304437151596554/bot ) et copier votre "tocken".
Votre bot est en ligne !

