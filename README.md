# Anas Bashandy
I am a self-taught iOS Developer, and here you can find some of the projects I have worked on.

## SPIntory

<a href="https://apps.apple.com/eg/app/spintory/id1543602143">
<picture>
  <source
          media="(prefers-color-scheme:light)"
          srcset="https://github.com/bashmoanas/portfolio/assets/34455425/1290f71a-6fe5-486c-a186-8c0015282611">
  <source
          media="(prefers-color-scheme:dark)"
          srcset="https://github.com/bashmoanas/portfolio/assets/34455425/bfb768a6-a832-4881-96ac-6c19f44936a1">
  <img alt="Shows the download on the App Store badge. Tap here to go the app page on the App Store."
       src="https://github.com/bashmoanas/portfolio/assets/34455425/1290f71a-6fe5-486c-a186-8c0015282611">
</picture>
</a>

SPIntory is meant to solve the problem of inventory management for small businesses. At the time, my family business was dealing with small quantities of spare parts and we needed a better way to keep track of the current stock at any time instead of using a spreadsheet. The app allows the person responsible of the inventory to add the spare parts he needs to track, with each part having a unique part number. He then can perform either a purchase or a sale transaction on previously saved parts and the current stock updates automatically.

The app was written in Swift using UIKit and Core Data. I wrote all the UI code programmatically to preserve a single source of truth. The app was designed with Model View Controller in mind as to adhere to the same design paradigm of UIKit. I used the Coordinator pattern to manage the app's navigation.



![SPIntoryScreenshots 001](https://github.com/bashmoanas/portfolio/assets/34455425/f9130ad8-56af-44e7-98fd-e23da093637e)



![SPIntoryScreenshots 002](https://github.com/bashmoanas/portfolio/assets/34455425/f79d1375-fbc6-42a3-a82c-9cf48727d54c)



![SPIntoryScreenshots 003](https://github.com/bashmoanas/portfolio/assets/34455425/8a92be31-b840-4015-b040-f7951c909bc9)



![SPIntoryScreenshots 004](https://github.com/bashmoanas/portfolio/assets/34455425/120bd26c-7e9a-40ac-a928-4d66208da10d)



## [ToDoListApp](https://github.com/bashmoanas/ToDoList)
A task tracking app that allows the user to add, edit and delete items at familiar table-based interface. The app handles the following actions:
- display the list
- add items to the list
- edit existing items on the list
- delete items from the list
- automatically save the list to disc

The project is built using UIKit, MVC, with the model being managed by a store to separate the logic from the view controller. 



![ToDoAppScreenshots 001](https://github.com/bashmoanas/portfolio/assets/34455425/2e5192ad-1775-490b-9a16-755517f8d69a)



## [Photorama](https://github.com/bashmoanas/Photorama)

Photorama reads a list of interesting photos from Flickr. The app saves the downloaded photos to disk. When the app relaunches, it first checks whether a photo is on the disk or not to avoid any unnecessary network call. If the image already exists, it's loaded from disk; if not, the app then send a request to download the image and then caches it for the future.



![PhotoramaScreenshots 001](https://github.com/bashmoanas/portfolio/assets/34455425/c6ae490d-6cb6-4cf0-850f-2ff3f474deda)


