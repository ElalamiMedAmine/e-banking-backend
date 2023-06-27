# e-banking-backend

![alami1](https://github.com/ElalamiMedAmine/aa/assets/94014119/1c13ced7-1503-492d-b654-f35798e7dd5d)

Les DTOs sont des conteneurs qui encapsulent les données nécessaires à un transfert spécifique. Ils regroupent des données provenant de différentes entités ou simplifient la structure des données lors des échanges au sein de l'application.
Et garantit une séparation claire entre la logique métier de l'application et la représentation des données. Elle permet de transmettre uniquement les données requises sans révéler les détails internes des entités ou des modèles de données sous-jacents.

![alami2](https://github.com/ElalamiMedAmine/aa/assets/94014119/aeb37b13-c802-4ee1-96e7-11b5b92cb797)
![alami3](https://github.com/ElalamiMedAmine/aa/assets/94014119/595a2377-17ca-47f4-a2cf-faadc13f7ff3)
![alami4](https://github.com/ElalamiMedAmine/aa/assets/94014119/c21e6ad5-68b5-4f56-9efd-951ca7bb7c5b)
![alami5](https://github.com/ElalamiMedAmine/aa/assets/94014119/527c8563-d854-48c2-88df-3b665a59debb)
![alami6](https://github.com/ElalamiMedAmine/aa/assets/94014119/03f68db5-99d8-4745-a056-aa945fa04492)
![alami7](https://github.com/ElalamiMedAmine/aa/assets/94014119/e20a0108-2a59-48ee-ae18-9df6c5bba5fd)
![alami9](https://github.com/ElalamiMedAmine/aa/assets/94014119/a945338e-5cac-4e22-aa45-0450e192f2cc)
![alami10](https://github.com/ElalamiMedAmine/aa/assets/94014119/df174dae-1a20-4485-9870-c77c9ceb8cd6)


<h4>La couche Backend (Contrôleur) regroupe la logique métier de l'application et est développée avec le framework Spring Boot, reconnu pour sa capacité à simplifier la création d'applications Java robustes. Les contrôleurs Spring Boot exposent des API REST qui permettent au frontend d'interagir avec les données et d'effectuer des opérations.</h4>

![alami11](https://github.com/ElalamiMedAmine/aa/assets/94014119/d888ec07-4f1e-405e-843d-046cee7d975a)
![alami12](https://github.com/ElalamiMedAmine/aa/assets/94014119/08b0ec61-30e6-4991-b8bb-982c54bda8ad)
![alami13](https://github.com/ElalamiMedAmine/aa/assets/94014119/378542d1-b414-4f05-b57c-c1ba193d0d29)


Nous avons ajoute l'annotation [@CrossOrigin("")] pour "BankAccountRestAPI" et "CustomerRestController" , cela va spécifier une configuration globale permettant d'accepter les requêtes cross-origin depuis n'importe quel domaine. En utilisant "" comme paramètre, vous autorisez toutes les origines à accéder à l'API, ce qui peut être pratique lors du développement et du test de votre application et pour le transfert de données entre le back-end et le front-end.

![alami14](https://github.com/ElalamiMedAmine/aa/assets/94014119/d479c04a-340e-4b7f-a1f0-37e5ea73c977)

La base de données MySQL est utilisée comme système de stockage pour les informations concernant les clients, les comptes bancaires et les opérations. Son modèle relationnel est adapté à la persistance des données et permet d'assurer leur intégrité et leur cohérence.

![alami15](https://github.com/ElalamiMedAmine/aa/assets/94014119/46772c88-b20d-427f-aaf2-721eb37e7d02)
![alami16](https://github.com/ElalamiMedAmine/aa/assets/94014119/ef12565d-b948-4f91-9efa-57e148ca104b)





