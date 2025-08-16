**VIDEO PLAYER STM32 ILI9486 8 BIT SD DMA tjpgd avi**

https://www.youtube.com/watch?v=es7YlJPMs6A


ffmpeg -i SpongeBob.mp4 -c:v mjpeg -s 320x240 -r 25 -q 15 noaudio.avi

![VIDEO PLAYER STM32 ILI9486 8 BIT SD DMA tjpgd avi](https://github.com/user-attachments/assets/7e273539-fdf9-40fc-9fa8-3d59a0f90553)




ffmpeg -i SpongeBob.mp4 -c:v mjpeg -s 480x320 -r 25 -q 15 noaudio1.avi

![Screenshot_1](https://github.com/user-attachments/assets/c62bc4af-80da-427d-a2a4-9d477de15718)


************************************************************

to do it:

1- use stm32f407 with fsmc + sdio dma cmsis

************************************************************


Code 60% from VADROV https://github.com/vadrov/stm32f4_fast_optimized_avi_player_osd 

40% from me

************************************************************
