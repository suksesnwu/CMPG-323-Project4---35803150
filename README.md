<a name="readme-top"></a>
<div id="header" align="center">
  <h1>CMPG-323-Project4---35803150</h1>
</div>

<details>
  <summary>In this document</summary/>
    <ol>
      <ul>
        <a href="#general-info">General Info</a>
        <ul>
          <li><a href="#register">Register</a></li>
          <li><a href="#login">Login</a></li>
        </ul>
      </ul>
      <ul><a href="#quick-start">Quick start</a></ul>
      <ul><a href="#iot-web-app-device-management-system">IoT Web App Device Management System</a>
        <ul>
          <li><a href="#categories">Categories</a></li>
          <li><a href="#zones">Zones</a></li>
          <li><a href="#devices">Devices</a></li>
        </ul>
      </ul>
      <ul><a href="#license">License</a></ul>
    </ol>
</details>

## General Info
### IoT Device Management System
***
This is an <a href="https://iotsystem35803150.azurewebsites.net/" target="_blank">IoT Web App Device Management System</a> that helps administrators register, organise, monitor, and remotely manage all IoT devices deployed by the organisation. Users and Administrator must register/login to be authorized so that they can register IoT devices, categorise them and deploy them throughout  the  organisation's  buildings  in  predefined  zones. 

**Zones**: _Keep track of areas where the IoT devices are deployed._

**Categories**: _Keep track of IoT devices that have particular shared characteristics._

**Device**: _The IoT device collect and share data about the way it is used and about the environment around it._


## Quick start
Go to <a href="https://iotsystem35803150.azurewebsites.net/" target="_blank">https://iotsystem35803150.azurewebsites.net</a> to go to the web app.

### Register
***
<a name="registered"></a>
To register a new user, follow these steps: 
1. Go to <a href="https://iotsystem35803150.azurewebsites.net/Identity/Account/Register">Register</a> in the left sidebar.
2. Type the email you wish to register with(try other email if username has already been taken).
3. Enter your password and make sure that the password and confirmation password do match. Consider the following: 
 - The Password must be at least 6 and at max 100 characters long.
 - Passwords must have at least one non-alphanumeric character.
 - Passwords must have at least one lowercase ('a'-'z').
 - Passwords must have at least one uppercase ('A'-'Z').

### Login
***
Follow these steps to login: 
1. Go to <a href="https://iotsystem35803150.azurewebsites.net/Identity/Account/Register">Login</a> in the left sidebar.
2. Enter your email address(user has to be <a href="#registered">registered</a> to login).
3. Click the **Login** button.

## IoT Web API Device Management System

### Categories
***
#### How to Create a New Category
- Go to <a href="https://iotsystem35803150.azurewebsites.net/Categories">Categories</a> in the left sidebar (it appears when you're logged in).
- Click the _plus_ button at the top of your screen or go to <a href="https://iotsystem35803150.azurewebsites.net/Categories/Create">Create Category</a>, you will be able to add new Category. 

Here you can:
- Write a Category name
- Add Category description

When you’re done, click the **Create** button to create a new category.

#### View Your Categories
To view a list of all the Categories, go to <a href="https://iotsystem35803150.azurewebsites.net/Categories">Categories</a> on the right side of the toolbar.

Here you can see:
- **Category Name**: _This is the name of the category_
- **Category Description**: _This is the category description_
- **Category Date Created**: _Shows the date, and time the category was created_

There are options for each categories, click on the icons next to any category to do the following (in order):
- **Edit**: _Opens **Edit Category** so you can make changes to the category._
- **View**: _See **Categories Details**._
- **Delete**: _Opens **Delete Category** so you can delete a category._

#### Edit and Update an Existing Category
You can edit a category that has already been created.
- Click on the edit icon of the category you would like to edit. This will open the category in the **Edit Category** screen, where you can make changes to category name and decription.
- Click **Save** button to save your changes.

#### Delete a Category
- To delete a category, click the delete icon on the right of any category. This will open category in the **Delete Category** screen, where you can permanently delete the category.
- Click **Delete** button. This is permanent and the category cannot be restored after this action is taken.

### Zones
***
#### How to Create a New Zone
- Go to <a href="https://iotsystem35803150.azurewebsites.net/Zones">Zones</a> in the left sidebar (it appears when you're logged in).
- Click the _plus_ button at the top of your screen or go to <a href="https://iotsystem35803150.azurewebsites.net/Zones/Create">Create Zone</a>, you will be able to add new Zone. 

Here you can:
- Write a Zone name
- Add Zone description

When you’re done, click the **Create** button to create a new zone.

#### View Your Zones
To view a list of all the Zones, go to <a href="https://iotsystem35803150.azurewebsites.net/Zones">Zones</a> on the right side of the toolbar.

Here you can see:
- **Zones Name**: _This is the name of the zone_
- **Zones Description**: _This is the zone description_
- **Zones Date Created**: _Shows the date, and time the zone was created_

There are options for each zones, click on the icons next to any zone to do the following (in order):
- **Edit**: _Opens **Edit Zone** so you can make changes to the zone._
- **View**: _See **Zones Details**._
- **Delete**: _Opens **Delete Zone** so you can delete a zone._

#### Edit and Update an Existing Zone
You can edit a zone that has already been created.
- Click on the edit icon of the zone you would like to edit. This will open the zone in the **Edit Zone** screen, where you can make changes to zone name and decription.
- Click **Save** button to save your changes.

#### Delete a Zone
- To delete a zone, click the delete icon on the right of any zone. This will open zone in the **Delete Zone** screen, where you can permanently delete the zone.
- Click **Delete** button. This is permanent and the zone cannot be restored after this action is taken.

### Devices
***
#### How to Create a New Device
- Go to <a href="https://iotsystem35803150.azurewebsites.net/Devices">Devices</a> in the left sidebar (it appears when you're logged in).
- Click the _plus_ button at the top of your screen or go to <a href="https://iotsystem35803150.azurewebsites.net/Devices/Create">Create Device</a>, you will be able to add new Device. 

Here you can:
- Write a Device name.
- Give the device a category.
- Give the device a zone.
- Add status.
- Click [x] if device is active.

When you’re done, click the **Create** button to create a new device.

#### View Your Devices
To view a list of all the Devices, go to <a href="https://iotsystem35803150.azurewebsites.net/Devices">Devices</a> on the right side of the toolbar.

Here you can see:
- **Device Name**: _This is the name of the device_
- **Status**: _This is the status of the device_
- **Is Active**: _[x] if active, else [] if device not active_
- **Date Created**: _Shows the date, and time the device was created_
- **Category**: _Shows selected category_
- **Zone**: _Shows selected zone_

There are options for each devices, click on the icons next to any device to do the following (in order):
- **Edit**: _Opens **Edit Device** so you can make changes to a device._
- **View**: _See **Device Details**._
- **Delete**: _Opens **Delete Device** so you can delete a device._

#### Edit and Update an Existing Device
You can edit a device that has already been created.
- Click on the edit icon of the device you would like to edit. This will open the device in the **Edit Device** screen, where you can make changes to device.
- Click **Save** button to save your changes.

#### Delete a Device
- To delete a device, click the delete icon on the right of any device. This will open device in the **Delete Device** screen, where you can permanently delete the device.
- Click **Delete** button. This is permanent and the device cannot be restored after this action is taken.


## License

- Copyright 2022 © <a href="https://www.nwu.ac.za/" target="_blank">NWU</a>.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
