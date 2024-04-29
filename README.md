# Asterisk
#  Mise en place et sécurisation d’une plateforme VoIP basée sur la solution open source Asterisk en utilisant issabel

## Introduction
Asterisk est une solution de téléphonie open source très populaire qui permet aux entreprises de mettre en place des systèmes de communication professionnels avancés. Asterisk est un logiciel de PBX open source très populaire utilisé pour mettre en place des systèmes de communication vocale sur IP (VoIP).

in out project  we used Issabel For the implementation of Asterisk<br>
**IssabelPBX is an opensource GUI (graphical user interface) that controls and manages Asterisk (PBX).**
<p align="center">
  <img width="250" height="250" src="issabel.png">
</p>

## Objectif 
La mise en place d’une solution de VoIP sécurisée basée sur des outils open source(**issabel**), précisément le serveur Asterisk et le softphone Zoiper. Les entreprises, bénéficiant d’une solution, une plateforme de VoIP assez flexible, peu couteuse, et protégée contre les attaques de sécurité de l’intérieur du réseau comme de l’extérieur aussi.
## Realisation 
In this [PDF](project.pdf) , you will find the complete Hull project. Below is an overview of its contents.

**1. Installation et configuration du serveur Asterisk** 
  - a. Installation d’Asterisk <br>
  - b. Configuration d’Asterisk  <br>

**2. Configuration de la VoIP** 
  - a. Configuration des trunks SIP  <br>
  - b. Installation et configuration des softphone (ZOIPER) <br> 
  - c. Mise en place des numéros de téléphone(extension)  <br>
  - d. Configuration des règles de routage  <br>

**3. Test et Validation de la plateforme VOIP** 
  - a. Tests fonctionnels   <br>
  - b. Vérification de la qualité des appels <br>

**4. Mise en œuvre des attaques contre le réseau VoIP** 
  - a. Localisation des serveurs VoIP  <br>
  - b. Arp poisoning VOIP  <br>
  - c. Interception d’appels entrants : Capture du trafic et écoute clandestine en utilisant Wireshark <br> 
  - d. Déni de services : Dos et DDos  <br>
  - e. Attaque sur l’authentification SIP  <br>
  - f. Capture de l’authentification SIP en utilisant Sipdum <br> 
     - i. Crack de la réponse d’authentification SIP  <br>

**5. Mise en œuvre des solutions de sécurité** 
  - a. VOIP Hardening : Implémentation des bonnes pratiques <br> 
  - b. Mise en place des IDS(snort)  <br>
  - c. Configuration Firewall : Iptables, ufw <br> 
  - d. Implémenter des solutions pour la mise en place QoS VoIP. <br> 
  - e. Implémentation des protocoles sécurisée VoIP VPN <br>
## Team
- [Hajar Ed-darrajy](https://github.com/haizy1) Author
- [Imane Chaik](https://github.com/rivenos) 
