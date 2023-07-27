# dtv-Product-Card

este es un paquete de pruebas de despliegue en NPM.
```
import { ProductCard, ProductButtons, ProductImage, ProductTitle } from 'dtv-product-card';
```

```
<ProductCard 
    product={ product } 
    initialValues={{
        count: 4,
        maxCount: 10,
    }}
>

    {
        ( /* { reset, increaseBy, isMaxCountReached, count } */ ) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
                  
</ProductCard>
```