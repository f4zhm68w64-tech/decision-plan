Decision Plan v5.10.3
- Backup cifrado opcional .dpbackup.
- AES-256-GCM mediante Web Crypto API.
- Clave derivada de contraseña con PBKDF2-SHA-256, salt aleatorio e iteraciones guardadas en el envelope.
- La contraseña nunca se guarda.
- Restauración detecta automáticamente JSON histórico o .dpbackup cifrado.
- Se conserva exportación JSON sin cifrar como alternativa.
