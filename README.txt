
Dentro de las carpeta años (2015,2016,2017), analiza las carpeta con este patron:
 '-> crear lista de carpetas I-XX-XX , M-XX-XX , R-XX-XX
 
 Los archivos deven de esta llamados como X-XX1-XX2_YYtexto.png
 X-XX1-XX2:  
    X: primera X letra: I,M,R
    XX1: 05,06,07 
    XX2: indica numero de ficha de ese año.
 
    yy: es el orden de 01,02,03,04,05,06 (los que me interesan son los 04,05 y 06)
    texto: contenido de la ficha: 
              registro_de_inicio_accion_correctora.png
              registro_de_final_accion_correctora.png
              repfoto.png", ficherotmp 
 
Este programa une los archivos:
   contiene("_04registro_de_inicio_accion_correctora.png")
   contiene("_05registro_de_final_accion_correctora.png")
   contiene("_06repfoto.png", ficherotmp) 
   
   En uno solo, llamandolo:
      
 /tmp/Presa_XXXX_03_m-16-03_InformeRecortado.pdf
 
 Siendo XXXX el nombre elegido en el combobox
 