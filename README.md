# Local Corona Notificator
This Python script sends an email with an overview of the current status of the corona virus based on the public data of the RKI.

It's a small privat project for me and my friends.

<hr>

### Before I publish the code, I try to improve and document the code. :)
If you are interested in the project, you are welcome to download the files and use them for private purposes.

## Requirements
- Python 3
- An email server

## Installation
1. Download the repo here and extract it: (Source Code)[https://github.com/derLesh/local-corona-notification/archive/main.zip]
2. Get the required modules `pip i requirements.txt`
3. Fill the `data.json` file with your personal information.
- Find the smtp data from your mail provider (SSL only)
4. Add a new user with `python3 main.py add <name> <email> <city>` or add it manully in the `data.json` file.
5. Wanna test the result first? Run `python3 run.py --test`

<hr>

Everything that is written here can and will be changed in the further development.
If you downloaded the repo earlier, please refer to the local readme.md file.

Thank you.
