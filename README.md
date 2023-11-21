# ETL-with-PySpark-and-PostgreSQL
The data that I’ll use is scraped from Ebay-Kleinanzeigen, which is the German branch 
of Ebay where people can advertise their properties. In our case, we will work with a 
dataset that contains information from over 370000 used cars; besides, it’s important 
to note that the content of the data is in German.

<img width="264" alt="image" src="https://github.com/AsaelSolorio/ETL-with-PySpark-and-PostgreSQL/assets/112660076/5cd1e0a2-54eb-401e-aaec-a2042f06f19f">

We can download the dataset from here
``` batch
wget https://raw.githubusercontent.com/cpatrickalves/eda-ebay-cars/master/dataset/autos.csv
```

next,we setup a EC2 instance on AWS to run Jupyter/spark notebook inside docker and you can make a scaffold the Makefile 
to install all the libraries or run the next commands on CLI

<img width="342" alt="image" src="https://github.com/AsaelSolorio/ETL-with-PySpark-and-PostgreSQL/assets/112660076/4444d7ee-2c15-4fa5-93e6-eea973178d30">

``` batch
sudo apt install python3-is-python
pip3 install --upgrade pip 
pip install psycopg2-binary
sudo apt install postgresql postgresql-contrib -y
sudo snap install docker -y
```
