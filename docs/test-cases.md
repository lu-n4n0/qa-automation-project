# Cas de Tests Manuels

---

## TC001 – Soumission formulaire réservation valide

### Préconditions
- L’utilisateur est sur la page d’accueil de https://automationintesting.online/

### Étapes
1. Remplir le champ "Nom" avec "Lucia"
2. Remplir le champ "Email" avec "lucia@example.com"
3. Remplir le champ "Téléphone" avec "987654321"
4. Sélectionner la date d’arrivée (aujourd’hui)
5. Sélectionner la date de départ (+2 jours)
6. Saisir "2" pour le nombre de personnes
7. Cliquer sur le bouton "Book"

### Résultat attendu
- Un message de confirmation s’affiche
- Le formulaire est vidé

### Statut
À tester

---

## TC002 – Validation du champ email (email invalide)

### Préconditions
- L’utilisateur est sur la page d’accueil

### Étapes
1. Remplir tous les champs sauf l’email (exemple : "lucia" ou "lucia@")
2. Cliquer sur "Book"

### Résultat attendu
- Message d’erreur s’affiche
- Formulaire non soumis

### Statut
À tester

---

## TC003 – Navigation vers la page de connexion backoffice

### Préconditions
- L’utilisateur est sur la page d’accueil

### Étapes
1. Cliquer sur le lien "Backoffice"
2. Vérifier que la page de connexion s’affiche

### Résultat attendu
- La page de connexion apparaît avec les champs "Username" et "Password"

### Statut
À tester
