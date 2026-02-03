# Apteczka Seniora - System Zarządzania Lekami

Aplikacja mobilna React Native pomagająca osobom starszym i ich opiekunom w zarządzaniu przyjmowaniem leków.

## 📱 Funkcje

### Dla Seniora
- **Skanowanie kodów kreskowych** - szybkie dodawanie leków przez skan
- **Przypomnienia o dawkach** - powiadomienia push o nadchodzących dawkach
- **Historia przyjęć** - śledzenie kiedy leki zostały przyjęte
- **Wykrywanie interakcji** - ostrzeżenia o niebezpiecznych połączeniach leków

### Dla Opiekuna
- **Monitorowanie podopiecznych** - podgląd czy senior przyjął leki
- **Alerty o pominięciach** - powiadomienia gdy dawka została pominięta  
- **Szybki kontakt** - możliwość zadzwonienia do seniora

## 📸 Galeria

### � Logowanie i Profil
<table align="center">
  <tr>
    <td align="center" width="25%">
      <img src="zdj/d7f67d58-7216-43d1-9e7d-3e868d4440cf.jpg" width="100%" />
      <br/><b>Logowanie</b><br/>Bezpieczny dostęp do konta
    </td>
    <td align="center" width="25%">
      <img src="zdj/eed89bad-13ad-45ec-bce0-47247ea2d9a0.jpg" width="100%" />
      <br/><b>Rejestracja</b><br/>Szybkie tworzenie konta
    </td>
    <td align="center" width="25%">
      <img src="zdj/cf756fa0-a330-4774-ad05-6b41741272a7.jpg" width="100%" />
      <br/><b>Profil Użytkownika</b><br/>Zarządzanie danymi
    </td>
    <td align="center" width="25%">
      <img src="zdj/79f432dc-21a9-418b-ac8a-977118dc4054.jpg" width="100%" />
      <br/><b>Statystyki</b><br/>Podsumowanie aktywności
    </td>
  </tr>
</table>

### 💊 Aplikacja Seniora
<table align="center">
  <tr>
    <td align="center" width="25%">
      <img src="zdj/0590f4cb-004d-4971-b932-1267a320d07b.jpg" width="100%" />
      <br/><b>Pulpit Seniora</b><br/>Najbliższe dawki i powiadomienia
    </td>
    <td align="center" width="25%">
      <img src="zdj/320626c3-4efe-4262-a137-f0bc7ec1c906.jpg" width="100%" />
      <br/><b>Harmonogram</b><br/>Dzienny plan przyjmowania leków
    </td>
    <td align="center" width="25%">
      <img src="zdj/1eaf659d-88dc-4d9a-a787-d66ad7c22373.jpg" width="100%" />
      <br/><b>Lista Leków</b><br/>Cyfrowa apteczka
    </td>
    <td align="center" width="25%">
      <img src="zdj/2c04f3fa-2a52-4500-9218-6dbfe17c24ad.jpg" width="100%" />
      <br/><b>Szczegóły Leku</b><br/>Informacje i dawkowanie
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="zdj/4130e08a-4417-4896-ba76-90e598678f54.jpg" width="100%" />
      <br/><b>Skaner Kodów</b><br/>Automatyczne rozpoznawanie leków
    </td>
    <td align="center">
      <img src="zdj/504dbd26-8b54-4697-b71a-cb7d11e60272.jpg" width="100%" />
      <br/><b>Weryfikacja</b><br/>Potwierdzenie danych z bazy
    </td>
    <td align="center">
      <img src="zdj/53033639-f767-4726-a6a4-a8cd4bd3a037.jpg" width="100%" />
      <br/><b>Analiza Interakcji</b><br/>Wykrywanie konfliktów lekowych
    </td>
    <td align="center">
      <img src="zdj/66928922-25f1-4305-8d2f-86eafb3f74c1.jpg" width="100%" />
      <br/><b>Ostrzeżenia</b><br/>Szczegółowe informacje o ryzyku
    </td>
  </tr>
</table>

### 👨‍⚕️ Strefa Opiekuna
<table align="center">
  <tr>
    <td align="center" width="25%">
      <img src="zdj/85379b37-5985-48c5-b9f8-ccd9ee0f91a5.jpg" width="100%" />
      <br/><b>Lista Podopiecznych</b><br/>Zarządzanie wieloma seniorami
    </td>
    <td align="center" width="25%">
      <img src="zdj/ac5fb8af-c353-49fd-9c57-4017f7097fd6.jpg" width="100%" />
      <br/><b>Panel Monitoringu</b><br/>Status realizacji dawek
    </td>
    <td align="center" width="25%">
      <img src="zdj/76203036-7746-48d8-8e1d-c5e1f9727467.jpg" width="100%" />
      <br/><b>Historia Przyjęć</b><br/>Pełny rejestr zdarzeń
    </td>
    <td align="center" width="25%">
      <img src="zdj/ba460ecc-e2e6-4b8c-95a0-1ae3a01fdb03.jpg" width="100%" />
      <br/><b>Alerty Opiekuna</b><br/>Powiadomienia o problemach
    </td>
  </tr>
</table>

## 🚀 Uruchomienie projektu

### Wymagania
- Node.js 18+
- npm lub yarn
- Expo CLI
- Konto Firebase (do konfiguracji backendu)

### Instalacja

```bash
# Klonowanie repozytorium
cd apteczka-seniora

# Instalacja zależności
npm install

# Uruchomienie w trybie deweloperskim
npm start
```

### Konfiguracja Firebase

1. Utwórz projekt w [Firebase Console](https://console.firebase.google.com/)
2. Włącz Authentication (Email/Password)
3. Utwórz bazę Firestore
4. Skopiuj konfigurację do pliku `.env`:

```env
EXPO_PUBLIC_FIREBASE_API_KEY=your_api_key
EXPO_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
EXPO_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
EXPO_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
EXPO_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=123456789
EXPO_PUBLIC_FIREBASE_APP_ID=1:123456789:web:abcdef
```

## 📁 Struktura projektu

```
src/
├── components/          # Komponenty UI
│   ├── common/          # Button, Input, Card
│   ├── medication/      # MedicationCard, InteractionAlert
│   └── reminders/       # DoseCard
├── screens/             # Ekrany aplikacji
│   ├── auth/            # Login, Register
│   ├── senior/          # Dashboard, Medications, Schedule, Scan
│   └── caregiver/       # MonitoringDashboard
├── navigation/          # React Navigation
├── services/            # Logika biznesowa
│   ├── api/             # Firebase operations
│   ├── barcode/         # Skanowanie kodów
│   ├── notifications/   # Push notifications
│   └── interactions/    # Sprawdzanie interakcji
├── store/               # Zustand state management
├── constants/           # Theme, colors, constants
├── types/               # TypeScript types
└── config/              # Firebase config
```

## 🔧 Technologie

- **React Native** + **Expo** - framework mobilny
- **Firebase** - backend (Auth, Firestore)
- **Zustand** - zarządzanie stanem
- **React Navigation** - nawigacja
- **Expo Camera** - skanowanie kodów
- **Expo Notifications** - powiadomienia push

## 📋 API Leków

Aplikacja używa:
- Lokalnej bazy popularnych polskich leków
- OpenFDA API jako fallback dla międzynarodowych leków

## ⚠️ Interakcje Lekowe

Wbudowana baza reguł zawiera popularne interakcje lekowe z poziomami ryzyka:
- 🟢 **Niskie** - niewielkie ryzyko
- 🟡 **Średnie** - wymaga uwagi
- 🟠 **Wysokie** - konsultacja z lekarzem
- 🔴 **Krytyczne** - nie łączyć

## 📲 Budowanie aplikacji

```bash
# Android APK
npx expo build:android

# iOS (wymaga konta Apple Developer)
npx expo build:ios

# Lub z EAS Build
npx eas build --platform all
```




