# Convertinator 1000 Showcase
<img width="1410" height="2000" alt="Image" src="https://github.com/user-attachments/assets/ade5f050-3050-43f3-aeba-d5116e38c496" />

# Description
The Convertinator 1000 is a basic power supply that converts voltage from a USB-C (5V) to 1.2V, 3.3V, 12V & 24V, also featuring an output for 5V. It has the input as the USB-C and the outputs as dupont headers as its main use is for prototyping small cicuits and basic breadboarding. It isnt made to handle strong current but the 12V & 24V connections should be able to handle a bit more.

# Reason
I designed this as a project that i could maybe use in the future when doing smaller projects as i get more and more proficient in hardware. Its not intended to run anything too heavy but can handle basic circuitly which is all I would need it for. It also worked perfectly as a project to do while parts for other projects were printing.

# Usage
To use the Convertinator 1000, take a USB-C plugged into any socket (as long as it supplies 5V) and plug it into the USB-C component on the Convertinator 1000. From there, take two dupont wires and connect them to the two headers for each voltage. One header is for the output voltage which on each connection is the header on the left, and the other is the ground which is always on the right. I highly advise you NOT to run anything above 1A on the 1.2V, 3.3V & 5V headers and NOT anything above 1.8A on the 12V & 24V headers.

#Assembly
Putting all the parts together is easy as can be. Since i figured this power supply wouldnt be moving much i havent mounted the pcb. So to assemble the Convertinator 1000, just print both components, put the pcb in the shell making sure all the gubbins on the bottom of the pcb cleanly fit into the groves on the bottom of the shell. Then mount the lid to the shell using a simple nut and bolt (4.8 mm) on the mounting holes on both parts. Then its all complete.

Here is how the pcb should be placed from the bottom of the shell:

<img width="515" height="720" alt="Image" src="https://github.com/user-attachments/assets/66136ae2-972d-4d9a-a34e-70019dc40f73" />

#BOM

| name                           | description | price (for units) | Link |
| -------------------------------| ------------- | ---------------------------|----------|
| USB4125-GF-A-0190               | USB-C Connector (amount: 1)| $ 0,60	(with tax: $ 0.73)| | https://nl.mouser.com/ProductDetail/GCT/USB4125-GF-A-0190?qs=QNEnbhJQKvbCz4hEJBS24w%3D%3D&mgh=1&utm_id=20333412842&utm_source=google&utm_medium=cpc&utm_marketing_tactic=emeacorp&gad_source=1&gad_campaignid=20337787384&gbraid=0AAAAADn_wf0-J8ZPiaWEc2p7nZkI8Egx1&gclid=CjwKCAjw9NjRBhATEiwA_p2J8TbbcIn--jgbaDbrnAjrV4zxDneDLBxv2wQ5ZcKiUP0pMeIcBXOIERoCALUQAvD_BwE |
| WR-PHD 2.54 MM SOCKET HEADER; 2 | 1*2 Female Dupont headers (amount: 5)| $ 0,38 per unit, $ 1,90 total (with tax: $ 2.30) | https://www.digikey.nl/nl/products/detail/w-rth-elektronik/61300211821/21556337?gclsrc=aw.ds&gad_source=1&gad_campaignid=18731631328&gbraid=0AAAAADrbLlg8GG39wR-PqZE72XBdIeVth&gclid=CjwKCAjw9NjRBhATEiwA_p2J8c4z4aGKsrhAR5Fd26k98iVsSH0wUBbg9CbgHyMsw87i4K3XROsmlhoCHpgQAvD_BwE |
| AMS1117-3.3| Step Down Voltage Regulator (amount :1)| $ 0.30 (with tax: $ 0.363) | https://www.digikey.nl/nl/products/detail/umw/AMS1117-3.3/17635254?gclsrc=aw.ds&gad_source=1&gad_campaignid=18731631328&gbraid=0AAAAADrbLlg8GG39wR-PqZE72XBdIeVth&gclid=CjwKCAjw9NjRBhATEiwA_p2J8e7fJyDa-4kdrUvqzgTWsfYkIJDbbBOVQrEF9TQRU03unzVr6sUrShoCddUQAvD_BwE |
| TMR_1-0512| Converter_DCDC:Converter_DCDC_TRACO_TMR-1-xxxx_Single_THT (amount: 1)| $ 15.36 (with tax: $ 18.59)| https://www.verical.com/pd/traco-electronic-ag-dc-dc-converter---regulator-modules-tmr0512-654650?utm_source=google&utm_medium=cpc&utm_campaign=brand_g-ppc-verical-emea-sku-english-en-electromechanical-verical_only-v4_q1_2025&utm_content=emea_en&gclsrc=aw.ds&gad_source=1&gad_campaignid=20881764860&gbraid=0AAAAADEt2opQLyZ3Vq_CSthlccwGRf045&gclid=CjwKCAjw9NjRBhATEiwA_p2J8RfCwhRbOkDoAn_7agMFW_UtzVX-x-yK7wlsQcp13RKAOCMngvoxSxoCjrEQAvD_BwE |
| TMR_1-0515| Converter_DCDC:Converter_DCDC_TRACO_TMR-1-xxxx_Single_THT (amount: 1)| $ 9,60  (with tax: $ 11.62)| https://nl.mouser.com/ProductDetail/TRACO-Power/TMR-1-0515?qs=ckJk83FOD0V3ECmEksFjYA%3D%3D&srsltid=AfmBOooDnF0C603pYjjxqZwpNetQO7iFfVdhXASMeJvEFaneDIy_Nd5W |
| AP7361C-12E| Step Down Voltage Regulator (amount :1)| $ 3,96 (with tax: $ 4.79)| https://www.digikey.nl/nl/products/detail/analog-devices-inc/ADP3338AKCZ-3.3-RL/994037?gclsrc=aw.ds&gad_source=1&gad_campaignid=20252971367&gbraid=0AAAAADrbLliaD6LTMp1CF3X2QJ6c757gd&gclid=CjwKCAjw9NjRBhATEiwA_p2J8fsopy2wre-vpmc76e9NPJ05GgQ3csTAmWMxEoNl-VS9nJujxQAppBoC-KsQAvD_BwE |





