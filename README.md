# synchronizeTasks
   +-----------------------+           +----------------------+
   |                       |           |                      |
   |    Google Tasks       | <-------> |   Google Sheets     |
   |                       |           |                      |
   +-----------------------+           +----------------------+
            ^                                   ^
            |                                   |
            |                                   |
            +-----------------------------------+
                     Synchronisation des tâches
### Function Description (English):

The provided function `synchronizeTasks` is designed to synchronize tasks between Google Tasks and a Google Sheets document. It's particularly useful when you want to manage tasks in both platforms simultaneously. 

#### Features:
- **Bidirectional Sync:** It synchronizes tasks in both directions, from Google Tasks to Google Sheets and vice versa.
- **Task Updates:** It updates tasks in Google Tasks if they are modified in the Google Sheets document.
- **New Task Creation:** If new tasks are added to the Google Sheets document, they are created in Google Tasks.
- **Task Deletion:** If tasks are deleted in the Google Sheets document, they are removed from Google Tasks accordingly.
- **Flexible Date and Time Handling:** It supports due dates and times for tasks, ensuring proper synchronization.

### Description de la fonction (Français):

La fonction fournie `synchronizeTasks` est conçue pour synchroniser les tâches entre Google Tasks et un document Google Sheets. Elle est particulièrement utile lorsque vous souhaitez gérer les tâches sur les deux plates-formes simultanément.

#### Caractéristiques :
- **Synchronisation bidirectionnelle :** Elle synchronise les tâches dans les deux sens, de Google Tasks vers Google Sheets et vice versa.
- **Mise à jour des tâches :** Elle met à jour les tâches dans Google Tasks si elles sont modifiées dans le document Google Sheets.
- **Création de nouvelles tâches :** Si de nouvelles tâches sont ajoutées au document Google Sheets, elles sont créées dans Google Tasks.
- **Suppression des tâches :** Si des tâches sont supprimées dans le document Google Sheets, elles sont également supprimées de Google Tasks.
- **Gestion flexible des dates et heures :** Elle prend en charge les dates et heures d'échéance des tâches, assurant une synchronisation adéquate.

- Sure, here's a guide to accompany the code for installing the Google Apps Script function:

### Installation Guide (English):

#### Prerequisites:
1. Google Account
2. Google Sheets document
3. Google Tasks enabled in Google Workspace (formerly G Suite)

#### Steps to Install:

1. Open your Google Sheets document.
2. Go to "Extensions" in the top menu.
3. Select "Apps Script".
4. Delete any code in the script editor and replace it with the provided script.
5. Before running the script, activate the Google Tasks service:
   - Click on the menu item "Resources" and then select "Advanced Google services...".
   - In the dialog that appears, locate "Tasks API" and click the corresponding toggle switch to turn it on.
6. Save the script with a name, for example, "SynchronizeTasks".
7. Close the script editor.

#### How to Use:
1. In your Google Sheets document, go to the menu and find the newly added menu option (likely named after the script you saved).
2. Select the menu option to run the script.
3. The script will synchronize tasks between your Google Tasks and Google Sheets, updating, creating, or deleting tasks as necessary.

### Guide d'installation (Français) :

#### Prérequis :
1. Compte Google
2. Document Google Sheets
3. Google Tasks activé dans Google Workspace (anciennement G Suite)

#### Étapes d'installation :

1. Ouvrez votre document Google Sheets.
2. Allez dans "Extensions" dans le menu supérieur.
3. Sélectionnez "Apps Script".
4. Supprimez tout code dans l'éditeur de script et remplacez-le par le script fourni.
5. Avant d'exécuter le script, activez le service Google Tasks :
   - Cliquez sur l'élément de menu "Ressources" puis sélectionnez "Services Google avancés...".
   - Dans la boîte de dialogue qui apparaît, localisez "API Tasks" et cliquez sur l'interrupteur correspondant pour l'activer.
6. Enregistrez le script avec un nom, par exemple, "SynchronizeTasks".
7. Fermez l'éditeur de script.

#### Comment utiliser :
1. Dans votre document Google Sheets, allez dans le menu et trouvez l'option de menu nouvellement ajoutée (probablement nommée d'après le script que vous avez enregistré).
2. Sélectionnez l'option de menu pour exécuter le script.
3. Le script synchronisera les tâches entre vos tâches Google et Google Sheets, mettant à jour, créant ou supprimant les tâches selon les besoins.

N'oubliez pas d'activer le service Google Tasks avant d'exécuter le script pour vous assurer que la synchronisation fonctionne correctement.
