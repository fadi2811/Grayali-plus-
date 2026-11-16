# Brancher grayaliup.com sur le site

Le site reste sur GitHub. On lui donne seulement une plus belle adresse.

## 1. Acheter le domaine (environ 10 à 15 € par an, soit 7 000 à 10 000 FCFA)

Chez un vendeur de domaines connu, par exemple Namecheap, Porkbun ou Cloudflare.
Cherche `grayaliup.com`, ajoute-le au panier et paie. Une carte Visa ou Mastercard
prépayée (par exemple Wave, Orange Money ou une banque) fonctionne en général.

## 2. Régler le DNS chez le vendeur

Dans la gestion du domaine, ouvre « DNS » et ajoute ces lignes :

| Type  | Nom   | Valeur                 |
|-------|-------|------------------------|
| A     | @     | 185.199.108.153        |
| A     | @     | 185.199.109.153        |
| A     | @     | 185.199.110.153        |
| A     | @     | 185.199.111.153        |
| CNAME | www   | fadi2811.github.io     |

## 3. Le dire à GitHub

1. Va sur github.com/fadi2811/Grayali-plus- → **Settings** → **Pages**.
2. Dans « Custom domain », écris `grayaliup.com` puis **Save**.
3. Attends que la vérification soit verte (de quelques minutes à 24 h).
4. Coche **Enforce HTTPS** dès que la case est disponible.

## 4. Ensuite (préviens Claude)

- Mettre la nouvelle adresse dans le site et dans l'aperçu WhatsApp.
- Refaire les QR codes et les prospectus avec `grayaliup.com`.
- L'ancienne adresse `fadi2811.github.io/Grayali-plus-` renverra automatiquement
  vers `grayaliup.com` : les prospectus déjà imprimés continueront de marcher.

**Bonus pro :** une adresse e-mail `contact@grayaliup.com`. Plusieurs vendeurs
proposent une redirection gratuite vers ton Gmail.
