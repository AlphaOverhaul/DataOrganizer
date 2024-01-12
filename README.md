<br/>
<p align="center">
  <a href="https://github.com/AlphaOverhaul/DataOrganizer">
    <img src="pictures/logo.png" alt="Logo" width="150">
  </a>

  <h3 align="center">DataOrganizer</h3>

  <p align="center">
    Web-based database tool to organize your belongings, create and manage shopping lists
    <br/>
    <br/>
    <a href="https://github.com/AlphaOverhaul/DataOrganizer"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/AlphaOverhaul/DataOrganizer">View Demo</a>
    .
    <a href="https://github.com/AlphaOverhaul/DataOrganizer/issues">Report Bug</a>
    .
    <a href="https://github.com/AlphaOverhaul/DataOrganizer/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/AlphaOverhaul/DataOrganizer/total) ![Issues](https://img.shields.io/github/issues/AlphaOverhaul/DataOrganizer) 

## About The Project

![Screen Shot](images/screenshot.png)

My tool, the DataOrganizer, was developed to create a uniform overview of our things such as food, technology and other consumables for me and my family.

> But I thought it might be helpful for others too, so here it is

Here's why you should use this tool:

* Keep track of what you own, how long it has until the expiry date and get all the important information about your items quickly
* If you have been burgled, you can quickly check what is missing and report it accordingly.
* You can also create shopping lists and use the built-in stock system to have the program automatically write a part of the shopping list.

Of course, this tool is not completely helpful in some cases, but I just had the idea and implemented it. For example, I really like using the automatic storage system, which my family doesn't do.

## Built With

**Vue.js** for the frontend and **SpringBoot** for the backend

* [Vue.js](https://vuejs.org/)
* [SpringBoot](https://spring.io/)

## Getting Started
#### Disclaimer: I take no responsibility for any damage caused by this tool. The tool is intended for LAN use only
Before you can use this tool in your browser, you need to set up the backend correctly

### Prerequisites

To do this, please go through the following steps

* Make sure that you have Java installed.
> This is required for SpringBoot to work

### Installation

1. get the zip file with the executable files
   
3. Extract all the files

4. Place the file **dataorganizer_backend.jar** on a server device

4. Place the file **dataorganizer_frontend** on a server device. Preferably the same as before

5. further stufffff

## Usage

You can add products to a list and add notes to them:

**PC Main:**  CPU: i9 13900kf - GPU: RTX 5090 - SSD: 4x ADATA XPG 2TB - Cooler: Artic Liquid Freezer 360 etc...
#
You can create categories such as **"Fridge"**.
So under "Fridge", you can add a product like:

**Butter:** Purchased: 12.01.2024 - Expires: 31.12.2070
#
As already mentioned, a stock system is also integrated in this tool. This allows you to set the current amount of butter you have in the fridge to 2. If you have used both, you can set the quantity to 0 and if the setting for automatic replenishment is set for this product, it is automatically placed on the shopping list with the configured quantity
However, this system is unlikely to be helpful for most use cases

## Roadmap
* I plan to create a stand-alone version of this tool. So you don't need a separate backend and frontend. However, this will only work for one user.
* Another planned feature is a client app in Electron. This will allow you to edit your entries and products directly in an app instead of via a browser.

## Support
If you like the project, you can support it on <a href="https://github.com/AlphaOverhaul/DataOrganizer/issues">Patreon</a> :)

## License

Copyright © 2024 AlphaOverhaul. All rights reserved
