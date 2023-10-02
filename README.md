
<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
# About The Project

![A test image](diagram.png)

An ETL project for the purpose of storing bitcoin to tl value inside of Google BigQuery without any cost.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Built With
* [![Python][Python-url]][Python.com]
* [![Pandas][Pandas-url]][Pandas.com]
* [![Power Bi][PowerBi-url]][PowerBi.com]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Prerequisites
This installation is valid for Windows 10/11 users.

## Installation

### 1. [Ubuntu][Ubuntu-Installation]
***
### 2. Apache Airflow
  

  ```sh
   sudo apt-get install software-properties-common
   ```
    
  ```sh
   sudo apt-add-repository universe
   ```

  ```sh
   sudo apt-get update
   ```
 
   ```sh
   sudo apt-get install python3-pip
   ```
 
   ```sh
   pip3 install apache-airflow
   ```
   After that installation finished close the terminal and reopen it
  
   ```sh
   airflow db init
   ```
  Create a folder named "dags" inside your "airflow" folder.
   
  Create a user. An example has given below.
   ```sh
   airflow users create \
          --username admin \
          --firstname admin\
          --lastname admin \
          --role Admin \
          --email admin@example.org
   ```
   
   ```sh
   pip install pandas
   ```
   
   ```sh
   pip install pandas-gbq
   ```
   
   ```sh
   pip install --upgrade numpy
   ```
   
   ```sh
   pip install pandas-gbq
   ```

***

### 3. [gcloud CLI][Gcloud-Installation]
***
### 4. Configure Necessary Information Inside of "bitcoin_tl_project_dag.py"
***
## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Contact

mbahadirerdem@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>




[Python.com]: https://www.python.org/
[Python-url]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Pandas.com]: https://pandas.pydata.org/
[Pandas-url]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[PowerBi.com]: https://powerbi.microsoft.com/en-us/
[PowerBi-url]: https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black

