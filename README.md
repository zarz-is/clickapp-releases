# Clickapp — Edición Comunidad Gratuita

Convierte tu **iPad o iPhone** en un panel táctil de control para tu **Mac** por Wi-Fi local: abre apps, organiza espacios personalizados, ejecuta macros/atajos y controla el volumen o la reproducción al instante.

> **Requisitos:** Mac con **macOS 14.0 o superior** · iPad o iPhone con **iPadOS/iOS 17.0 o superior** · ambos dispositivos en el **mismo Wi-Fi**.

---

## 1. Descargas directas

| Dispositivo | Descarga |
|---|---|
| **Mac** *(Apple Silicon e Intel)* | [**Descargar Clickapp-Mac-Installer.dmg**](https://github.com/zarz-is/clickapp-releases/releases/latest/download/Clickapp-Mac-Installer.dmg) |
| **iPad / iPhone** *(AltStore / SideStore / Sideloadly)* | [**Descargar Clickapp-iPad-iOS-Demo.ipa**](https://github.com/zarz-is/clickapp-releases/releases/latest/download/Clickapp-iPad-iOS-Demo.ipa) |

También puedes ver todas las versiones en [**Releases**](https://github.com/zarz-is/clickapp-releases/releases/latest).

---

## 2. Cómo instalar en Mac (2 minutos)

1. Descarga y abre **`Clickapp-Mac-Installer.dmg`**.
2. Arrastra **`Clickapp.app`** dentro de la carpeta **Aplicaciones**.
3. **Al abrirla por primera vez:** como esta demo gratuita se distribuye fuera de la App Store, macOS mostrará un aviso de seguridad (*"no se ha podido verificar que esté libre de software malicioso"*). Para abrirla:
   - Pulsa **OK / Listo** en ese aviso.
   - Abre **Ajustes del Sistema → Privacidad y seguridad**.
   - Baja hasta la sección **Seguridad** y pulsa **Abrir igualmente** junto a *Clickapp*.
   - Confirma con tu contraseña o Touch ID. *(En versiones anteriores de macOS también funciona hacer **clic derecho → Abrir** sobre la app).*
4. Cuando Clickapp te lo pida, concede permiso de **Accesibilidad** (*Ajustes del Sistema → Privacidad y seguridad → Accesibilidad → activa Clickapp*) y permite **Red local** para que pueda abrir apps, simular atajos y verse con tu iPad.

---

## 3. Cómo instalar en iPad o iPhone

Apple no permite instalar archivos `.ipa` directamente desde Safari fuera de la App Store. Para instalarla gratis en tu iPad o iPhone tienes **dos opciones muy sencillas**:

### Opción A — Con AltStore o SideStore *(recomendada: actualiza sola)*
1. Instala [AltStore](https://altstore.io/) o [SideStore](https://sidestore.io/) en tu iPad/iPhone.
2. En la pestaña **Sources**, añade esta fuente oficial de Clickapp:
   ```text
   https://raw.githubusercontent.com/zarz-is/clickapp-releases/main/altstore-source.json
   ```
3. Busca **Clickapp** dentro de la fuente y pulsa **Free / Get**.

### Opción B — Con Sideloadly desde Mac o Windows *(rápida por cable)*
1. Descarga [Sideloadly](https://sideloadly.io/) en tu ordenador y conecta el iPad o iPhone por cable USB.
2. Descarga [`Clickapp-iPad-iOS-Demo.ipa`](https://github.com/zarz-is/clickapp-releases/releases/latest/download/Clickapp-iPad-iOS-Demo.ipa) y arrástralo dentro de Sideloadly.
3. Introduce tu Apple ID y pulsa **Start**.

### Ajustes obligatorios en el iPad / iPhone (solo la primera vez)
1. **Activar Modo de desarrollador:** ve a **Ajustes → Privacidad y seguridad → Modo de desarrollador**, actívalo y reinicia el iPad/iPhone si te lo pide.
2. **Confiar en tu certificado** *(si aparece "Desarrollador no fiable" al abrir)*: ve a **Ajustes → General → VPN y gestión de dispositivos**, toca tu correo de Apple ID y pulsa **Confiar**.
3. Al abrir Clickapp por primera vez, pulsa **Permitir** cuando pregunte por acceso a la **Red local**.

> **Nota sobre cuentas gratuitas de Apple:** Apple caduca cada **7 días** cualquier app instalada fuera de la App Store con una cuenta gratuita. Solo tienes que pulsar **Refresh** en AltStore/SideStore (o repetir **Start** en Sideloadly) para renovarla sin perder tus paneles ni configuraciones.

---

## 4. Cómo conectar tu iPad y tu Mac

1. Conecta **Mac** e **iPad/iPhone** a la **misma red Wi-Fi**.
2. Abre **Clickapp** en el Mac y después en el iPad.
3. Se detectarán automáticamente por red local; introduce el **PIN de 4 dígitos** que aparece en pantalla y ya puedes empezar a crear espacios o lanzar apps.

---

## Solución rápida de problemas

- **El Mac dice que Clickapp está dañada o no se puede abrir:** sigue el paso 3 de Mac (*Ajustes del Sistema → Privacidad y seguridad → Abrir igualmente*).
- **El iPad se queda en "Buscando..." y no encuentra el Mac:** comprueba que ambos están en el mismo Wi-Fi (sin VPN activa que bloquee la red local) y revisa *Ajustes → Privacidad y seguridad → Red local* en ambos dispositivos.
- **Al tocar un botón en el iPad no ejecuta la acción en el Mac:** asegúrate de haber activado **Clickapp** en *Ajustes del Sistema → Privacidad y seguridad → Accesibilidad* en el Mac.
