# CRYPTOBOT-PI
# 🛡️ CryptoBot Pi - Assistant Cryptographique CLI

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Raspberry Pi](https://img.shields.io/badge/platform-Raspberry%20Pi-red.svg)](https://www.raspberrypi.com/)
[![PyCryptodome](https://img.shields.io/badge/crypto-PyCryptodome-green.svg)](https://www.pycryptodome.org/)

**Assistant cryptographique intelligent exécuté sur Raspberry Pi avec interface en ligne de commande**

---

## 🚀 Fonctionnalités

### 🔐 **15 Algorithmes Implémentés**

#### 📊 **Cryptographie Classique**
- **Vigenère** - Chiffrement/Déchiffrement
- **César** - Chiffrement/Déchiffrement

#### ⚡ **Cryptographie Symétrique Moderne**
- **AES-256-GCM** - Standard industriel
- **ChaCha20** - Optimisé pour Raspberry Pi

#### 🔑 **Cryptographie Asymétrique**
- **RSA** - Génération de clés (1024/2048/4096 bits)
- Chiffrement/Déchiffrement RSA-OAEP
- Signature et vérification RSA-PKCS1.5-SHA256

#### 🔍 **Hachage**
- **SHA-256** - Calcul et vérification de hash
- Salting automatique pour la sécurité

#### 🛠️ **Utilitaires**
- Sauvegarde des clés dans des fichiers
- Affichage des clés générées
- Interface interactive intuitive

---

## 📋 Installation

### Prérequis
- Raspberry Pi 4 (modèle B recommandé)
- Ubuntu Server 25.10 (ou version supérieure)
- Python 3.9+

### Étapes d'installation

```bash
# 1. Cloner le repository
git clone https://github.com/[votre-username]/crypto-chatbot-pi.git
cd crypto-chatbot-pi

# 2. Créer un environnement virtuel
python3 -m venv crypto_env
source crypto_env/bin/activate

# 3. Installer les dépendances
pip install pycryptodome

# 4. Exécuter CryptoBot Pi
python crypto_pro_complete.py
