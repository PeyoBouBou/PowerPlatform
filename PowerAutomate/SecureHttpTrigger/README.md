# Power Automate 
## Sécuriser un HTTP Trigger

Petite Solution pour illustrer la sécurisation d'un HTTP Trigger dans un Cloud Flow

Pour éviter tout déclenchement, j'ai mis la condition dans les "Conditions du déclencheur"

Sinon les commentaires dans le Cloud Flow expliquent la suite

Le Secret est directement stocké dans une variable d'environnement de type String. Mais il est possible de la stocker dans un Azure Key Vault : https://learn.microsoft.com/power-apps/maker/data-platform/environmentvariables#use-azure-key-vault-secrets-preview

La [Solution](https://docs.microsoft.com/powerapps/maker/data-platform/solutions-overview) s'adapte sur un environement Dataverse standard

:warning: La **Solution** est UnManaged