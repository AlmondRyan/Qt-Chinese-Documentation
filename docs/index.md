# Welcome

Welcome. This is an **unofficial** localized Qt Documentation into Chinese.  

But if you want to add more translation in your language to help more Qt Programmers enjoy localized Documentation, that's super cool!  

I really appreciate about more languages. You can simply fork the Repository in the up-right corner, and localize, after it just send Pull Request, that's simple!  

And by the way, you can simply clone the repository, and run `mkdocs serve` then follow the command prompt informations, you can host your own Translated Qt Documentation in your own browser!  

So that's it, wish you enjoy!

## Other Links

- **Qt Official English Documentation**: [Link](https://doc.qt.io/)
- **MkDocs**: [Link](https://www.mkdocs.org/)
- **Material for MkDocs**: [Link](https://github.com/squidfunk/mkdocs-material)

## Copyright Notice

Qt official documentation is licensed under [GNU FDL 1.3](https://www.gnu.org/licenses/fdl-1.3.html), that I licensed my translated project under FDL License too.  

Qt: (c) 2024 The Qt Company. The Qt logo as well as Qt®, Qt Quick®, Built with Qt®, Boot to Qt®, Qt Quick Compiler®, Qt Enterprise®, Qt Mobile® and Qt Embedded® are registered trademarks of The Qt Company Ltd.  

## How to contribute translation

1. **Fork the repository**
    - Click at the up-right corner of the documentation, fork the repository to your own GitHub account.
2. **Clone your Fork**
    - Open your GitBash (or other shell you like) then execute the command below:
    ```Sh
    git clone https://github.com/your-username/your-forked-repo.git
    cd your-forked-repo
    ```
3. **Create a new Branch (optional)**
    - To make the master branch more tidy and clean, I highly recommended to make a new branch.
    - You can execute the command below:
    ```Sh
    git checkout -b new-translation-branch
    ```
4. **Localize**
    - You can start translating now!
5. **Commit your changes**
    - After translating, you need to commit your changes:
    ```Sh
    git add .
    git commit -m "Add translation for [language]"
    ```
6. **Push the changes**
    - After committing, you need to push the commit to the server:
    ```Sh
    git push origin new-translation-branch
    ```
7. **Create Pull Request**
    - Go to GitHub, and open this repository then click on "New Pull Request", select your branch, then create!

## How to run documentation locally:

1. **Install MkDocs**
    - You need to install MkDocs, if you don't have one. We need to install via `pip`, so make sure you have already install Python on your PC.
    ```Sh
    pip install mkdocs
    ```
2. **Run local server**
    - Run the commands in the root of the documentation
    ```Sh
    mkdocs serve
    ```
3. **Open Web Page**
    - After you serving the documentation, you can open a browser that you like, open `127.0.0.1:8000`(The url is default) then enjoy!