# Bird Bot Cousin
<br/>
Bird Bot Cousin is a fork of natewong1313/bird-bot following it's owner's decision to archive the reposityory and has added the pull request from
contributors of that repo that were not applied due to it being archived. Although I've done this, the fixes and improvements are not solutions I
have provided nor am I well-versd enough in coding to maintain this in any signficant form of contribution. It has merely been assembled for my
own use, reference, and convenience;, and, if you're interested, you're more than welcome to to use it.
<br/>


## Bird Bot (Original Description)
[Support Discord](https://discord.gg/kfAqBKv)<br/><br/>
Bird Bot is an auto-checkout bot that currently supports Walmart and Best buy. It is intended to be used to purchase Nintendo Switch consoles. More sites will be added in the future.

* Easy to use interface built on PyQt5
* Waits for items to restock if they are out of stock
* Optional price checker
* Lightning fast auto-checkout

<p align="center">
  <img src="https://i.imgur.com/E105F74.png" alt="Bird Bot UI" width="738">
</p>


## Installation
[View The Docs Here](https://nateskicks13.gitbook.io/bird-bot/) - The original installation instruction as provided by Nate Wong.

Alternatively, the previous instructions were restored for quick reference:

<table align="center" border="0">
<tr><td colspan=2 align="left">
  
## Getting Started	
Here's what you need to do to get Bird Bot installed on your computer.
- If you're on Windows you you may want to download and install Git to execute but it is not necessary
- Python version 3.6 or higher
</td></tr>
<br>
<tr><td colspan=2 align="left">

## Prerequisites	
* **Python 3** - you can download it a 64-bit version of [Python 3.8](https://www.python.org/ftp/python/3.8.2/python-3.8.2-amd64.exe) from the provided link
* Be sure to add it to PATH - i.e."Add Python 3.8 to PATH"	during installation
* Also, installing to anything other than the default repository may cause issues.

  </td></tr>

<table align="center" border="0">
<tr><td colspan=2 align="left">

## Installation
 
 Start by copying the repository to your machine by running each command
```sh	
git clone https://github.com/natewong1313/bird-bot.git	
cd bird-bot	
pip install -r requirements.txt	
```	
If you don't have git installed, you can instead download the repository [here](https://github.com/natewong1313/bird-bot/archive/master.zip). Then cd into it and run `pip install -r requirements.txt`	
</td></tr>

<tr><td colspan=2 align="left">

## How to Use the Program

To start the bot, run 	
```sh	
python app.py	
```	
To start making tasks, you will first need to setup a profile. A profile contains your shipping, billing, and payment details that are used to checkout. Click the wallet icon on the sidebar and you will the profiles page. Once you've filled out your information, name the profile and then click the save button. You can use the load profile dropdown to check existing profiles or delete profiles.	

<p align="center">	
  <img src="https://i.imgur.com/BTTki9y.png" alt="Bird Bot Profiles" width="738">	
</p>	

After you're done making a profile, you will want to create a task. Tasks will automatically checkout the item if it is instock, or wait for it to restock. You can run as many tasks as you would like. To make a task, go back to the homepage and click the add task button in the top right. You will then see a pop-up window appear. Choose a site, input the link of the product you want to checkout, and choose a profile. There are two numbers that will be automatically filled out in the bottom left. These numbers are how many seconds the bot will sleep for if it is waiting for a restock or an error occurs. You can change these to whatever you prefer. If you are waiting for a product to restock for a certain price, click the max price checkbox and input the highest price you want to pay for the item. Then click add task	
<p align="center">	
  <img src="https://i.imgur.com/Kya9pbe.png" alt="Bird Bot Popup" width="438">	
</p>	

Now that you have made a task(s), you can start them by clicking the play icon. You can delete the task by clicking the trash can icon. Make sure to not delete the task if it's running.	
<p align="center">	
  <img src="https://i.imgur.com/edPtLPV.png" alt="Bird Bot Tasks" width="738">	
</p>
</td></tr>
<tr><td colspan=2 align="left">

## Common Issues

- [When trying to start the bot](https://nateskicks13.gitbook.io/bird-bot/common-errors-1/opening-the-bot) - 'pip' is not recognized
- [After Starting Tasks](https://nateskicks13.gitbook.io/bird-bot/common-errors-1/after-starting-tasks) - Stuck on Tas Data, Error Loading Product Page, or ConnectionError
- [Adding to the Cart](https://nateskicks13.gitbook.io/bird-bot/common-errors-1/adding-to-cart) - Error Adding to cart
- [Checkout Errors])https://nateskicks13.gitbook.io/bird-bot/common-errors-1/checkout-errors) - Error Submitting Shipping, Error Submitting Payment/Payment fail, Error Authorizing
- [Browser Errors](https://nateskicks13.gitbook.io/bird-bot/common-errors-1/browser-errors) - Browser isn't opening

</td></tr>
<tr><td colspan=2 align="left">

## Special Thanks
To all the contributors of the former, now archived repo, and voluntarily contributing to improving it's minor flaws.

</td></tr>
</table>
