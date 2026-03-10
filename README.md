# Bibliothek M295 / M294

Full-Stack-Webanwendung zur Verwaltung eines persönlichen Buchbestands. Das Projekt besteht aus einem Java Spring Boot Backend und einem React Frontend.

**Features:** Benutzerregistrierung & Login (JWT), Bücher erfassen/bearbeiten/löschen, Kategorien, Suche & Sortierung, Favoriten, Lesestatus, Notizen, Fälligkeitsdaten, PDF- & Excel-Export, Deutsch/Englisch, Dark/Light Mode.

## Voraussetzungen

- Java 17+
- Maven 3.6+
- Node.js 18+
- npm 8+

## Starten

### 1. Backend

Projekt in IntelliJ IDEA öffnen und folgende Datei starten:

```
LB_294_Indujan/LibraryM295-new/src/main/java/ch/library/LibraryApplication.java
```

Das Backend läuft auf **http://localhost:8080**.

### 2. Frontend

In einem neuen Terminal:

```bash
cd library-frontend
npm install
npm run dev
```

Das Frontend ist erreichbar unter **http://localhost:5173**.

> Beide müssen gleichzeitig laufen, damit die App funktioniert.

## API-Endpunkte

| Methode | Endpunkt | Beschreibung |
|---|---|---|
| POST | /auth/register | Registrieren |
| POST | /auth/login | Einloggen |
| GET | /books | Alle Bücher abrufen |
| POST | /books | Neues Buch erstellen |
| PUT | /books | Buch aktualisieren |
| DELETE | /books/{id} | Buch löschen |
