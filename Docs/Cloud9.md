AWS Cloud9 is a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser. It includes a code editor, debugger, and terminal. Using Cloud9, we can get an instance of this modular Node.js IRC bot running in no time.

# Requirements
- An Amazon Web Services account: [Tutorial](https://www.youtube.com/watch?v=WviHsoz8yHk)
- An [Cloud9 Environment]

# Tutorial
## 1. Installing the repository

In order for the updater to work, you will have needed to download everything from the [Github Repositroy](https://github.com/ApexTon/Modular-Node.js-IRC-Bot/). In order to download everything from the Github repository, you will need to clone it. In order to clone it, you will need to have installed git.

1. With your environment open, in the AWS Cloud9 IDE, start a new terminal session, if one isn't already started. (To start a new terminal session, on the menu bar, choose Window and then New Terminal.)

If you already have git past version v1.7.9 installed in your environment, skip to the next part of this tutorial. Otherwise, follow the following depending on what platforum you have.
If you're unsure, type `git --version` in a Terminal session.

### Installing Git - Amazon Linux

2. Update the package listing by typing `sudo yum -y update`.
3. Install git by typing `sudo yum -y install git`.

### Installing Git - Ubuntu

2. Update the package listing by typing `sudo apt update`
3. Install git by typing `sudo apt install -y git`.

To confirm you have git installed, type `git --version` in the terminal session

### Cloning the repository

Type `git clone https://github.com/Apexton/Modular-Node.js-IRC-Bot`.


## Running the bot

1. Go to your IDE
2. Edit `config.js` to suit your needs.
3. Save `config.js` by clicking Save from the File Menu
4. Install all the required node dependencies via the terminal `npm install`.
5. Run the `main.js` file

- Terminal: `node main.js`
- IDE: Run -> Run With -> Node.JS
