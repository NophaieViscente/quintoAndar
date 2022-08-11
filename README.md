<h1 align="center"> Realtor </h1>

## Objective of this project : 
**Given an input, the algorithm provides the apartments/houses that best match the customer's choice.**

## How was it built?
* The first step was data collection;<br/> 
(Property data were collected through a crawler from the www.quintoandar.com.br)<br/> 
The web scrapping code is in this notebook : <br/>
[Scrapping quintoandar.com.br](code/scrapping_quintoAndar.ipynb)<br/><br/>

* The second step was process data;<br/>
(The processing of the data was carried out so that a dataset could be obtained in an easy-to-analyse format, as the data coming from the crawler was in .json format)<br/>
The process data code is in this notebook : <br/>
[Processing data from quintoandar.com.br](code/process_data.ipynb)<br/><br/>

* The third step was analyzing data;<br/>
(The analysis aims to suggest properties for rent according to the user's preference, given their preference input, properties in the center of São Paulo that meet these criteria are suggested)<br/>
The data analysis code is in this notebook: <br/>
[Data analysis from quintoandar.com.br](code/analyzing_data.ipynb)<br/><br/>


## How to use this project ?
* To use the codes in this project, you need a python venv.<br/> 
The repository can be cloned using **git clone https://github.com/NophaieViscente/quintoAndar**, done that the necessary libraries can be installed using the command:<br/>
**pip install -r requirements.txt**
