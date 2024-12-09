🇷🇺 [Russian README](https://github.com/Dellenoam/NotPixelBot/blob/master/README_RU.md)

# NotPX Bot ⬛

Automated script for NotPixel with painting on canvas using a template, passing proof-of-humanity checks and more 

## Requirements

[![Python](https://img.shields.io/badge/python-%3E%3D3.10-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Node.js](https://img.shields.io/badge/Node.js-%3E%3D20.18.0-6DA55F?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/)

## Features  

<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>Supported</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SuperMegaCool Capybara intro</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Tournament update</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Passing proof-of-humanity checks</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>NotPX API change detection</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Script in .exe</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Simple scripts for installation and uninstallation</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Proxy binding to session</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>User-Agent binding to session</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Auto-detect new .session and register it in bot</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Auto-paiting</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Auto-tasks</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Auto-input of the secret words we know</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Auto-input of daily secret words</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Watching ads</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Auto-use bombs</td>
      <td><img src="https://img.shields.io/badge/Work_in_Progress-orange?style=flat-square" alt="X badge"></td>
    </tr>
    <tr>
      <td>Auto-claim PX</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Auto-upgrade boosters</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Night mode</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Async working</td>
      <td>✅</td>
    </tr>
  </tbody>
</table>

## Why are we better than the rest of the public scripts?

### ✨ Capybara Intro (game changer, killer feature)

![Capybara Intro](https://github.com/Dellenoam/NotPixelBot/blob/master/assets/Capybara_Intro.gif)

### 🔍 Proof-of-Humanity checks

We use **real** task solutions for proof-of-humanity checks instead of random responses, so you don't get banned.

There is still a chance of being banned, but it we did everything possible to prevent it.

### 🎨 Auto-Painting

We don't use random coordinates to paint on the canvas.

Our script automatically paints on the canvas using a template using data received from the websocket connection. It means that you will receive a PX for each painting you make!

### 🌟 Simple scripts to install NotPixelBot and uninstall it

We provide simple scripts for easy installation and uninstallation of the NotPixelBot.

### 🔗 We have a clear use of ref system

If you change the ref id to your own in the settings, that's what it will be. Our script does not prevent you from doing this, unlike some public scripts.

### 🚀 Regular updates

We update NotPixelBot according to changes in NotPixel.

## [Settings](https://github.com/Dellenoam/NotPixelBot/blob/master/.env-example)

<table>
  <thead>
    <tr>
      <th>Settings</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>API_ID / API_HASH</td>
      <td>API credentials for Telegram API</td>
    </tr>
    <tr>
      <td>PLAY_INTRO</td>
      <td>True/False playing intro on script start (DON'T YOU DARE TO TURN THIS OFF)</td>
    </tr>
    <tr>
      <td>INITIAL_START_DELAY_SECONDS</td>
      <td>Delay range in seconds to use for a random delay when starting the session</td>
    </tr>
    <tr>
      <td>ITERATION_SLEEP_MINUTES</td>
      <td>How long the script will wait before starting the next iteration of the script (painting, claiming and e.t.c)</td>
    </tr>
    <tr>
      <td>USE_REF</td>
      <td>True/False the use of a referral to start the bot</td>
    </tr>
    <tr>
      <td>REF_ID</td>
      <td>Referral ID to be used</td>
    </tr>
    <tr>
      <td>TOURNAMENT_TEMPLATE_ID</td>
      <td>ID of the tournament template</td>
    </tr>
    <tr>
      <td>SLEEP_AT_NIGHT</td>
      <td>True/False sleep at night</td>
    </tr>
    <tr>
      <td>NIGHT_START_HOURS</td>
      <td>Start hours range of the night</td>
    </tr>
    <tr>
      <td>NIGHT_END_HOURS</td>
      <td>End hours range of the night</td>
    </tr>
    <tr>
      <td>ADDITIONAL_NIGHT_SLEEP_MINUTES</td>
      <td>Additional minutes range to sleep at night</td>
    </tr>
    <tr>
      <td>ROUND_START_TIME_DELTA_MINUTES</td>
      <td>Additional minutes after the start of the round</td>
    </tr>
    <tr>
      <td>ROUND_END_TIME_DELTA_MINUTES</td>
      <td>Additional minutes before the end of the round</td>
    </tr>
    <tr>
      <td>CLAIM_PX</td>
      <td>True/False auto-claim px</td>
    </tr>
    <tr>
      <td>UPGRADE_BOOSTS</td>
      <td>True/False auto-upgrade boosters</td>
    </tr>
    <tr>
      <td>PAINT_PIXELS</td>
      <td>True/False auto-painting</td>
    </tr>
    <tr>
      <td>COMPLETE_TASKS</td>
      <td>True/False auto-completing tasks</td>
    </tr>
    <tr>
      <td>PARTICIPATE_IN_TOURNAMENT</td>
      <td>True/False participate in tournament</td>
    </tr>
    <tr>
      <td>COMPLETE_QUESTS</td>
      <td>True/False auto-input of the secret words we know</td>
    </tr>
    <tr>
      <td>COMPLETE_DANGER_TASKS</td>
      <td>True/False auto-completing dangerous tasks</td>
    </tr>
    <tr>
      <td>WATCH_ADS</td>
      <td>True/False auto-watch ads</td>
    </tr>
  </tbody>
</table>

## How to install 📚

Before you begin, make sure you have meet the [requirements](#requirements). It's really IMPORTANT, without these requiremenets, you can NOT install our script.

### Obtaining API Keys

1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

Sometimes when creating a new application, it may display an error. It is still not clear what causes this, but you can try the solutions described on [stackoverflow](https://stackoverflow.com/questions/68965496/my-telegram-org-sends-an-error-when-i-want-to-create-an-api-id-hash-in-api-devel).

### Linux manual installation

```shell
git clone https://github.com/asish1346/NotPro.git
cd NotPro
python3 -m venv .venv
source .venv/bin/activate
pip install poetry
poetry install --only main
cp .env-example .env
nano .env  # Specify your API_ID and API_HASH, the rest is taken by default
```

### Windows manual installation

```shell
git clone https://github.com/asish1346/NotPro.git
cd NotPixelBot
python -m venv .venv
.venv\Scripts\activate
pip install poetry
poetry install --only main
copy .env-example .env
# Then open .env in any text editor and specify your API_ID and API_HASH, the rest is taken by default
```

### Windows installation using powershell script

NOTE: The install.ps1 script installs Chocolatey, a package manager for Windows, and uses it to install Python, Git, and NodeJS, if they are not already installed

We have also created powershell script which allows you to easily install NotPixelBot on Windows.

Before running the script, you must do some preparation

Open powershell and enter there this command. This will allow you to run scripts without restrictions.

```shell
Set-ExecutionPolicy Unrestricted -Scope CurrentUser
```

Ok, now we are ready. Execute following commands:

```shell
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/Dellenoam/NotPixelBot/refs/heads/master/windows_scripts/install.ps1" -OutFile "$env:TEMP\install.ps1"

powershell -ExecutionPolicy Bypass -File "$env:TEMP\install.ps1"
```

After that script will be downloaded to the temp folder and executed. When it asks you to enter path where to do git clone, just enter the path where you want to do git clone. For example `C:\Users\username\Scripts\NotPixelBot` without any quotes.

Navigate to the folder with the installed bot. Copy the .env-example file and rename it to .env, then open it in any editor and write down the API_ID and API_HASH that you received earlier.

Now you can proceed to the [Run the script](#run-the-script) section.

### Windows uninstallation using powershell script

NOTE: The install.ps1 script installs Chocolatey, which is then used to install Python, Git, and Node.js. This uninstall.ps1 script will also uninstall these programs using Chocolatey, including Chocolatey itself. However, it will not remove the NotPixelBot folder. Therefore, please be cautious.

If you want to uninstall NotPixelBot, run following commands:

```shell
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/Dellenoam/NotPixelBot/refs/heads/master/windows_scripts/uninstall.ps1" -OutFile "$env:TEMP\uninstall.ps1"

powershell -ExecutionPolicy Bypass -File "$env:TEMP\uninstall.ps1"
```

### Run the script

![NotPixel Intro](https://github.com/Dellenoam/NotPixelBot/blob/master/assets/NotPixel_Intro.gif)


#### Using start.bat

You can run the script using start.bat script, just execute it.

#### Manually

Before running the script, you ALWAYS need to activate the virtual environment and check for updates.

```shell
# Linux
source .venv\bin\activate
# Windows
.venv\Scripts\activate

# Linux/Windows
git pull
```

To run the script, use `python3 main.py` on Linux or `python main.py` on Windows.

Also, you can use flag `--action` or `-a` to quickly run the script with specified action.

```shell
# Linux
python3 main.py --action [1/2]
# Windows
python main.py --action [1/2]

# Or

# Linux
python3 main.py -a [1/2]
# Windows
python main.py -a [1/2]
```

Where [1/2] is:

    1 - Creates a session
    2 - Run bot

So for example if you want to create a session, you can run this command:

```shell
# Linux
python3 main.py --action 1
# Windows
python main.py --action 1

# Or

# Linux
python3 main.py -a 1
# Windows
python main.py -a 1
```

## Contacts

If you have any questions or suggestions, please feel free to contact us in comments.

[![Capybara Society Telegram Channel](https://img.shields.io/badge/Capybara%20Society-Join-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/capybara_society)
