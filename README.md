## Виконання команд WP CLI

### Референси

* https://developer.wordpress.org/cli/commands/

Отримуєму назву контейнера в якому запущено wordpess image:

``docker ps``

В консолі, в колонці NAMES копіюємо назву

Далі виконуємо потрібну нам команду:

``sudo docker exec -it kvantum-electronicscomua_wordpress_1 wp fs yml_import --feed_id=3 --skip_exists=1 --allow-root``



