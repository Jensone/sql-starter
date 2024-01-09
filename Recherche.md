# Recherche avec SQL

On dispose de différent opérateur comme en programmation pour faire des recherches dans une base de données :


## Opérateurs logique 

AND et OR 

## Opérateurs arthmétiques 

| Opérateur | Description |
| --- | --- |
| + | Addition |
| - | Soustraction |
| * | Multiplication |
| / | Division |
| % | Modulo |

## Opérateurs comparaison 

Tableau complet : https://sql.sh/cours/where


## Exemple 

```sql
SELECT * FROM `products` 
WHERE (CONVERT(`name` USING utf8) 
LIKE '%smartphone%' 
AND CONVERT(`description` USING utf8) 
LIKE '%smartphone%') 
````

