# Django installation

*This chapter is based on awesome tutorials by Geek Girls Carrots (http://django.carrots.pl/) and django-marcador (http://django-marcador.keimlink.de/).*

## Virtual environment

Before we will install Django, we will make you install something very handy and useful, that will help you with keeping everything tidy on your computer. It is possible to skip this step, but we think, that you should start with the best setup possible to save a lot of troubles in a future.

That's why we want you to create a Virtual environment (also called `virtualenv`). It will isolate things you do from your computer, so you will have everything important in one place. Neat, right?

All you need to do is find a folder in which you want to create the `virtualenv`, for example your home directory. In Windows it could look like: `C:\Users\Name\` (where `Name` is a name of the user).

### Windows

To create `virtualenv` you need to open command line `cmd` and type there `C:\Python\python -m venv blog`. It will look like this:

    C:\Users\Name> C:\Python34\python -m venv blog

where `C:\Python34\python` is folder in which you previously installed Python and `blog` is a name of your `virtualenv`. You can use any other name, but stick to lowercase and use no spaces. It is also good idea to keep the name short :).

### Linux and OS X

Creating `virtualenv` in both Linux and OS X is as simple as typing in console (remember, that we expect that you have python 3.4 installed):

    ~$ python -m venv blog

### Working with virtualenv

The command above will create a folder `blog` that contains our virtual environment (basically bunch of folders and files). All we want to do now is starting it by:

    C:\Users\Name> blog\Scripts\activate

for Windows users, or:

    ~$ source blog/bin/activate

You will know that you have `virtualenv` started when you see that the prompt in your command line or console looks like:

    (blog) C:\Users\Name>

or:

    (blog) ~$

so the prefix `(blog)` appears!

Ok, we have all important things in place. We can finally install Django!

## Installing Django

Now, when you have your `virtualenv` started, you can install Django using PIP. In console/command-line you type `pip install django==1.6.4`.

    (blog) ~$ pip install django==1.6.4
    Downloading/unpacking django==1.6.4
    Installing collected packages: django
    Successfully installed django
    Cleaning up...

That's it! Now you are finally ready to create a Django application.


