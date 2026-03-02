# AGA-Evernote-Clone 📝

[![Framework](https://img.shields.io/badge/Framework-WPF-blue.svg)](https://docs.microsoft.com/en-us/dotnet/desktop/wpf/)
[![Architecture](https://img.shields.io/badge/Pattern-MVVM-green.svg)](https://learn.microsoft.com/en-us/dotnet/architecture/maui/mvvm)
[![Cloud](https://img.shields.io/badge/Cloud-Azure%20%26%20Firebase-orange.svg)](#)

### 📝 Description
A sophisticated note-taking application inspired by Evernote, built using **WPF (Windows Presentation Foundation)**. This project demonstrates advanced desktop development techniques, focusing on a clean User Interface, **MVVM pattern**, and seamless integration with **Cloud-based services** and **AI Speech APIs**.

---

### ✨ App Features
* **Advanced Note Management:** Create, organize, and manage complex notes with ease.
* **Rich Text Editing:** Integrated tools for formatting and styling your content.
* **Speech to Text:** Converting input audio to text using **Speech Recognition** technology.
* **Dynamic UI:** A responsive and modern interface designed for a smooth user experience.
* **Cloud Integration:** Scalable backend support leveraging industry-leading cloud providers.

### 🛠️ Code Features
* **MVVM Architecture:** Strictly following the **Model-View-ViewModel** pattern for clean separation of concerns.
* **Cloud Authentication:** Implementing secure user login and registration using **Google Firebase**.
* **Cloud Storage:** Utilizing **Microsoft Azure** for robust and reliable data persistence.
* **Cognitive Services:** Integration with **Azure Speech API** for real-time voice-to-text conversion.
* **Object-Oriented Design:** Applying **SOLID principles** to maintain an extensible codebase.

### 💻 Tech Stack
* **Language:** C#
* **UI Framework:** WPF (.NET Framework / .NET)
* **Design Pattern:** MVVM
* **Backend/Auth:** Google Firebase
* **Database/Storage:** Microsoft Azure
* **AI Services:** Azure Cognitive Services (Speech SDK)

---

### ⚠️ Note for Usage & Security
For security purposes, the cloud configurations have been omitted. To run this application locally, you must provide your own credentials:

1. **Azure Storage:** Copy your *Azure Connection String*, *Container Name*, and *Storage Blob Link* and paste them in `Database/AzureStorageHelper.cs`.
2. **Speech Recognition:** Copy your own *Azure Speech Recognition Region* and *API Key* and paste them in the `Speech()` method in `ViewModel/NotesVM/NotesVM.cs`.
3. **Firebase Database:** Copy your *Firebase database link* and paste it in `Database/DatabaseHelper.cs`.
4. **Firebase Auth:** Copy your *Firebase Authentication API Key* and paste it in `Database/FirebaseAuthHelper.cs`.

---

### 🚀 Getting Started
1. Clone the repository.
2. Open the solution in **Visual Studio**.
3. Apply the security configurations mentioned above.
4. Build and run the application.

---

### 🤝 Connect with Me
* [LinkedIn](https://linkedin.com/in/agaabdelgawad)
* [GitHub Profile](https://github.com/agaabdelgawad)

---
*If you find this project useful for learning WPF/MVVM, feel free to give it a ⭐!*
