<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Mini-Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites-and-installation">Prerequisites and Installation</a></li>
      </ul>
    </li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

Accurate solar energy production forecasting is becoming more relevant as the world is shifting towards greener energy alternatives. Traditional literature focuses mainly on improving model parameters and getting hold of more data to help increase the accuracy of predictions, while some other applicable algorithms, already used and tested in similar contexts, remain not so widely researched in the solar sphere. This paper presents the application of the Self- Organizing Map (SOM) clustering algorithm to the solar
energy prediction challenge. 

The method is tested on a 2016 HI-SEAS weather station dataset of various meteorological observations, including wind speed, humidity and atmospheric pressure. First, SOM is used as a pre-processor to map similar data points to nodes that are then clustered into three distinct units. Then, each cluster is fed into a separate Support Vector Machine regressor to compare the accuracy of the prediction results (SOM-SVR) versus that of not applying SOM at all (noSOM-SVR). Performance is evaluated by comparing the root mean squared error of each model. Results indicate that the application of SOM-SVR increases the accuracy on average across all clusters versus noSOM-SVR. This can offer more insight into how to obtain better prediction accuracies coupled with further research in this field.

### Built With

- <a href="https://cran.r-project.org/bin/windows/base/">R</a>

<!-- GETTING STARTED -->
## Getting Started

This is a list of instructions on how anyone can get started with this code.

### Prerequisites & Installation

Clone the repo
```sh
    git clone https://github.com/lynxalytics/solarity.git
```
