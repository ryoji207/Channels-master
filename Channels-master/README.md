## Quick start:

* Clone the repository: `git clone git@github.com:gregzaal/Auto-Voice-Channels.git`
* Go to the directory: `cd Auto-Voice-Channels`
* Make folder to store guild settings: `mkdir guilds`
* Install pip: `sudo apt-get -y install python3-pip`
* Install requirements: `python3 -m pip install -r requirements.txt`
* Install venv: `pip3 install virtualenv`
* Make venv: `python3 -m virtualenv bot-env`
* Use venv: `. bot-env/bin/activate`
* Create your application + bot here: <https://discordapp.com/developers/applications>
* Set up `config.json`:
  * `admin_id` is your ID, for the bot to DM you when it logs on, joins servers, gets errors, etc.
  * `client_id` is the bot ID.
  * `log_timezone` is for the time displayed in logs, see [this list](https://stackoverflow.com/questions/13866926/is-there-a-list-of-pytz-timezones).
  * `token` is your bot's private token you can find [here](https://discordapp.com/developers/applications) - do not share it with anyone else.

```json
{
    "admin_id":123456789012345678,
    "client_id":987654321098765432,
    "log_timezone":"Africa/Johannesburg",
    "token":"XXXXXXXXXXXXXXXXXXXXXXXX.XXXXXX.XXXXXXXXXXXXXXXXXXXXXXXXXXX"
}
```

* Invite the bot to your own server, replacing `<YOUR BOT ID>` with... your bot ID: `https://discordapp.com/api/oauth2/authorize?client_id=<YOUR BOT ID>&permissions=286280784&scope=bot`
* Start your bot: `python3 auto-voice-channels.py`



