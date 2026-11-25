# Historias de Usuario - Canal Digital BBVA

**HU1 – Autenticación de cliente**
- Como cliente de BBVA, quiero iniciar sesión con usuario, contraseña y segundo factor para acceder a mis productos financieros.
- Criterio: el sistema permite el ingreso solo si las credenciales y el segundo factor son correctos. (Responsable: Cristian Alexis Daza Guerra)

**HU2 – Consulta de saldo**
- Como cliente, quiero ver el saldo de mi cuenta para conocer mi disponibilidad.
- Criterio: el saldo se muestra en la pantalla principal tras autenticarse y se actualiza con Redis para consultas rápidas. (Responsable: Cristian Alexis Daza Guerra)

**HU3 – Transferencia entre cuentas**
- Como cliente, quiero transferir dinero entre mis cuentas BBVA para organizar mis finanzas.
- Criterio: la transferencia se confirma con un comprobante y genera un evento en Kafka para notificar. (Responsable: Cristian Alexis Daza Guerra)

**HU4 – Historial de movimientos**
- Como cliente, quiero consultar mis últimos movimientos para hacer seguimiento a mis gastos.
- Criterio: se listan los movimientos con fecha, descripción y valor, consultando la base de datos o caché. (Responsable: Cristian Alexis Daza Guerra)

**HU5 – Cierre de sesión seguro**
- Como cliente, quiero cerrar sesión de forma segura para proteger mi información.
- Criterio: al cerrar sesión, el token de OAuth2 se invalida y se redirige a la pantalla de inicio. (Responsable: Cristian Alexis Daza Guerra)
