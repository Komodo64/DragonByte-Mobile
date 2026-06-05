# DragonByte Mobile Store

## Proyecto Final - Bases de Datos Avanzadas

Sistema de gestión para venta de celulares, accesorios y servicio técnico desarrollado en Oracle PL/SQL.

## Funcionalidades

* Gestión de clientes
* Gestión de productos
* Registro de ventas
* Control de inventario
* Servicio técnico y reparaciones
* Vistas de seguridad
* Reportes empresariales
* Control de concurrencia ACID

## Tecnologías utilizadas

* Oracle Live SQL
* SQL
* PL/SQL

## Componentes implementados

### Tablas

* clientes
* productos
* ventas
* detalle_ventas
* reparaciones
* log_cambios

### Procedimientos

* registrar_venta_completa
* registrar_reparacion

### Trigger

* trg_validar_stock_detalle

### Vistas

* v_catalogo_publico
* v_reporte_ventas_detallado

## Reglas de negocio

1. No se permiten productos con precio menor o igual a cero.
2. No se permite vender más stock del disponible.
3. Las vistas públicas no muestran información sensible.

## Integrantes

* Brandon Alessandro Beckerman Hernández Escobar y Johny Matheo Fraco Zuleta
