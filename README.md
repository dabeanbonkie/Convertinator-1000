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

| item                           | Second Header |
| -------------------------------| ------------- |
|USB4125-GF-A-0190               | Content Cell  |
|WR-PHD 2.54 MM SOCKET HEADER; 2 | https://www.digikey.nl/nl/products/detail/w-rth-elektronik/61300211821/21556337?gclsrc=aw.ds&gad_source=1&gad_campaignid=18731631328&gbraid=0AAAAADrbLlg8GG39wR-PqZE72XBdIeVth&gclid=CjwKCAjw9NjRBhATEiwA_p2J8c4z4aGKsrhAR5Fd26k98iVsSH0wUBbg9CbgHyMsw87i4K3XROsmlhoCHpgQAvD_BwE
|
