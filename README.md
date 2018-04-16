# Hardware

## Descripción
   Módulo descriptivo del hardware del proyecto, se incluyen los sensores utilizados, con sus respectivos datasheets, circuitos de protección para dichos sensores, componentes de cada bloque de circuitos y el diagrama y montaje tanto del emisor (arma) como del receptor (diana).

## Tabla de Contenidos
- [Componentes](#componentes)
- [Lista de Módulos](#lista-de-módulos)
- [Documentación Técnica](#documentación-técnica)
- [Caracterización de los sensores](https://github.com/Fedora-Eugenio/Documentacion/blob/master/CARACTERIZACI%C3%93N%20DE%20LOS%20SENSORES.docx)

## Componentes
1. **Sensores**

   1.1. *Analógicos*
   
      - **Acelerómetro**: Utilizado para realizar las interacciones del usuario con el arma. Dichas interacciones serán las siguientes:
        
        *Cambio de modos de juego:*   
        
        ![ModoJuego](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/ModoJuego.jpg)
        
        
        *Recarga del arma:*
        
        ![Recarga](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/Recarga.jpg) 
        

   - **Ultrasonido**: Con este sensor se podrá medir la distancia, entre el arma (emisor) y la diana (receptor), la cual afectará al puntaje, siendo esta un factor multiplicativo. 
   
   1.2. *Digitales*
   
   - **Pulsador**: Utilizado como el gatillo del arma.
   - **Fototransistores**: Serán usados como los receptores del haz de luz emitido por el láser y actuarán como blancos de disparo. Cada fototransistor irá acompañado de una resistencia de 1k Ohm en paralelo como se muestra en el siguiente esquemático:
       
2. **Amplificadores Operacionales**

   2.1. [LM324N](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/LM324.pdf)
   
   2.2. [DM74LS04](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/74ls04.pdf)
   
3. **Componentes**

   3.1. *Resistencias* 
      - 5 x 1k Ohm
      - 4 x 200 Ohm
      - 6 x 15k Ohm
      - 6 x 22k Ohm
      - 2 x 330 Ohm
      - 1 x 240 Ohm
         
   3.2. *Capacitores*  
      - 5 x 10uF
      - 1 x 100uF
         
   3.3. *Diodos*   
      - 5 x BZX55C
      - 1 x Diodo Verde
      - 1 x 1N5819
   
4. **Reguladores**

   4.1. [LM2940-5](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/LM2940.PDF)
   
   4.2. [LM317](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/LM317.pdf)
         

## Lista de Módulos
- **Circuitos de Protección**
  - Analógicos
  
  ![Proteccion Analogica](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/Proteccion%20Analogica.PNG) 
  
  - Digitales
  
  ![Proteccion Digital](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/Proteccion%20Digital.PNG) 
  
  
- **Fuentes Reguladas**
  - 5V y 3V
  
  ![Fuentes reguladoras](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/Fuentes%20reguladoras.PNG) 

- **Prototipo Arma-Emisor**

![IMG_20180415_213101](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/IMG_20180415_213101.jpg)

![IMG_20180415_213111](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/IMG_20180415_213111.jpg)

![IMG_20180415_213125](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/IMG_20180415_213125.jpg)

- **Prototipo Diana-Receptor**

![silueta2](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/silueta2.jpg) 

   Cada círculo rojo representa la ubicación de los fototransistores en la diana real. 

## Documentación Técnica
- [Acelerómetro](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/Low_G_X-Y-Z_Axis_MMA7260Q.pdf)
- [Ultrasonido](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/srf05tech.pdf)
- [Fototransistores](https://github.com/Fedora-Eugenio/Hardware-emisor/blob/master/XRNI53W.pdf)


