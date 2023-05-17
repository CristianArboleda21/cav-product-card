# CAV-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Cristian Arboleda

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'cav-product-card'

```

```
<ProductCard 
    product={ product }
    initialValues={{
    count: 4,
    maxCount: 10
    }}
>
    {
        ( { reset, isMaxCountReached, maxCount, count, increaseBy } ) => (
            <>
            <ProductImage />
            <ProductTitle  />
            <ProductButtons />              
            </>
        )
    }

</ProductCard>

```
     