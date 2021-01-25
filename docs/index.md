# Technische Dokumentation der SWITCH edu-ID

Diese Anleitung richtet sich an SWITCHaai[^1] Service Provider (SP)[^2] Administratoren.

## Linking
Voraussetzung für die Nutzung der SWITCH edu-ID[^3] an der UniBE ist eine Verlinkung des Campus Accounts mit einer vorhandenen oder neu zu erstellenden SWITCH edu-ID.

- [Technische Details zum Linking-Process](./linking/aai-api.md)

## Staging Server
Um zu simulieren wie sich Ihr Service Provider nach der Umstellung auf die SWITCH edu-ID verhält, stellen wir Ihnen einen sogenannten Staging Server[^4] zur Verfügung.

- [Funktionsweise des Staging Server](./staging-server/how-it-works.md)
- [Verwendung des Staging Servers](./staging-server/how-to-use.md)

## Anpassung der Service Provider
Im Normalfall müssen Sie für den Wechsel auf die SWITCH edu-ID keine Anpassungen an Ihrem Service Provider vornehmen.
Eine Ausnahme besteht dann, wenn Sie sich bei der Installation nicht an die Vorgaben von SWITCH gehalten oder nachträgliche Anpassungen vorgenommen haben.

Wenn Sie nebst dem edu-ID Login auch weiterhin die Anmeldung mit dem Campus Account zulassen möchten haben wir für Sie eine [Übersicht erstellt](./service-provider/hybrid-login.md), wie dies realisiert werden kann.

[^1]: Shibboleth/SAML basiertes Anmeldesystem.
[^2]: Dienstleistung welche SWITCHaai/edu-ID als Anmeldesystem nutzt.
[^3]: Nachfolger von SWITCHaai und eine lebenslange, persistente ID im Hochschulumfeld
[^4]: System zur Simulation einer Anmeldung mit der SWITCH edu-ID an einem SP