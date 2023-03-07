# Eli-hehe
# Wireup lab Eli Cyberdefenders

### Tham gia tại https://cyberdefenders.org/blueteam-ctf-challenges/98

## 1. The folder to store all your data in - How many files are in Eli's downloads directory?

find . -type d -name 'Downloads'

![image](https://user-images.githubusercontent.com/124852865/223416888-65787aad-014f-410b-981a-751ee38ba815.png)

Answer: 6

## 2. Smile for the camera - What is the MD5 hash of the user's profile photo?

![image](https://user-images.githubusercontent.com/124852865/223416986-84171fb8-cb08-4df2-bfe3-af355c2fae21.png)

Answer: 5ddd4fe0041839deb0a4b0252002127b


## 3. Road Trip! - What city was Eli's destination in?

![image](https://user-images.githubusercontent.com/124852865/223417059-d329654f-a257-4e8a-b38e-5d6b47b01db7.png)

Answer: Plattsburgh

## 4. Promise Me - How many promises does Wickr make?

find . -name '*Promises*'



![image](https://user-images.githubusercontent.com/124852865/223417111-b11e8727-d260-4404-ab5a-aa5c43544965.png)


Answer: 9

## 5. Key-ty Cat - What are the last five characters of the key for the Tabby Cat extension?

grep -rnw '.' -e '[tT]abby [cC]at'

![image](https://user-images.githubusercontent.com/124852865/223417208-a13b2ea8-4601-4536-a58b-2045fd2c094c.png)

Answer: DAQAB

## 6. Time to jam out - How many songs does Eli have downloaded?

find . -type f -name '*.mp3'

![image](https://user-images.githubusercontent.com/124852865/223417299-d68cac18-6dd4-4384-92fd-236f36675cd0.png)

Answer: 2

## 7. Autofill, roll out - Which word was Autofilled the most?

Answer: email

## 8. Dress for success - What is this bird's image's logical size in bytes?

ls -l 2021CTF-Chromebook/2021CTF-Chromebook/decrypted/mount/user/Downloads/tux.png

![image](https://user-images.githubusercontent.com/124852865/223417356-ab6b2833-90ae-4bb9-88ab-03790981e994.png)

Answer: 46,791

## 10. Repeat customer - What was Eli's top visited site?

![image](https://user-images.githubusercontent.com/124852865/223417465-569ac5bc-7f37-438a-b6ee-e5fe25e936ea.png)

Answer: protonmail.com

## 11. Vroom Vroom, What is the name of the car-related theme?

![image](https://user-images.githubusercontent.com/124852865/223417536-d3a85c35-b40d-4fb5-84e7-262b8865fb42.png)

Answer: Lamborghini Cherry

## 12. You got mail - How many emails were received from notification@service.tiktok.com?

grep -rnw '.' -e 'notification@service.tiktok.com'

![image](https://user-images.githubusercontent.com/124852865/223417616-4e458183-ca58-464f-b79d-6c1ca9cd4536.png)

Answer: 6


## 13. Hungry for directions - Where did the user request directions to on Mar 4, 2021, at 4:15:18 AM EDT

![image](https://user-images.githubusercontent.com/124852865/223417671-5a79eeaa-fe23-4079-b1c9-29f765e1afa6.png)

Answer: Chick-fil-A

## 14. Who defines essential? - What was searched on Mar 4, 2021, at 4:09:35 AM EDT

![image](https://user-images.githubusercontent.com/124852865/223417778-6dfa9214-191f-4526-b949-23078e366a8d.png)

Answer: is travelling to get chicken essential travel

## 15. I got three subscribers, and counting - How many YouYube channels is the user subscribed to?

![image](https://user-images.githubusercontent.com/124852865/223417848-31e45404-31a5-420e-b59a-f128b82c1eca.png)

Answer: 0

## 16. Time flies when you're watching YT - What date was the first YouTube video the user watched uploaded?

![image](https://user-images.githubusercontent.com/124852865/223418041-7de845eb-c362-4a86-bb2f-4d20383491d6.png)

Answer: 27/01/2021

## 17. How much? - What is the price of the belt?

![image](https://user-images.githubusercontent.com/124852865/223418094-143565bd-64ac-4818-9185-e5829e4e2889.png)

Answer: 98.5

