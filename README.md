# feribarra-product-card

Este es un paquete de pruebas de despliegue en NPM.

### Fernando Ibarra


```
import { ProductButtons, ProductCard, ProductImage, ProductTitle } from "../feribarra-product-card"
```

```
  <ProductCard
        product={product}
        initialValues={{
            count: 4,
            maxCount: 10
        }}

    >
        {
            ({ reset, isMaxCountReached, maxCount, count, increaseBy }) => (
                <>
                    <ProductImage />
                    <ProductTitle />
                    <ProductButtons />
                </>
            )
        }
    </ProductCard>
```