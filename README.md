Esta aplicación implementa un quiosco de comida con una interfaz para que los usuarios puedan navegar por diferentes categorías de productos y generar sus ordenes

Para la versión 0.60 se decidió realizar la interfaz principal del usuario para que pueda realizar sus ordenes y tener un vistazo general de su vista.

VERSIÓN 0.60 29/05/2024
FUNCIONALIDADES PRINCIAPLES

----------CLIENTE-------------
*Se implementó un menú vertical con todas las categorias disponibles de productos para realizar su pedido con sus íconos ilustrativos para una mejor UX.

*Se implementó una lista de todos los productos disponibles con sus precios, imágenes y botón correspondiente de agregar al carrito.

*Se implementó un sistema de carrito de compras que al agregar un prodcuto con su botón correspondiente, se agrega a una lista vertical del lado derecho de la pantalla mostrando el nombre del producto, su precio, la cantidad que se desea pedir, el subtotal de cada cantidad de productos y el total del pedido.

*Se implementó una confirmación de pedidos, para que el cliente complete su pedido y sea mandado al sistema de cocina para su posterior preparación.

----------COCINA---------
*Se implementó un sistema en tiempo real que muestra los pedidos confirmados por los clientes con los detalles de la orden y los productos a preparar con el fin de llevar un manejo de pedidos y mejorar la eficiencia de los mismos.



This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
