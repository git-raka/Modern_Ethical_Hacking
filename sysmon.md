# SYSMON
Sysymon is execelent way to forward your logs and monitor log of all activity in your computer windows

https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon

![image](https://user-images.githubusercontent.com/77326619/177029458-7a6df3ad-cf46-42bf-ae7f-c148a9b6b9c9.png)

Create "Sysmon" dir in programs file 
![image](https://user-images.githubusercontent.com/77326619/177029568-a80e7aef-7d53-41c3-b420-ccbf821bb919.png)

and extract the sysmon in the sysmon dir programs file
![image](https://user-images.githubusercontent.com/77326619/177029611-e65f6920-6947-4f0c-a750-70a350e0116a.png)

now open the repository of github sytsmon modular
https://github.com/olafhartong/sysmon-modular

download the zip file


<img width="187" alt="image" src="https://user-images.githubusercontent.com/77326619/177029789-54177149-d6f2-403b-b454-b00a1d17a28c.png">


extracct sysmon modular in sysmon dir

![image](https://user-images.githubusercontent.com/77326619/177029846-1af95fa0-1d2a-4697-8c75-8e087eecddc9.png)

open cmd and go to sysmon program file

![image](https://user-images.githubusercontent.com/77326619/177029933-937fd065-5cc5-4142-8408-4094a896432d.png)

now you need to disable excecution policy

![image](https://user-images.githubusercontent.com/77326619/177030033-ade34229-5276-40aa-9d08-dbaf71a4557d.png)


![image](https://user-images.githubusercontent.com/77326619/177030082-42acb6aa-4b6d-44a7-baff-4ea7bcdd0d33.png)


![image](https://user-images.githubusercontent.com/77326619/177030153-2cab58e1-86c8-4a99-a668-7e0353f5cf65.png)

Merge-AllSysmonXml -Path ( Get-ChildItem '[0-9]*\*.xml') -AsString | Out-File sysmonconfig.xml

![image](https://user-images.githubusercontent.com/77326619/177030238-ccae2125-56f8-4239-a972-20d3b22fb465.png)

Now you can see your all log on your computer

![image](https://user-images.githubusercontent.com/77326619/177030393-bc6ba329-6dda-4cdd-91c5-a9e06d3db96d.png)

