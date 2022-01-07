# Fall-Detection-IoT-device-using-NodeMCU-and-MPU6050
**Fall Detection IoT device** 
<p>
  <img src = "https://img.shields.io/badge/Arduino_IDE-00979D?style=for-the-badge&logo=arduino&logoColor=whit">
</p> </br>

---

## Setup
**Change these parameters in programs**
1. Add Your WIFI details in *Fall_detection.ino* file : </br>
```
const char *ssid =  "WIFI Name";     // Enter your WiFi Name
const char *pass =  "WIFI Password"; // Enter your WiFi Password
```
2. Add IFTTT Private Key that is API key in *Fall_detection.ino* : </br>
```
const char *privateKey = "Webhooks Key in IFTTT";
```
3. Add WIFI details in *Send_sms.ino* : </br>
```
WiFi.begin("SSID(WIFI_NAME)","WIFI Password");
```
4. Add IFTTT Private key API key and Event name in *Send_sms.ino* : </br>
```
MakerIFTTT_Key ="IFTTT Webhooks Key";
MakerIFTTT_Event ="Webhooks_Event_Name";
```

---

## Also check PDF file of report of project - 
[View PDF](https://github.com/ishanjogalekar/Fall-Detection-IoT-device-using-NodeMCU-and-MPU6050/blob/main/IoT%20Project%20.pdf)
