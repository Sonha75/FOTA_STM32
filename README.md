### FOTA_STM32
## Webserver: Using Node js, include backend and frontend.
   Backend: Javascript, HTTP.
   
   Frontend: Html.
   
   API using express library in Node js.
   
   ![image](https://github.com/user-attachments/assets/18af0089-6afe-4bc9-bb1d-771c2f886583)
## Client:
   Using Render(a free hosting with limited resources) to deploy server OTA 
   IP DNS : https://ota-render.onrender.com/
## Device 
Communication: module ESP32 using Wifi for download firmware from server OTA and transfer to STM32

MCU: STM32F1xx for receiving firmware from ESP32 and booting it to flash memory

![image](https://github.com/user-attachments/assets/e3a4c5c4-43d2-4eb1-b751-6e9c2f29d198)

# Communication between ESP32 and STM32
Flow 
![image](https://github.com/user-attachments/assets/c81498a8-a756-4e53-9bb9-70e4ef99d63e)

Start Message
![image](https://github.com/user-attachments/assets/2b2d3790-d0ab-432d-8ac4-133e8bb78c6f)

Page Ready Message
![image](https://github.com/user-attachments/assets/2713c0d1-8185-4eae-9d2a-d35a8b8e5260)

Block data message
![image](https://github.com/user-attachments/assets/b7dcdc67-28be-4c5d-b41d-f62deddd3669)

Block mask request message
![image](https://github.com/user-attachments/assets/7662a794-cc36-4370-a18e-3653394f0ab9)

Block mask response message
![image](https://github.com/user-attachments/assets/9177a1e0-dd85-4d01-a359-bfdf37a9d238)

Page done message
![image](https://github.com/user-attachments/assets/7b53e9d4-98ad-4f25-8bab-61bdad5bc711)

End update message
![image](https://github.com/user-attachments/assets/774e262f-2a59-48b1-bc43-aa525b27f469)

## Result

![image](https://github.com/user-attachments/assets/bcd92e6a-37c2-4133-b670-aef3fae2eeb9)


