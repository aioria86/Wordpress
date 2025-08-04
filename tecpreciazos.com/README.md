# 🛒 TecPreciazos - Sitio de Comercio Electrónico

Repositorio con la versión de respaldo del sitio web desarrollado en WordPress para **TecPreciazos**, un ecommerce B2B/B2C que operó durante todo el año 2024 como proyecto transicional hacia la nueva plataforma actualmente activa: [modatechperu.com](https://modatechperu.com/).

## 📌 Descripción del Proyecto

El sitio fue diseñado como una solución de comercio electrónico moderna, enfocada en la venta de productos tecnológicos con precios especiales para empresas, distribuidores y clientes finales. Contó con funcionalidades de catálogo personalizado, registro de representantes de venta, automatización de cotizaciones y gestión de pedidos en línea.

El modelo de negocio es muy similar al de [ovalo24miami.com](https://ovalo24miami.com), y esta versión sirvió como base para la evolución del ecosistema de venta online de la empresa.

---

## 📂 Estructura del Repositorio

Este repositorio incluye la estructura del sitio WordPress **sin datos sensibles**, sin la carpeta `/uploads`, ni archivos de configuración privados. Debido a las políticas de GitHub sobre tamaño de archivos, el sitio comprimido completo (sin archivos pesados ni privados) se encuentra en el siguiente enlace:

🔗 **Descarga del comprimido**  
[Google Drive - WordPress Site](https://drive.google.com/file/d/1mDDqNHE-LS1sPlBSRgWPh0kiSYRvUThS/view?usp=drive_link)

---

## 🖼️ Capturas del Sitio

### 🏠 Página de Inicio (Home)
- [Home - Vista 1](https://drive.google.com/file/d/1SpkIn9vqlPcEWFlsgC7YIDanbXD24h7b/view?usp=drive_link)
- [Home - Vista 2](https://drive.google.com/file/d/1bIonljoRbWA2mVCtzWmjTmOXsSu3bmTq/view?usp=drive_link)
- [Home - Vista 3](https://drive.google.com/file/d/1E6qPW8wr-ZolFI3YmgKlfEAqknV4MGTx/view?usp=drive_link)

### 📦 Catálogo de Productos (Archive)
- [Vista de Archive con filtros](https://drive.google.com/file/d/13crh8d5et4AgGuBDrhfcnjddUVq8RLpO/view?usp=drive_link)

### 🔍 Página de Producto
- [Detalle del producto](https://drive.google.com/file/d/13crh8d5et4AgGuBDrhfcnjddUVq8RLpO/view?usp=drive_link)

### 🛒 Carrito y Checkout
- [Carrito de compras](https://drive.google.com/file/d/1k8JKR2bx6yJyJZQJDqU54hYKvXQnTBjg/view?usp=drive_link)
- [Formulario de pago - Checkout 1](https://drive.google.com/file/d/1TPa3Czv1kKFe93zUtmxh8fSyM_apmL1t/view?usp=drive_link)
- [Formulario de pago - Checkout 2](https://drive.google.com/file/d/1Cxb1rAf8hNnaYTVLfdqUtARBlZqjfvPO/view?usp=drive_link)

### 📦 Confirmación de Pedido
- [Resumen de pedido](https://drive.google.com/file/d/1VlYbqi90KGa4hPgOEvjCX86Po2ymCqkl/view?usp=drive_link)

---

## 🧮 Generador de Lista de Precios

Durante la operación del sitio, se desarrolló una función personalizada en Excel conectada al backend de WordPress que permitía generar y actualizar en tiempo real una lista completa de precios del catálogo, incluyendo:

    Nombre del producto

    SKU

    Precio de venta actual

    Estado de stock

    Etiquetas de proveedor

Esta funcionalidad facilitó el control de precios y la atención a clientes mayoristas con información constantemente actualizada.

🧾 [Lista de precios personalizada](https://docs.google.com/spreadsheets/d/1iTIjpUMJ_7lxmexuLHaBxFJCBdYfA87G/edit?usp=drive_link)

---

## 🔌 Plugins Más Relevantes

Durante el desarrollo del sitio, se usaron múltiples plugins. A continuación, se destacan 10 de los más importantes:

1. **Elementor / Elementor Pro**  
   Constructor visual avanzado para crear páginas con diseño profesional sin necesidad de código.

2. **WooCommerce**  
   Motor principal de comercio electrónico para gestionar productos, pedidos y pagos.

3. **Checkout Field Editor**  
   Personalización de los campos del formulario de pago, adaptándolos al modelo B2B/B2C.

4. **User Registration (Pro)**  
   Registro de clientes con campos personalizados y lógica condicional avanzada.

5. **Code Snippets**  
   Inserción de fragmentos de código PHP sin editar archivos del tema directamente.

6. **Dynamic Visibility for Elementor**  
   Control de visibilidad de secciones en Elementor según condiciones específicas del usuario.

7. **PDF Invoices & Packing Slips**  
   Generación automática de facturas PDF para cada pedido.

8. **Export Products, Orders & Customers**  
   Exportación de pedidos, productos y clientes en formatos CSV o XML para gestión externa.

9. **All-in-One WP Migration**  
   Facilitó la migración y respaldo del sitio durante su transición y rediseño.

10. **Loco Translate**  
   Traducción de cadenas de texto directamente desde el panel de WordPress.

---

## ⚠️ Notas Finales

- **Este repositorio no contiene archivos sensibles** como claves API, archivos de configuración (`wp-config.php`), ni la carpeta `/uploads`.
- Los plugins activos en producción se desactivaron para efectos de respaldo.
- Cualquier archivo mayor a 100MB ha sido excluido del push a GitHub, y se ha proporcionado su descarga externa.

---

## 👨‍💻 Autor

Este desarrollo fue realizado por Juan Manuel Pérez García como parte del ecosistema de proyectos digitales de Ovalo24 Perú / Tecpreciazos / Modatech Perú.

