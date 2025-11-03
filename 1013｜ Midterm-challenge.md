# 'Energy regulator' —— the Outer Box of A Future Product based on Arduino
The content will bes divided into 4 chapters:  
-  01 How it looks like?
-  02 Why I made this product?
-  03 How it works?
-  04 What did I do?
-  05 My reflection

## 01 How it looks like?  
 - My product is mainly composed of five parts: PLA box, acrylic board, spring, hinge, and an Arduino and screen holder⬇️:  
<img width="1086" height="806" alt="截屏2025-11-03 08 35 46" src="https://github.com/user-attachments/assets/5f36c58d-8cd9-4877-8a9e-65d2b5faae11" />

 - When they are fully assembled, they look like this⬇️:
   <img width="1012" height="731" alt="截屏2025-11-03 18 58 19" src="https://github.com/user-attachments/assets/af6588c3-ac92-4706-8983-8b03a0cface4" />
   <img width="600" height="431" alt="截屏2025-11-03 18 58 51" src="https://github.com/user-attachments/assets/83404559-3ffb-45c6-aa7a-97a0aff3bec1" />



## 02 Why I made this product?  
 - Because I imagined a future where technology develops at an incredible pace to the point where **the flow of energy is almost imperceptible**. I hope that this product will **visualize energy**, **reminding people** that technology is not magic that appears out of thin air, but rather truly consumes energy such as **electricity, water, and fossil fuels on Earth**.


## 03 How it works?  
 - You can put the arduino board and the screen (I used apple watch as an example) fixed to **the holder board**.
 - **Springs and hinges** on the box allow you to open and close the box tightly at will. At the same time, since the bottom is flat, you can use it upright on the tabletop. You can also attach a magnetic sticker to the flat back of the box and attach it wherever you want.
 - Transparent panels made of **acrylic** allow you to observe real-time changes in the data on the screen while also providing protection.

## 04 What did I do?  
 - Here are my technical files⬇️:
   1. 3d model of [**the pla box**](https://github.com/alice-xiyan/HTAM/blob/main/arduino_box.stl) and [**the spring**](https://github.com/alice-xiyan/HTAM/blob/main/spring.3mf)
   2. Leaser cutting file of [**the acrylic board**](https://github.com/alice-xiyan/HTAM/blob/main/leaser%20cutting.svg)
   3. 3d model of [**the Arduino and screen holder**](https://github.com/alice-xiyan/HTAM/blob/main/holder.3mf)

     
 - Making this box mainly includes four steps, which are⬇️:
   - Step1: drawing a sketch
   - Step2: 3D modeling
   - Step3: laser cutting
   - Step4: 3D print parts, assemble and optimize
  
 - **Step1: drawing a sketch**
   - I determined the approximate size and draw a sketch like this⬇️:
   - <img width="652" height="822" alt="截屏2025-11-03 19 56 59" src="https://github.com/user-attachments/assets/2a94d88c-583d-4a50-9e1a-561d54c0e9ec" />
     
 - **Step2: 3D modeling**
   - I first built a rectangular box with hinges⬇️:
   - <img width="664" height="463" alt="截屏2025-11-03 20 05 59" src="https://github.com/user-attachments/assets/9bfd4892-1080-4237-b69c-727523460f27" />

   - Then I added the spring switch part (this part is very difficult, I debugged it for a long time by watching this [tutorial video](https://www.bilibili.com/video/BV1FdYVeUEHD/?spm_id_from=333.337.search-card.all.click&vd_source=6616351be640f616ca5221f0eabd5609))⬇️:
   - <img width="665" height="461" alt="截屏2025-11-03 20 06 35" src="https://github.com/user-attachments/assets/bdd24a87-9f11-4b9b-8bf2-574c2e657e07" />
   - <img width="666" height="463" alt="截屏2025-11-03 20 06 17" src="https://github.com/user-attachments/assets/4bfb2687-fcf7-4013-be4b-983901b97b27" />

   - After that, I modified the four corners of the box into smooth rounded corners, using the rotate tool to check if it can close tightly⬇️:
   - <img width="665" height="458" alt="截屏2025-11-03 20 07 01" src="https://github.com/user-attachments/assets/db36d776-822a-401f-9857-812592773d89" />
   - <img width="662" height="450" alt="截屏2025-11-03 20 07 16" src="https://github.com/user-attachments/assets/ae1d8b88-79ef-482c-bc99-5d6ee03cb222" />


   - Then, I opened transparent panels on the acrylic board according to the sketch⬇️:
   - <img width="667" height="464" alt="截屏2025-11-03 20 07 38" src="https://github.com/user-attachments/assets/ecab9313-9f89-4ab3-9d53-30f835635bf0" />
     
   - Finally, I made the Arduino and screen holder (I later realized that this kind of slender column design has a big problem)⬇️:
   - <img width="897" height="461" alt="截屏2025-11-03 20 43 03" src="https://github.com/user-attachments/assets/4196a7f3-9131-44c6-9e5e-58a370062471" />


   - The 3d modeling part is down!(temporarily)

 - **Step3: Leasering cutting**
   - I used laser cutting to slot my acrylic sheets so that the acrylic sheets could fit together with the bumps on the box.
   - In this process, I learned two very important facts:
     - Fact 1: Remember to set the right speed and strength according to the material you use and the effect you want to achieve
     - Fact 2: Because the dpi numbers of Adobe Illustrator and the leaser cutting softerware are different, the size of the sketch will change on the computer, which will need to be adjusted manually.

 - **Step4: 3D print parts, assemble and optimize**
   - The printing process was smooth, and I learned how to use the bambu x1 printer。
   - <img width="615" height="552" alt="截屏2025-11-03 20 55 42" src="https://github.com/user-attachments/assets/661c0447-8272-416d-9794-932a713813a5" />
   
   - However, after the first printing, I found that the spring was not elastic enough, and when the box was closed, the spring would have a protrusion and could not remain horizontal with the plane.
   - So I redesigned the spring, added more cut-out parts, rotated it 90 degrees to print so that it can avoid the support problem (very useful advice from teacher!)
   - <img width="1273" height="878" alt="截屏2025-11-03 21 00 16" src="https://github.com/user-attachments/assets/6b737de9-0a63-4261-9c2c-04c2751dfb5f" />

**_Then, after assembly, the whole process of production ends here!_**  
**_Congrats!!_**  ヾ(@^▽^@)ノ   

## 05 My reflection
 - Here are some points that can be improved next time:
   - Do not 3D print thin and small pillars, as this structure will be very fragile. I should thicken the bottom of the pillars or adopt another fixing method
   - When I fit the acrylic sheet with the box, I should do a test first to make sure the size is just right. Since I have been dealing with the problem of inconsistent sketch size, the acrylic board does not stick very well in the end.
   - My arduino board is not perfectly aligned to the pane.
  
 - In conclusion:
   - I think this was a very meaningful practical assignment, and I greatly improved my ability to make prototypes through this midterm project, which was very helpful for me, and I learned a lot about modeling and 3D printing! ：）




 
  

