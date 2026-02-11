# Template de Evaluacion de Producto para Importacion

Template reutilizable para evaluar si un producto candidato vale la pena importar
desde China para reventa en Argentina (MercadoLibre, tiendas web, retail).

Fuentes consultadas para armar este template:
- https://bluemail.com.ar/blog/importaciones/costo-landed-como-calcular-el-costo-total-de-tu-importacion
- https://comoimportarenargentina.com.ar/costos-de-importacion-argentina/
- https://despachante-aduana.com/como-importar-productos-desde-china/
- https://santandertrade.com/es/portal/analizar-mercados/argentina/tramites-aduaneros-importacion
- https://www.argentina.gob.ar/cnce/investigaciones/medidasvigentes
- https://es.sino-shipping.com/flete-china-argentina/
- https://academia.nubimetrics.com/demanda-producto
- https://qualityinspection.org/checklist-for-importers/
- https://tacticasdeimportacion.com/margen-ganancia-importacion-productos/

---

## INSTRUCCIONES DE USO

1. Copiar este template completo para cada producto candidato
2. Completar TODOS los campos (marcar "N/A" o "POR INVESTIGAR" si falta info)
3. Al final, completar la seccion de SCORING para obtener un puntaje numerico
4. Comparar puntajes entre productos para priorizar cuales importar primero
5. Un producto con puntaje menor a 50/100 normalmente NO vale la pena

---

## SECCION 0: DATOS BASICOS DEL ANALISIS

```
Fecha del analisis:        _______________
Analista:                  _______________
Producto:                  _______________
Version del analisis:      ___ (1, 2, 3... para re-evaluaciones)
Estado:                    [ ] Candidato  [ ] Aprobado  [ ] Descartado
Motivo de descarte (si aplica): _______________
```

---

## SECCION 1: IDENTIFICACION DEL PRODUCTO

### 1.1 Descripcion general

```
Nombre del producto:              _______________
Nombre en ingles (para buscar):   _______________
Nombre en chino (si se tiene):    _______________
Categoria general:                _______________
Subcategoria:                     _______________
Material principal:               _______________
Uso / funcion:                    _______________
```

### 1.2 Clasificacion arancelaria (NCM / HS Code)

```
Posicion NCM (8 digitos):         _______________
Descripcion oficial NCM:          _______________
Capitulo NCM:                     _______________
Seccion del arancel:              _______________
Fuente de la clasificacion:       [ ] Despachante  [ ] VUCE  [ ] Estimacion propia
Nivel de confianza:               [ ] Confirmado por despachante  [ ] Estimado (VERIFICAR)
```

**IMPORTANTE:** La clasificacion NCM determina TODOS los impuestos y requisitos.
Un error aqui cambia radicalmente los costos. Siempre confirmar con despachante
antes de hacer un pedido grande.

**Donde verificar:**
- VUCE (Ventanilla Unica de Comercio Exterior): https://www.vuce.gob.ar
- Sistema Maria (ARCA/ex-AFIP): consultar con despachante
- Arancel integrado del MERCOSUR

### 1.3 Busqueda en proveedores

```
Palabras clave en Alibaba:       _______________
Palabras clave en 1688.com:      _______________
Palabras clave en Made-in-China: _______________
Palabras clave en Global Sources: _______________
Categoria en Alibaba:            _______________
Cantidad de proveedores encontrados: _______________
Rango de precios FOB encontrados:    USD ___ a USD ___
```

---

## SECCION 2: COSTOS REALES DE IMPORTACION

### 2.1 Costo del producto (origen)

```
Precio FOB por unidad:                   USD ___
Precio EXW por unidad (si aplica):       USD ___
Moneda de negociacion:                   [ ] USD  [ ] RMB/CNY
Costo del molde / tooling (si aplica):   USD ___
Costo de packaging personalizado:        USD ___
Costo de etiquetado especial:            USD ___
Costo de muestra(s):                     USD ___
Descuento por volumen a partir de:       ___ unidades = USD ___ c/u
Forma de pago acordada:                  [ ] 30/70  [ ] TT 100%  [ ] L/C  [ ] Trade Assurance
```

### 2.2 Datos fisicos del producto (para calcular flete)

```
Peso neto por unidad:                    ___ kg
Peso bruto por unidad (con packaging):   ___ kg
Dimensiones por unidad (cm):             ___ x ___ x ___ cm
Volumen por unidad:                      ___ m3

Unidades por caja master (carton):       ___
Peso de caja master:                     ___ kg
Dimensiones caja master (cm):            ___ x ___ x ___ cm
Volumen caja master:                     ___ m3 (= ___ CBM)

Cantidad total a importar:               ___ unidades
Total de cajas master:                   ___
Volumen total del embarque:              ___ CBM
Peso total del embarque:                 ___ kg
```

### 2.3 Flete internacional

```
TIPO DE ENVIO:  [ ] Maritimo FCL  [ ] Maritimo LCL  [ ] Aereo  [ ] Courier

--- MARITIMO ---
Puerto de origen:                        _______________
Puerto de destino:                       [ ] Buenos Aires  [ ] Otro: ___
Tipo de contenedor:                      [ ] 20GP  [ ] 40GP  [ ] 40HQ
Costo del flete:                         USD ___
BAF (Bunker Adjustment Factor):          USD ___
PSS (Peak Season Surcharge):             USD ___
Otros recargos:                          USD ___
Tiempo de transito estimado:             ___ dias (referencia: 38-42 dias China-Buenos Aires)

--- AEREO ---
Costo por kg:                            USD ___
Peso cobrable (mayor entre real y volumetrico): ___ kg
Costo total aereo:                       USD ___
Tiempo de transito estimado:             ___ dias

--- COURIER (DDP) ---
Costo total:                             USD ___
Incluye impuestos:                       [ ] Si  [ ] No
Tiempo de transito estimado:             ___ dias

Flete interno China (fabrica a puerto/aeropuerto): USD ___
```

### 2.4 Seguro internacional

```
Tipo de seguro:                          [ ] Basico  [ ] All Risk
Valor asegurado (CIF + 10% normalmente): USD ___
Prima del seguro:                        USD ___ (referencia: 0.3%-1% del valor CIF)
Seguro estadistico (1% del CFR):         USD ___
```

### 2.5 Valor en aduana (base imponible)

```
Valor FOB declarado:                     USD ___
(+) Flete internacional:                 USD ___
(+) Seguro:                              USD ___
(=) VALOR CIF:                           USD ___
```

### 2.6 Tributos aduaneros en Argentina

```
IMPUESTO                          | ALICUOTA    | BASE DE CALCULO         | MONTO USD
----------------------------------|-------------|-------------------------|----------
Derecho de Importacion (DI)       | ____%       | Sobre CIF               | USD ___
Tasa de Estadistica (TE)          | 0.5%        | Sobre CIF               | USD ___
IVA                               | 21% o 10.5% | Sobre (CIF+DI+TE)      | USD ___
IVA Adicional                     | 20% o 10%   | Sobre (CIF+DI+TE)      | USD ___
Percepcion de Ganancias           | 6% o 3%     | Sobre (CIF+DI+TE)      | USD ___
Percepcion de Ingresos Brutos     | _____%      | Sobre (CIF+DI+TE)      | USD ___
Tasa de Comprobacion de Destino   | ____%       | (si aplica)             | USD ___
Derecho Antidumping (si aplica)   | ____%       | Sobre CIF               | USD ___
----------------------------------|-------------|-------------------------|----------
TOTAL TRIBUTOS ADUANEROS          |             |                         | USD ___
```

**Notas sobre tributos:**
- Derecho de Importacion: va de 0% a 35% segun NCM. Los rangos comunes son 0%, 8%, 14%, 16%, 18%, 20%, 25%, 35%
- IVA: 21% general, 10.5% para ciertos bienes de capital, informatica y telecomunicaciones
- IVA Adicional: 20% si sos inscripto en IVA, 10% para ciertos bienes
- Percepcion de Ganancias: 6% general, 3% para inscriptos en ganancias
- Percepcion de IIBB: varia por provincia (consultar)
- IVA e IIBB se recuperan como credito fiscal. Ganancias se recupera a fin de ano
- Verificar antidumping vigente: https://www.argentina.gob.ar/cnce/investigaciones/medidasvigentes

### 2.7 Gastos de despacho y operativos en Argentina

```
CONCEPTO                                  | MONTO USD
------------------------------------------|----------
Honorarios despachante de aduana           | USD ___
Tasa de oficializacion (aduana)            | USD 10
Tasa de digitalizacion (aduana)            | USD 28
Gastos de terminal portuaria / deposito    | USD ___
Desconsolidado (si es LCL)                | USD ___
Tasa AGP (ex Admin. Gral. de Puertos)     | USD ___
Flete interno (puerto/aeropuerto a deposito)| USD ___
Gastos del agente de carga (forwarder)     | USD ___
Almacenaje (si hay demoras)               | USD ___
Verificacion de canal (rojo/naranja)       | USD ___
Gastos bancarios (transferencia, etc.)     | USD ___
Seguro interno (deposito)                 | USD ___
Otros gastos:                             | USD ___
------------------------------------------|----------
TOTAL GASTOS OPERATIVOS                   | USD ___
```

### 2.8 COSTO LANDED TOTAL (resumen)

```
CONCEPTO                          | MONTO USD
----------------------------------|----------
(A) Costo del producto (FOB total)| USD ___
(B) Flete internacional           | USD ___
(C) Seguro                        | USD ___
(D) Tributos aduaneros            | USD ___
(E) Gastos de despacho/operativos | USD ___
----------------------------------|----------
COSTO LANDED TOTAL                | USD ___
COSTO LANDED POR UNIDAD           | USD ___

Factor de importacion = Costo Landed / Costo FOB = ___x
(Referencia tipica: 1.8x a 3.5x dependiendo del producto y arancel)
```

---

## SECCION 3: ANALISIS DE MERCADO ARGENTINO

### 3.1 Investigacion de precios de venta

```
CANAL DE VENTA                | PRECIO MINIMO | PRECIO PROMEDIO | PRECIO MAXIMO
------------------------------|---------------|-----------------|---------------
MercadoLibre (publicacion)    | ARS ___       | ARS ___         | ARS ___
MercadoLibre (en USD aprox)   | USD ___       | USD ___         | USD ___
Tiendas online (ej. Tiendanube)| ARS ___      | ARS ___         | ARS ___
Retail fisico (si aplica)     | ARS ___       | ARS ___         | ARS ___
Precio mayorista (si aplica)  | ARS ___       | ARS ___         | ARS ___

Tipo de cambio usado:         USD 1 = ARS ___
Fecha del relevamiento:       _______________
```

### 3.2 Costos de venta en MercadoLibre

```
Comision de MercadoLibre:              ___% (rango: 11.8% a 17.14% segun categoria)
Costo fijo por unidad (si aplica):     ARS ___
Costo de envio gratis (si ofreces):    ARS ___
Costo de publicidad (si usas):         ARS ___ por venta estimada
Costo Mercado Pago (si cobras cuotas): ___%
Percepcion IIBB MercadoLibre:          ___%
Impuesto al debito/credito:            ___%

Precio de venta neto (despues de comisiones): ARS ___  =>  USD ___
```

### 3.3 Analisis de competencia

```
Cantidad de publicaciones activas en ML:      ___
Cantidad de vendedores unicos:                ___
Vendedores MercadoLider:                      ___ de ___
Hay marcas dominantes:                        [ ] Si: ___  [ ] No
Tipo de competencia:                          [ ] Importadores  [ ] Fabricantes locales  [ ] Mixto
Barrera de entrada percibida:                 [ ] Baja  [ ] Media  [ ] Alta

Vendedor #1 (lider):
  - Nombre:               ___
  - Reputacion:           ___
  - Precio:               ARS ___
  - Ventas estimadas/mes: ___
  - Diferencial:          ___

Vendedor #2:
  - Nombre:               ___
  - Reputacion:           ___
  - Precio:               ARS ___
  - Ventas estimadas/mes: ___
  - Diferencial:          ___

Vendedor #3:
  - Nombre:               ___
  - Reputacion:           ___
  - Precio:               ARS ___
  - Ventas estimadas/mes: ___
  - Diferencial:          ___
```

**Herramientas para analizar competencia en MercadoLibre:**
- Nubimetrics (https://www.nubimetrics.com) - ventas estimadas, tendencias, demanda
- Real Trends (https://www.real-trends.com) - seguimiento de competidores
- Extension de Chrome "MercadoLibre Product Analytics"
- Busqueda manual: ordenar por "Mas vendidos" para ver lideres

### 3.4 Demanda y volumen de mercado

```
Volumen de busquedas en ML (Nubimetrics):     ___
Tendencia de busqueda:                         [ ] Creciente  [ ] Estable  [ ] Decreciente
Ventas estimadas del mercado/mes:              ___ unidades
Precio promedio de venta:                      ARS ___
Tamano de mercado estimado (mensual):          ARS ___

Google Trends Argentina (tendencia):           [ ] Creciente  [ ] Estable  [ ] Decreciente
Volumen de busqueda Google (si aplica):        ___ busquedas/mes
```

### 3.5 Estacionalidad

```
Es un producto estacional:     [ ] Si  [ ] No  [ ] Parcialmente

Si es estacional:
  Meses de alta demanda:       _______________
  Meses de baja demanda:       _______________
  Variacion de precio entre temporadas: ___%
  Pico de ventas:              Mes ___
  Valle de ventas:             Mes ___

Consideraciones:
  Tiempo para que llegue el producto (produccion + envio): ___ semanas
  Hay que pedir con ___ meses de anticipacion al pico
```

### 3.6 Potencial de diferenciacion

```
Puedo agregar valor con:
  [ ] Marca propia (branding)
  [ ] Packaging premium
  [ ] Bundle / combo con otros productos
  [ ] Garantia extendida
  [ ] Manual en espanol
  [ ] Servicio post-venta
  [ ] Personalizacion (colores, grabado, etc.)
  [ ] Accesorios incluidos
  [ ] Certificacion de calidad visible
  [ ] Contenido/tutoriales de uso
  [ ] Otro: _______________

Diferencial principal vs. competencia: _______________
```

---

## SECCION 4: REGULACIONES Y CERTIFICACIONES

### 4.1 Organismos que intervienen

```
ORGANISMO    | INTERVIENE | MOTIVO                                    | ESTADO
-------------|------------|-------------------------------------------|-------
ARCA (Aduana)| SI siempre | Despacho de importacion                  | -
ENACOM       | [ ] Si/No  | Equipos con radiofrecuencia/telecom       | ___
ANMAT        | [ ] Si/No  | Contacto con piel, alimentos, cosmeticos  | ___
SENASA       | [ ] Si/No  | Origen animal/vegetal                     | ___
IRAM/INTI    | [ ] Si/No  | Normas de seguridad electrica/juguetes    | ___
SEDRONAR     | [ ] Si/No  | Precursores quimicos                      | ___
RENAR/ANMaC  | [ ] Si/No  | Armas, explosivos                        | ___
Sec. Energia | [ ] Si/No  | Eficiencia energetica                    | ___
Otro:        | [ ] Si/No  | ___                                       | ___
```

### 4.2 Certificaciones necesarias

```
CERTIFICACION        | REQUERIDA | COSTO APROX | TIEMPO APROX    | ESTADO
---------------------|-----------|-------------|-----------------|-------
Homologacion ENACOM  | [ ] Si/No | USD ___     | 10-12 semanas   | ___
Registro ANMAT       | [ ] Si/No | USD ___     | ___ semanas     | ___
Certificado SENASA   | [ ] Si/No | USD ___     | ___ semanas     | ___
Marca S (IRAM)       | [ ] Si/No | USD ___     | ___ semanas     | ___
Certificado INTI     | [ ] Si/No | USD ___     | ___ semanas     | ___
Etiquetado IRAM      | [ ] Si/No | USD ___     | ___ semanas     | ___
Eficiencia energetica| [ ] Si/No | USD ___     | ___ semanas     | ___
Otro:                | [ ] Si/No | USD ___     | ___ semanas     | ___
---------------------|-----------|-------------|-----------------|-------
TOTAL CERTIFICACIONES|           | USD ___     |                 |
```

**NOTA:** Desde 2025, Argentina reconoce ciertas certificaciones internacionales
(FCC, CE, etc.) para facilitar importaciones en algunas categorias. Verificar si
el producto califica en: https://www.argentina.gob.ar/noticias/el-gobierno-elimina-barreras-tecnicas

### 4.3 Medidas antidumping

```
El producto tiene antidumping vigente:  [ ] Si  [ ] No  [ ] Verificar
Derecho antidumping:                    ___% o USD ___ por unidad
Numero de resolucion:                   _______________
Fecha de vencimiento de la medida:      _______________
Link de consulta:                       https://www.argentina.gob.ar/cnce/investigaciones/medidasvigentes

Hay investigacion antidumping en curso: [ ] Si  [ ] No
```

### 4.4 Restricciones especificas

```
El producto es de importacion PROHIBIDA:        [ ] Si  [ ] No
El producto requiere licencia especial:          [ ] Si  [ ] No
Hay cupos o cuotas de importacion:               [ ] Si  [ ] No
Requiere etiquetado especifico argentino:        [ ] Si  [ ] No
  Idioma espanol obligatorio:                    [ ] Si  [ ] No
  Datos del importador en etiqueta:              [ ] Si  [ ] No
  Composicion/materiales en etiqueta:            [ ] Si  [ ] No
  Instrucciones de uso en espanol:               [ ] Si  [ ] No
  Talle/medidas en sistema metrico:              [ ] Si  [ ] No
Requiere manual en espanol:                      [ ] Si  [ ] No
Requiere garantia legal obligatoria:             [ ] Si  [ ] No  (ley 24.240: 6 meses minimo)
```

**PRODUCTOS CON RESTRICCIONES CONOCIDAS (verificar actualizacion):**
- Ropa y calzado: requieren etiquetado IRAM especifico
- Juguetes: requieren certificacion de seguridad
- Electronica con radiofrecuencia: ENACOM obligatorio
- Alimentos/cosmeticos/contacto con piel: ANMAT
- Celulares: restriccion historica (verificar estado actual)

---

## SECCION 5: EVALUACION DEL PROVEEDOR

### 5.1 Datos del proveedor principal

```
Nombre de la empresa:               _______________
Plataforma donde se encontro:       [ ] Alibaba  [ ] 1688  [ ] Made-in-China  [ ] Otro: ___
Tipo:                                [ ] Fabricante  [ ] Trading Company  [ ] Ambos
URL del perfil:                      _______________
Ubicacion (ciudad, provincia):       _______________
Anos en el negocio:                  ___
Facturacion anual declarada:         USD ___

Verificaciones:
  [ ] Trade Assurance (Alibaba)
  [ ] Verified Supplier
  [ ] Gold Supplier (anos: ___)
  [ ] Auditoria de terceros (SGS, Bureau Veritas, TUV, etc.)
  [ ] Licencia de negocios verificada
  [ ] Tiene certificaciones ISO: ___
  [ ] Exporta a Latinoamerica actualmente
```

### 5.2 Capacidad y condiciones

```
MOQ (cantidad minima de pedido):     ___ unidades
MOQ negociado:                       ___ unidades
Capacidad de produccion mensual:     ___ unidades
Tiempo de produccion (lead time):    ___ dias
Puede hacer OEM/marca propia:        [ ] Si  [ ] No
Puede personalizar packaging:        [ ] Si  [ ] No
Certificaciones del producto que tiene: _______________
Acepta inspeccion de terceros:       [ ] Si  [ ] No
```

### 5.3 Comunicacion y confiabilidad

```
Tiempo de respuesta promedio:        ___ horas
Idioma de comunicacion:              [ ] Ingles  [ ] Espanol  [ ] Otro: ___
Calidad de la comunicacion:          [ ] Excelente  [ ] Buena  [ ] Regular  [ ] Mala
Tiene experiencia con Argentina:     [ ] Si  [ ] No  [ ] No sabe
Acepta enviar muestras:              [ ] Si (costo: USD ___)  [ ] No
Medio de comunicacion:               [ ] WhatsApp  [ ] WeChat  [ ] Email  [ ] Alibaba Chat
```

### 5.4 Proveedores alternativos (backup)

```
Proveedor alternativo #1:
  Nombre:     _______________
  Precio FOB: USD ___
  MOQ:        ___
  Notas:      _______________

Proveedor alternativo #2:
  Nombre:     _______________
  Precio FOB: USD ___
  MOQ:        ___
  Notas:      _______________
```

---

## SECCION 6: LOGISTICA Y OPERACION

### 6.1 Caracteristicas del envio

```
Tipo de carga:                    [ ] General  [ ] Peligrosa  [ ] Refrigerada  [ ] Sobredimensionada
Fragilidad:                       [ ] Alta  [ ] Media  [ ] Baja
Requiere empaque especial:        [ ] Si: ___  [ ] No
Requiere palletizado:             [ ] Si  [ ] No
Apilable:                         [ ] Si  [ ] No
Sensible a humedad:               [ ] Si  [ ] No
Sensible a temperatura:           [ ] Si  [ ] No
Tiene baterias de litio:          [ ] Si (requiere documentacion especial)  [ ] No
Contiene liquidos:                [ ] Si  [ ] No
Contiene imanes:                  [ ] Si  [ ] No
```

### 6.2 Modalidad de envio recomendada

```
MODALIDAD      | COSTO TOTAL | COSTO/UNIDAD | TIEMPO    | RECOMENDADO
---------------|-------------|--------------|-----------|------------
Maritimo FCL   | USD ___     | USD ___      | ___ dias  | [ ]
Maritimo LCL   | USD ___     | USD ___      | ___ dias  | [ ]
Aereo          | USD ___     | USD ___      | ___ dias  | [ ]
Courier/Express| USD ___     | USD ___      | ___ dias  | [ ]

Modalidad elegida: _______________
Justificacion:     _______________
```

**Referencia de costos de flete (actualizacion: consultar cotizacion vigente):**
- Maritimo FCL 20GP China-Buenos Aires: ~USD 2,750-3,300
- Maritimo FCL 40GP China-Buenos Aires: ~USD 3,000-3,800
- Maritimo LCL: ~USD 30-200 por CBM (varia por temporada)
- Aereo (>1000kg): ~USD 8-12 por kg
- Tiempo de transito maritimo: 38-42 dias promedio

### 6.3 Timeline completo

```
ETAPA                                    | TIEMPO ESTIMADO | FECHA ESTIMADA
-----------------------------------------|-----------------|---------------
Negociacion con proveedor                | ___ dias        | ___
Envio y recepcion de muestras            | ___ dias        | ___
Aprobacion de muestras                   | ___ dias        | ___
Produccion                               | ___ dias        | ___
Inspeccion pre-embarque (si aplica)      | ___ dias        | ___
Transito (fabrica a puerto China)        | ___ dias        | ___
Transito internacional                   | ___ dias        | ___
Llegada a puerto + descarga              | ___ dias        | ___
Despacho aduanero                        | ___ dias        | ___
Transporte interno (puerto a deposito)   | ___ dias        | ___
Preparacion para venta (etiquetado, etc.)| ___ dias        | ___
-----------------------------------------|-----------------|---------------
TIEMPO TOTAL ESTIMADO                    | ___ dias        |
```

### 6.4 Almacenamiento y distribucion

```
Donde se almacenara:                [ ] Deposito propio  [ ] Deposito terceros  [ ] Fulfillment ML
Costo de almacenaje mensual:        ARS ___ o USD ___
Espacio requerido:                  ___ m2 o ___ m3
Condiciones especiales de almacen:  _______________
Usa Mercado Libre Full:             [ ] Si  [ ] No  [ ] A evaluar
Logistica de envio al comprador:    [ ] ML Full  [ ] ML Flex  [ ] Correo Argentino  [ ] Transporte propio
```

---

## SECCION 7: ANALISIS FINANCIERO Y VIABILIDAD

### 7.1 Inversion inicial requerida

```
CONCEPTO                                  | MONTO USD
------------------------------------------|----------
Costo del producto (FOB x cantidad)       | USD ___
Muestras                                  | USD ___
Flete internacional                       | USD ___
Seguro                                    | USD ___
Tributos aduaneros                        | USD ___
Gastos de despacho y operativos           | USD ___
Certificaciones (si aplica)               | USD ___
Flete interno                             | USD ___
Packaging/etiquetado local (si aplica)    | USD ___
Capital de trabajo (ML cobra diferido)    | USD ___
Otros:                                    | USD ___
------------------------------------------|----------
INVERSION TOTAL REQUERIDA                 | USD ___
```

### 7.2 Estructura de costos por unidad

```
CONCEPTO                              | POR UNIDAD (USD)  | % DEL TOTAL
--------------------------------------|-------------------|------------
Costo FOB                             | USD ___           | ___%
Flete internacional (proporcional)    | USD ___           | ___%
Seguro (proporcional)                 | USD ___           | ___%
Tributos aduaneros                    | USD ___           | ___%
Gastos de despacho (proporcional)     | USD ___           | ___%
Costo LANDED por unidad               | USD ___           | 100%

(+) Costos de venta:
Comision MercadoLibre                  | USD ___           | ___%
Envio (si ofreces gratis)             | USD ___           | ___%
Publicidad ML (si usas)               | USD ___           | ___%
Impuestos s/venta (IIBB, etc.)        | USD ___           | ___%
Embalaje para envio individual         | USD ___           | ___%
--------------------------------------|-------------------|------------
COSTO TOTAL POR UNIDAD                | USD ___           |
```

### 7.3 Calculo de margen y rentabilidad

```
Precio de venta unitario (ARS):                ARS ___
Precio de venta unitario (USD al TC ___):       USD ___
(-) Costo total por unidad:                     USD ___
(=) MARGEN BRUTO por unidad:                    USD ___
    Margen bruto (%):                           ___%

(-) Gastos fijos prorrateados (alquiler, etc.): USD ___
(-) Costo de devolucion estimado (___% de ventas): USD ___
(=) MARGEN NETO ESTIMADO por unidad:            USD ___
    Margen neto (%):                            ___%
```

**Margenes de referencia:**
- Margen bruto minimo recomendado: 40% (para cubrir imprevistos)
- Margen bruto ideal: 50-70%
- Si el margen bruto es menor a 30%, el producto es RIESGOSO
- Considerar que el tipo de cambio puede variar significativamente

### 7.4 Proyeccion de ventas y ROI

```
Ventas estimadas por mes:                       ___ unidades
Facturacion mensual estimada:                   USD ___
Ganancia neta mensual estimada:                 USD ___

TIEMPO DE RECUPERO DE INVERSION:
  Inversion total:                              USD ___
  Ganancia neta mensual:                        USD ___
  Meses para recuperar inversion:               ___ meses

ROI DE LA OPERACION:
  ROI = (Ganancia neta total / Inversion) x 100 = ___%

  Escenario optimista (ventas x 1.3):          ROI = ___%
  Escenario base:                               ROI = ___%
  Escenario pesimista (ventas x 0.5):          ROI = ___%
```

### 7.5 Analisis de sensibilidad

```
Que pasa si...                              | Impacto en margen
--------------------------------------------|-------------------
El dolar sube 20%                           | ___%
El dolar baja 20%                           | ___%
El flete sube 50%                           | ___%
El proveedor sube precio 15%               | ___%
ML sube comisiones 3%                       | ___%
Vendo 50% menos de lo estimado             | ___%
Debo vender con 20% descuento              | ___%
Hay 30% de stock que no se vende (queda)   | ___%
```

---

## SECCION 8: ANALISIS DE RIESGOS

### 8.1 Riesgos identificados

```
RIESGO                                    | PROBABILIDAD | IMPACTO  | MITIGACION
------------------------------------------|--------------|----------|-------------------
Producto no pasa aduana (certificacion)   | [ ] A/M/B    | [ ] A/M/B| ___
Calidad inferior a la muestra             | [ ] A/M/B    | [ ] A/M/B| ___
Proveedor no cumple plazo                 | [ ] A/M/B    | [ ] A/M/B| ___
Dano en transito                          | [ ] A/M/B    | [ ] A/M/B| ___
Tipo de cambio desfavorable               | [ ] A/M/B    | [ ] A/M/B| ___
Competencia baja precios                  | [ ] A/M/B    | [ ] A/M/B| ___
Demanda menor a la estimada              | [ ] A/M/B    | [ ] A/M/B| ___
Producto defectuoso (devoluciones)        | [ ] A/M/B    | [ ] A/M/B| ___
Cambio regulatorio / nuevos aranceles     | [ ] A/M/B    | [ ] A/M/B| ___
Nuevo antidumping                         | [ ] A/M/B    | [ ] A/M/B| ___
Producto se vuelve obsoleto/moda          | [ ] A/M/B    | [ ] A/M/B| ___
Stock no se vende (capital inmovilizado)  | [ ] A/M/B    | [ ] A/M/B| ___
Estafa del proveedor                      | [ ] A/M/B    | [ ] A/M/B| ___
Problema de propiedad intelectual/marca   | [ ] A/M/B    | [ ] A/M/B| ___
Otro: ___                                 | [ ] A/M/B    | [ ] A/M/B| ___

A = Alto, M = Medio, B = Bajo
```

### 8.2 Plan de contingencia

```
Si el producto no se vende como esperado:
  - Reducir precio a: ARS ___ (margen minimo aceptable: ___%)
  - Vender por mayorista a: ARS ___
  - Vender lote completo a: ARS ___ (perdida maxima aceptable: USD ___)
  - Otro canal: _______________

Si hay problemas de calidad:
  - Proveedor tiene politica de reposicion: [ ] Si  [ ] No
  - Trade Assurance cubre: [ ] Si  [ ] No
  - Tengo proveedor alternativo: [ ] Si  [ ] No
```

### 8.3 Dificultad operativa

```
Nivel de dificultad general:    [ ] Facil  [ ] Moderado  [ ] Dificil  [ ] Muy dificil

Factores que suman dificultad:
  [ ] Requiere certificaciones (cuantas: ___)
  [ ] Producto fragil o voluminoso
  [ ] Tiene baterias de litio
  [ ] Necesita servicio post-venta / garantia tecnica
  [ ] Alta tasa de devoluciones esperada
  [ ] Producto estacional (timing critico)
  [ ] Competencia muy fuerte / precios ajustados
  [ ] Requiere conocimiento tecnico para vender
  [ ] Requiere re-packaging o etiquetado local
  [ ] Producto perecedero o con fecha de vencimiento
  [ ] Otro: ___
```

---

## SECCION 9: SCORING FINAL (PUNTAJE PONDERADO)

Asignar un puntaje de 1 a 10 a cada criterio, luego multiplicar por el peso.
El puntaje maximo posible es 100.

```
CRITERIO                          | PESO | PUNTAJE (1-10) | PONDERADO
----------------------------------|------|----------------|----------
Margen de ganancia                | 20%  | ___            | ___
Demanda del mercado               | 18%  | ___            | ___
Nivel de competencia favorable    | 12%  | ___            | ___
Facilidad regulatoria             | 12%  | ___            | ___
Relacion peso/valor (efic. flete) | 10%  | ___            | ___
Confiabilidad del proveedor       | 8%   | ___            | ___
Inversion inicial accesible       | 7%   | ___            | ___
Potencial de diferenciacion       | 5%   | ___            | ___
Baja estacionalidad / demanda estable | 4%  | ___         | ___
Facilidad operativa               | 4%   | ___            | ___
----------------------------------|------|----------------|----------
PUNTAJE TOTAL                     | 100% |                | ___/100
```

### Guia de interpretacion del puntaje

```
PUNTAJE   | DECISION                | ACCION
----------|-------------------------|-----------------------------------
80-100    | EXCELENTE               | Importar sin dudas. Prioridad alta.
65-79     | BUENO                   | Vale la pena. Verificar riesgos puntuales.
50-64     | REGULAR                 | Proceder con cautela. Hay mejores opciones?
35-49     | DEBIL                   | No recomendable salvo que algo cambie.
0-34      | DESCARTADO              | No importar. Buscar otra opcion.
```

### Guia para asignar puntajes por criterio

**Margen de ganancia (peso 20%):**
- 9-10: Margen bruto >70%
- 7-8: Margen bruto 50-70%
- 5-6: Margen bruto 40-50%
- 3-4: Margen bruto 30-40%
- 1-2: Margen bruto <30%

**Demanda del mercado (peso 18%):**
- 9-10: Producto en tendencia creciente, muchas busquedas, ventas altas
- 7-8: Demanda estable y significativa
- 5-6: Demanda moderada
- 3-4: Demanda baja o nicho muy pequeno
- 1-2: Casi sin demanda o mercado saturado sin espacio

**Nivel de competencia favorable (peso 12%):**
- 9-10: Pocos competidores, ningun lider dominante, espacio para entrar
- 7-8: Competencia moderada, hay espacio para diferenciarse
- 5-6: Competencia fuerte pero hay nichos
- 3-4: Muy competido, dificil diferenciarse
- 1-2: Dominado por grandes marcas o precios imposibles de igualar

**Facilidad regulatoria (peso 12%):**
- 9-10: Sin intervenciones de terceros organismos, despacho directo
- 7-8: Una certificacion simple
- 5-6: Requiere certificacion pero es manejable
- 3-4: Multiples certificaciones, proceso largo
- 1-2: Casi imposible de certificar o producto restringido

**Relacion peso/valor (peso 10%):**
- 9-10: Muy liviano y de alto valor (ej: joyeria, electronica pequena)
- 7-8: Buen ratio peso/valor
- 5-6: Ratio aceptable
- 3-4: Pesado o voluminoso para su valor
- 1-2: Muy pesado o voluminoso, el flete se come el margen

**Confiabilidad del proveedor (peso 8%):**
- 9-10: Fabricante verificado, con auditorias, exporta a LatAm
- 7-8: Verified Supplier con buena trayectoria
- 5-6: Proveedor con Trade Assurance pero sin auditar
- 3-4: Proveedor nuevo o con poca informacion
- 1-2: Sin verificaciones, dudas sobre legitimidad

**Inversion inicial accesible (peso 7%):**
- 9-10: Menos de USD 1,000
- 7-8: USD 1,000 - 3,000
- 5-6: USD 3,000 - 8,000
- 3-4: USD 8,000 - 15,000
- 1-2: Mas de USD 15,000

**Potencial de diferenciacion (peso 5%):**
- 9-10: Muchas formas de agregar valor unico
- 7-8: Varias opciones de diferenciacion
- 5-6: Alguna diferenciacion posible
- 3-4: Dificil diferenciarse (commodity)
- 1-2: Producto generico sin posibilidad de agregar valor

**Baja estacionalidad (peso 4%):**
- 9-10: Se vende parejo todo el ano
- 7-8: Leve estacionalidad
- 5-6: Estacionalidad moderada
- 3-4: Muy estacional (solo unos meses)
- 1-2: Producto de una sola temporada

**Facilidad operativa (peso 4%):**
- 9-10: No requiere servicio post-venta, no fragil, facil de enviar
- 7-8: Operacion simple con alguna consideracion menor
- 5-6: Requiere algo de atencion (embalaje especial, garantia)
- 3-4: Operacion compleja (servicio tecnico, producto fragil)
- 1-2: Muy complejo (baterias, producto delicado, alto retorno)

---

## SECCION 10: DECISION FINAL

```
PUNTAJE OBTENIDO:                   ___/100
DECISION:                           [ ] IMPORTAR  [ ] NO IMPORTAR  [ ] INVESTIGAR MAS

Principales fortalezas del producto:
1. _______________
2. _______________
3. _______________

Principales debilidades/riesgos:
1. _______________
2. _______________
3. _______________

Condiciones para proceder:
1. _______________
2. _______________
3. _______________

Proximo paso:                       _______________
Fecha limite para decidir:          _______________
Responsable:                        _______________
```

---

## SECCION 11: CHECKLIST PRE-PEDIDO (completar antes de hacer la orden)

```
[ ] NCM confirmado por despachante de aduanas
[ ] Cotizacion de flete vigente obtenida
[ ] Muestra recibida y aprobada
[ ] Precio FOB negociado y confirmado por escrito
[ ] Forma de pago acordada (Trade Assurance recomendado)
[ ] MOQ y condiciones por escrito
[ ] Certificaciones necesarias identificadas y en tramite
[ ] Antidumping verificado (no aplica o monto conocido)
[ ] Despachante de aduanas contratado
[ ] Forwarder/agente de carga contratado
[ ] Seguro de carga cotizado
[ ] Inspeccion pre-embarque coordinada (si aplica)
[ ] Packaging y etiquetado acordado con proveedor
[ ] Proforma invoice recibida
[ ] Calculo de costo landed actualizado y verificado
[ ] Fondos disponibles para cubrir inversion total
[ ] Plan de venta definido (precio, canal, estrategia)
[ ] Plan de contingencia definido (si no se vende)
```

---

## NOTAS Y OBSERVACIONES

```
_______________________________________________________________
_______________________________________________________________
_______________________________________________________________
_______________________________________________________________
_______________________________________________________________
```

---

Ultima actualizacion del template: Febrero 2026
