# Домашнее задание к занятию «Вычислительные мощности. Балансировщики нагрузки» Соловьев Д.В.

Terraform файлы можно найти в папке [terraform](./terraform/)  
Итог выполнения команды ```terraform apply```:  
![terraform apply](./pictures/terraform%20apply.PNG)  
![yandex cloud](./pictures/yandex%20cloud.PNG)  

1. Созданный bucket:  
   ![bucket](./pictures/bucket.PNG)  
   Файл в бакете:  
   ![file](./pictures/file.PNG)  
   
2. Группа ВМ:  
   ![VM Group](./pictures/VM%20Group.PNG)  
   ВМ из группы:  
   ![VMs](./pictures/VMs.PNG)  
   Загруженная в object storage [картинка](./terraform/files/picture.png) отображаемая на публичном ip адресе одной из ВМ:  
   ![picture](./pictures/picture.PNG)  

3. Созданный сетевой балансировщик:  
   ![Load Balancer](./pictures/Load%20Balancer.PNG)  
   Загруженная в object storage [картинка](./terraform/files/picture.png) отображаемая на публичном ip адресе балансировщика:  
   ![picture 2](./pictures/picture%202.PNG)  
   Картинка по прежнему доступна по адресу балансировщика не смотря на то что одна из виртуальных машин отсутствует:  
   ![picture 3](./pictures/picture%203.PNG)