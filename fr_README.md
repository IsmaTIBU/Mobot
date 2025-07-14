# MoBot - Robot Mobile
### *Pour un aperçu plus complet de mon travail, visitez mon portfolio sur [imonge.es](https://imonge.es/proyecto/3?lang=fr).*
>**Remarque**: Le seul programme qui peut être testé sans ce matériel est le programme de reconnaissance d'image "balltracking.py" qui suit les balles colorées, et qui utilisera la caméra par défaut d'un ordinateur. Selon la caméra utilisée, les résultats peuvent varier. Ce programme est destiné à être utilisé avec une Picamera2. Il fonctionne également bien avec la caméra du portable Acer de mon collègue.

## Aperçu
L'objectif de ce projet est que le robot devienne entièrement autonome en lui permettant de recevoir des instructions verbales de l'utilisateur pour les exécuter lorsqu'elles sont envoyées. Pour cela, nous avons utilisé le programme MoBotSim qui traite les commandes verbales sous forme de texte et les modifie pour qu'elles puissent être envoyées via communication série au robot. De plus, pour l'analyse des mots, nous avons dû utiliser WhisperAI en python et le lier avec le programme précédent.
### Fonctionnalités Principales
MoBot offre trois fonctionnalités principales :
1. **Traitement d'image de flux vidéo en temps réel**
   - Suit une balle dans le flux vidéo en temps réel et détecte sa couleur :
2. **Interprétation de Commandes Vocales**
   - Interprète les commandes vocales de l'utilisateur grâce à une IA et utilise cette transcription textuelle pour déduire les actions correspondantes à effectuer par le robot.
      -  Langues : Français
3. **Mouvement du Robot**
   - Code situé dans l'Arduino capable de lier différentes instructions avec les mouvements devant être exécutés par le robot
---
## Quelques résultats illustrés par vidéo
1. **Traitement d'image de flux vidéo en temps réel** :  
Ici nous faisions quelques tests sur la façon dont la caméra du robot détecterait la balle et si elle la détecterait correctement. Vous pouvez voir une traînée rouge chaque fois que nous bougeons la balle, suivant son centre.
[Regarder la vidéo](https://github.com/user-attachments/assets/0bd85940-c4d1-4439-9bbd-5f775ef4f498)
2. **Interprétation de Commandes Vocales** :  
Dans cette vidéo, nous voulions principalement démontrer que même si l'utilisateur demande au robot d'effectuer des tâches impossibles dans certains scénarios, il est capable de toujours garder à l'esprit que son intégrité passe en premier et activera un protocole d'évitement d'obstacles. Cependant, de cette façon, vous pouvez également voir comment fonctionne l'interprétation des commandes vocales.
[Regarder la vidéo](https://github.com/IsmaTIBU/Mobot/blob/main/Video_MoBot_2.mov)
3. **Scan autonome du robot** :  
L'objectif du robot dans cette tâche est de scanner une pièce sans s'écraser contre les murs.
[Regarder la vidéo](https://github.com/user-attachments/assets/4f919ec4-3920-405f-a559-740e681eeb6c)
