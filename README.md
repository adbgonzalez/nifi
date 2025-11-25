# README — Guía de Apache NiFi  
*Material docente para o módulo de Big Data Aplicado*

Este repositorio contén unha colección estruturada de documentos en formato **Markdown** para introducir, organizar e empregar Apache NiFi en contornas educativas e profesionais.

Os materiais avanzan de forma progresiva: dende a introdución e boas prácticas ata procesadores específicos, integración con sistemas externos (HDFS, MinIO, SQL, Mongo, Kafka, APIs HTTP) e o potente **Record API**, fundamental para ETLs modernos.

---

## 📁 Contidos

### **01 — Introdución a Apache NiFi**  
➡️ [`01.nifi-introducion.md`](01.nifi-introducion.md)

Documento inicial que explica que é NiFi, os seus compoñentes principais, arquitectura e primeiros fluxos.

---

### **02 — Organización e boas prácticas**  
➡️ [`02.nifi-organizacion-boas-practicas.md`](02.nifi-organizacion-boas-practicas.md)

Como estruturar fluxos de forma profesional, empregar Process Groups, Parameter Contexts, manter a documentación e traballar de forma segura.

---

### **03 — Guía de procesadores e integración con sistemas externos**  
➡️ [`03.nifi-procesadores-guia.md`](03.nifi-procesadores-guia.md)

Este bloque reúne todos os documentos específicos por tecnoloxía:

- `03.01.nifi-procesadores-basicos.md`  
- `03.02-minio-hdfs.md`  
- `03.03-sql-mongo.md`  
- `03.04-http.md`  
- `03.05-kafka.md`  
- `03.06-record-api.md`  

Inclúe:
- procesadores básicos (GenerateFlowFile, LogAttribute, UpdateAttribute…)  
- integración con MinIO/S3 e HDFS  
- SQL e MongoDB  
- APIs HTTP  
- Kafka  
- Record API (ConvertRecord, UpdateRecord, QueryRecord, ValidateRecord…)

---

## 💡 Uso recomendado

1. Comezar por **01** para comprender a arquitectura e os fundamentos.  
2. Aplicar as boas prácticas do **02**.  
3. Continuar co bloque **03**, que serve como referencia completa para todos os procesadores e integracións.  
4. Empregar o **Record API** para traballos profesionais e ETLs complexos.

---