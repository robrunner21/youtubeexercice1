# youtubeexercice1

Bienvenue sur l'exercice 1 de la chaine de rob_runner

## Résumé

Cette exercice est un challenge donné par rob_runner suite aux différents tutoriel qu'il a fait sur sa chaine.

Le but est de faire un site en prennant exemple sur le site de groupie tracker réalisé par rob_runner et deux de ses acolites durant un cours.

Toute les ressources nécessaire sont dessous.

## Les JSON

Voici le lien du JSON qui vous sera necessaire à créer votre page (La partie artiste): https://groupietrackers.herokuapp.com/api/artists

Ce JSON est tiré de cette API: https://groupietrackers.herokuapp.com/api/

## Les SVG

Le display en liste:
```svg
<svg width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="0.5" y="0.5" width="47" height="47" rx="9.5" fill="#C4C4C4" fill-opacity="0.23" stroke="#B1B1B1"/>
<rect x="9" y="9" width="30" height="2" rx="0.5" fill="#2D2B3D"/>
<rect x="9" y="16" width="30" height="2" rx="0.5" fill="#2D2B3D"/>
<rect x="9" y="23" width="30" height="2" rx="0.5" fill="#2D2B3D"/>
<rect x="9" y="30" width="30" height="2" rx="0.5" fill="#2D2B3D"/>
<rect x="9" y="37" width="30" height="2" rx="0.5" fill="#2D2B3D"/>
</svg>
```

Le display en bulles:
```svg
<svg width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="0.5" y="0.5" width="47" height="47" rx="9.5" fill="#C4C4C4" fill-opacity="0.23" stroke="#B1B1B1"/>
<rect x="8" y="8" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="8" y="26" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="26" y="8" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="26" y="26" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="17" y="8" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="17" y="26" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="35" y="8" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="35" y="26" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="17" y="17" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="17" y="35" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="35" y="17" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="35" y="35" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="8" y="17" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="8" y="35" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="26" y="17" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
<rect x="26" y="35" width="5" height="5" rx="0.5" fill="#2D2B3D"/>
</svg>
```

Le diplay en grand style mp3:
```svg
<svg width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="0.5" y="0.5" width="47" height="47" rx="9.5" fill="#C4C4C4" fill-opacity="0.23" stroke="#B1B1B1"/>
<rect x="10" y="10" width="10" height="10" rx="1" fill="#2D2B3D"/>
<rect x="28" y="10" width="10" height="10" rx="1" fill="#2D2B3D"/>
<rect x="28" y="28" width="10" height="10" rx="1" fill="#2D2B3D"/>
<rect x="10" y="28" width="10" height="10" rx="1" fill="#2D2B3D"/>
</svg>
```

Les boutons pour le style mp3:
```svg
<svg width="200" height="60" viewBox="0 0 200 60" fill="none" xmlns="http://www.w3.org/2000/svg">
<circle cx="20" cy="30" r="20" fill="#C4C4C4"/>
<circle cx="180" cy="30" r="20" fill="#C4C4C4"/>
<circle cx="100" cy="30" r="30" fill="#C4C4C4"/>
<rect x="105" y="18" width="5" height="25" fill="white" stroke="white" stroke-linejoin="round"/>
<rect x="90" y="18" width="5" height="25" fill="white" stroke="white" stroke-linejoin="round"/>
<rect x="23" y="18" width="5" height="25" fill="white" stroke="white" stroke-linejoin="round"/>
<rect x="172" y="18" width="5" height="25" fill="white" stroke="white" stroke-linejoin="round"/>
<path d="M7 30L20.5 18V43L7 30Z" fill="white"/>
<path d="M20.5 18H21C21 17.8031 20.8844 17.6245 20.7048 17.5439C20.5252 17.4632 20.315 17.4955 20.1678 17.6263L20.5 18ZM7 30L6.66782 29.6263C6.56367 29.7189 6.50288 29.8507 6.5001 29.99C6.49732 30.1293 6.55281 30.2635 6.65318 30.3602L7 30ZM20.5 43L20.1532 43.3602C20.2976 43.4992 20.5112 43.5386 20.6957 43.4601C20.8802 43.3816 21 43.2005 21 43H20.5ZM20.1678 17.6263L6.66782 29.6263L7.33218 30.3737L20.8322 18.3737L20.1678 17.6263ZM6.65318 30.3602L20.1532 43.3602L20.8468 42.6398L7.34682 29.6398L6.65318 30.3602ZM21 43V18H20V43H21Z" fill="white"/>
<path d="M193.5 31L180 43V18L193.5 31Z" fill="white"/>
<path d="M180 43H179.5C179.5 43.1969 179.616 43.3755 179.795 43.4561C179.975 43.5368 180.185 43.5045 180.332 43.3737L180 43ZM193.5 31L193.832 31.3737C193.936 31.2811 193.997 31.1493 194 31.01C194.003 30.8707 193.947 30.7365 193.847 30.6398L193.5 31ZM180 18L180.347 17.6398C180.202 17.5008 179.989 17.4614 179.804 17.5399C179.62 17.6184 179.5 17.7995 179.5 18H180ZM180.332 43.3737L193.832 31.3737L193.168 30.6263L179.668 42.6263L180.332 43.3737ZM193.847 30.6398L180.347 17.6398L179.653 18.3602L193.153 31.3602L193.847 30.6398ZM179.5 18V43H180.5V18H179.5Z" fill="white"/>
</svg>
```

## Conclusion

Vous pourrez drop vos créations sur #⚗️•Creations sur le discord: https://discord.com/invite/QsUPRsEjWT

Les meilleurs créations et le site de rob_runner seront uploadé sur ce github si leurs créateurs sont d'accord après la sortie de la vidéo de présentation des sites.

Bon courage!
