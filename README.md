# sms-phone-locator-privacy

## 📄 Privacy Policy (FR)

**Dernière mise à jour : 2025**

Cette application, **SMS Phone Locator**, permet à un utilisateur autorisé de localiser un téléphone à distance via l’envoi d’un SMS contenant un code prédéfini.  
L’application fonctionne **uniquement en local** sur le téléphone.  
Elle **ne collecte, ne stocke, ne partage et n’envoie aucune donnée personnelle** à des serveurs externes.

---

### 1. Données traitées

L’application peut accéder aux éléments suivants :

| Donnée | Usage | Stockée ? | Envoyée ? |
|-------|--------|-----------|-----------|
| **Position GPS** | Déterminer la position du téléphone sur demande | ❌ Non | ✅ Par **SMS** au **numéro demandeur uniquement** |
| **Messages SMS reçus** | Lire le SMS contenant le code de localisation | ❌ Non | ❌ Non |
| **SMS sortants** | Envoyer la réponse de localisation | ❌ Non | ✅ Au **numéro demandeur uniquement** |
| **Sonnerie / vibration / flash** (si mode *Ring*) | Faire sonner le téléphone | ❌ Non | ❌ Non |

➡️ **Aucune donnée n’est transmise à Internet.**  
➡️ **Aucune donnée n’est partagée avec des tiers.**  
➡️ **Aucune donnée n’est stockée.**

---

### 2. Fonctionnement

1. Le téléphone reçoit un SMS contenant un code.
2. L’application vérifie que le code est valide.
3. Si oui :
   - Active la géolocalisation
   - Récupère la position
   - Renvoie la position par SMS **uniquement au numéro demandeur**

---

### 3. Permissions utilisées

| Permission | Raison |
|-----------|--------|
| `RECEIVE_SMS` | Détecter les SMS de demande |
| `SEND_SMS` | Envoyer la position en réponse |
| `ACCESS_FINE_LOCATION` | Obtenir la position GPS précise |
| `FOREGROUND_SERVICE` | Garder le service actif lors de la localisation |
| `POST_NOTIFICATIONS` | Afficher un statut pendant la localisation |

---

### 4. Contact
📧 support.smsphonelocator@sfr.fr

---

## 📄 Privacy Policy (EN)

**Last updated: 2025**

This application, **SMS Phone Locator**, allows an authorized user to locate a phone remotely by sending an SMS containing a predefined code.  
The application works **locally only** on the device.  
It **does not collect, store, share, or transmit any personal data** to any server or third party.

---

### 1. Data Processed

| Data | Purpose | Stored? | Shared? |
|------|---------|---------|---------|
| **GPS Location** | Determine phone location on request | ❌ No | ✅ Sent **via SMS** to the **requesting number only** |
| **Incoming SMS** | Detect and validate the request code | ❌ No | ❌ No |
| **Outgoing SMS** | Send location response | ❌ No | ✅ Sent **only to the sender** |
| **Ringtone / vibration / flash** (Ring mode) | Help locate the phone physically | ❌ No | ❌ No |

➡️ **No data is uploaded to the Internet.**  
➡️ **No data is shared with third parties.**  
➡️ **No data is stored.**

---

### 2. How It Works

1. The phone receives an SMS containing a command code.
2. The app verifies the code.
3. If valid:
   - Activates GPS
   - Retrieves the location
   - Sends the location back **via SMS to the sender only**

---

### 3. Permissions Used

| Permission | Purpose |
|-----------|---------|
| `RECEIVE_SMS` | Detect command SMS |
| `SEND_SMS` | Send location response |
| `ACCESS_FINE_LOCATION` | Retrieve precise location |
| `FOREGROUND_SERVICE` | Keep service active |
| `POST_NOTIFICATIONS` | Display GPS status notification |

---

### 4. Contact
📧 support.smsphonelocator@sfr.fr
