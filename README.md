# Sistema de Gestión de Almacén

Este es un sistema de gestión de almacén desarrollado con Next.js, Prisma, tRPC y MySQL (t3app).

## Funcionalidades

- Gestión de entrada y salida de productos en el almacén.
- Control de inventario de materia prima de fábrica.
- Interfaz de usuario intuitiva para operaciones en el almacén.
- Seguimiento de movimientos de inventario y registros históricos.

## Requisitos del Sistema

- Node.js >= 14.x
- npm >= 6.x
- MySQL >= 5.x

## Configuración

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/tu-proyecto.git
```
2. Instala las dependencias:
```bash
cd StockProject
npm install
```
3. Configura la base de datos MySQL en el archivo .env:
```bash
DATABASE_URL=mysql://usuario:contraseña@localhost:3306/nombre_base_de_datos
```
4.Ejecuta las migraciones de la base de datos:
```bash
npx prisma migrate dev --name "prisma-init"
```
5.Inicia el servidor de desarrollo:
```bash
npm run dev
```
