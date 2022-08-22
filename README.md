# Purpose of this repository
Sample Headless CMS Sulu template

## How to launch

```
    # docker compose build --pull --no-cache
    # docker compose up -d

    After the php-fpm is ready to handle connections attach a shell to the docker and do :
    # php bin/adminconsole sulu:build dev
```


## Next steps

Change the config/webspaces to match your website conf (modify name and key)