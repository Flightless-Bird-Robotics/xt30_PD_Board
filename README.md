# xt30_PD_Board
A small xt30 power delivery board with space for 6 standart xt30 connectors
<img width="3120" height="4208" alt="XT30_PD_Board_Photo" src="https://github.com/user-attachments/assets/b8a24ea0-033b-4119-bff2-65343b8d1d51" />
<img width="1528" height="1198" alt="XT30_PD_Board_Screenshot" src="https://github.com/user-attachments/assets/3514df22-fbb6-47f1-9a2a-d2b35945e15a" />
<img width="1558" height="810" alt="XT30_PD_Board_Screenshot_Bottom" src="https://github.com/user-attachments/assets/a223c642-9acd-4f34-aad2-2b9657ea8b21" />
## Warnings
The holes for the xt30 connectors on this Board are 2.7mm in diameter.
However there does not seem to be a standard for this size. All the ones I know of will fit, but I recommend to measure what you have available before getting this board manufactured.

The board has been tested with 30A continuously in still air. 


## Manufacturing
To get the multicolor version, you need to order from JLCPCB, since I'm not aware of any other manufacturer supporting multicolor Silkscreen.
The non color variant can be manufactured from any manufacturer. For that I recommend to use the XT30_PD_Board_Without_Color_Gerber.zip file.

To order the color version, upload the XT30_PD_Board_Gerber.zip file to JLCPCB. You can find the file in the Hardware folder.
Now select "White" for the PCB color, and "ENIG" for the Surface finish.
Now you need to open the advanced options, and select "EasyEDA multi-color silkscreen" under silkscreen technology.
Now you can check how the PCB will look under "Gerber Viewer" at the top of the page. The black rectangles at the back are normal and show where the holes for the xt30 connectors are. They won't be on the finished PCB. The preview at the top will not show the multicolor silkscreen!
If you haven't ordered a multicolor silkscreen at JLC before, you can get a coupon for it here https://jlcpcb.com/resources/multicolor-silkscreen-pcb
<img width="2545" height="4223" alt="XT30_PD_Board_Ordering_Instructions" src="https://github.com/user-attachments/assets/19dccfdc-ec86-4b1c-b8ca-fd2c57d75405" />
