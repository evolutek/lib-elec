# Mais comment c'est-il qu'on fait donc ?
On commence par clone le repo sur sa bécane.
Ensuite faut setup cette lib dans KiCad.

## Ajouter le PATH vers la lib
0. Ouvrir KiCad
1. *Preferences -> Configure Paths...*
2. Cliquer sur "+"
3. Créer la variable LIBELEC et ajouter le PATH (*/ton/path/lib-elec*)
4. Cliquer sur "OK"

## Ajouter les symbols
0. Ouvrir KiCad
1. *Preferences -> Manage Symbol Libraries...*  
1.5. Choisir la config global ou specific à un projet (global dans notre cas)
2. Cliquer sur "Add existing library to table" (bouton dossier)
3. Aller à */ton/path/lib-elec/LibKicad* puis sélectionner les 3 fichiers .kicad_sym (ComponentsEvo, ConnectorsEvo, MarkingEvo) puis cliquer sur "Open"
4. Cliquer sur "OK"

## Ajouter les footprints
0. Ouvrir KiCad
1. *Preferences -> Manage Footprints Libraries...*  
1.5. Choisir la config global ou specific à un projet (global dans notre cas)
2. Cliquer sur "Add Existing" (bouton dossier)
3. Aller à */ton/path/lib-elec/LibKicad* puis sélectionner les 3 dossiers .pretty (ComponentsEvo, ConnectorsEvo, MarkingEvo) puis cliquer sur "Open"
4. Cliquer sur "OK"

✨ *Ta-da* ✨ t'es maintenant apte bg
