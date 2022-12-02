# Power Automate 
## Sécuriser un HTTP Trigger

- Petite Solution pour illustrer la sécurisation d'un HTTP Trigger dans un Cloud Flow

![image](https://user-images.githubusercontent.com/6080558/205266510-39d701a0-9195-46d9-bd8e-c859aab67b09.png)

- Pour éviter tout déclenchement, j'ai mis la condition dans les "Conditions du déclencheur"

![image](https://user-images.githubusercontent.com/6080558/205266543-437626f2-50df-4618-a4e9-713434f75575.png)

- Sinon les commentaires dans le Cloud Flow expliquent la suite

![image](https://user-images.githubusercontent.com/6080558/205268367-093c905b-8861-44aa-84c8-9dfd1753b3fd.png)

Le Secret est directement stocké dans une variable d'environnement de type String. Mais il est possible de la stocker dans un Azure Key Vault : https://learn.microsoft.com/power-apps/maker/data-platform/environmentvariables#use-azure-key-vault-secrets-preview

La [Solution](https://docs.microsoft.com/powerapps/maker/data-platform/solutions-overview) s'adapte sur un environement Dataverse standard

:warning: La **Solution** est UnManaged
