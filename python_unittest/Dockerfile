
FROM python:3.8

# working directory
WORKDIR /usr/src/app

# copy requirement file to working directory
COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

# test
RUN python -m unittest run.py

COPY . .

ENTRYPOINT ["python", "./run.py"]
