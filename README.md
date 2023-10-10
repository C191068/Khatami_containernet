# Intro

![Screenshot from 2023-10-08 10-34-18](https://github.com/C191068/Khatami_containernet/assets/89090776/f806bc79-cc17-45e7-bdcb-59088eb7a7d2)

must be under above directory 



![Screenshot from 2023-10-07 12-02-16](https://github.com/C191068/Khatami_containernet/assets/89090776/2d8f212e-ba10-4aa5-9945-50260eaf0b82)

not installing under python3 directory such error will occur 


https://stackoverflow.com/questions/19256127/two-versions-of-python-on-linux-how-to-make-2-7-the-default


![Screenshot from 2023-10-09 11-39-30](https://github.com/C191068/Khatami_containernet/assets/89090776/441d2f24-7aaf-41c4-95e2-b597702765f9)

the above error occurs for some process running at port 6653

![Screenshot from 2023-10-09 14-17-57](https://github.com/C191068/Khatami_containernet/assets/89090776/d449912c-c233-4b1e-82f8-5b8c214f72b4)
then we kill those those process


![Screenshot from 2023-10-09 14-18-46](https://github.com/C191068/Khatami_containernet/assets/89090776/f840ec76-d83b-4c65-a9ce-9304f00ba582)
the above error occures because we did not Create a custom slice file and define resources


![Screenshot from 2023-10-09 14-26-48](https://github.com/C191068/Khatami_containernet/assets/89090776/7a2fe5f5-d4a5-4d32-aa0f-3bd8c5fee253)



![Screenshot from 2023-10-09 14-55-56](https://github.com/C191068/Khatami_containernet/assets/89090776/4e392bca-e4f9-4f4a-979a-f6e2ceb3adee)

the file which is oened by giving the first command we ate the below 


```

[Unit]
Description=Slice that limits docker resources 
Before=slices.target
[Slice]
CPUAccounting=true
CPUQuota=50%    
MemoryAccounting=true
MemoryHigh=2G  
MemoryMax=3G 
MemoryMaxSwap=10G

```


learned it from below

https://baykara.medium.com/docker-resource-management-via-cgroups-and-systemd-633b093a835c





![Screenshot from 2023-10-10 11-07-55](https://github.com/C191068/Khatami_containernet/assets/89090776/2c8e5812-5923-485d-85c4-e0bfccb3d5f0)


![Screenshot from 2023-10-09 15-03-49](https://github.com/C191068/Khatami_containernet/assets/89090776/6f5d77c0-24e4-45c4-81fe-b0aeb6d4121c)


![Screenshot from 2023-10-09 15-04-48](https://github.com/C191068/Khatami_containernet/assets/89090776/eb018d2d-21b4-4f88-84f4-b529e168c848)


![Screenshot from 2023-10-09 15-05-21](https://github.com/C191068/Khatami_containernet/assets/89090776/af1453db-97ee-4fd0-bd11-5cc2c8deb668)



![Screenshot from 2023-10-10 12-38-57](https://github.com/C191068/Khatami_containernet/assets/89090776/1053d002-ceee-4e07-89ae-4e1042920b6a)

![Screenshot from 2023-10-10 14-55-37](https://github.com/C191068/Khatami_containernet/assets/89090776/2cc96f17-d8f1-46af-abbb-e7825921c081)

![Screenshot from 2023-10-10 14-59-44](https://github.com/C191068/Khatami_containernet/assets/89090776/a068661a-4275-4aab-8d6f-9740931abc9d)

![Screenshot from 2023-10-10 15-02-10](https://github.com/C191068/Khatami_containernet/assets/89090776/33e3608a-b0dd-4600-8366-2f4ef470359e)

![Screenshot from 2023-10-10 15-06-47](https://github.com/C191068/Khatami_containernet/assets/89090776/418c940b-e843-4e41-b0fe-7a0918c7410b)

![Screenshot from 2023-10-10 15-32-32](https://github.com/C191068/Khatami_containernet/assets/89090776/21e670c9-d855-4c79-8ab9-2251ee2e8aca)


![Screenshot from 2023-10-10 15-39-16](https://github.com/C191068/Khatami_containernet/assets/89090776/e7332379-9d57-4da8-8c6c-2b76a9ed14cd)


![Screenshot from 2023-10-10 15-40-15](https://github.com/C191068/Khatami_containernet/assets/89090776/03cbe610-c8f7-4b60-ad4d-b7c858d26651)


![Screenshot from 2023-10-10 15-49-04](https://github.com/C191068/Khatami_containernet/assets/89090776/0526f856-96ff-41c2-a383-060b7eac84f2)


![Screenshot from 2023-10-10 15-50-36](https://github.com/C191068/Khatami_containernet/assets/89090776/91f8b5a6-a08b-4c85-8dfc-bfba15bd798d)


![Screenshot from 2023-10-10 15-56-29](https://github.com/C191068/Khatami_containernet/assets/89090776/e380c34d-2228-449f-a58f-c121b4d8b984)


![Screenshot from 2023-10-10 15-57-58](https://github.com/C191068/Khatami_containernet/assets/89090776/fff22663-ce58-4b10-b20e-accd10b94b13)



































































