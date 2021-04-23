# Swift-Local-Storage
This mobile application creates a local storage. User can input name and birthday and user can see informations even if the application is closed.

First of all I have designed aspect of application from Main.storyboard.

<img width="488" alt="Ekran Resmi 2021-04-23 15 06 32" src="https://user-images.githubusercontent.com/49618009/115874475-cedd2000-a44c-11eb-9d4e-ecc437f0f306.png">


And I have linked my elements to ViewController.swift. Later I have written my application codes. 
In this project, I have used UserDefaults. This library provides to store your informations. You can see these codes below.

Here these codes are in button function.

<img width="551" alt="Ekran Resmi 2021-04-23 15 55 57" src="https://user-images.githubusercontent.com/49618009/115875200-a43f9700-a44d-11eb-9aa8-1abed1155e85.png">

When user click save button the app save informations.

<img width="385" alt="4-23 15 08 04 kopya" src="https://user-images.githubusercontent.com/49618009/115875407-db15ad00-a44d-11eb-9746-13b642086609.png">

After closing app and when open again, because I have used UserDefaults, user can see informations in the screen.

<img width="488" alt="Ekran Resmi 2021-04-23 15 08 44" src="https://user-images.githubusercontent.com/49618009/115875847-54150480-a44e-11eb-963e-2e0460c6ec1d.png">

After I have written deleting codes. You can see these code in deleteButton functions.

<img width="504" alt="Ekran Resmi 2021-04-23 15 56 14" src="https://user-images.githubusercontent.com/49618009/115876310-d1d91000-a44e-11eb-968e-331f82a3e87d.png">

When user click delete button all information is lost.

<img width="385" alt="1-04-23 15 09 07 kopya" src="https://user-images.githubusercontent.com/49618009/115876405-f208cf00-a44e-11eb-91be-83b403919bb4.png">

And again when you close and open again the app you can see no information.

<img width="488" alt="Ekran Resmi 2021-04-23 15 06 32" src="https://user-images.githubusercontent.com/49618009/115876495-0f3d9d80-a44f-11eb-8e40-de99e5c7bf6f.png">
