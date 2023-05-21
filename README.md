# Anas Bashandy
I am a self-taught iOS Developer, and here you can find some of the projects I have worked on.

## SPIntory

<a href="https://apps.apple.com/eg/app/spintory/id1543602143">
<picture>
  <source media="preferes-colors-scheme:light" srcset="https://github.com/bashmoanas/portfolio/assets/34455425/d1f3db05-d905-4e36-804a-f7ea3e8b2452">
  <source media="preferes-colors-scheme:dark" srcset="[https://github.com/bashmoanas/portfolio/assets/34455425/d1f3db05-d905-4e36-804a-f7ea3e8b2452](https://github.com/bashmoanas/portfolio/assets/34455425/9399122d-1d72-4848-ac7c-cac3dba6f750)">
  <img alt="Shows the download on the App Store badge. Tap here to go the app page on the App Store." src="https://github.com/bashmoanas/portfolio/assets/34455425/9399122d-1d72-4848-ac7c-cac3dba6f750">
</picture>
</a>

SPIntory is meant to solve the proble of inventory management for small businesses. At the time, my family business was dealing with small quantities of spare parts and we needed a better way to keep track of the current stock at any time instead of using a spreadsheet. The app allows the person responsible of the inventory to add the spare parts he needs to track, with each part having a unique part number. He then can perform either a purchase or a sale transaction on previously saved parts and the current stock updates automatically.

The app was written in Swift using UIKit and Core Data. I wrote all the UI code programmatically to preserve a single source of truth. The app was designed with Model View Controller in mind as to adhere to the same design paradigm of UIKit. I used the Coordinator pattern to manage the app's navigation.


## ToDoListApp

A task tracking app that allows the user to add, edit and delete items at familiar table-based interface. The app handles the following actions:
- display the list
- add items to the list
- edit existing items on the list
- delete items from the list
- automatically save the list to disc

The project is built using UIKit, MVC, with the model being managed by a store to separate the logic from the view controller. 

## Photorama

Photorama reads a list of interesting photos from Flickr. The app saves the downloaded photos to disk. When the app relaunches, it first checks whether a photo is on the disk or not to avoid any unnecessary network call. If the image already exists, it's loaded from disk; if not, the app then send a request to download the image and then caches it for the future.
