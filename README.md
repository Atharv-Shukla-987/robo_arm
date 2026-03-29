# robo_arm
A robotic arm controled by hand gestures based on ardiuno.

# BOM 

here is everthing u need to build it.
# Robo Arm – Electronics
Parts - links
<br>
6 x Servo Motor – MG966R Series - https://www.amazon.in/4-Pack-MG996R-Torque-Digital-Helicopter/dp/B07MFK266B
<br>
Servo Driver PCA9685 - https://robu.in/product/16-channel-12-bit-pwmservo-driver-i2c-interface-pca9685-arduino-raspberry-pi/
<br>
Battery Pack (5V, 2200 mAh) - https://www.amazon.com/Gecoty-Battery-Upgrade-2400mAh-Rechargeable/dp/B07ZD72FR8?crid=1SUXXTEM72AMX&dchild=1&keywords=5v%2Brc%2Bbattery&qid=1608902830&sprefix=5V%2BRC%2Caps%2C230&sr=8-2&linkCode=sl1&tag=aram1-20&linkId=cf33cc25cb1525b1538bbb631d1613ce&language=en_US&th=1
<br>
Arduino Uno - https://store-usa.arduino.cc/collections/uno/products/arduino-uno-rev3
<br>
Arduino HC-05 - https://www.amazon.in/DSD-TECH-HC-05-pass-through-communication/dp/B01G9KSAF6?crid=1IFONEUAED3QQ&dib=eyJ2IjoiMSJ9.YTOhgskeygFJoLsnoIkV3HENKHSi6o57akOaoMbxUSICCvO-WHtfalLdwLJiZ7yqiPHWxnXfik2aEKYGwppEYZndfsR4HLNoxvFLSDmOa0xDEIqXbHr6v7gWi0DBGnyvgpaFUCX0LT-yDRoW4F95o9hDgLJz8kuk3AuUqYtVBuj0i7jzrXllZvh9zEFKbuKKD7tdHqhI8YwXq8fyHKPYpBbd-97E31Ej0wSD_OjIO57dYQJYIm1gSZhgotbfQujzk42j66lzIEjwKb9ekok84Aa0GOxHYeuBzEFbWEJ_Scs.-7QQyBG_o9JhWPleHX-oWbyvaCRLb2j8xB_8d42iRpE&dib_tag=se&keywords=Arduino+HC-05&qid=1774806953&sprefix=arduino+hc-05%2Caps%2C466&sr=8-24
<br>
Breadboard - https://www.amazon.in/Breadboards-Include-Solderless-Distribution-Connecting/dp/B07DL13RZH?crid=QM7NTRZ24UOH&dib=eyJ2IjoiMSJ9.-pSFUPINFTpn_JpnEhQU7lNqKXydB1qeLtW_OSGPBiqhaQskpV5YJ0NjpT0tLIpA-LV2fOVmboiRdmZikdrvxGjAGjqw07-KkvSbz3jxkB6UH8FE7gIzl75FGh1YA9I0wHM8iPFs5XmSj0QSRIwB5IYu-norv126Bp_LEXT0h_PzlbUIFMMR6kfihJQuDKivDxxdA9JN7HFJ7Wwwo6_r5YrcGWe5SJ_nbRP9m_hbSLX-YRmyFX6Kl_sslOEN4snf278EcyQs08dMZTte4z3N8sURwvE6_qMvCDucdFea_kE.xzl_uL3EMZ1adfdyMS7fGlHBmU-QKyfUUOQg1q8PnUs&dib_tag=se&keywords=4PCS+Breadboards+Kit+Include+2PCS+830+Point+2PCS+400+Point+Solderless+Breadboards+for+Proto+Shield+Distribution+Connecting+Blocks&nsdOptOutParam=true&qid=1774807136&sprefix=4pcs+breadboards+kit+include+2pcs+830+point+2pcs+400+point+solderless+breadboards+for+proto+shield+distribution+connecting+blocks%2Caps%2C488&sr=8-6 
<br>
Jumper Wires - https://www.amazon.in/REES52-Pieces-Jumper-Wire-Wires/dp/B01HON4T6Q?crid=1EEP2W3ZY2782&dib=eyJ2IjoiMSJ9.Gf6cDFSp0GkyAyUzrzuVhIOJwud4j91KMQGhEPcdm9N-kCBJsivYGvlm16_fEHBUgM5KUmjSU2AHfqE6IFmiFJhd0oXNTcU-LSG2Zyda9N1PRJ5NHDkUv4_I280C8ieTBqgCIhXlVcoHgE_pdB6GrU3Vek2IDsAfhrkNCzoKxFpnwAL1nsPqs16yCVSQxyYv7KaM9R_5BdefYWvAMBK0PFd3cgM0QqzhfINFBYwH-eO1uzThrl5ICRM-5EsjeCCkViJTf9azNf9RXjP7M0jvNOFamSGqskuUDeMX9Ju0Rdw.JCPfQNifQXYYc4j0FRS6ByFP1mC3NwsagZWU5os6qIo&dib_tag=se&keywords=ELEGOO+120pcs+Multicolored+Dupont+Wire+40pin+Male+to+Female%2C+40pin+Male+to+Male%2C+40pin+Female+to+Female+Breadboard+Jumper+Ribbon+Cables+Kit+Compatible+with+Arduino+Projects&nsdOptOutParam=true&qid=1774807227&sprefix=elegoo+120pcs+multicolored+dupont+wire+40pin+male+to+female%2C+40pin+male+to+male%2C+40pin+female+to+female+breadboard+jumper+ribbon+cables+kit+compatible+with+arduino+projects+%2Caps%2C438&sr=8-1
<br>
NEMA 17 Stepper Motor - https://www.amazon.in/4-2kg-cm-Precision-Reversible-Printers-Robotics/dp/B0FBLF5YVR?dib=eyJ2IjoiMSJ9.7sn1QQSO7pfApcpue4W3rNf3VSoGombnos6ycK7idC11jKe-bZBlsWf9QFCxKiNBKGEtC71DJABco9-bT3_ac-yS_XB196Tv3m9DrnDvb6RdHWVNZVcBzIwcNdTPFa7DXj1ksYxVx_ofVIaogIdD-ZPSAtd5GgRcdBnLjOljCzcY8Sc-kp2_IueIhFuEaSQLM8ZE3TjeU_UpEvZhKGcDr0Tn_YQUwt-3sijIpin1O8dtrsR4-RftjN-KkjQoMbU5E7J2o-j0kyCAOZy3dox6iyC1mAcH_7ZbdAE3kTk-KEI.dPWC7Q4fTY9kZJzDTnril0orjl6av3r1629mf4pbD8U&dib_tag=se&keywords=nema+17+stepper+motor&qid=1774807724&sr=8-5
<br>
A4988 Stepper Motor Driver - https://robu.in/product/a4988-driver-stepper-motor-driver/
<br>
LiPo 11.1V, 2200mAh, 3s - https://robu.in/product/orange-2200mah-3s-30c60c-lithium-polymer-battery-pack-lipo/
<br>
# Hand Glove – Electronics
Parts - Links
<br>
3 x Flex Sensor - https://www.amazon.in/TESTIN-ELECTRONICS-Robotics-Breadboard-Connectors/dp/B0FZ5RLCSS?source=ps-sl-shoppingads-lpcontext&psc=1&smid=A1LULBHI7A07S5
<br>
MPU6050 (Accelerometer) - https://www.amazon.com/HiLetgo-MPU-6050-Accelerometer-Gyroscope-Converter/dp/B01DK83ZYQ?
<br>
Arduino Nano - https://store.arduino.cc/products/arduino-nano
<br>
3 x Resistors (10K) - https://www.amazon.in/10K-ohm-Watt-Resistor-Tolerance/dp/B09VH1K4GW
<br>
Resistors (220R) - https://harishprojects.com/products/220r-resistor-1-4w?variant=45673682075826&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic
<br>
9V Battery - https://www.amazon.in/Eveready-9-Volt-eveready-Battery/dp/B07Y348F5D?source=ps-sl-shoppingads-lpcontext&psc=1&smid=A3JJCP2CFGNMJ6
<br>
Battery clip - https://harishprojects.com/products/9v-battery-clip-connector-buy-50-get-5-free?variant=44431177351346&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic
<br> 
3 x Capacitor (100nF) - https://kitsguru.com/products/100nf-50v-monolithic-ceramic-capacitor-104-100pcs
<br>
Arduino HC-05 - https://www.amazon.in/DS-Robotics-Transceiver-Integrated-Communication/dp/B087C39X6D
<br>
Braided Cable Sleeve - https://robu.in/product/nylon-8mm-expandable-braided-sleeve-for-wire-protection-2m-length/
