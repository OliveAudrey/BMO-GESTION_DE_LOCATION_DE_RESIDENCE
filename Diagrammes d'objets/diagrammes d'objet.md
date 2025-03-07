Ce diagramme d'objet représente des instances concrètes des classes définies dans le diagramme de classe. Il illustre un exemple précis de réservation dans une résidence, avec les relations entre les objets.  

 **1. Instances et Attributs**  

- Client1 (JeanDupont) : Un utilisateur ayant un identifiant "C001", un pseudo et un mot de passe sécurisé. Il effectue une réservation.  
- Réservation1 (R12345) : Un enregistrement d'une réservation pour une période donnée (du 10 au 15 juillet 2025) avec un avis laissé par le client et un prix total de 500€.  
- Paiement1 : Correspond au paiement de **500€** effectué par carte bancaire pour valider la réservation.  
- Gestionnaire1 (Admin01) : Administrateur de la résidence, responsable de la gestion des disponibilités et des tarifs.  
- Résidence1 (BelleVue) : Un établissement situé en bord de mer, contenant plusieurs éléments disponibles à la réservation.  
- Élément1 (Studio 101) : Une unité de la résidence, avec des dates de disponibilité et d'occupation.  
- Option1 (Petit-déjeuner) : Un service optionnel proposé avec le studio, facturé à 10€.  

**2. Relations entre les Objets**  

- **Client1 effectue** une **Réservation1**.  
- **Réservation1 engendre** un **Paiement1**.  
- **Gestionnaire1 gère** une **Résidence1**.  
- **Résidence1 contient** un **Élément1**.  
- **Élément1 propose** une **Option1**.  


Ce diagramme permet de visualiser une instance concrète du processus de réservation d’un studio dans une résidence. Il montre comment les objets interagissent entre eux, depuis l'action du client jusqu'à la gestion par l'administrateur. Le modèle met en évidence le lien entre paiement, avis, options et disponibilité des éléments.  

IRAKOZE Olive Audrey et TOMBEZE Noah
