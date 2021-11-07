# Los mecanismos de autentificación remota.

![Example](https://github.com/MariaDelCarmenHernandezDiaz/Recursos-Test/blob/main/Practicas/20160615060659_doble-factor.png?raw=true "Example")

De acuerdo con Narváez, D. (s. f.). La autenticación de clientes de acceso remoto es una cuestión de gran importancia para la seguridad. Y los mecanismos más destacables se presentan a continuación.

Protocolo de autenticación extensible (EAP). Mecanismo de autenticación arbitrario, valida las conexiones de acceso remoto. Es una estructura de soporte, no un mecanismo específico de autenticación. Desarrollado a la demanda de métodos de autenticación que utilizan dispositivos de seguridad: Tarjetas inteligentes, de identificación, calculadora de cifrado, calculadora de cifrado.

EAP-MSCHAP. Utiliza el mismo protocolo de desafío mutuo que CHP basado en PPP, usado para autenticar credenciales de los clientes. Es un protocolo de autenticación basado en contraseña ampliamente utilizado como un método de autenticación en VPN basadas en PPTP (Protocolo de túnel punto a punto).

EAP-TLS. ​Extensible Authentication Protocol es un framework de autenticación usado habitualmente en redes WLAN Point-to-Point Protocol. Aunque el protocolo EAP no está limitado a LAN inalámbricas y puede ser usado para autenticación en redes cableadas, es más frecuente su uso en las primeras. 

EAP-RADIUS. No es un tipo de seguridad EAP, al contrario es el paso de cualquier tipo EAP, a un servidor RADIUS realizada por un autenticador de mensajes EAP. Un framework de autenticación usado habitualmente en redes WLAN Point-to-Point Protocol. Los métodos modernos capaces de operar en ambientes inalámbricos incluyen EAP-TLS, EAP-SIM, EAP-AKA, PEAP, LEAP y EAP-TTLS.

MS-CHAP. Proporciona seguridad de alto nivel para las conexiones de acceso remoto, mejorando problemas de la versión anterior, como autenticación unidireccional. La versión de Microsoft del protocolo de autenticación de contraseñas de cifrado por desafío mutuo, el cual es irreversible
