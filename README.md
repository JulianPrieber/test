<h1 align="center">
  <br>
  <a href="https://github.com/JulianPrieber/littlelink-custom"><img src="https://i.imgur.com/qNe686V.png" alt="LittleLink Custom"></a>
</h1>

<h4 align="center">The "plug and play" approach to LittleLink</h4>

<p align="center">

</p>
      
<p align="center">
  <a href="#About">About</a> •
  <a href="#Function">Function</a> •
  <a href="#Demo">Demo</a> •
  <a href="#Features">Features</a> •
  <a href="#Installation">Installation</a> •
  <a href="#Updating">Updating</a> •
  <a href="#Fork-Structure">Fork structure</a> •
  <a href="#License">License</a> •
  <a href="#Special-thanks">Special thanks</a> •
  <a href="#Additional-credit">Additional credit</a>
</p>

<p align="center">
  <a href="https://julianprieber.github.io/littlelink-custom-demo/"><img src="https://i.imgur.com/EJNaMNW.png" alt="Live Demo" width="250" ></a>
</p>

![Discord Banner 3](https://discordapp.com/api/guilds/955765706111193118/widget.png?style=banner3)

---

## About
LittleLink Custom is a fork of [LittleLink Admin](https://github.com/latuminggi/littlelink-admin) with a set goal of making the admin panel easier to use and setup, for inexperienced and first-time user's, with the addition of many custom features themed around customization for the individual users, LittleLink pages.

LittleLink Custom was made for the purpose of making LittleLink as well as LittleLink Admin easier to use and setup, by people who have never coded before nor have extensive web hosting knowledge.
This project is set up in a way that you can just drag and drop the LittleLink Custom directory onto your web host's root directory without ever having to touch the source code or deal with pesky terminal commands.

In addition to an easier setup process, this fork adds many custom features for an improved and more feature rich user experience. All UI pages feature a dark mode, which automatically applies if your operating system's or browser theme is set to dark. LittleLink Custom adds light unobtrusive CSS animations for an esthetically pleasing responsive design. Many small changes like this have been implemented that add up to a substantial feature set that sets LittleLink Custom apart from other forks.

<br>
	    
## Function    
LittleLink Custom provides you with a website similar to [Linktree](https://linktr.ee). Many social media platforms only allow you to add one link, with this you can simply link to your LittleLink Custom page and have all the links you want displayed on one site. 
You can share all your links to your social media platform or important links to easy accessible and hosted on your own web-server or web-hosting provider. 
On this website, other users can register and create their own links, you can access other user via the Admin Panel.
	    
<br>
	    
## Demo	    

<h3 align="center">Try a live demonstration of the LittleLink page with button animations and selectable dark mode</h3>
<br>	    
<p align="center">
  <a href="https://julianprieber.github.io/littlelink-custom-demo/"><img src="https://i.imgur.com/EJNaMNW.png" alt="Live Demo" width="350" ></a>
</p>
	    
## Features
	
|                                                 | LittleLink Custom  | LittleLink Admin¹   |LittleLink      |
| ------------------------------------------------| :----------------: | :---------------: | :--------------: |
| Creating a link page with more than 20 buttons  |         ✔️         |        ✔️        |        ✔️        |
| Code free setup                                 |         ✔️         |        ✔️        |        ❌        |
| Raising important links on the page             |         ✔️         |        ✔️        |        ❌        |
| Ordering links                                  |         ✔️         |        ✔️        |        ❌        |
| Counting clicks                                 |         ✔️         |        ✔️        |        ❌        |
| Managing users and pages and links              |         ✔️         |        ✔️        |        ❌        |
| Automatic dark mode detection                   |         ✔️         |        ✖️²       |        ❌        |
| Button hover animations                         |         ✔️         |        ❌        |        ❌        |
| custom link option                              |         ✔️         |        ❌        |        ❌        |
| Social Share Preview for individual users       |         ✔️         |        ❌        |        ❌        |
| No database required                            |         ✔️         |        ❌        |        ❌        |
| Update notice if new version is available       |         ✔️         |        ❌        |        ❌        |
| Setup without command line                      |         ✔️         |        ❌        |        ❌        |
		    
¹[littlelink-admin](https://github.com/latuminggi) by [latuminggi](https://github.com/latuminggi/littlelink-admin) | 
²Not fully implemented on most pages

<br></br>
<h3 align="center">All LittleLink Custom pages automatically apply the Dark Mode Theme if your preferred theme setting in your browser or operating system is set to dark.</h3>
<p align="center">
<img height="650" src="https://i.imgur.com/vHyAO4V.png">
</p>
	    
<br></br>
<h3 align="center">Lightweight CSS animations</h3>
<p align="center">
<img height="450" src="https://i.imgur.com/OL0sf89.gif">
</p>

<br>

## Installation

### Downloading and installing steps:
* **[Download](https://github.com/JulianPrieber/littlelink-custom/releases)** the latest release of LittleLink Custom and simply place the folder 'littlelink-custom' in the root directory of your website.

### That's it! No coding no command line setup just plug and play.

<br>	

#### Now access your install of LittleLink Custom with 'your-domain-name.com/littlelink-custom'.
* At first, you will be greeted with a 'MissingAppKeyException'.
* This is totally normal on first setups, simply click on the 'Generate app key' button and then 'Refresh now' and you're done.

#### You can now log in to the Admin Panel with the credentials:
-   **email:** `admin@admin.com`
-   **password:** `12345678`


### Optional configuration:
Optionally, you can change the app name in your ".env" file in the root directory of your LittleLink Custom installation. At the moment this is set to
APP_NAME="LittleLink Custom" you can change "LittleLink Custom" to what ever you like. This setting defines the page title and welcome message.

Additionally, the littlelink-custom directory can be renamed to anything you see fit, further customizing your personal LittleLink Custom install.

<br>

## Updating

When a **new version** is released, you will get an update notification on your Admin Panel.

### Disclaimer: Always make a backup  before updating in case something breaks!

To update, simply download the 'update' file from the [release tab on GitHub](https://github.com/JulianPrieber/littlelink-custom/releases). Do not use the regular release for the update, as it contains files that will overwrite important files that store your links and user information, effectively resetting your installation.

The downloaded archive contains a 'README' which tells you exactly how to update.

In most cases, you will just have to move the contents of the update file into your LittleLink Custom directory. It is essential to overwrite existing files for the updates to apply.

### Exceptions:
If the update contains new features like new buttons, you would have to use the command line to implement these new features. This step will always be optional. Instructions on how to do this will always be in the 'README' file.

<br>

## Fork-Structure
Fork of a fork of a fork of LittleLink...
<br>
#### LittleLink fork-tree:
<pre>
LittleLink
   │
   └── LittleLink Admin
         │
         └── LittleLink Admin (fork)
               │
               └── LittleLink Custom
</pre>
<br>
LittleLink Custom is a fork of LittleLink Admin.

> "LittleLink Admin is an admin panel for littlelink that provides you a website similar to [Linktree](https://linktr.ee)."

LittleLink Admin is in itself a fork of [LittleLink](https://github.com/sethcottle/littlelink) 

> "LittleLink is a lightweight DIY alternative to services like [Linktree](https://linktr.ee) and [many.link](https://many.link/). LittleLink was built using [Skeleton](http://getskeleton.com/), a dead simple, responsive boilerplate—we just stripped out some additional code you wouldn't need and added in branded styles for popular services."

<br>

## License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://raw.githubusercontent.com/JulianPrieber/littlelink-custom/main/LICENSE?token=GHSAT0AAAAAABRPYRQAPFRUGQA4A2OMFBUQYQWHZCQ)


<br>

## Special-thanks 

### special thanks to:
* [Seth Cottle](https://github.com/sethcottle) for creating [LittleLink](https://github.com/sethcottle/littlelink) the base of all this.
* [Khashayar Zavosh](https://github.com/khashayarzavosh) for creating [LittleLink Admin](https://github.com/khashayarzavosh/littlelink-admin), the base framework of the admin panel and many other essentials features of this project.
* [Aprillio Latuminggi (latuminggi)](https://github.com/latuminggi) for creating the fork this fork is based [LittleLink Admin (fork)](https://github.com/latuminggi/littlelink-admin)  
   
<h4 align="center">Thank you!</h4>

| [![sethcottle](https://avatars.githubusercontent.com/u/1301949?v=4)](https://github.com/sethcottle) | ![khashayarzavosh](https://avatars.githubusercontent.com/u/60265643?v=4)		| ![latuminggi](https://avatars.githubusercontent.com/u/6211719?v=4)		|
|:------------------------------------------------------------------------------------------------------------------------:	|:----------------------------------------------------------------------------------------------------:	|:----------------------------------------------------------------------------------------------------:	|
|                                                      Seth Cottle                                                      |                                             Khashayar Zavosh                                             |                                             Aprillio Latuminggi                                             |
|                                 **[LittleLink](https://github.com/sethcottle/littlelink)**                                |              **[LittleLink Admin](https://github.com/khashayarzavosh/littlelink-admin)**              |             **[LittleLink Admin (fork)](https://github.com/latuminggi/littlelink-admin)**             |

<br>

## Additional-credit

- [laravel](https://github.com/laravel/laravel)
- [panel template](https://colorlib.com/wp/bootstrap-sidebar)
- [button animations](https://github.com/IanLunn/Hover)
- [general animations](https://github.com/animate-css/animate.css)


