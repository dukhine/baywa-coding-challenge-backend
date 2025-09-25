# BayWa Coding Challenge Backend

## Übersicht

Entwickeln Sie ein Spring Boot Backend für ein Newsletter-Registrierungssystem. Das Backend läuft in einem Docker-Container, verwaltet Newsletter-Anmeldungen und kommuniziert über eine REST-API mit einem bereits existierenden Frontend.

## Aufgabenstellung

### Funktionale Anforderungen

Entwickeln Sie einen REST-API-Service mit folgender Funktionalität:

- **Newsletter-Registrierung**: Endpoint zur Entgegennahme von E-Mail-Adressen für Newsletter-Anmeldungen
- **E-Mail-Validierung**: Überprüfung auf gültiges Format und Vermeidung von Duplikaten
- **Persistierung**: Speicherung in relationaler Datenbank (H2/PostgreSQL) sowie zusätzlich in einer Datei
- **Error-Handling**: Strukturierte JSON-Fehlerantworten bei Validierungsfehlern oder anderen Problemen

### Technologie-Stack

- **Java**: Version 21
- **Framework**: Spring Boot
- **Build-Tool**: Maven
- **Datenbank**: H2 und/oder PostgreSQL
- **ORM**: Spring Data JPA
- **Testing**: JUnit 5, Mockito, Spring Boot Test
- **Containerisierung**: Docker/Docker-Compose

### Qualitätsanforderungen

- **Tests**: Umfassende Unit- und Integrationstests (Spring Boot Tests, Spring Boot Test Slices)
- **Validierung**: Robuste Input-Validierung und Exception-Behandlung
- **Logging**: Angemessenes Logging von wichtigen Ereignissen
- **CI/CD** (optional): GitHub Actions Pipeline für automatisierte Tests und Build

## Setup & Entwicklung

### Voraussetzungen
- Java 21
- Maven 3.8+
- Docker & Docker-Compose

## Frontend-Integration

Das Frontend wird in einem separaten Repository unter https://github.com/guenyoobaywa/Coding-Challenge entwickelt

Stellen Sie sicher, dass Ihr Backend mit dem Frontend kompatibel ist.

## Zeitrahmen

**Geschätzte Bearbeitungszeit**: 2 Stunden

## Abgabe

- Vollständiges Git-Repository mit Commit-History
- Ausführbare Test-Suite
- Setup-Anweisungen in der README
- Kurze Beschreibung Ihrer Lösung und Architekturentscheidungen

---

**Viel Erfolg bei der Coding Challenge!** 🚀
