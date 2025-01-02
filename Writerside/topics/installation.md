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

- Unzip the download file from codecanyon. You will find four folders: `dr_assistant_pro` and `documentation`
- Go to `dr_assistant_pro` folder and zip all files under `dr_assistant_pro` folder.
  `(if you use unix like operating system, press Ctrl+H/ Command +H to show dotted files)`.
- Upload the zip file to your website `public_html` and extract it.
- Make sure the index.php has permission `755`
- Open a new tab and go to your web domain. Dr Assistant Pro automatically redirect you to the `/install` path to
  install the application
- Follow the further installation Steps

## Install in Cloud (LAMP)

- Unzip the download file from codecanyon. You will find four folders: `dr_assistant_pro` and `documentation`
- You can take look
  of [this doc](https://medium.com/@franciscojbarrera/how-to-deploy-laravel-on-digital-ocean-lamp-e69046906fe)
  to create environment.
- Once environment setup is complete open a new tab and go to your web domain. Dr Assistant Pro automatically redirect
  you to the `/install` path to
  install the application.
- Follow the further installation Steps

## Install in Cloud (LEMP)

- Unzip the download file from codecanyon. You will find four folders: `dr_assistant_pro` and `documentation`
- You can take look
  of [this doc](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-laravel-with-nginx-on-ubuntu-22-04)
  to create environment.
  All you just need to
  ignore [Step 3](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-laravel-with-nginx-on-ubuntu-22-04#step-3-creating-a-new-laravel-application),
  instate of creating a new laravel project all you need is just copy the `dr_assistant_pro` from your local to your
  cloud.
- Once environment setup is complete open a new tab and go to your web domain. Dr Assistant Pro automatically redirect
  you to the `/install` path to
  install the application.
- Follow the further installation Steps