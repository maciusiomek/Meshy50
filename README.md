<center><h1>Meshy50</h1></center>
<h4>A meshtastic node based on nRF52840 Pro Micro with GPS!</h4> 
<img width="750" height="auto" alt="Meshy50_2026-Nov-05_08-59-25PM-000_CustomizedView16964282033" src="https://github.com/user-attachments/assets/200acc66-9e6c-41c7-80b7-733e9533de00" />
<hr>
<h2>Components and pricing.</h2>

So basically, this project is based on faketec pcb. It's about $50-70 per board with shipping! You'll need the things from the table bellow:

<table>
  <tr>
    <th>Quantity</th>
    <th>Part</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Heltec HT-RA62 LoRa module</td>
    <td>$7</td>
  </tr>
  <tr>
    <td>1</td>
    <td>10x2mm 3V vibration motors (optional)</td>
    <td>$3.5 for 10pcs</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Good 868MHz antena</td>
    <td>$7</td>
  </tr>
  <tr>
    <td>3</td>
    <td>SI2312 mosfets (needed for the buzzer, vibra motor, gps)</td>
    <td>$4 for 100pcs</td>
  </tr>
  <tr>
    <td>1</td>
    <td>NRF52840 Pro Micro/Supermini</td>
    <td>About $5</td>
  </tr>
  <tr>
    <td>1</td>
    <td>9032 buzzer (optional)</td>
    <td>$3 for 10pcs</td>
  </tr>
  <tr>
    <td>1</td>
    <td>ATGM336H GPS module (optional)</td>
    <td>About $5-7</td>
  </tr>
  <tr>
    <td>5</td>
    <td>10k ohm 1206 SMD resistors</td>
    <td>$1.5 for 100pcs</td>
  </tr>
  <tr>
    <td>1</td>
    <td>3D printed case</td>
    <td>Basically free</td>
  </tr>
  <tr>
    <td>1</td>
    <td>20mm nylon strap (optional)</td>
    <td>You can get it from that old backpack</td>
  </tr>
  <tr>
    <td>1</td>
    <td>18650 battery holder</td>
    <td>$3</td>
  </tr>
  <tr>
    <td>1</td>
    <td>SLLB510100 switch/button</td>
    <td>Like $0.75</td>
  </tr>
  <tr>
    <td>1</td>
    <td>0.96 OLED</td>
    <td>$4</td>
  </tr>
</table>

Remember that because of these shitty EU tarrifs, the price just straight up sadly doubles. That's why my final price is about $50-70, depending whether you buy in bulk or not.
<hr>
<h2>Assembly and flashing</h2>
Solder everything on like on the image bellow and that battery holder on the back<br>
<img width="600" height="auto" alt="image" src="https://github.com/user-attachments/assets/c20d8d8f-57c8-49fd-ba63-3482ad21849d" /><br>
<br>
Now go to https://flasher.meshtastic.org/ and choose "NRF52 Pro-micro DIY". Then click flash and follow what's on the screen.<br>
<img width="1000" height="auto" alt="image" src="https://github.com/user-attachments/assets/87e78621-09c6-4860-8b11-f63fc611c7d4" /><br>
<br>
Then on the app configure your pins.
<br>
<table>
  <tr>
    <th>Pin</th>
    <th>Function</th>
  </tr>
  <tr>
    <td>0</td>
    <td>Switch left</td>
  </tr>
  <tr>
    <td>31</td>
    <td>Battery voltage</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Vibra EN</td>
  </tr>
  <tr>
    <td>8</td>
    <td>Buzzer EN</td>
  </tr>
  <tr>
    <td>24</td>
    <td>GPS EN</td>
  </tr>
  <tr>
    <td>20</td>
    <td>GPS TX</td>
  </tr>
  <tr>
    <td>22</td>
    <td>GPS RX</td>
  </tr>
</table>

So umm, now you should be done! Yippe!
<hr>
Also I've made this repeater enclosure, if you want to use it, it's called Meshy50-repeater.stl!
<img width="1000" height="auto" alt="Meshy50-repeater_2026-Nov-08_12-52-00AM-000_CustomizedView22369549720" src="https://github.com/user-attachments/assets/7def0e45-e27f-459b-9031-903c3e80e598" />

<img width="1000" height="auto" alt="8ac05e12-ce3b-466f-bbca-a514f8749015" src="https://github.com/user-attachments/assets/3e5127bc-c838-4ab4-b5f0-0ac5eb974dad" />





