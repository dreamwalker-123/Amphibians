# Amphibians
We have created an application to display a list of amphibians along with their information and images. The data is retrieved from the Internet via a network query and contains the name, type, description, and image URL of each amphibian.

What do we have here:
1) uses-permission android:name="android.permission.INTERNET"
2) android:name=".AmphibiansApplication" for class AmphibiansApplication : Application() with container: AppContainer
3) DI implementation with repository, container, implementation of the Factory pattern on the viewModel object
4) we used Coil library and created AsyncImage
5) we used Retrofit library and created networkApiService
