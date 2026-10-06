# Plan de Pruebas

## Objetivo
Verificar que las funciones principales del sistema de inventario operen de acuerdo con los requisitos establecidos.

## Alcance
Validación de endpoints de la API, lógica de negocio, persistencia en base de datos y generación de reportes.

## Elementos que serán probados
- Módulo de registro de productos
- Módulo de consulta de existencias
- Funciones de actualización y eliminación
- Lógica de entradas y salidas
- Generación de reportes

## Tipos de pruebas
- Pruebas funcionales
- Pruebas de integración
- Pruebas de validación de datos
- Pruebas de regresión

## Criterios de aceptación
- Todos los campos obligatorios deben validarse
- El stock no puede ser negativo
- La API debe retornar códigos HTTP correctos

## Criterios de aprobación/rechazo
- Aprobación: 100% de pruebas pasan
- Rechazo: fallos que alteren la integridad del inventario

## Ambiente de pruebas
- Entorno local con Node.js en contenedores Docker

## Responsables
- Equipo de desarrollo y QA

## Herramientas utilizadas
- Jest, Supertest, Postman, Thunder Client
