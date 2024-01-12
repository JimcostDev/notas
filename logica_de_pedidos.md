# Lógica de Pedidos en Restaurante

## Generación de QR
- Crea un QR que contenga el identificador único de la mesa.

## Manejo de Menú y Carrito
- Desarrolla en el frontend la interfaz para que el cliente vea el menú y agregue productos al carrito.

## Envío de Pedido al Backend
- Al confirmar el pedido, envía la información del carrito y el identificador de la mesa al backend a través de solicitudes HTTP (por ejemplo, POST).

## Lógica de Pedidos en el Backend
- En el backend, asocia los productos seleccionados con la mesa correspondiente y registra el pedido.

## Confirmación en Cocina
- Notifica a la cocina sobre el nuevo pedido asociado a una mesa específica.

## Pago en Caja
- Asegúrate de que la aplicación solo genere pedidos y no procese pagos. El pago se realizará en caja física.

## Manejo de Usuarios y Autenticación Interna
- Mantén la autenticación interna para el personal de trabajo que gestiona la información desde sus dashboards.

## Historial de Pedidos
- Implementa un sistema para mantener un historial de pedidos y asocia cada pedido con la mesa correspondiente.

## Ubicación a través del QR
- Utiliza la información del QR para tener la ubicación de la mesa y asociarla con el pedido.

## Pruebas
- Realiza pruebas exhaustivas para asegurarte de que la lógica de pedidos y la asociación con el QR funcionen correctamente.
