Video Tutorial
--------------

For a visual guide, check out my YouTube video on how to run this bot: YouTube Tutorial

How to Use the Telegram Remove Background Bot
---------------------------------------------

1.  **Clone the Repository**:

    -   First, clone the repository to your local machine using the following command:

        ```
        [git clone https://github.com/your-username/telegram-remove-background-bot.git](https://github.com/noteduard33/telegram-remove-background-bot.git)

        ```

2.  **Navigate to the Bot Directory**:

    -   Change your working directory to the bot folder:

        ```
        cd telegram-remove-background-bot

        ```

3.  **Create a Virtual Environment**:

    -   Set up a Python virtual environment (venv) by running:

        ```
        python -m venv env

        ```

4.  **Activate the Virtual Environment**:

    -   On Windows:

        ```
        cd env
        cd Scripts
        activate
        cd ..
        cd ..

        ```

    -   On Linux:

        ```
        source env/bin/activate

        ```

5.  **Install Dependencies**:

    -   Install the required Python packages using pip:

        ```
        pip install -r requirements.txt

        ```

6.  **Get Your Telegram API Token**:

    -   Go to Telegram and search for **BotFather**.
    -   Start a chat with BotFather and use the `/newbot` command to create a new bot.
    -   Follow the instructions to set a name and username for your bot.
    -   Once created, BotFather will provide you with an **API token**. Copy this token.
7.  **Create a .env File**:

    -   In the root directory of your bot, find a `.env` file.
    -   Replacing `'YOUR TOKEN'` with the actual API token:

        ```
        TOKEN='YOUR TOKEN'

        ```

8.  **Run the Bot**:

    -   Execute the following command to start your bot:

        ```
        python bot.py

        ```

9.  **Test Your Bot**:

    -   Open Telegram and search for your bot using the username you set earlier.
    -   Start a chat with your bot and send an image.
    -   Wait for the bot to process the image and receive the edited version.
10. **Enjoy!** Your Telegram Remove Background Bot is now up and running. Good luck! 🚀
