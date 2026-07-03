# Tate 🥟 — Pedidos de empanadas

Web app simple (un solo archivo `index.html`, sin dependencias) para armar el pedido de empanadas del grupo de amigos y mandarlo por WhatsApp a Tate.

## Cómo se usa

Abrí `index.html` en cualquier navegador (celu o compu). No necesita servidor ni instalación.

### Módulo 1 — 👥 Amigos
Cargás el pedido **predeterminado** de cada amigo: nombre + las empanadas que suele pedir (tipo y cantidad). Se guarda en el dispositivo (`localStorage`), así queda listo para la próxima.

### Módulo 2 — 🛵 Armar pedido
Marcás con checkbox **quiénes están** para pedir hoy. La app consolida automáticamente todas las empanadas, muestra el total y arma el mensaje. Al tocar **«Enviar por WhatsApp»** abre WhatsApp con el pedido listo para mandarle a Tate.

> Configurá el número de Tate una vez en ⚙️ (dentro de la pestaña «Armar pedido»).
