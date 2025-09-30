
<style>
/* 1. RESET Y BASE */
body {
    margin: 0;
    padding: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
    line-height: 1.6;
}

/* 2. CONTENEDOR PRINCIPAL FLEXBOX */
.container-doc {
    display: flex;
    max-width: 1400px; 
    margin: 0 auto;
    padding-top: 10px;
}

/* 3. BARRA LATERAL (ÍNDICE) - FIJA A LA IZQUIERDA */
.sidebar {
    width: 300px; /* Ancho fijo para el índice */
    padding: 20px;
    padding-top: 40px; 
    border-right: 1px solid #eee;
    background-color: #f9f9f9;
    
    /* La magia de la columna fija: */
    position: sticky; 
    top: 0; 
    height: 100vh; /* Ocupa toda la altura visible */
    overflow-y: auto; /* Permite hacer scroll solo en el índice */
}

/* 4. CONTENIDO PRINCIPAL (DERECHA) */
.content-area {
    flex: 1; /* Ocupa todo el espacio restante */
    padding: 20px 40px;
}

/* 5. ESTILOS DE NAVEGACIÓN */
.sidebar ul {
    list-style: none;
    padding-left: 10px;
    margin-top: 5px;
}
.sidebar ul ul {
    border-left: 2px solid #ddd;
    padding-left: 10px;
    margin-top: 2px;
}
.sidebar a {
    text-decoration: none;
    color: #0366d6;
}
.sidebar a:hover {
    text-decoration: underline;
}
</style>

<div class="container-doc">
    <div class="sidebar">
        
        # 🗺️ Índice General de Productos
        
        
        <hr>
        ## PRODUCTO 1
        <a id="producto1"></a>

        ### 🖥️ Backstage (Uso Interno)
        1.  **[Actividades Pendientes del Equipo](#producto1-backstage-actividades)**
        2.  **[Definiciones](#producto1-backstage-definiciones)**
            * [Brief (CV)](#producto1-brief-cv)
            * [Guía de Estimación](#producto1-guia-estimacion)
            * [Priorización](#producto1-priorizacion)
        3.  **[Proceso de Diseño](#producto1-backstage-proceso-diseno)**
            * [Investigación](#producto1-investigacion)
            * [Ejecución](#producto1-ejecucion)
        4.  **[Validación](#producto1-backstage-validacion)**
        5.  **[Hand off](#producto1-backstage-hand-off)**
            * [Proceso para agregar componentes a BAU](#producto1-proceso-bau)
            * [DS template](#producto1-ds-template)
            * [User story template](#producto1-user-story-template)
            * [Alcance del cross review](#producto1-cross-review)
        6.  **[Implementación](#producto1-backstage-implementacion)**
            * [QA template](#producto1-qa-template)
        7.  **[Cierre](#producto1-backstage-cierre)**

        ### 👤 Frontstage (Para el Cliente)
        1.  **[Actividades Pendientes de Cliente](#producto1-frontstage-actividades-cliente)**
        2.  **[Minutas](#producto1-frontstage-minutas)**
        3.  **[PRD (Documento de Requerimientos)](#producto1-frontstage-prd)**
        4.  **[Roadmap](#producto1-frontstage-roadmap)**
        5.  **[Diseños y Entregables](#producto1-frontstage-disenos)**
        6.  **[Documentos y Archivos](#producto1-frontstage-documentos-archivos)**


        <hr>
        ## PRODUCTO 2
        <a id="producto2"></a>

        ### 🖥️ Backstage (Uso Interno)
        1.  **[Actividades Pendientes del Equipo](#producto2-backstage-actividades)**
        2.  **[Definiciones](#producto2-backstage-definiciones)**
            * [Brief (CV)](#producto2-brief-cv)
            * [Guía de Estimación](#producto2-guia-estimacion)
            * [Priorización](#producto2-priorizacion)
        3.  **[Proceso de Diseño](#producto2-backstage-proceso-diseno)**
            * [Investigación](#producto2-investigacion)
            * [Ejecución](#producto2-ejecucion)
        4.  **[Validación](#producto2-backstage-validacion)**
        5.  **[Hand off](#producto2-backstage-hand-off)**
            * [Proceso para agregar componentes a BAU](#producto2-proceso-bau)
            * [DS template](#producto2-ds-template)
            * [User story template](#producto2-user-story-template)
            * [Alcance del cross review](#producto2-cross-review)
        6.  **[Implementación](#producto2-backstage-implementacion)**
            * [QA template](#producto2-qa-template)
        7.  **[Cierre](#producto2-backstage-cierre)**

        ### 👤 Frontstage (Para el Cliente)
        1.  **[Actividades Pendientes de Cliente](#producto2-frontstage-actividades-cliente)**
        2.  **[Minutas](#producto2-frontstage-minutas)**
        3.  **[PRD (Documento de Requerimientos)](#producto2-frontstage-prd)**
        4.  **[Roadmap](#producto2-frontstage-roadmap)**
            
        <hr>
        ## PRODUCTO 3
        <a id="producto3"></a>
        <hr>
        ## PRODUCTO 4
        <a id="producto4"></a>
        <hr>
        ## PRODUCTO 5
        <a id="producto5"></a>
        </div>
    <div class="content-area">

        # 📚 Contenido Detallado de la Documentación

        # PRODUCTO 1
        
        ## 🖥️ Backstage
        
        ### 1. Actividades Pendientes del Equipo
        <a id="producto1-backstage-actividades"></a> 
        Contenido de la actividad pendiente del Producto 1...
        
        ### Brief (CV)
        <a id="producto1-brief-cv"></a>
        Contenido del Brief CV del Producto 1...

        </div>
</div>