## Audio forensics
## This post from cyber talents [Here](https://cybertalents.com/learn/introduction-to-cybersecurity/19-audio-forensics)

What you will learn?

-   data hidden inside the audio file .
-   data hidden in waves .

data hidden inside the audio file  :

there are many ways to hide data inside the audio file data we will cover 2 of them .

1.  using tool to keep the file in the metadata ( deep sound ) .
    

-   deep sound is windows based tool to hide files inside audio files , it can hide or extract files from the audio file .  
      
    

![](https://lh5.googleusercontent.com/t6QYzPlBAUE4RtaTzJsZIkyuoFB1ixOs_z_Y09ZQth3VA-e0ZqzSUGGLVE53JhLj1nyoZI0GRHVT29X0NumnXi3gbGFuaQJwh4K4QYDG0kKLfLTE7UykcXLM_a0LUr6CcqgksAw)

-   data hidden in waves .  
      
    

1- in the wave frames you can control the values of it .  
the frames consists of many pulses which has top and bottom values , you can set this values to any value you want .  
  

by using a python script you can inject the values you want to an audio wav , of build a wav file from the values you want

  
[read&write wave file](https://docs.python.org/3/library/wave.html)

2- hide data in wav spectrogram .  
- you can use an online tool (like [spectrum-analyzer](https://academo.org/demos/spectrum-analyzer/) ) to view the

spectrogram of the wave .

![](https://lh6.googleusercontent.com/KJPb751F2fl48Y_9Vqsa2Gdh5zxM4eVjIbsmauStH5v_MQq19gJyrMCjDh4g4C-C-4lcsY9hQ45Pm1-aa19CofGkv2cvNpKWn2HrYCpR1KQIDMyMtVY3dBgH371kkBPqO3bJQt8)

but the problem is that you have to wait for all the audio file being played to find out the hidden message on the spectrogram , unless you know the time where the message were .

-   using [audacity](https://www.audacityteam.org/)
    

![](https://lh5.googleusercontent.com/bT5DDOA3m1a0jrrUsE6Cc0zEazVRGPnORLmhLGoSzDmPR9iMKZdtVWrBDzuRVnCCPxMr7zqjuzSSnPpUOeqHXROLVTrF5l8bkdV6vqYn-9gU7rFTLOSuxXLosLZVG12WC8TbSeU)

but if the file is too long you won't find the text in easy way , so in many time

you’ll have the problem as the website .

-   sox tool .
    

![](https://lh3.googleusercontent.com/GWi5vwzxjj11Q2aEfEwpJnAGU1zqAJOpRJRLjpL0qxgPgXSN6MUyyBPtQp1bec1NNqF2PFXkNg6mSsygkCn1uijrXKadOEJUsCOMwH91O3xYrAjUzHnLYoo7vxeNMihpF8nr004)

  
you can install it for linux .

it give you the output of all audio spectrogram in a form of image file , so you can recognize where is the text .

but the problem of it is that , sox tool is not work for many types of audio files.

## again, we say that this article is not owned by us it is  on the cyber talents platform. You can access it from [here](https://cybertalents.com/learn)
