# Storefront

- Open your terminal and clone this repository
    
    First make sure you have a ssh key if you dont have go to my dotfiles repository and follow the instructions

    ```
    git clone git@github.com:ayushkpai/storefront.git
    ```

- Next install python and add dependencies

    Also documented in dotfiles

    ```
    uv add django
    uv add mysqlclient
    uv add django-debug-toolbar
    ```

- To run the project

    ```
    uv run manage.py runserver
    ```
