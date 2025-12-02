# 📒 Registry Service - Eureka (Paso 2)

**Puerto:** `8761`

Servidor que mantiene un registro activo de todas las instancias de microservicios disponibles (`AUTH`, `PRODUCT`, `INVOICE`, `GATEWAY`, etc.).

## 🚀 Ejecución
1.  Requiere que **Config Server** esté corriendo.
2.  Inicie el servicio.
3.  **Verificación:** Acceda a `http://localhost:8761`

---
**Nota:** Con todas las APIs corriendo:

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/477e5888-c4cc-451d-95e3-93f8d50abba8" />

---
### 🔗 Mapa de Arquitectura
0. [Config data](https://github.com/AlexaRamirezV/config-data.git)
1.  [Config Server](https://github.com/AlexaRamirezV/config-service.git)
2.  ➡️ **[Registry Service]**
3.  [Gateway Service](https://github.com/AlexaRamirezV/gateway-service.git)
4.  [Admin Service](https://github.com/AlexaRamirezV/admin-service.git)
5.  APIs del sistema:
   * [Auth](https://github.com/AlexaRamirezV/DWB-auth.git)
   * [Customer](https://github.com/AlexaRamirezV/DWB-customer.git)
   * [Product](https://github.com/xEriis/Backend.git)
   * [Invoice](https://github.com/AlexaRamirezV/DWB-invoice.git)
