![image](https://user-images.githubusercontent.com/12781303/96605153-0fce6d80-1320-11eb-885f-7581a42ad273.png)

<h>OpenCore-0.6.2-Ryzentosh  </h>
EFI ของ Ryzentosh ทีทำงานดีที่สุดของฉัน<br>
ฉันทำขึ้นเพื่อใช้ส่วนตัวหรือถ้าท่านไหนจะลองนำไปรับแต่งฉันก็ไม่ว่าอะไร

## สเปคคอมพิวเตอร์
* CPU AMD Ryzen 5 2600<br>
* VGA RX5600XT Red Devil<br>
* B450M Steel Legend<br>
* Ram 16GB DDR4 A-DATA<br>
* NVMe M.2 BLACK SN750 250GB<br> 
* HHD 1 TB WDC<br>
* SSD 120 GB Colorful SL300<br>
* MONITOR AOC 23 นิ้ว

<h>ระบบ OS ของฉันและ SMBIOS</h>
OS Catalina 10.15.7<br>
Mac Pro 7,1 [2019] มันทำงานได้ดี<br>
และเหมาะกับเครื่องของฉัน

<h>ทำงาน</h>
Ethernet<br>
Display Port audio & HDMI<br>
Audio output<br>
Sleep<br>
Microphone input<br>
Gpu ทำงานได้เต็มที่

</h>ไม่ทำงาน</h>
Hardware Virtualization

</h>Update Big Sur beta 10</h>
สำหรับการอักเดท มันสามรถอัพเดทได้ปกติเพียงแค่คุณแก้ไขตามนี้<br>
* EFI -> OC -> config.plist | เปิดไฟล์แก้ไข<br>
* Misc -> Security -> SecurrBootModel = Disabled<br>
* Reboot 1 ครั้ง แล้วทำการอัพเดท Big Sur beta 10 ได้เลย