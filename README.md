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
          <li><a href="#login">Login</a></li>
        </ul>
      </ul>
      <ul><a href="#quick-start">Quick start</a></ul>
      <ul><a href="#iot-automation-device-management-system">IoT Automation Device Management System</a>
        <ul>
          <li><a href="#categories">Categories</a></li>
          <li><a href="#zones">Zones</a></li>
          <li><a href="#devices">Devices</a></li>
        </ul>
      </ul>
      <ul><a href="#orchestrator">Orchestrator</a></ul>
    </ol>
</details>

## General Info
### IoT Device Management System
***
This is an IoT UIPath Automation Device Management System that helps administrators register, organise, monitor, and remotely manage all IoT devices deployed by the organisation. Users and Administrator must login to be authorized so that they can register IoT devices, categorise them and deploy them throughout  the  organisation's  buildings  in  predefined  zones. 

**Zones**: _Keep track of areas where the IoT devices are deployed._

**Categories**: _Keep track of IoT devices that have particular shared characteristics._

**Device**: _The IoT device collect and share data about the way it is used and about the environment around it._


## Quick start
Clone the repository to open it on your PC

### Login
***
Follow these steps to login: 
1. Navigate to Category/Zone folder
2. The login is on made available on each User Acceptance Testing

## IoT Automation Device Management System

### Categories
***
#### How to Create a New Category
- Open Create Category.xaml
- Execute, if web app logged in, log out
- Automation will create all categories provided in the excel


When you’re done, click the **Stop** button UiPath Studio.

#### View Your Categories
To view a list of all the Categories:
- Open ReadCategory.xaml
- Execute, if web app logged in, log out
- Automation will read all categories.


When you’re done, click the **Stop** button UiPath Studio.

#### Edit and Update an Existing Category
You can edit categories that has already been created.
- Open UpdateCategories.xaml
- Execute, if its logged in, log out.
- Automation will log in and update description of categories.

#### Delete a Category
You can delete zones that has already been created.
- Open DeleteCategory.xaml
- Execute, if its logged in, log out.
- Automation will log in and delete categories.

### Zones
***
#### How to Create a New Zone
- Open CreateZone.xaml
- Execute, if web app logged in, log out
- Automation will create all zones provided in the excel


When you’re done, click the **Stop** button UiPath Studio.

#### View Your Zones
To view a list of all the Zones:
- Open ReadZone.xaml
- Execute, if its logged in, log out.
- Automation will log in and read all zones.

When you’re done, click the **Stop** button UiPath Studio.
#### Edit and Update an Existing Zone
You can edit a zone that has already been created.
- Open UpdateZones.xaml
- Execute, if its logged in, log out.
- Automation will log in and update description of zones.

#### Delete a Zone
You can delete zones that has already been created.
- Open DeleteZones.xaml
- Execute, if its logged in, log out.
- Automation will log in and delete zones.

### Devices
***
#### How to Create a New Device
- Open CreateDevices.xaml
- Execute, if web app logged in, log out
- Automation will create all devices provided in the excel


When you’re done, click the **Stop** button UiPath Studio.

#### View Your Devices
To view a list of all the Devices:
- Open ReadDevices.xaml
- Execute, if its logged in, log out.
- Automation will log in and read all devices.


#### Edit and Update an Existing Device
You can edit a device that has already been created.
- Open UpdateDevices.xaml
- Execute, if its logged in, log out.
- Automation will log in and update status of devices.

#### Delete a Device
You can delete a device that has already been created.
- Open DeleteDevices.xaml
- Execute, if its logged in, log out.
- Automation will log in and delete devices in a loop.


## Orchestrator

![orchestrator proof](https://user-images.githubusercontent.com/69342894/198301325-51d9701c-af46-4b19-9616-7847eb246a4c.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
