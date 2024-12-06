# Web scraping
This project implements a web scraping technics where it scrape suburl, imageurl and augmanted text and store in sqllite database also offer downlode imange from spacific suburl.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

1.Create the virtual environment:
```
conda create --name Ven python=3.12

```
2.On windows, you can activate the virtual environment using :
```
activate Ven
```
On mac, linux the command is :
```
source activate Ven
```
3.Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
    

## Usage

To run this project you have to, use the following command and step:

```bash
python main.py 
```
step:
1-Enter domain url which you have to scarpe: # https://www.oth-aw.de/
2-if you wan to  download images from the scraped URLs? (yes/no): #yes
3-Provide the path where you want to save the images: # G:\ 
4-Provide the URL from the database to scrape images: #  https://www.oth-aw.de/hochschule/services/service-center-digitale-aufgaben/ueber-uns/


    