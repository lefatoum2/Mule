# MuleSoft
![img1](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/9b90ee31-1312-4cdf-8499-33771e8f37c3/deu5k00-107f9aa5-00c5-45bb-b52b-a61f96c0d93d.jpg/v1/fill/w_1280,h_931,q_75,strp/shrek_and_donkey_in_the_loud_house_style_by_benny49_deu5k00-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9OTMxIiwicGF0aCI6IlwvZlwvOWI5MGVlMzEtMTMxMi00Y2RmLTg0OTktMzM3NzFlOGYzN2MzXC9kZXU1azAwLTEwN2Y5YWE1LTAwYzUtNDViYi1iNTJiLWE2MWY5NmMwZDkzZC5qcGciLCJ3aWR0aCI6Ijw9MTI4MCJ9XV0sImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl19.VTpDsPT3tuo3JjEFFVdHB-khVfypbp7BIGGtq2dhqVE)



## WebHook (POST)
![img2](./images/image.png)
![img3](./images/image1.png)
![img4](./images/image-1.png)
![img5](./images/image-2.png)

## SFTP
Téléchargez le serveur SFTP de test:
https://www.rebex.net/tiny-sftp-server/#download

## Scatter-Gather

## Scheduler

## Dataweave
```dw
%dw 2.0
output application/java
var a1 = [1, "a", true]
var a2 = {"Chris":2, "Tai":34,"TY":23}
---

{
	adde: a1 ++ a1 ,
	add2 :  a1+a1,
	minus1 : a2 - "Chris",
	minius2 : a2 -- {"Chris":2}
}
```
