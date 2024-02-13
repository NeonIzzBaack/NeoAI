<h1 align="center">NeoAI - AI Aimbot</h1>
<p align="center">
    <a href="https://github.com/NeonIzzBaack/NeoAI">
        <img src="https://github.com/McDaived/AIMi/assets/18085492/56684d14-9573-403e-bb06-6c323d475ebc" alt="Logo" width="500" height="150">
    </a>
<h4 align="center">NeoAI es un aimbot de IA, funciona mediante la detección de objetos en tiempo real con redes neuronales y reconoce patrones similares a los movimientos humanos y la formación humana e identificará la cabeza como objetivo.</h4>
<h6 align="center">Esto no se considera trampa en los juegos porque no modifica los archivos del juego ni interfiere con los juegos, solo toma el control en nombre del usuario.</h6>
  <p align="center">
<img src="https://github.com/McDaived/AIMi/assets/18085492/9e53d002-80ec-472b-9156-5416a061790e" alt="Your Image Description" width="500">
<img src="https://github.com/McDaived/AIMi/assets/18085492/c430ab48-99e4-466b-833f-77879a5a01e9" alt="Your Image Description" width="260">


## ![](https://github.com/McDaived/NoRecoil-CS2/assets/18085492/fdee8c61-c0f7-41a2-80a0-15c1b5f5bb95)Information :
- Es una versión mejorada **YOLOv7 se usará en la próxima versión**
- Es la versión **CPU 80%-GPU 20%** solo usando OpenCV, **en la próxima versión se desarrollará para que funcione más rápido y con mayor precisión,**
- No necesitas RTX para que funcione.
- Esta versión está actualmente optimizada para juegos cs2, valorant, fps, etc.
- GUI del detector de objetos para que veas cómo reconoce el modelo.

    
***Download latest version of python then install it like this pictures..***

![](https://www.python.org/downloads/)
          
</details>
<details> 
        <summary>⚠ Ligera vibración por qué ?⚠</summary> 
    
``Cuando uses NeoAI, verás una ligera vibración en aimbot porque es una versión beta, todo se mejorará en las próximas versiones.
Será mejor y más preciso en las próximas versiones porque funciona muy bien para algunas personas y funciona bien para mí.
 varía según los procesadores que pueden analizar la red neuronal, pero aún así funciona bien.``

          
</details>

<details> 
        <summary>⚠ Apuntando AL SUELO ¿Por qué? ⚠</summary> 
Importante: Para hacer que funcione



1. Desactiva la entrada sin formato en cualquier juego que quieras jugar.

2. Deshabilite la mejora del puntero: Propiedades del mouse->Opciones del puntero->Mejorar la precisión del puntero

          
</details>

<details> 
        <summary>⚠ Mouse input no funciona en Valorant ¿por qué? ⚠</summary> 
  
Si lo usa en valorant, no funciona porque necesita un controlador del kernel para evitarlo, alguien hizo que funcionara en valorant usando esto.

[Click Here](https://www.unknowncheats.me/forum/3912497-post139.html)


## ![]How to use :
1. Descargue [Python](https://www.python.org/).
2. Descarga NeoAI.
3. Extráelo.
4. Deshabilite la precision del puntero ``Propiedades del mouse``->``Opciones del puntero``->``Mejorar la precisión del puntero``
5. Desactiva ${\color{red}RAW}$ ${\color{red}INPUT}$ en cualquier juego que quieras jugar, **si está disponible**.

**PD: No necesita hacer nada más, simplemente abra el programa desde CMD o haga doble clic y usted mismo descargará todas las bibliotecas necesarias.**

6. ``Python start.py`` o doble-click.

## ![] Settings :

<summary>Optimización para cs2</summary>
    La mejor configuración para CS2 y asegúrese de usar este punto de mira o crear su propio punto de mira, para hacer que la red natural sea más rápida y dé algo de espacio para analizar el modelo.

1. Importe esta mira en la configuración del juego ``CSGO-YE93T-V6tTU-Cxa9r-jCf7s-2XJaA ``

2. para obtener mejores resultados, utilice esta configuración

![image](https://github.com/McDaived/AIMi/assets/18085492/5fc8c79b-0dd5-4989-9223-9e93760f84a1)

    
</details>

<details> 
        <summary>For Stretch Screen (Optional)</summary> 
    change line 70 in detect file from lib folder.
    
```py
origbox = (int(Wd/3.1 - ACTIVATION_RANGE/4),#gui box capture
               int(Hd/2.5 - ACTIVATION_RANGE/4),
               int(Wd/4 + ACTIVATION_RANGE/1),
               int(Hd/2 + ACTIVATION_RANGE/2))
```

</details>

<details> 
        <summary>Change Hotkey hold mode (Optional)</summary> 
    line 118 in detect file from lib folder.
    
```py
if button == button.x2: #Change this button.x2 for example : button.left for left click mouse


```

</details>


## ![](https://github.com/McDaived/Discord-Profile-Card/assets/18085492/952742cf-9744-4ccb-9de1-766560ebae12)Features :
- (F1) Aimbot: Always On/Hold Mode
- (Mouse4) Hold Mode: Press/Release
- (0) Exit
- With gui objects detector.

## ![](https://github.com/McDaived/AIMi/assets/18085492/cc9f4ef7-bce7-488a-82dc-e4baa198896a)Change Log :
```diff
Update (Nov 15 2023)
+ improve the neural network a little faster.
+ made aimbot a little smooth.
+ Add sound when active aimbot.
+ Add setting for Stretch Screen in Readme.
+ made Aim a little accurate.
+ Fix aim on head.
```


## ![](https://github.com/McDaived/AIMi/assets/18085492/575d27e7-105d-4861-ba99-79e3ac2432dc)About :

### Neural network :
Neural network aimbots are great for a lot of reasons... Probably most importantly, it never access the memory of the game, so it's practically invisible to "Anti-Cheat" sofware, additionally, they can abstract it capabilities to many different games without code modifications.
![](https://github.com/McDaived/AIMi/assets/18085492/a861b711-21e4-4d42-bd87-44d35be9b8b2)

### YOLOvX :
The detection network is trained on a combination of video game images and the **COCO** dataset, it is optimized to recognize human-like objects as quickly as possible, the detection engine can be abstracted to many FPS games.

To know more about [yolov3](https://github.com/ultralytics/yolov3)

![](https://github.com/McDaived/AIMi/assets/18085492/50e29940-26f7-4eb7-a136-818ef8b22348)

### OpenCV :
it provide an abstraction layer for working with the screen capture data, but it it also allows us to harness the power of GPU hardware by interfacing CUDA and OpenCL, it uses OpenCV to process that image into a form that is recognizable to the object-detection engine.

![](https://github.com/McDaived/AIMi/assets/18085492/57f36a86-c149-44ac-a140-6fc05a0bad99)


