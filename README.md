# cientotreinta

una pequeño clon de treinta

# Roadmap

el sistema contará con los siguientes modulos y campos

- Ventas
    - Cotizaciones (Funciona a modo de presupuesto para los clientes)
        - seleccionar un cliente
        - seleccionar los productos
        - verificar los precios
        - compartir con el client
    - Venta libre (Registrar ingreso sin seleccinoar productos del inventario)
    - Venta de productos
        - estado: Pagado | Deuda
        - fecha
        - conceptop
        - nota de comprobante
        - monto total
        - descuento
        - pagos[]:
            - metodo de pago
            - monto
        - productos[]:
            - cantidad
- Gastos
    - estado: Pagado | Deuda
    - fecha
    - categoria: Nomina | Arriendo | Compra de productos | etc
    - si Compra de productos:
        - productos
            - cantidad
    - monto
    - metodo de pago
    - concepto
- Inventario
    - productos
    - stock
- Balance
    - Ingresos vs Egresos / Gastos
- Deudas
    - Por cobrar
    - Por pagar
- Perfil
    - Usuario:
        - Nombre
        - Apellido
        - Tipo de documento
        - Cedula
        - Telefono
        - Correo
    - Configuracion
        - Notificar unidades bajas
        - Inventario en 0: Vender simple (las unidades pueden quedar en negativo) | Bloequedar venta sin unidades
        - Acceso biometrico
        - Multimoneda
- Prefuntas frecuentes
- Notificaciones
- Autenticacion
    - Login
    - Registro
    - Logout

