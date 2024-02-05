# UnrealEngine5_NvidiaAnsel
Una versión portada basada en Unreal Engine 4.27 versión Nvidia Ansel. Proporciona dos versiones, una versión normal y una versión de rastreo automático.

Corrección: Se han solucionado algunos defectos en la instalación y se ha estandarizado el archivo build.cs.
## actualizar
Actualizado a la versión 5.2, agregando más opciones de configuración:
![image](https://github.com/MonsterGuo/UE5_NvidiaAnsel/assets/39860733/303d32df-57e9-492a-a3e2-a93c438cc1b6)

# Instalación: instale el complemento en cualquier lugar y el motor podrá identificar la ubicación del complemento.

#Ansel_Captura
Una herramienta basada en los complementos Nvidia_Ansel modificados de Unreal Engine 4.27 que se puede utilizar para generar videos 360 o 360 estereoscópicos.
Esta es una versión modificada basada en el complemento Ansel de Unreal Engine 4.27.
Antes de comenzar su trabajo necesita preparar:
#### 1. Confirme que se haya instalado el controlador de su tarjeta gráfica:
Actualmente probado: versiones del controlador Nvidia 456.71~551.79.
#### 2. Si necesita cambiar la ubicación para guardar un solo cuadro: instale el componente GeForceExperience de Nvidia.
**Sin modificaciones: guarde de forma predeterminada en la "carpeta de videos" especificada por el sistema

(1) Haga clic en "Configuración"

![Pasted image 20220324120858](https://user-images.githubusercontent.com/39860733/159846088-18804c78-c19a-47ca-8edc-ea44e3d7a3af.png)
(2) Desactive la "Superposición en el juego". Este paso es para garantizar que "Ansel" pueda iniciarse normalmente. No sé por qué. De todos modos, debe apagarse para que se pueda iniciar Ansel dentro de Unreal.

![Pasted image 20220324121037](https://user-images.githubusercontent.com/39860733/159846137-8b6e1ee7-57e3-4cb8-b1bb-c78f52e559b2.png)
(3) Haz clic en "Cobertura del juego" para cubrir la configuración.

![Pasted image 20220324120645](https://user-images.githubusercontent.com/39860733/159846194-877e800a-cc0b-48e6-9712-8b22d08c5ee8.png)
(4) Haga clic en la opción "Configuración"

![Pasted image 20220324121245](https://user-images.githubusercontent.com/39860733/159846343-153054d9-3cf0-4304-b42d-8202dafcbe8e.png)
(5) Establecer la ruta para guardar

![Pasted image 20220324122738](https://user-images.githubusercontent.com/39860733/159846366-b01d8273-55bc-4cd4-9ff7-26e082e122e4.png)
![Pasted image 20220324122852](https://user-images.githubusercontent.com/39860733/159846373-489b35b0-f155-4791-80d8-2cbacb7be82b.png)
#### 3. A continuación se muestra un escenario comúnmente utilizado en Unreal Engine 4
1. Primero apague la "exposición automática" de la escena. El valor aquí se puede configurar de acuerdo con su propio valor predeterminado.

![Pasted image 20220324125255](https://user-images.githubusercontent.com/39860733/159846410-f6ff752d-283a-41c4-9fdd-45e8394a5bd6.png)  

#### Configurador mejorado para proporcionar resultados de mayor resolución
![QQ截图20231016195724](https://github.com/MonsterGuo/UE5_NvidiaAnsel/assets/39860733/ba1eb235-7de5-44ab-a0a8-7ecf0be4bd28)


