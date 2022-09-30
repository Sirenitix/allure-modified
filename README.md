## Allure modified
To install this custom version of the Allure report follow the next steps
```
curl -o allure-2.19.0.zip -Ls https://github.com/Sirenitix/allure-modified/raw/main/allure-2.19.0.zip   
sudo apt install unzip
sudo unzip allure-2.19.0.zip -d /opt
sudo ln -s /opt/allure-2.19.0/bin/allure /usr/bin/allure
```

Go to the project directory, and write the below command to generate report! (By default it will store data in tmp directory)
```
allure serve allure-results 
```
