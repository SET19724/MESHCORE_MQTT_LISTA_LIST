# 📡 MQTT Brokers List / Lista Brokerów MQTT

🌍 **[English](#-english)** | 🇵🇱 **[Polski](#-polski)**

---

<a name="-polski"></a>
## 🇵🇱 Polski

Poniżej znajduje się lista serwerów i ustawień MQTT, które udało mi się znaleźć. 

> 💡 **Wskazówka:** Jeśli chcesz działać jako obserwator (observer), gorąco polecam użycie narzędzia **remoteterm**.

### Zestawienie Konfiguracji

| Projekt / Mapa | Host (Broker) | Port | Transport | TLS | Dodatkowe informacje |
|---|---|---|---|---|---|
| **[MeshCom DK](https://analyzer.meshcom.dk/#/live)** | `mqtt.meshcom.dk` | `1883` | TCP | ❌ NIE | - |
| **[MeshCore KRK](https://meshcorekrk.cma.pl/#/live)** | `mqtt.riko.dev` | `1883` | TCP | ❌ NIE | **User/Pass:** `meshcore` / `meshcore` |
| **[Riko.dev](https://litescope.riko.dev/)** | `mqtt.meshcorekrk.cma.pl` | `1883` | TCP | ❌ NIE | **User/Pass:** `litescope` / `meshcore` | **Token Aud:**meshcore/<region>/<observer-id> |
| **[MeshMapper](https://meshmapper.net)** | `mqtt.meshmapper.net` | `443` | WEBSOCKETS | ✅ TAK | **Auth:** `TOKEN` |
| **[MeshCore CZ](https://mapa.meshcore.cz)** | `mqtt.meshcore.cz` | `443` | WEBSOCKETS | ✅ TAK | **Auth:** `TOKEN`<br>**Token Aud:** `mapa.meshcore.cz` |

#### 📝 Szablon do dodawania nowych wpisów:
```text
BROKER HOST: 
BROKER PORT: 
TRANSPORT: 
USE TLS:
