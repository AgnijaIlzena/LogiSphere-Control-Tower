<p align="center">
  <img src="logo/logo.png" alt="LogiSphere Control Tower" width="360">
</p>

# LogiSphere Control Tower

Projet M2 Data Engineer (YNOV) : la Control Tower temps réel d'une flotte de **4 000 véhicules** qui assure **120 000 expéditions par jour**. Elle doit gérer un flux IoT instable (retards, doublons, trous), tenir les pics et continuer à fonctionner pendant une panne.

**SLO :** alerte température < 10 s · position visible < 30 s · RPO télémétrie 2 min · RPO expédition 0 · RTO 5 min

## Données

- **Temps réel (JSONL) :** `telemetrie`, `evenements_expedition`, avec `heure_evenement` et `heure_reception`
- **Référentiels (CSV) :** `vehicules`, `chauffeurs`, `hubs`, `trajets`, `expeditions`
- **Batch externe (CSV) :** `transporteur_AAAAMMJJ`

Modèle : [`data/drawio-data model.png`](data/drawio-data%20model.png)

## Maquettes

[Accueil](maquette%20proj%20ynov%20archi/acceuil.png) · [Expéditions](maquette%20proj%20ynov%20archi/expedition.png) · [Expédition unitaire](maquette%20proj%20ynov%20archi/expedition_unitaire.png) · [Véhicules](maquette%20proj%20ynov%20archi/vehicule.png) · [Chargement](maquette%20proj%20ynov%20archi/loading.png) · [404](maquette%20proj%20ynov%20archi/error%20404.png)

## Dépôt

`LogiSphere_Control_Tower_FR.pdf` (brief) · `data/` (modèle de données) · `logo/` · `maquette proj ynov archi/` (maquettes) · `Trello.png` (sprints)
