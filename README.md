## LucyGPT
## Bot commands
- `/retry` – Regenerate last bot answer
- `/new` – Start new dialog
- `/mode` – Select chat mode
- `/balance` – Show balance
- `/settings` – Show settings
- `/help` – Show help

## Setup
1. OpenAI API key

2. Telegram bot token

3. Edit `config/config.example.yml` and `config/config.example.env`:
    ```bash
    mv config/config.example.yml config/config.yml
    ```
    ```bash
    mv config/config.example.env config/config.env
    ```

4. And now **run**:
    ```bash
    docker-compose --env-file config/config.env up --build
    ```
