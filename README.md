# Amaia Casino

MVP de gestión de créditos en modo demo/sandbox.

## Alcance inicial
- Super Admin
- Vendedores
- Jugadores
- Billeteras de créditos demo
- Transferencias y ajustes registrados
- Historial y auditoría
- Límites y bloqueo de cuentas
- Reportes

> Este repositorio comienza en modo demo: los créditos no representan dinero real ni habilitan apuestas con dinero real.

## Arquitectura prevista
- Next.js / React
- Node.js
- PostgreSQL
- Prisma
- Autenticación por roles

## Roles
ADMIN -> VENDEDOR -> JUGADOR

Cada movimiento de créditos se registra en un ledger auditable. Los vendedores no pueden crear saldo; solo distribuir el saldo demo asignado por administración.
