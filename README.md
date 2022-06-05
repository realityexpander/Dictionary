# Slang-Dictionary
American Slang Dictionary app using CLEAN architecture, MVVM, Use Cases, GSON, Retrofit, Compose, Room with caching, Hilt Dependency Injection, API from dictionaryapi.dev

[<img src="https://user-images.githubusercontent.com/5157474/172029910-e6c7fc81-7bf6-48e3-954c-4dc7ed8ef5cf.png" width="325"/>](https://user-images.githubusercontent.com/5157474/172029910-e6c7fc81-7bf6-48e3-954c-4dc7ed8ef5cf.png)
[<img src="https://user-images.githubusercontent.com/5157474/172029917-787daa35-8fc8-41da-a811-6db635fe36df.png" width="325"/>](https://user-images.githubusercontent.com/5157474/172029917-787daa35-8fc8-41da-a811-6db635fe36df.png)
[<img src="https://user-images.githubusercontent.com/5157474/172029922-b5f6a748-4dc7-4d82-bd3f-dab8f2dbaeef.png" width="275"/>](https://user-images.githubusercontent.com/5157474/172029922-b5f6a748-4dc7-4d82-bd3f-dab8f2dbaeef.png)

- Allows users to search for American Slang and regular words
- Automatically caches words locally for use off-line

---- Tech used ----
- List of words is cached locally in a `Room` database
- Uses custom query for `Room` database
- Shows proper use of `Dagger-Hilt` & SOLID & CLEAN architecture
- Uses compose for view layer, `ViewModel` and `mutableState` to send UI events
- Uses Flow for API, UI & Database events
- Uses Resource sealed class to handle errors and messaging
- Custom tap event handling to hide keyboard

To install the Apk:

1. Open this link on your Android device:
   https://github.com/realityexpander/Slang-Dicitonary/blob/master/SlangDictionary_1.0.apk
2. Tap the "skewer" menu and tap the "download"

   [![](https://user-images.githubusercontent.com/5157474/147434050-57102a30-af32-46ed-a90b-d94e0c4a4f35.jpg)]()
3. Allow the file to download (DO NOT click "show details")
4. After the file is downloaded, click "OK" to install
5. Click "OK" to install
6. Click "OK" to launch

If you have developer options turned on, you may need to turn off "USB Debugging" if the "Waiting for debugger" dialog is displayed.