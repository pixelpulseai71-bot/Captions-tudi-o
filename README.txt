CaptionStudio - UI project (Jetpack Compose)

ISTEMAL KAISE KAREIN:
1. Android Studio mein New Project > Empty Activity (Compose) banao.
   Name: CaptionStudio, Package: com.example.captionstudio, Min SDK: 24.
2. app/build.gradle.kts ke dependencies mein ye add karo, phir Sync Now:
     implementation("androidx.navigation:navigation-compose:2.8.4")
     implementation("androidx.compose.material:material-icons-core")
3. Is zip ke andar ka "app/src/main/java/com/example/captionstudio" folder
   apne project mein same jagah par copy karke purani files replace kar do.
4. Run ▶ dabao.
