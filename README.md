# 🌐 Aura Safe App  

> 🚨 Your AI-Powered Personal Safety Companion  
> Flutter • Firebase • AI • SOS • Voice • Maps • Biometric Lock  

---

## 📱 Project Overview  
Aura Safe App is a **multi-level Flutter project** combining **safety, AI, and calmness**.  
It helps users stay protected in emergencies, trigger SOS hands-free, connect with trusted contacts, and restore peace through journaling and breathing features.  

---

## ⚙️ Tech Stack  
- **Frontend:** Flutter (Dart)  
- **Backend:** Firebase Auth, Firestore, Secure Storage  
- **AI Services:** Gemini API / Custom ML  
- **APIs:** Google Maps, Directions, Speech-to-Text, TTS  
- **Security:** Biometric Auth, Encrypted Vault  

---

## 🧱 Development Levels  

| Level | Module | Files | Key Tasks | Output |
|:------|:--------|:-------|:-----------|:--------|
| **Level 1** | Multi-Screen Core | `main.dart`, `screens/home_screen.dart`, `screens/map_screen.dart`, `screens/sos_screen.dart`, `screens/profile_screen.dart` | 1.1 Create `MainScreen` (StatefulWidget)<br>1.2 4 Screens as StatelessWidgets<br>1.3 Add `BottomNavigationBar`<br>1.4 Animate body with `AnimatedSwitcher` | Bottom nav with smooth transitions |
| **Level 2** | Bottom Navigation Styling | `main.dart` | Icons, Neon theme, semi-transparent dark bar | Themed navigation |
| **Level 3** | Alert Cards | `widgets/alert_card.dart` | Glassmorphism, color-coded by alert | Reusable alert cards |
| **Level 4** | Subtle Animations | `widgets/buttons.dart`, `widgets/loading_card.dart` | Neon animation + shimmer | Smooth UX |
| **Level 5** | Typography | `theme.dart` | `google_fonts` + `poppins` theme | Modern clean font |
| **Level 6** | User Auth | `screens/login_screen.dart`, `screens/signup_screen.dart`, `services/auth_service.dart` | Firebase login/signup, stay signed in | Core auth |
| **Level 7** | Contacts | `screens/contacts_screen.dart`, `services/contact_service.dart` | Firestore contacts + permission | SOS contacts |
| **Level 8** | Map + SOS | `screens/map_screen.dart` | Live location, animated marker, floating SOS | Realtime map |
| **Level 9** | Smart Route | `services/directions_service.dart` | Directions API + polyline routes | Route AI |
| **Level 10** | Profile | `screens/profile_screen.dart` | Glassmorphism + profile pic animation | User dashboard |
| **Level 11** | Help Vault | `screens/vault_screen.dart` | `flutter_secure_storage` | Encrypted data |
| **Level 12** | Biometric Lock | `screens/lock_screen.dart` | `local_auth` | FaceID / Fingerprint |
| **Level 13** | Edit Profile | `screens/edit_profile_screen.dart` | Editable profile + vault sync | Update UI |
| **Level 14** | Voice SOS | `screens/voice_sos_screen.dart` | `speech_to_text`, pulse mic | Hands-free trigger |
| **Level 15** | Hardware SOS | `screens/hardware_sos_screen.dart` | Power button trigger | Instant help |
| **Level 16** | AI Assistant | `screens/ai_assistant_screen.dart` | Chat UI + suggestions | AI Safety Chat |
| **Level 17** | Post Incident | `screens/post_incident_screen.dart` | Calm UI, guided flow | Recovery steps |
| **Level 18** | Emotion Check-In | `screens/ai_emotion_screen.dart`, `services/emotion_service.dart` | Mood input + AI advice | Emotional wellness |
| **Level 19** | Voice Assistant | `screens/voice_assistant_screen.dart` | TTS + speech recognition | Crisis guidance |
| **Level 20** | Incident Vault | `screens/incident_vault_screen.dart`, `services/vault_service.dart` | Encrypted notes, audio, photo | Safe records |
| **Level 21** | Report Generator | `screens/report_template_screen.dart`, `services/ai_report_service.dart` | AI text → PDF report | Auto summary |
| **Level 22** | Route AI | `services/route_ai_service.dart` | Safest path suggestion | Smart routing |
| **Level 23** | Calm Mode | `screens/calm_mode_screen.dart`, `widgets/breathing_widget.dart` | Guided breathing, vibration | Calm mode |
| **Level 24** | Reflection Journal | `screens/journal_screen.dart` | Affirmations + daily reflection | Mindful journaling |
| **Level 25** | Final QA | All | Test triggers, navigation, AI, UI | Production-ready app |

---

## 🌈 Features  
✅ Multi-screen navigation with animations  
✅ Live SOS & voice trigger system  
✅ Firebase user authentication  
✅ Smart AI assistant for safety situations  
✅ Encrypted Vault for incident storage  
✅ Biometric lock (Fingerprint / FaceID)  
✅ Calm mode & reflection journaling  
