On a créé une API basique pour une boutique en ligne qui permet de créer, lire, modifier et supprimer des produits ( Product ). Les Product auront quatre champs obligatoires :

- name : le nom du produit, de type String
- description : la description du produit, de type String
- price : le prix du produit, de type Number
- inStock : si le produit est en stock, de type Boolean.

On a implémenté cinq routes :

- GET: /api/products
Retournera tous les produits sous la forme{ products: Product[] }
- GET:/api/products/:id
Retournera le produit avec le_id fourni sous la forme { product: Product }
- POST:/api/products
Créera un nouveau Product dans la base de données.
- PUT: /api/products/:id
Pour modifier un produit
- DELETE: /api/products/:id
Pour supprimer un produit
