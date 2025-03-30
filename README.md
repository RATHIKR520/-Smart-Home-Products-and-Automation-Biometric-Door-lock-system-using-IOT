# -Smart-Home-Products-and-Automation-Biometric-Door-lock-system-using-IOT 
Dual-factor authentication with SMS alerts and anti-spoofing.  

## Features  
- Dual fingerprint sensors (entry/exit).  
- PIN verification after fingerprint scan.  
- Real-time SMS alerts with timestamps.  
- Local logging to SD card.  
- Admin remote control via SMS.  

## Setup  
1. **Libraries:** Install `Adafruit_Fingerprint`, `RTClib`, `LiquidCrystal_I2C`, `Keypad`, and `SD`.  
2. **Wiring:** Follow pin mappings in the code comments.  
3. **Enroll Fingerprints:** Use the R305 enrollment example.  
4. **Configure GSM:** Insert SIM card with SMS plan.  

## Usage  
- Scan fingerprint → Enter PIN → Door unlocks.  
- Fake attempts trigger SMS alerts.  
- Admin commands: `UNLOCK`, `LOG`.  

## Troubleshooting  
- **SMS Not Sent:** Check GSM antenna and APN settings.  
- **SD Card Error:** Ensure `log.txt` exists.  
