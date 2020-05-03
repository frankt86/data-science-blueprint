Requirements
==================================================

To install the Data Science blueprint and benefit from all its features, a few requirements will have to be checked

- Python >= 3
- Docker

And that's it. To check your python version, you can type in this instruction in your favorite terminal.
Knowing which executable is installed on your machine will help you decide on the python interpreter to choose ::

        python --version
        python3 --version

Regarding Docker, you must be able to run docker commands without being sudo. Therefore, you must be able to check
this command on your terminal::

        docker --version

If it appears that you need to be sudo to run docker, then you must add your user account to the docker group that
was created after installing docker on your machine. This can be done thanks to this command::

        sudo usermod -aG docker $USER