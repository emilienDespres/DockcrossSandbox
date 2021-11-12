FROM dockcross/manylinux2014-x64

ENV DEFAULT_DOCKCROSS_IMAGE myimage

RUN echo "Hello from myimage"

RUN python3 --version
RUN python3 -m pip install --upgrade pip
RUN sudo apt-get install python3-venv

RUN python3-venv myvenv
RUN source myvenv/bin/activate
RUN python3 -m pip install build
Run sudo apt-get install -y python-dev
