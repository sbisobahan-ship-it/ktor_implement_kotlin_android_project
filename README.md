# ktor_implement_kotlin_android_project

# build.gradle.kts (project lavel 
plugins {
  .....
  .....

  
    kotlin("jvm") version "2.2.10"
    kotlin("plugin.serialization") version "2.2.10"
}

# build.gradle.kts (Moduil lavel)
dependencies {

   .....
   .....
   .....
   .....

   
    // Ktor Client
    implementation("io.ktor:ktor-client-core:3.3.0")
    implementation("io.ktor:ktor-client-okhttp:3.3.0") // Android এর জন্য OkHttp engine
    implementation("io.ktor:ktor-client-content-negotiation:3.3.0")
    implementation("io.ktor:ktor-serialization-kotlinx-json:3.3.0")

    // Coroutines
    implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.10.2")
