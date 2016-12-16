# sympassons
banque de sons doux pour mumble (sweety soundpack)

a. Cliquez sur le lien suivant pour télécharger notre banque de sons mumble plus discrets :
sympassons.zip
b. Une fois cette archive zip enregistrée dans votre ordinateur, décompressez-la (ou ouvrez-la pour en verser le contenu dans un dossier que vous conserverez toujours au même endroit pour que Mumble l'y retrouve)
c. Ouvrez Mumble, cliquez sur "Configurer" puis "Paramètres"
d. Dans les paramètres,assurez-vous d'avoir coché la case "Avancé" puis allez au menu "Messages"
e. Là vous pourrez double-cliquer tout à droite sur chaque son (coché) que vous souhaitez remplacer, une fenêtre s'ouvre pour vous permettre de désigner l'emplacement de l'audio correspondant (leurs intitulés sont identiques aux originaux, en anglais).

Voir l'illustration sur la source Wiki : http://wiki.mumble.info/images/8/82/Mumble_configuration_message.png

Unpack the archive somewhere on your system.
Click on "Configure" -> "Settings" or "Mumble" -> "Settings" on Mac OS X.
A new window appears. Make sure that "Advanced" is checked and then click on "Messages".
Now doubleclick those entries in the column "Path" which you want to change.
Enjoy !:)


Pour simplifier les choses aux débutants et paresseux,
sous Debian (donc aussi Ubuntu) vous pouvez vous contenter d'utiliser le script fourni ;)

Il télécharge automatiquement la banque de sons "sympassons.zip"
puis la décompresse dans le dossier ~/config/Mumble/
car c'est là aussi qu'il modifie le fichier de paramétrages audio de l'utilisateur Mumble en y ajoutant juste quelques lignes de texte grâce à la commande suivante :

echo "2\logsound=~/.config/Mumble/CriticalError.wav
5\logsound=~/.config/.config/Mumble/ServerConnected.wav
6\logsound=~/.config/.config/Mumble/ServerDisconnected.wav
9\logsound=~/.config/.config/Mumble/Recording.wav
20\logsound=~/.config/.config/Mumble/TextMessage.wav
3\logsound=~/.config/.config/Mumble/Warning.wav
4\logsound=~/.config/.config/Mumble/Information.wav
7\logsound=~/.config/.config/Mumble/UserJoin.wav
8\logsound=~/.config/.config/Mumble/UserLeave.wav
10\logsound=~/.config/.config/Mumble/YouKicked.wav
11\logsound=~/.config/.config/Mumble/YouKicked.wav
12\logsound=~/.config/.config/Mumble/SelfMute.wav
13\logsound=~/.config/.config/Mumble/OtherSelfMute.wav
14\logsound=~/.config/.config/Mumble/YouMuted.wav
15\logsound=~/.config/.config/Mumble/YouMutedOther.wav
16\logsound=~/.config/.config/Mumble/OtherMutedOther.wav
17\logsound=~/.config/.config/Mumble/ChannelJoin.wav
18\logsound=~/.config/.config/Mumble/ChannelLeave.wav
19\logsound=~/.config/.config/Mumble/Warning.wav" >> ~/.config/Mumble/Mumble.conf

En fin de parcours, les fichiers "sympassons.zip" et le script, devenus inutiles, s'auto-supprimeront.
