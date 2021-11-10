FROM dockcross/windows-shared-x86

ENV DEFAULT_DOCKCROSS_IMAGE myimage

RUN echo "Hello from myimage"

RUN pip -v
RUN pip --show

RUN python3 -m pip install --upgrade pip
RUN python3 -m pip install build
RUN python3 -m pip install venv