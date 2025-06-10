# Anforderungen für LN1 (Gewichtung 3): 
### Grundsätzliches:
Sie führen als Gruppe ein Fachgespräch (Soll 25 -30 Min) zu den Konfigurationen und Diensten des von ihnen erstellten Netzwerkes mit einer Lehrkraft.

# Leistungsnachweis:
### Planung
 * Ihr Team hat sich zur Bewältigung der kommenden Aufgaben sinnvoll organisiert und nutzt ein Collaborationstool
 * Sie dokumentieren/präsentieren & reflektieren Ihren Planungsprozess innerhalb ihres Teams
### Übergabe/Fachgespräch
 * Sie halten die vorgegebene Zeit ein (Soll 25 -30 Min).
 * Sie gliedern Ihre Übergabe erkennbar und zielorientiert.
 * Sie erfassen die Aufgabenstellung systematisch, bieten Lösungswege an und beurteilen diese kritisch.
 * Sie können auf Nachfragen  angemessen reagieren.
### Dokumente die zum Übergabe/Fachgespräch vorliegen müssen.
 * Es liegt ein Netzwerkplan mit Legende, Adressinformationen und Kennzeichnung der VLAN vor (Kein Screenshot der PT Simmulation!)
 * Es liegt ein IPAM und eine Portzuordnungstabelle vor
 * Es liegt ein kommentiertes Listing der Config-Scripts der Netzwerkgerräte (Switches, Router) vor.
### Funktionsfähiges Netzwerk in Form eines Demonstrators (Cisco Packet Tracer)
 * Alle (Infrastruktur-)Geräte, Server und Clients sind nativ mit IPv6 konfiguriert (kein "dual stack")
 * Für die Transportnetze sind „Unique Local Unicast Adressen“ verwendet worden
 * Für die Standortnetze sind „globale Unicast Adressen“ verwendet worden
 * An den Standorten HH und HL gibt  es mindestens zwei durch VLANs getrennte Netzwerke mit eigenem globalen Präfix
 * Die Standortnetzwerke wurden mittels eines Routers und L3 Switches eingerichtet
 * Die statischen Routen sind konfiguriert und das Routing funktioniert
 * Clients und Server haben „globale Unicast Adressen“ erhalten
 * Die Adressvergabe für die Clients ist zunächst statisch erfolgt

# Anforderungen zur Absicherung des Netzwerks

#### Router:

*Erstellen eines Banners*
 * Setzen von Passwörtern
 * SSH-Zugang (via IPv6)

*L3 Switches*
 * Erstellen eines Banners
 * Setzen von Passwörtern
 * SSH-Zugang (via IPv6)
