# Installation

Before you jump off to install the software please make sure you already have the list bellow

## Service requirement for installation

- Apache 2 / Nginx
    - Make sure apache2 rewrite mode is enabled.
- PHP 8.2 or higher
- MySQL 8.0 or higher
- PHP extensions
    - xml
    - pdo
    - OpenSSL
    - Mbstring
    - Tokenizer
    - Ctype
    - Fileinfo
    - Imagick

## Install in cPanel

- Unzip the download file from codecanyon. You will find four folders: `application.zip` and `documentation`
- Upload the `application.zip` zip file to your website `public_html` and extract it.
- Make sure the index.php has permission `755`
- Open a new tab and go to your web domain. Dr Assistant Pro automatically redirect you to the `/install` path to
  install the application
- Follow the further installation Steps

## Install in Cloud (LAMP)

- **Prepare your environment :** You can take look
  of [this doc](https://medium.com/@franciscojbarrera/how-to-deploy-laravel-on-digital-ocean-lamp-e69046906fe)
  to create environment.
- Unzip the download file from codecanyon. You will find four folders: `application.zip` and `documentation`
- copy `application.zip` to your desire server directory using `scp`, example command
  ```
  scp ~/Downloads/DrAssistnatPro/application.zip root@yourserverip:/var/www/application.zip
  ```
- Extract the zip to the desire location and visit the website, system will take you to the installation page
- Follow the further installation Steps

## Install in Cloud (LEMP)

- **Prepare your environment :** You can take look
  of [this doc](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-laravel-with-nginx-on-ubuntu-22-04)
  to create environment.
  All you just need to
  ignore [Step 3](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-laravel-with-nginx-on-ubuntu-22-04#step-3-creating-a-new-laravel-application),
  instate of creating a new laravel project all you need is just copy the `application.zip` from your local to your
  cloud.
- Unzip the download file from codecanyon. You will find four folders: `application.zip` and `documentation`
- copy `application.zip` to your desire server directory using `scp`, example command
  ```
  scp ~/Downloads/DrAssistnatPro/application.zip root@yourserverip:/var/www/application.zip
  ```
- Extract the zip to the desire location and visit the website, system will take you to the installation page
- Follow the further installation Steps