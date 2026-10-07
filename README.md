# Calidad de Software

Este repositorio está orientado a la materia de Calidad de Software y busca documentar conceptos básicos relacionados con la garantía de calidad en el desarrollo de software.

## Objetivo

La calidad de software se centra en construir productos confiables, mantenibles, seguros y útiles para los usuarios. Esto implica no solo escribir código funcional, sino también validar que el sistema se comporte correctamente bajo diferentes condiciones.

## Conceptos básicos

### 1. Pruebas de software

Las pruebas son actividades que permiten verificar si el software cumple con los requisitos esperados y si funciona correctamente antes de entregarse al usuario.

Algunas razones importantes para probar software son:

- Detectar errores tempranamente.
- Reducir riesgos en producción.
- Mejorar la confianza en los cambios.
- Facilitar el mantenimiento del sistema.

### 2. Test unitarios

Los tests unitarios se enfocan en validar componentes o funciones individuales de forma aislada. Por ejemplo, si una función suma dos números, se puede probar que devuelve el resultado esperado en distintos escenarios.

Características principales:

- Prueban piezas pequeñas del sistema.
- Son rápidos de ejecutar.
- Ayudan a detectar fallos en lógica específica.
- Se suelen automatizar con herramientas como Jest, PyTest, JUnit, entre otras.

Ejemplo de idea:

- Entrada esperada: 2 + 3
- Resultado esperado: 5

Si la función falla en este caso, el test indica un problema puntual y fácil de corregir.

### 3. Pruebas E2E (End-to-End)

Las pruebas E2E validan el flujo completo del sistema, desde la interacción del usuario hasta la respuesta final de la aplicación. Se suelen ejecutar como si un usuario real estuviera utilizando la aplicación.

Características principales:

- Verifican escenarios completos.
- Validan integración entre módulos.
- Pueden incluir navegación, formularios, autenticación y acciones del usuario.
- Se usan herramientas como Playwright, Cypress o Selenium.

Ejemplo de escenario:

- Un usuario inicia sesión.
- Agrega un producto al carrito.
- Finaliza la compra.
- Verifica que la orden se registra correctamente.

Estas pruebas son más lentas que los test unitarios, pero aportan mayor confianza sobre el comportamiento real del sistema.

## Diferencia entre pruebas unitarias y E2E

- Test unitarios: validan piezas pequeñas y aisladas.
- Pruebas E2E: validan el comportamiento real del sistema completo.
- Los unit tests son rápidos y frecuentes.
- Las pruebas E2E son más completas, pero también más costosas de ejecutar.

## Recomendaciones

- Combinar pruebas unitarias y E2E para obtener mejor cobertura.
- Mantener las pruebas automatizadas y fáciles de leer.
- Revisar y actualizar pruebas cuando cambia la lógica del sistema.
- Priorizar la calidad sobre la cantidad de pruebas.

## Conclusión

La calidad de software no depende solo del código escrito, sino también de la capacidad del equipo para validar que el sistema funciona como se espera. La combinación de pruebas unitarias y pruebas E2E es una práctica clave para entregar software confiable y robusto.
