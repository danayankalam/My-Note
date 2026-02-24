# My Note


![Version](https://img.shields.io/badge/version-v1.0.0-blue)
![Kotlin](https://img.shields.io/badge/Kotlin-2.2.10-purple)
![Compose](https://img.shields.io/badge/Jetpack%20Compose-UI-brightgreen)
![Architecture](https://img.shields.io/badge/Architecture-MVVM-orange)
![Status](https://img.shields.io/badge/Status-Stable-success)


A modern note-taking application built with a standard Android architecture and best development practices.

##✨ Features

Fully built with Jetpack Compose

Clean MVVM architecture

Dependency Injection using Dagger Hilt

Local database powered by Room

Settings storage using DataStore (Preferences)

Navigation handled by Navigation Compose

Fast and reliable offline storage

Modern, clean, and scalable UI

Dark & Light theme support
## 🧱 Tech Stack
- Kotlin
- Jetpack Compose
- MVVM
- Room Database
- DataStore Preferences
- Dagger Hilt
- Navigation Compose
- Coroutines & Flow



##🎯 Project Goal

This project was designed and implemented to:

Practice standard Android architecture

Build a real-world note-taking application

Serve as a portfolio project.

---

## 📂 Project Structure

```

mynote/
   ├── base/
   │   └── NoteApp.kt
   ├── core/
   │   └── util/
   ├── HighlightText.kt
   │       └── PersianDate.kt
   ├── data/
   │   └── local/
   │       ├── datastore/
   │       │   ├── AppSettings.kt
   │       │   ├── DataStoreExt.kt
   │       │   ├── ThemeDataStore.kt
   │       │   └── ThemeManager.kt
   │       └── db/
   │           ├── AppDatabase.kt
   │           ├── dao/
   │           │   └── NoteDao.kt
   │           └── entity/
   │               └── NoteEntity.kt
   ├── di/
   │   ├── DatabaseModule.kt
   │   └── DataModule.kt
   ├── MainActivity.kt
   ├── navigation/
   │   ├── navGraph.kt
   │   └── Screens.kt
   ├── repository/
   │   └── NotesRepository.kt
   ├── ui/
   │   ├── event/
   │   │   └── UiEvent.kt
   │   ├── model/
   │   │   └── NoteUiModel.kt
   │   ├── screen/
   │   │   ├── add_edit/
   │   │   │   ├── AddEditNoteScreen.kt
   │   │   │   └── components/
   │   │   │       ├── AddEditTopAppBar.kt
   │   │   │       ├── ColorPalette.kt
   │   │   │       ├── ContentTextField.kt
   │   │   │       ├── PinCheckbox.kt
   │   │   │       └── TitleTextField.kt
   │   │   └── notes/
   │   │       ├── components/
   │   │       │   ├── AppAlertDialog.kt
   │   │       │   ├── EmptyState.kt
   │   │       │   ├── MessageHandler.kt
   │   │       │   ├── MyCustomSnackbar.kt
   │   │       │   ├── NoteCard.kt
   │   │       │   ├── NotesList.kt
   │   │       │   └── SearchBar.kt
   │   │       ├── NoteListScreen.kt
   │   │       └── NotesTopBar.kt
   │   └── theme/
   │       ├── Color.kt
   │       ├── Theme.kt
   │       └── Type.kt
   └── viewModel/
  │        └── NotesViewModel.kt
```


## ▶️ Run the Project

1. Clone the repository:
```bash
git clone https://github.com/sadegh-it/My-Note.git

```
2. Open the project in Android Studio

3. Build and run on an emulator or physical device
---


## 📥 Download
- [Download APK (v1.0.1)](https://github.com/sadegh-it/My-Note/releases/latest)

