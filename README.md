# marionette-cookiecutter
Cookiecutter template for Marionette+webpack project in coffeescript


## How to use ##

1. Install Cookiecutter if you don't have it already.

   https://cookiecutter.readthedocs.io/en/latest/installation.html

2. Generate your project with the following command. Fill in the details as prompted
by cookiecutter.

   ```
   cookiecutter https://github.com/mukund-krish/marionette-cookiecutter.git
   ```

3. You should now have the project generated in a new folder with the name
you entered for ```repo_name```.

4. ```cd``` into the generated folder.

5. Do a ```npm install``` to install all the node depenencies.

6. Now you are ready to write code!. To start the webpack development server, type ...

   ```
   ./node_modules/.bin/webpack-dev-server --inline
   ```
