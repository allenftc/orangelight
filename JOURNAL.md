---
title: "orangelight"
author: "Allen"
description: "Kendryte K230 Development Board"
created_at: "2025-07-8"
---

Total Time Spent: 7h

# July 6
I completely rearranged the K230 symbol so that the pins were in locations that made sense.
Before: It is all very messy and ordered by physical location rather than purpose

![image](https://github.com/user-attachments/assets/b531016a-8ba5-4fb4-a399-51c9c4855aa7)
![image](https://github.com/user-attachments/assets/3b2ecffb-f552-43d7-8849-2e9bdfcc743e)
![image](https://github.com/user-attachments/assets/9a873f66-a4c5-4c46-b155-9491d030414f)
![image](https://github.com/user-attachments/assets/8c721352-f8e7-49fd-b76f-dc5c76513947)

After: Actually arranged by function of the pins
![image](https://github.com/user-attachments/assets/61263691-c9e6-41ff-932e-5cbc09ead2b4)
![image](https://github.com/user-attachments/assets/80ff8402-1e9b-42c6-ae6c-1419a7c82b32)
![image](https://github.com/user-attachments/assets/5991c419-79f4-46e2-9caf-150fb7c71d68)
![image](https://github.com/user-attachments/assets/bb610c6e-aaca-4215-abb4-6a340a19032e)
![image](https://github.com/user-attachments/assets/08bb1319-1489-4e85-9581-1abcef2956ab)
![image](https://github.com/user-attachments/assets/581005a2-e62d-48a4-aedf-911944c19123)
![image](https://github.com/user-attachments/assets/7825348d-28f7-4a12-95b7-4ceca1ceb5ba)

Time Spent: 4h

# July 10
The RAM has been completed. I mostly followed the example schematic although there were a few things like the VREFs and power connections that I had to figure out.

![image](https://github.com/user-attachments/assets/1988c3ae-81a7-4f01-8c04-af776ed4227c)

I added both a 512MB flash chip and an SD card slot so I can make it more compact later but also have the option of an SD card. (There is more RAM than flash 💀💀💀).

![image](https://github.com/user-attachments/assets/8a70338d-9cea-4f9d-82cc-bd549c04b203)

Time Spent: 3h

# July 12
I added the clocks, reset circuit, and the USB connector. The USB connector was a little confusing because I didn't know what the ID and CC pins did but I understand now. 

<img width="1153" height="1132" alt="image" src="https://github.com/user-attachments/assets/f08e62ab-af18-4c66-8a1f-9c2dc1f1df84" />
