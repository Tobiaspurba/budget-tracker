Untuk memaksimalkan penggunaan, disarankan melakukan step-step berikut:

1. pada file 'build.gradle (module: app)' tambahkan pada DEPENDENCIES kode berikut:

          implementation 'com.google.android.material:material:1.4.0-alpha02'
      
          def room_version = "2.2.6"
      
          implementation "androidx.room:room-runtime:$room_version"
          kapt "androidx.room:room-compiler:$room_version"
      
          // optional - Kotlin Extensions and Coroutines support for Room
          implementation "androidx.room:room-ktx:$room_version"

2. Pastikan Device Emulator men-support API diatas 30, dengan android requirement minimal 11.0 (Nougut).
3. Aplikasi menggunakan build tools versi 30.0.2 dengan target SDK versi 30.
4. Jalankan.
5. Selamat menikmati!
