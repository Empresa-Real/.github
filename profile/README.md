
# SupplyCore

<div align="center">

**Ingeniería de software para la optimización de cadenas de suministro ágiles y logística retail.**

</div>

En **SupplyCore** desarrollamos soluciones tecnológicas de alto rendimiento orientadas a resolver la complejidad operativa en cadenas de suministro dinámicas. Inspirados en los modelos de respuesta rápida y distribución ágil del sector retail, diseñamos plataformas que maximizan la visibilidad, sincronizan la demanda con el inventario y facilitan la toma de decisiones basada en datos.

## Plataforma: OptiWay

**OptiWay** es nuestro sistema integral de optimización y gestión logística, concebido para responder a las exigencias de disponibilidad inmediata de producto en tienda y rotación eficiente de inventario entre centros de distribución y puntos de venta.

### Contexto del Negocio y Problema
En el retail moderno, la falta de visibilidad en tiempo real sobre inventarios, ventas y reposición genera dos grandes ineficiencias:
1. **Exceso de stock ocioso** en ciertas ubicaciones con altos costos de almacenamiento.
2. **Quiebres de stock (escasez)** en tiendas de alta rotación, provocando pérdida directa de ventas.

**OptiWay** centraliza la información operativa y proporciona herramientas analíticas para sincronizar la reposición de mercancía con la demanda real del mercado.

### Capacidades del Sistema
* **Red Logística Centralizada:** Registro y administración de productos, tiendas comerciales y centros de distribución (CD).
* **Control de Inventarios y Ventas:** Captura continua de niveles de stock y flujo de mercancía.
* **Patrones de Demanda:** Análisis de consumo y rotación diferenciado por ubicación y zona geográfica.
* **Recomendaciones de Reposición:** Algoritmos de sugerencia de reabastecimiento inteligente desde bodegas y CDs hacia tiendas.
* **Órdenes de Reabastecimiento:** Trazabilidad integral y seguimiento del ciclo de vida de los pedidos de transferencia.
* **Reportes Analíticos:** Métricas de rotación de productos, días de inventario y detección de cuellos de botella logísticos.

### Valor Agregado
* **Mayor Disponibilidad:** Reducción drástica de quiebres de stock en puntos de venta.
* **Eficiencia de Capital:** Minimización de inventarios ociosos y sobrestock.
* **Decisiones Basadas en Datos:** Planificación logística ágil respaldada por métricas operativas en tiempo real.

## Ecosistema de Repositorios

| Repositorio | Descripción | Stack Principal |
| :--- | :--- | :--- |
| **OptiWay-Backend** | API REST y lógica de dominio bajo Arquitectura Hexagonal | Java 17, Spring Boot 4, Spring Security 7, PostgreSQL (Supabase) |
| **OptiWay-Frontend** | Interfaz de usuario para planificación, monitoreo y gestión | Frontend Web, REST Client |

## Principios de Ingeniería

* **Arquitectura Hexagonal (Puertos y Adaptadores):** Núcleo de negocio desacoplado de bases de datos y frameworks externos.
* **Seguridad y Control de Acceso (RBAC):** Autenticación y autorización estricta basada en roles operativos mediante JWT.
* **Diseño Orientado al Dominio:** Modelado fiel de las entidades logísticas y operativas de la cadena de suministro.

---

<div align="center">
<sub>Desarrollado por el equipo de <b>SupplyCore</b></sub>
</div>
