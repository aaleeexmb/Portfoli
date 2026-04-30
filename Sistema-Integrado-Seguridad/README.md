
# Implementación de un Sistema Integrado de Seguridad con pfSense

En este proyecto se ha implementado un sistema de seguridad perimetral utilizando **pfSense** como firewall principal. Se ha diseñado una infraestructura de red segmentada con distintas subredes (administración, servidores e invitados), aplicando reglas de **firewall y NAT** para controlar el tráfico entre ellas. Además, se ha integrado un sistema de detección y prevención de intrusiones (IDS/IPS) mediante **Snort**, permitiendo identificar actividades sospechosas como escaneos de puertos.

También se ha configurado un **proxy web con Squid y SquidGuard** para el filtrado de contenido HTTP, junto con **PFBlockerNG** para el bloqueo de dominios mediante DNS. Este proyecto tiene una aplicación directa en entornos corporativos, ya que permite mejorar la seguridad de la red, controlar el acceso a internet de los usuarios y proteger los sistemas frente a posibles ataques externos
