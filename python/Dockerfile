# Get Python 2.7
FROM python:2.7-slim

# Create work dir
WORKDIR /app

ADD . /app

# Install packages from requirements.txt
RUN pip install --trusted-host pypi.python.org -r requirements.txt

#  make port 81 public. 
EXPOSE 80

#  EVN variables 
ENV NAME world

#  Run the app

CMD ["python","app.py"] 

