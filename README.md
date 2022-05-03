# jtv-product-card

Este es un paquete de pruebas de despliegue en NPM

### Jair Tello

## Ejemplo

```js
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from "jtv-product-card"
```

```js
<ProductCard
    product={product}
    initialValues={{
      count: 4,
      maxCount: 10,
    }}
  >
    {({ reset, increaseBy, maxCount, isMaxCountReached, count }) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )}
</ProductCard>
```