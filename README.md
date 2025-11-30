# Gakkel Drone Embedded

Système embarqué Python pour détection de formes via caméra sur Raspberry Pi . POC de surveillance drone sous-marin.

## Objectif

POC de système de surveillance pour drone sous-marin capable de :
- Détecter des formes géométriques simples (cercle, carré, triangle)
- Streamer les données de détection vers un serveur central
- Fonctionner de manière autonome sur Raspberry Pi 3

## Stack Technique

- **Plateforme** : Raspberry Pi 3 Model B
- **Langage** : Python 3.x
- **Frameworks** :
  - Flask (API REST)
  - OpenCV (vision par ordinateur)
  - picamera (capture vidéo)
- **Communication** : HTTP/WebSocket vers serveur Java
