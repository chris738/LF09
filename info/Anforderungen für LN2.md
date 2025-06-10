# Anforderungen für LN2 (Gewichtung 1):

## Es gibt drei Themen zur Auswahl (ACL, DHCPv6, OSPFv3).
### Jedes Team wählt sich eines der Themen als LN2 aus. 
 
### Leistungsnachweis:
#### ACL inkl. Dokumentation
 * Der SSH-Zugang darf nur von den PCs des Standorts Hamburg erfolgen
 * Die PCs des Standorts Hamburg dürfen auf die Webserver via http und https zugreifen
 * Die PCs des Standorts Lübeck dürfen auf die Webserver nur mit https zugreifen
 * Entwerfen Sie mindestens eine weitere sinnvolle Regel, welche die Sicherheit des Netzwerks erhöht
#### DHCPv6  inkl. Dokumentation
 * Realisieren Sie einen DHCPv6 Dienst im Modus "SLAAC with DHCPv6-Server" auf den Routern
 * Sie konfigurieren den DHCPv6 Dienst am Standort Hamburg im Modus "Stateful"
 * Sie konfigurieren einen zentralen DHCPv6-Service, der alle Standorte bedient. Es steht Ihnen frei, ob dieser Dienst auf einem Router oder dem Server in Berlin läuft.
#### OSPFv3  inkl. Dokumentation
 * Sie ersetzen die manuelle Konfiguration der Routingeinträge durch das dynamische Routingprotokoll OSPFv3.
