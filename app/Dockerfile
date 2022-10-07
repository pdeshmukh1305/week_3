FROM python

# Install the Django system from requirements.txt
COPY requirements.txt /tmp/
RUN pip3 install -r /tmp/requirements.txt

# Make this a Volume
VOLUME /app

# Make sure this is the working directory
WORKDIR /app


EXPOSE 8000

# Note - Terminal commands to build and run
# docker build -t my_django .
# docker run -it -p8000:8000 -v "$(pwd)/app:/app" my_django /bin/bash