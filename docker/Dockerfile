FROM dockcross/windows-shared-x86

ENV DEFAULT_DOCKCROSS_IMAGE myimage

RUN echo "Hello from myimage"

RUN python3 --version

RUN python3 -m pip install --upgrade pip
RUN python3 -m pip install build
RUN sudo apt-get install -y python3-venv