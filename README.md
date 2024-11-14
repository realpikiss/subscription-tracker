
# 🎯 Subscription Tracker

Un outil de détection et gestion d'abonnements à partir des relevés bancaires.

## 📝 Description
Outil qui analyse les relevés bancaires (CSV) pour détecter et gérer automatiquement les abonnements en utilisant des algorithmes de détection de patterns et un dictionnaire de services connus.

## 🚀 Features

### MVP (En cours)
- Upload relevés bancaires (CSV)
- Détection automatique d'abonnements
- Dashboard simple

### Futures Features
- Interface utilisateur améliorée
- Statistiques et analyses
- Suggestions d'optimisation

## 💻 Stack Technique
- **Backend**: Python (FastAPI, Pandas)
- **Database**: SQLite/PostgreSQL
- **Frontend**: À définir

## 🛠️ Setup Local

1. Cloner le repository
```bash
git clone https://github.com/realpikiss/subscription-tracker.git
cd subscription-tracker
```

2. Créer environnement virtuel
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
.\venv\Scripts\activate  # Windows
```

3. Installer dépendances
```bash
pip install -r requirements.txt
```

## 📊 Structure Projet
```
subscription-tracker/
├── backend/
│   ├── app/
│   │   ├── services/
│   │   │   ├── parser/     # Parsing CSV
│   │   │   └── detector/   # Détection abonnements
│   │   └── models/         # Modèles données
│   └── tests/              # Tests unitaires
├── data/
│   └── known_services.yaml # Services connus
└── docs/                   # Documentation
```

## ⚡ Progression
- [x] Setup initial
- [ ] Parser CSV
- [ ] Détection basique
- [ ] Interface simple
- [ ] Tests unitaires
- [ ] Documentation

## 🤝 Contribution
Projet en développement actif. Contributions bienvenues via Issues et Pull Requests.

## 📄 License
MIT License
```
