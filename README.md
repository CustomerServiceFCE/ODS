# ODS - Órdenes de Servicio

Formulario web para radicar Órdenes de Servicio del equipo de **Customer Service de Full Circle Electronics**.

## 🔗 Acceso al formulario

**[👉 Abrir formulario de ODS](https://customerservicefce.github.io/ODS/)**

## 📋 Cómo funciona

1. El usuario llena el formulario y lo envía.
2. Se crea automáticamente un registro en la lista de SharePoint `Ordenes_de_servicio`.
3. El BDM responsable recibe una solicitud de aprobación en Microsoft Teams.
4. Si aprueba: el equipo de Operaciones y CS del país recibe un correo con todos los detalles y archivos adjuntos.
5. Si rechaza: CS recibe una notificación con el motivo y un link para editar y reenviar.

## 🛠️ Arquitectura

- **Frontend:** HTML/CSS/JavaScript (este repo, hosteado en GitHub Pages).
- **Backend:** Power Automate (flujo "ODS - Procesar nueva orden").
- **Datos:** SharePoint Online (sitio COLCustomerService).
  - Lista `Ordenes_de_servicio` (consolida Colombia y México).
  - Lista `BDMs`.
  - Lista `Clientes`.

## 👩‍💼 Responsable

María Florez · mariaf@fcelect.com · Líder de Customer Service

## 📞 Soporte

Si el formulario presenta problemas, contactar a María Florez o al equipo de Customer Service.
