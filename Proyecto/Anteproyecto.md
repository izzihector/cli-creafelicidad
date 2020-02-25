# Cumbre - Gestión en Software 
## Etapa: Anteproyecto y Modelamiento
## Nombre: Crea Felicidad
## Tipo: Implementación de Odoo
- Localización: Argentina
- Vertical: Cadena de Bares

## Datos de la(s) Compañia
Empresa 1
#
- Empresa de Consolidación: Si
- Empresa Padre: No
- Razon social: Holding
- CUIT: 30111111118
- Dirección: Sin Dirección
- Inicio de Actividades: Actual
#
Empresa 2
#
- Empresa de Consolidación: No
- Empresa Padre: Holding
- Razon social: INDUSTRIAS S.R.L.
- CUIT: 30712261516
- Dirección: MARCELO T. DE ALVEAR 482 Piso:2 Dpto:C - BARRIO : GUEMES, BARRIO GUEMES, 5000-CORDOBA
- Inicio de Actividades: Fecha de contrato social: 2012-03-14
#
Empresa 3
#
- Empresa de Consolidación: No
- Empresa Padre: Holding
- Razon social: FELICIDAD S.R.L.
- CUIT: 30714353418
- Dirección: MARCELO T. DE ALVEAR 482 Piso:2 Dpto:C - BARRIO : GUEMES, BARRIO GUEMES, 5000-CORDOBA
- Inicio de Actividades: Fecha de contrato social: 2014-01-02

## Datos de la(s) Unidad(es) Operativa(s)
#
Unidad Operativa 1
#
- Nombre Fantasía: Capitán
- Empresa:
- Dirección:
- Código:

### Parametrizaciones de la Compañia
#### Estructura empresarial
- [ ] Monoempresa
- [x] Multiempresa
~~~
* Monoempresa: Una estructura de una sola razon social, tiene definida una forma juridica y un solo plan de cuentas
* Multiempresa: Una estructura de multiples empresas, tienen definida una forma juridica y un plan de cuentas por empresa, pueden o no compartir maestros como clientes, proveedores y productos, pero no comparten movimientos
~~~
#### Tipo de estructura empresarial
- [ ] Simple
- [x] Holding
~~~
* Simple: Las empresas, en el caso de multiples empresas, aunque compartan la misma base de datos, no tienen relacion entre si, y se comportan de forma independiente unas de otras
* Holding: Las empresas se relacionan entre si por medio de una empresa padre que sirve de concolidación, esta empresa puede o no tener un numero fiscal (en caso de no tenerlo se debe colocar uno ficticio) y tambien tiene su plan de cuentas. Es importante tener en cuenta que un holding no es una forma jurídica específica. Se trata de una estructura y de un modelo de gestión: es decir, de una organización económica que integran distintas compañías.
~~~
#### Estructura de negocios
- [x] Simple unidad de negocio
- [ ] Multi-unidad de negocio
~~~
* Simple unidad de negocio: La estructura empresarial misma es una unidad de negocio unica en si misma
* Multi-unidad de negocio: Cuando una razon social tiene distintas unidades que generan ingresos y cierres de caja independientes se comportan como unidades de negocio, sin embargo comparten el mismo plan de cuentas y razon social. Un ejemplo de esto son las sucursales que dependen de una misma razón social (no debe confundirse con franquicias)
~~~
