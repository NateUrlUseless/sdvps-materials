###Что такое DevOps. СI/СD -- Вангер А.Ю.


##Задание 1


![Скриншот-1](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/1.png)
![Скриншот-2](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/2.png)
![Скриншот-3](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/3.png)
![Скриншот-4](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/4.png)


##Задание 2


![Скриншот-5](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/5.png)
![Скриншот-4](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/6.png)

##Задание 3

![Скриншот-6](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/7.png)
![Скриншот-7](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/8.png)
![Скриншот-8](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/9.png)


#Доработка 

![Скриншот-10](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/10.png)
![Скриншот-11](https://github.com/NateUrlUseless/sdvps-materials/blob/main/CICD/11.png)

#Код для пуша в нексус репозиторий
```
                      stage('Push image') {  

                            sh 'docker login -u admin -p 123 http://51.250.2.9:8081/'
                            sh 'docker push  http://51.250.2.9:8081/Golang}'
                            }
```
