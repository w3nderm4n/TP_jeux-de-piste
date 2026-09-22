# Étape 2 — Découverte des paramètres

## Méthode

`GET`

## URL

http://172.16.3.254:8001/decouverte-des-parametres

## Paramètre

| Nom | Type | Valeur |
|---|---|---|
| `nom` | `Query` | `mael` |

## Requête complète

GET http://172.16.3.254:8001/decouverte-des-parametres?nom=mael

---

# Étape 3 — Plusieurs paramètres

## Méthode

`GET`

## URL

http://172.16.3.254:8001/plusieurs-parametres

## Paramètres

| Nom | Type | Valeur |
|---|---|---|
| `prenom` | `Query` | `mael` |
| `age` | `Query` | `18` |

## Requête complète

GET http://172.16.3.254:8001/plusieurs-parametres?prenom=mael&age=18

---

# Étape 4 — Requête POST

## Méthode

`POST`

## URL

http://172.16.3.254:8001/un-peu-de-post

## Corps de la requête

Aucun corps n'est défini.

---

# Étape 5 — Content-Type JSON

## Méthode

`POST`

## URL

http://172.16.3.254:8001/5-content-type

## Header

| Nom | Valeur |
|---|---|
| `Content-Type` | `application/json` |

Aucun contenu JSON n'est défini dans le corps.

---

# Étape 6 — Méthode PUT

## Méthode

`PUT`

## URL

http://172.16.3.254:8001/put-method-6

## Headers

| Nom | Valeur |
|---|---|
| `Content-Type` | `text/html` |
| `Accept` | `application/json` |

Aucun corps n'est défini.

---

# Étape 7 — Suppression avec DELETE

## Méthode

`DELETE`

## URL

http://172.16.3.254:8001/et-oui-delete

## Paramètre

| Nom | Type | Valeur |
|---|---|---|
| `filename` | `Query` | `test` |

## Requête complète

DELETE http://172.16.3.254:8001/et-oui-delete?filename=test

---

# Étape 8 — Modification avec PATCH

## Méthode

`PATCH`

## URL

http://172.16.3.254:8001/etape8/api/users/12345

## Header

| Nom | Valeur |
|---|---|
| `Content-Type` | `application/json` |

## Corps JSON

{
  "role": "Developer",
  "email": "test@test.com"
}

---

# Étape 9 — POST avec API Key

## Méthode

`POST`

## URL

http://172.16.3.254:8001/etape9

## Headers

| Nom | Valeur |
|---|---|
| `Content-Type` | `application/json` |
| `api-key` | `FenelonBTSSIO ` |
| `User-Agent` | `FenelonBTSSIO-UserAgent-LaRochelle-v1.0` |

## Corps JSON

{
  "name": "Donald Duck"
}
