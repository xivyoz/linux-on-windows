# Installation du Sous-système Windows pour Linux (WSL)

Avec WSL, vous pouvez exécuter un environnement Linux directement sous Windows, sans la surcharge d'une machine virtuelle. Voici comment installer et configurer le WSL :

## Étape 1 : Activation des fonctionnalités requises

1. Ouvrez le **Panneau de configuration**.
2. Naviguez vers **Programmes**.
3. Sélectionnez **Activer ou désactiver des fonctionnalités Windows**.
4. Assurez-vous de cocher les cases suivantes :
   - **Sous-système Windows pour Linux**.
   - **Virtual Machine Platform**.
5. **Redémarrez** votre ordinateur pour que les modifications prennent effet.

## Étape 2 : Mise à jour pour le WSL

1. Ouvrez **Paramètres**.
2. Dirigez-vous vers **Windows Update**.
3. Sélectionnez **Vérifier les mises à jour**.
4. Cherchez et installez la mise à jour intitulée **Windows Subsystem for Linux Update**.

> 📝 **Note** : Si vous ne trouvez pas cette mise à jour :
> - Cliquez sur **Options avancées**.
> - Activez l'option **Obtenir des mises à jour pour autres produits Microsoft Corporation**.
> - Revenez à **Windows Update** et vérifiez à nouveau les mises à jour.
> - Installez la mise à jour **Windows Subsystem for Linux Update** si elle apparaît.

## Étape 3 : Installation de votre distribution Linux préférée

1. Ouvrez le **Microsoft Store**.
2. Cherchez votre distribution Linux préférée et installez-la.

Pour les utilisateurs d'**Ubuntu**, vous pouvez [cliquer ici](https://www.microsoft.com/store/productid/9PDXGNCFSCZV?ocid=pdpshare) pour télécharger directement.

## Étape 4 : Initialisation et lancement de votre distribution Linux

1. Ouvrez le sous-système Linux que vous avez installé. Pour y accéder depuis le Terminal ou Powershell :
   - Tapez `bash` pour entrer dans le mode Linux. **OU**
   - Utilisez le nom de votre sous-système. Par exemple, pour Ubuntu, tapez `ubuntu`.
2. Lors de la première exécution, vous serez invité à créer un utilisateur et à définir un mot de passe pour ce compte.

🌟 **Astuce** : Vous pouvez accéder aux fichiers de votre système Windows depuis le terminal Linux en naviguant vers `/mnt/`, par exemple `/mnt/c/` pour accéder au disque C.

---

Félicitations ! Vous avez maintenant le Sous-système Windows pour Linux configuré sur votre machine. Profitez de l'expérience Linux sans quitter Windows !
