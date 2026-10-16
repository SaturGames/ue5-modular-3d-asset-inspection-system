# UE5 - Sistema Modular de Inspección de Objetos & Lectura | Gameplay & Puzles (v0.1, v0.2 & v0.3)

Sistema modular y desacoplado de inspección de objetos 3D, overlay de lectura de documentos y activación de mecanismos desarrollado en **Unreal Engine 5.4**. Diseñado enfocado en arquitectura limpia, escalabilidad y separación de responsabilidades lógicas mediante el uso de Eventos Personalizados (CE) y gestión contextual de UI/Inputs.

> **Core Focus:** Clean Architecture, Modular Inspection, State Management & Event-Driven UI.

---

## Demostración Visual y Arquitectura de Blueprints

### Showcase del Prototipo (Greybox & Gameplay)
<img width="1920" height="986" alt="1-G" src="https://github.com/user-attachments/assets/6718b91b-d3b4-47dd-95f9-2f8ac8301521" />
<img width="1920" height="1029" alt="2-G" src="https://github.com/user-attachments/assets/e6cf589f-df0a-4e63-baa1-b46403c90c21" />
<img width="1920" height="1029" alt="3-G" src="https://github.com/user-attachments/assets/e90bb01a-dfcb-4097-9cd4-d66c2d7d22bc" />
<img width="1920" height="1029" alt="4-G" src="https://github.com/user-attachments/assets/b2e46405-925f-49dc-9365-fe3e257846f6" />
<img width="1920" height="1029" alt="5-G" src="https://github.com/user-attachments/assets/2540546b-d34e-4ab9-b52c-285a3ba819ec" />
<img width="1920" height="1029" alt="6-G" src="https://github.com/user-attachments/assets/f31a48f8-927f-43a1-ae00-9502bd8f9a61" />

### Arquitectura de Blueprints y Código Documentado
<img width="1920" height="1029" alt="1-E" src="https://github.com/user-attachments/assets/8ea3b940-93a6-49a4-89ac-027fa451f16a" />
<img width="1920" height="1029" alt="2-E" src="https://github.com/user-attachments/assets/ef61fa06-d1be-45dd-bf6a-fee7a6e52abe" />
<img width="1920" height="1029" alt="3-E" src="https://github.com/user-attachments/assets/a80ff56d-f729-4d70-b3e1-1fb5a659f11d" />
<img width="1920" height="1029" alt="4-E" src="https://github.com/user-attachments/assets/ab179289-5e62-4269-84de-849fc4cd7741" />
<img width="1920" height="1029" alt="5-E" src="https://github.com/user-attachments/assets/66c9528d-7839-4446-a1f2-4312c85c313a" />

---

## Aspectos Técnicos e Implementación

- **Arquitectura Modular & Variantes:** Implementación escalable de 3 modos de inspección: rotación libre 3D, overlay de lectura de documentos (`[R]`) e interacción contextual de componentes (`[F]`).
- **Detección Eficiente & Triggering:** Uso de *Box Collisions* dedicados para delimitar áreas de interacción sin sobrecargar el *Tick* del personaje ni depender de la orientación directa de la cámara.
- **Flujo de Gameplay & Estados:** Control estricto de banderas (*flags*) e Inputs de usuario para asegurar transiciones limpias entre la vista en primera persona y el modo de inspección sin fugas de memoria ni llamadas redundantes.
- **Game Feel & Feedback Audiovisual:** Integración de transiciones de UI reactivas y efectos de audio espacializados (Audio para tomar/soltar, crujido de papel y clics mecánicos) para elevar la respuesta táctil de cada objeto.

---

## Demostración en Video

-  **Prototipo Fase 1 (Base & System Demo):** [Ver demostración en LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7516890680833617920/)

---

**Desarrollado por Satur Games** | *Gameplay & Systems Programmer*
