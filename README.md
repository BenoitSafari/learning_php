# Wordpress - WooCommerce template

## TODO
- [x] **Add Wordpress to Docker-compose**
- [ ] **Add WooCommerce plugin to Wordpress**
  - [ ] Install plugin
  - [ ] Configure plugin
    - See https://woocommerce.com/document/woopayments/startup-guide/

- [x] **Fix permission issue with VSCode editing volumes**

## Developpment setup
Run the following command on your host *(in project root)* to get write permission in your editor.
```sh
chmod -R 777 src
```

## Env
Creates a `.env` file at project root and set the following variables

```
WORDPRESS_DB_USER="username"
MYSQL_USER="username"

WORDPRESS_DB_PASSWORD="strongP@ssword1"
MYSQL_PASSWORD="strongP@ssword1"

WORDPRESS_DB_NAME="name_for_my_db"
MYSQL_DATABASE="name_for_my_db"

MYSQL_ROOT_PASSWORD="strongP@ssword2"
```