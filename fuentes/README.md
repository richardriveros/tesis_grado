# Directorio de Fuentes

Este directorio almacena copias digitales y materiales relacionados con las fuentes bibliográficas documentadas en el arqueo.

## Estructura de Archivos

Las fuentes se organizan por tipo y por año:

```
fuentes/
├── libros/
│   └── 2014/
│       └── F001_Hernandez_Metodologia/
│           ├── README.md
│           └── extractos/
├── articulos/
│   └── 2026/
├── tesis/
│   └── 2025/
├── conferencias/
│   └── 2024/
├── web/
│   └── 2026/
└── tecnicos/
    └── 2025/
```

## Organización

1. **Por Tipo**: Cada tipo de fuente tiene su directorio principal
   - `libros/`: Libros académicos y textos de referencia
   - `articulos/`: Artículos de revistas científicas
   - `tesis/`: Otras tesis doctorales y de maestría
   - `conferencias/`: Actas y memorias de conferencias
   - `web/`: Recursos y documentos web
   - `tecnicos/`: Documentos técnicos, reportes y manuales

2. **Por Año**: Dentro de cada tipo, subdirectorios por año de publicación

3. **Por Fuente**: Cada fuente tiene su propio directorio con formato:
   - `F###_ApellidoPrimerAutor_PalabraClave/`
   - Ejemplo: `F001_Hernandez_Metodologia/`

## Contenido por Fuente

Cada directorio de fuente debe contener:

- **README.md**: Información básica de la fuente (copia del registro del arqueo)
- **extractos/**: Fragmentos relevantes o citas textuales
- **notas/**: Notas y análisis de la fuente
- **metadata.json**: Metadatos estructurados (opcional)

## Consideraciones de Derechos de Autor

⚠️ **IMPORTANTE**: 
- No almacene copias completas de obras con derechos de autor
- Solo incluya extractos breves para propósitos de citación académica
- Respete las leyes de propiedad intelectual
- Para obras con acceso abierto, incluya el enlace al repositorio oficial

## Cómo Agregar Materiales de una Fuente

1. Identifique el ID de la fuente en el arqueo (ej. F001)
2. Navegue al directorio correspondiente por tipo y año
3. Cree el subdirectorio con formato `F###_Apellido_PalabraClave/`
4. Agregue el README.md con información básica
5. Incluya solo extractos relevantes o enlaces
6. Documente las páginas y secciones consultadas

## Ejemplo

Ver `libros/2014/F001_Hernandez_Metodologia/` para una estructura de referencia.

---
*Última actualización: 2026-01-21*
