**WINDOWS MYSQL**

![](media/image1.png){width="6.1375in" height="2.3180555555555555in"}No
permite hacer pull pero la red esta bien

Configurar dns manualmente

![](media/image2.png){width="5.927910104986877in"
height="3.510906605424322in"}

Pull exitoso

![Texto El contenido generado por IA puede ser
incorrecto.](media/image3.png){width="5.886237970253719in"
height="2.385749125109361in"}

Instancianciar la imagen mysql:latest

![](media/image4.png){width="6.1375in" height="0.13194444444444445in"}

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser incorrecto.](media/image5.png){width="6.1375in"
height="4.227083333333334in"}

Entrar a mysql

![](media/image6.png){width="5.009706911636045in"
height="2.260731627296588in"}

creamos todas nuestras tablas

![Texto El contenido generado por IA puede ser
incorrecto.](media/image7.png){width="4.512379702537183in"
height="3.07207239720035in"}

![](media/image8.png){width="2.53125in" height="3.5in"}verificar que
todas las tablas se hayan creado correctamente

creamos nuestro sp para los 1000 inserts por
tabla![](media/image9.png){width="5.490277777777778in"
height="4.436805555555556in"}

Seguido de esto lo ejecutamos

![Interfaz de usuario gráfica, Texto El contenido generado por IA puede
ser incorrecto.](media/image10.png){width="4.917352362204724in"
height="1.9794433508311462in"}

Luego de esto lo primero que tenemos que hacer es crear los schemas y
asignarle las tablas

![](media/image11.png){width="5.104421478565179in"
height="2.8361668853893263in"}

Creamos los usuarios y asignamos privilegios

![Texto El contenido generado por IA puede ser
incorrecto.](media/image12.png){width="6.1375in" height="2.625in"}

**WINDOWS SQLSERVER**

Instalamos el contenedor de sqlserver

![](media/image13.png){width="6.1375in" height="0.22569444444444445in"}

Ingresamos al contenedor

![](media/image14.png){width="4.448537839020123in"
height="0.33338035870516186in"}

salimos de ahí y empezamos a instalar dependencias de sqlserver

![Texto El contenido generado por IA puede ser
incorrecto.](media/image15.png){width="6.1375in"
height="1.1479166666666667in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image16.png){width="5.886237970253719in"
height="1.8648436132983377in"}

![](media/image17.png){width="6.1375in" height="0.7243055555555555in"}

![](media/image18.png){width="6.1375in" height="0.6284722222222222in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image19.png){width="6.1375in" height="2.125in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image20.png){width="6.1375in"
height="1.1534722222222222in"}

Después de instalar todas las dependencias y herramientas ejecutamos
sqlserver de forma interactiva y ejecutamos sqlcmd de forma correcta
(con la ruta)

![Texto El contenido generado por IA puede ser
incorrecto.](media/image21.png){width="6.1375in"
height="0.7194444444444444in"}

Lo siguiente es ingresar todo el código de nuestra base de datos

![](media/image22.png){width="6.1375in" height="0.41875in"}

Procedure con los 1000 inserts por tabla

![](media/image23.png){width="4.983766404199475in"
height="3.312361111111111in"}

Creamos los schemas, los logins y usuarios correctamente

![Texto El contenido generado por IA puede ser
incorrecto.](media/image24.png){width="6.1375in"
height="2.0104166666666665in"}

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser
incorrecto.](media/image25.png){width="2.11865157480315in"
height="1.3222779965004374in"}

**WINDOWS POSTGRESQL**

Ahora vamos a ejecutar el contenedor de postgresql de windows

![](media/image26.png){width="6.1375in" height="0.22708333333333333in"}

Ingresamos al contenedor

![Texto El contenido generado por IA puede ser
incorrecto.](media/image27.png){width="5.834146981627296in"
height="0.739686132983377in"}

Creamos nuestras tablas

![Texto El contenido generado por IA puede ser
incorrecto.](media/image28.png){width="6.1375in" height="1.73125in"}

Creamos la función

![Texto El contenido generado por IA puede ser
incorrecto.](media/image29.png){width="6.1375in"
height="1.7486111111111111in"}

Y la llamamos y verificamos

![Texto El contenido generado por IA puede ser
incorrecto.](media/image30.png){width="3.5909306649168853in"
height="5.69865157480315in"}

Creamos schemas pasamos tablas

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser
incorrecto.](media/image31.png){width="4.594390857392826in"
height="2.166969597550306in"}

Y creamos usuarios dándole los respectivos permisos

![Texto El contenido generado por IA puede ser
incorrecto.](media/image32.png){width="4.979861111111111in"
height="1.2293383639545057in"}

![](media/image33.png){width="4.761081583552056in"
height="0.44797900262467194in"}

![Captura de pantalla de un celular El contenido generado por IA puede
ser incorrecto.](media/image34.png){width="3.392416885389326in"
height="1.7465912073490815in"}

**WINDOWS MONGO**

![Texto El contenido generado por IA puede ser
incorrecto.](media/image35.png){width="6.1375in"
height="1.6694444444444445in"}Creamos las coleccioes

![Imagen que contiene Texto El contenido generado por IA puede ser
incorrecto.](media/image36.png){width="2.8391185476815397in"
height="1.5954779090113735in"}

Bucle para 1000 documentos

![Texto El contenido generado por IA puede ser
incorrecto.](media/image37.png){width="3.0168252405949256in"
height="1.164507874015748in"}

Verificamos los documentos por conexión

![Interfaz de usuario gráfica, Aplicación El contenido generado por IA
puede ser incorrecto.](media/image38.png){width="1.5312193788276465in"
height="2.387328302712161in"}

Creamos los "schemas"

![Texto El contenido generado por IA puede ser
incorrecto.](media/image39.png){width="1.9016360454943133in"
height="0.7531966316710411in"}

Pasamos las colecciones a los "schemas"

![Imagen que contiene Patrón de fondo El contenido generado por IA puede
ser incorrecto.](media/image40.png){width="4.441603237095363in"
height="1.3950995188101487in"}

Creamos usuarios

![Texto El contenido generado por IA puede ser
incorrecto.](media/image41.png){width="2.3081911636045493in"
height="2.6883639545056868in"}

Comprobamos que los usuarios se hayan creado

![Texto El contenido generado por IA puede ser
incorrecto.](media/image42.png){width="3.308768591426072in"
height="1.1319477252843395in"}

![Imagen que contiene Texto El contenido generado por IA puede ser
incorrecto.](media/image43.png){width="1.8231714785651794in"
height="0.552159886264217in"}

**UBUNTU OS**

Ejecutamos el contenedor de Ubuntu con todos los puertos que se van a
usar (lógicamente no usamos los puertos que ya tenemos en uso)

![](media/image44.png){width="6.1375in" height="0.41041666666666665in"}

**OS UBUNTU SQLSERVER**

Instalamos dependencias y configuramos repositorios para empezar a
descargar sqlserver

![](media/image45.png){width="6.1375in" height="0.4166666666666667in"}

instalamos mssql-server

![Texto El contenido generado por IA puede ser
incorrecto.](media/image46.png){width="3.8442869641294837in"
height="0.531324365704287in"}

Configuramos área geográfica

![Texto El contenido generado por IA puede ser
incorrecto.](media/image47.png){width="6.1375in"
height="1.3208333333333333in"}

Seleccionamos la zona de horario

![Interfaz de usuario gráfica, Texto El contenido generado por IA puede
ser incorrecto.](media/image48.png){width="2.1252963692038493in"
height="0.7605227471566054in"}

Al final nos pedirá que sigamos con la configuración de nuestro
producto, a todo respondemos yes y seleccionamos la edición developer

![Texto El contenido generado por IA puede ser
incorrecto.](media/image49.png){width="4.7402449693788276in"
height="1.4793733595800524in"}

Configuramos contraseña

![Texto El contenido generado por IA puede ser
incorrecto.](media/image50.png){width="5.229896106736658in"
height="1.802334864391951in"}

Ejecutamos logs

![Texto El contenido generado por IA puede ser
incorrecto.](media/image51.png){width="3.969304461942257in"
height="0.635505249343832in"}

Cuando acaben los logs verificamos los servicios con este comando

![Texto El contenido generado por IA puede ser
incorrecto.](media/image52.png){width="6.1375in"
height="0.7138888888888889in"}

instala las librerías y herramientas de ODBC (Open Database
Connectivity).

![Texto El contenido generado por IA puede ser
incorrecto.](media/image53.png){width="4.3756102362204725in"
height="0.9063768591426071in"}

Aceptamos todo y luego abrimos sqlcmd

![Texto El contenido generado por IA puede ser
incorrecto.](media/image54.png){width="6.1375in"
height="0.5972222222222222in"}

Salimos y volvemos a ejecutar la consola como paso final para
"desbloquear la herramienta"

![Texto El contenido generado por IA puede ser
incorrecto.](media/image55.png){width="6.1375in"
height="0.6083333333333333in"}

Creamos las tablas

![](media/image56.png){width="6.1375in" height="0.20416666666666666in"}

Verificamos la creación de nuestras tablas

![Texto El contenido generado por IA puede ser
incorrecto.](media/image57.png){width="2.3024048556430445in"
height="3.3963068678915134in"}

Cremos nuestro procedure

![Texto El contenido generado por IA puede ser
incorrecto.](media/image58.png){width="6.1375in"
height="0.4791666666666667in"}

A continuación lo ejecutamos

![](media/image59.png){width="3.323170384951881in"
height="2.032665135608049in"}

Creamos los schemas

![Texto El contenido generado por IA puede ser
incorrecto.](media/image60.png){width="5.0490605861767275in"
height="0.9837620297462817in"}

Luego logins, users y asignación de permisos

![Texto El contenido generado por IA puede ser
incorrecto.](media/image61.png){width="4.5047725284339455in"
height="1.8002777777777779in"}

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser
incorrecto.](media/image62.png){width="2.979582239720035in"
height="1.8127526246719161in"}

**UBUNTU MYSQL**

Descargamos mysql en Ubuntu

![Texto El contenido generado por IA puede ser
incorrecto.](media/image63.png){width="5.813311461067366in"
height="0.635505249343832in"}

Ejecutamos el servicio de mysql

![](media/image64.png){width="3.073345363079615in"
height="0.1875262467191601in"}

Verificamos que el servicio este corriendo

![](media/image65.png){width="6.1375in" height="0.5506944444444445in"}

Y ejecutamos mysql

![](media/image66.png){width="4.5815540244969375in"
height="1.6599825021872265in"}

Creamos la base de datos y las tablas en ella

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser
incorrecto.](media/image67.png){width="4.196301399825022in"
height="3.060832239720035in"}

Creamos procedure

![Texto El contenido generado por IA puede ser
incorrecto.](media/image68.png){width="4.083903105861768in"
height="2.437840113735783in"}

Ejecutamos

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser
incorrecto.](media/image69.png){width="4.6360640857392825in"
height="1.9273523622047244in"}

Creamos schemas y pasamos tablas

![Texto El contenido generado por IA puede ser
incorrecto.](media/image70.png){width="3.534468503937008in"
height="2.6810444006999123in"}

Luego usuarios y permisos

![Interfaz de usuario gráfica, Texto El contenido generado por IA puede
ser incorrecto.](media/image71.png){width="4.8166262029746285in"
height="2.0642694663167105in"}

**Conectamos**

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser
incorrecto.](media/image72.png){width="3.277195975503062in"
height="2.4521489501312335in"}

**UBUNTU OS MONGO**

Agregamos la clave gpg de mongo

![](media/image73.png){width="6.1375in" height="0.5791666666666667in"}

Añadimos repositorio de mongo

![](media/image74.png){width="6.1375in" height="0.38472222222222224in"}

Actualizamos directorios

![](media/image75.png){width="3.656760717410324in"
height="0.4375612423447069in"}

Descargamos mongo y tratamos de iniciar el servicio

![Interfaz de usuario gráfica, Texto El contenido generado por IA puede
ser incorrecto.](media/image76.png){width="4.708990594925634in"
height="0.8021948818897637in"}

Abrimos otra consola, verificamos que el servicio este corriendo y
entramos a mongo db

![](media/image77.png){width="6.1375in" height="1.538888888888889in"}

Usamos feria, creamos la colecciones y documentos. Y ejecutamos el bucle
de las 1000 inserciones

![](media/image78.png){width="6.1375in" height="0.7458333333333333in"}

Creamos "schemas" y pasamos colecciones. Usuarios con sus permisos

![](media/image79.png){width="4.084810804899387in"
height="2.2748851706036746in"}

verificamos inserts

![Texto El contenido generado por IA puede ser
incorrecto.](media/image80.png){width="4.496212817147857in"
height="5.8560433070866145in"}

![](media/image81.png){width="2.96916447944007in"
height="0.1875262467191601in"}

![](media/image82.png){width="2.1461329833770777in"
height="0.21878062117235345in"}

![](media/image83.png){width="3.3546347331583553in"
height="0.14585411198600176in"}

![](media/image84.png){width="5.75080271216098in"
height="0.46881561679790024in"}

![Aplicación El contenido generado por IA puede ser
incorrecto.](media/image85.png){width="2.6253663604549433in"
height="1.2605927384076991in"}

**UBUNTU OS POSTGRES**

Actualizamos directorios y descargamos PostgreSQL

![Texto El contenido generado por IA puede ser
incorrecto.](media/image86.png){width="5.063206474190726in"
height="0.718850612423447in"}

Creamos directorios necesarios

![](media/image87.png){width="2.5524398512685913in"
height="0.16668963254593175in"}

![](media/image88.png){width="6.1375in" height="0.42986111111111114in"}

Inicializamos el servicio de postgres

![](media/image89.png){width="6.1375in" height="0.41388888888888886in"}

Ingresamos a la consola de postgres

![](media/image90.png){width="4.415714129483814in"
height="2.0794520997375328in"}

Creamos base de datos y tablas

![](media/image91.png){width="6.1375in" height="0.3472222222222222in"}

![](media/image92.png){width="3.466890857392826in"
height="2.6703412073490815in"}

Creamos funcion

![Texto El contenido generado por IA puede ser
incorrecto.](media/image93.png){width="4.354774715660542in"
height="2.344076990376203in"}

Ejecutamos funcion y verificamos

![Interfaz de usuario gráfica, Aplicación El contenido generado por IA
puede ser incorrecto.](media/image94.png){width="2.45544728783902in"
height="2.2390102799650045in"}

Creamos schemas, usuarios y gestión de permisos

![Interfaz de usuario gráfica, Texto El contenido generado por IA puede
ser incorrecto.](media/image95.png){width="4.010976596675415in"
height="3.3754713473315836in"}

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser
incorrecto.](media/image96.png){width="4.813171478565179in"
height="2.6253663604549433in"}

![](media/image97.png){width="4.698572834645669in"
height="0.3021259842519685in"} apt update, apt install nano -y

![Texto El contenido generado por IA puede ser
incorrecto.](media/image98.png){width="5.84456583552056in"
height="0.9167946194225722in"}

Detenemos el servicio

![](media/image99.png){width="6.1375in" height="0.29375in"}

Y lo iniciamos para que lea el archivo y se apliquen las nuevas
configuraciones

![](media/image100.png){width="6.1375in" height="0.28402777777777777in"}

MODIFICAMOS PUERTOY LISENT ADRESS

![Texto El contenido generado por IA puede ser
incorrecto.](media/image101.png){width="6.1375in"
height="1.1981977252843394in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image101.png){width="0.8027482502187226in"
height="0.4239238845144357in"}

**Docker in Docker**

Ejecutamos contenedor con privilegios especiales

![](media/image102.png){width="6.1375in" height="0.5034722222222222in"}

Instalamos docker

Apt update

![](media/image103.png){width="3.3650524934383204in"
height="0.27087160979877517in"}

Ejecutamos el docker demon

![](media/image104.png){width="2.3128226159230096in"
height="0.45839676290463693in"}

**DIND POSTGRESQL**

Ejecutamos el contenedor de PostgreSQL

![](media/image105.png){width="6.1375in" height="0.18958333333333333in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image106.png){width="5.521604330708661in"
height="0.7917771216097987in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image107.png){width="2.6726706036745407in"
height="1.2189206036745406in"}

![Interfaz de usuario gráfica, Texto El contenido generado por IA puede
ser incorrecto.](media/image108.png){width="2.3970516185476813in"
height="0.8643646106736658in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image109.png){width="3.2921259842519683in"
height="0.8959580052493439in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image110.png){width="3.7050853018372703in"
height="0.9044542869641294in"}

![](media/image111.png){width="6.1375in" height="1.6034722222222222in"}

**DIND SQLSERVER**

creamos el contenedor de sqlserver

![](media/image112.png){width="6.1375in" height="0.2263888888888889in"}

ejecutamos el contenedor y abrimos sqlcmd

![](media/image113.png){width="6.1375in" height="0.5472222222222223in"}

![](media/image114.png){width="6.1375in" height="1.1243055555555554in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image115.png){width="4.469373359580053in"
height="0.7605227471566054in"} ![Imagen que contiene Interfaz de usuario
gráfica El contenido generado por IA puede ser
incorrecto.](media/image116.png){width="1.5496456692913385in"
height="0.7284055118110236in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image117.png){width="2.5491568241469817in"
height="2.148665791776028in"}

![Interfaz de usuario gráfica, Texto El contenido generado por IA puede
ser incorrecto.](media/image118.png){width="2.96916447944007in"
height="1.9273523622047244in"}

**DIND MONGO**

![](media/image119.png){width="6.1375in" height="0.37083333333333335in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image120.png){width="4.625645231846019in"
height="0.6875962379702537in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image121.png){width="4.744451006124234in"
height="2.5196522309711287in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image122.png){width="4.696288276465442in"
height="1.1694313210848644in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image123.png){width="3.2684306649168855in"
height="1.6574507874015747in"}

![Imagen que contiene Interfaz de usuario gráfica El contenido generado
por IA puede ser
incorrecto.](media/image124.png){width="1.698153980752406in"
height="0.7501049868766404in"}

**DIND MYSQL**

Creamos el contenedor de mysql

![](media/image125.png){width="6.1375in" height="0.3326388888888889in"}

Entramos al contenedor

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser
incorrecto.](media/image126.png){width="4.64658573928259in"
height="1.7657031933508311in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image127.png){width="3.1003357392825897in"
height="1.3798195538057743in"} ![Texto El contenido generado por IA
puede ser incorrecto.](media/image128.png){width="3.5213243657042868in"
height="1.1355752405949255in"}

![Imagen que contiene Interfaz de usuario gráfica El contenido generado
por IA puede ser
incorrecto.](media/image129.png){width="3.966486220472441in"
height="0.9938013998250219in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image130.png){width="2.723844050743657in"
height="1.0420078740157481in"}

![Texto El contenido generado por IA puede ser
incorrecto.](media/image131.png){width="4.3547342519685035in"
height="1.3751782589676291in"}

![Interfaz de usuario gráfica, Texto, Aplicación El contenido generado
por IA puede ser incorrecto.](media/image132.png){width="6.1375in"
height="4.550694444444445in"}

La instalación de mongo en Linux se me complico un poco entro en un
bucle y me toco cerrar la ventana pero por suerte funciono

Tenia el sistema dañado de tantos intentos para descargar sqlserver

dpkg \--purge \--force-all mssql-server

rm -rf /opt/mssql /var/opt/mssql

rm /etc/apt/sources.list.d/mssql-server.list

recupere paquetes dañados

echo -e \"Package: base-files\\nStatus: install ok installed\\nPriority:
required\\nSection: admin\\nInstalled-Size: 0\\nMaintainer: Ubuntu
Developers \<ubuntu-devel-discuss@lists.ubuntu.com\>\\nArchitecture:
amd64\\nVersion: 1\\nDescription: Minimal dpkg status file to recover
apt\" \> /var/lib/dpkg/status

apt-get update

configuración para el repositorio de mongo

curl -fsSL https://pgp.mongodb.com/server-6.0.asc \| gpg \--dearmor -o
/usr/share/keyrings/mongodb-server-6.0.gpg

echo \"deb \[signed-by=/usr/share/keyrings/mongodb-server-6.0.gpg\]
https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/6.0 multiverse\"
\> /etc/apt/sources.list.d/mongodb-org-6.0.list

apt-get update

arregle dependencias rotas

wget
https://launchpad.net/ubuntu/+archive/primary/+files/libssl1.1_1.1.1f-1ubuntu2.24_amd64.deb

dpkg -i libssl1.1_1.1.1f-1ubuntu2.24_amd64.deb

arranque manual (aquí entro en bucle)

mkdir -p /data/db

mongod \--dbpath /data/db

Y finalmente

![](media/image133.png){width="6.1375in" height="4.779166666666667in"}

COMANDOS UTILIZADOS

Docker images: visualizar las imágenes instaladas

docker pull: descargar imagen

docker run \--name mysql-feria -e MYSQL_ROOT_PASSWORD=feria -e
MYSQL_DATABASE=feria -p 3306:3306 -d mysql:latest: comando para
instanciar la imagen y generar el contenedor de mysql

docker run: instanciar imagen, echar a correr el contrenedor

\--name mysql-feria: asignarle nombre del contenedor\
-e MYSQL_ROOT_PASSWORD=feria: contraseña de usuario root\
-e MYSQL_DATABASE=feria: creación de la base de datos feria -p
3306:3306: asignar puerto\
-d mysql:latest: imagen instanciada, y dando la orden para que se
ejecute el contenedor en segundo plano \"detached\" con -d

show tables: muestra todas las tablas

docker attach Ubuntu_docker: entrar a la terminal de Linux obviamente
primero hay que iniciarlo

docker start: inicializar contenedores.\
**-i (interactive):** Mantiene la entrada estándar abierta, lo que
permite interactuar con la terminal.

**-t (tty):** Asigna una pseudo-TTY (terminal), lo que hace que la
experiencia de la *shell* sea funcional.

Comando para descargar sqlserver en el os de Ubuntu

apt update && apt install -y gnupg wget

apt update && apt install -y curl apt-transport-https && curl
https://packages.microsoft.com/keys/microsoft.asc \| apt-key add - &&
add-apt-repository \"\$(wget -qO-
https://packages.microsoft.com/config/ubuntu/20.04/mssql-server-2019.list)\"
&& apt update && apt install -y mssql-server

actualizamos paquetes e instalamos postgres

apt update

apt install -y postgresql postgresql-contrib

añadir usuario postgresql

useradd -m -s /bin/bash postgres

preparamos directorios:

mkdir -p /var/lib/postgresql/data

chown -R postgres:postgres /var/lib/postgresql

mkdir -p /var/run/postgresql

chown postgres:postgres /var/run/postgresql

arrancamos motor manualmente(debemos conocer la version de nuestro
postgresql

ls /usr/lib/postgresql/):

/usr/lib/postgresql/16/bin/pg_ctl -D /var/lib/postgresql/data -l logfile
start

Ingresamos a postgres: Psql

Cremos nuevo volumen

![](media/image33.png){width="4.761081583552056in"
height="0.44797900262467194in"}

Duplicamos voplumen

docker run \--rm -v pgdata_feria:/from -v
\$(pwd)/pgdata_feria_ubuntu:/to alpine sh -c \"cp -a /from/. /to/\"

duplicamos volumen de mongo

docker run \--rm -v mongo_feria_data:/from -v
mongo_feria_data_ubuntu:/to alpine ash -c \"cd /from && cp -a . /to\"

descargar mongo en Linux ubuntu

apt-get update && apt-get install -y gnupg curl && curl -fsSL
https://pgp.mongodb.com/server-6.0.asc \| gpg \--dearmor -o
/usr/share/keyrings/mongodb-server-6.0.gpg && echo \"deb \[
signed-by=/usr/share/keyrings/mongodb-server-6.0.gpg \]
https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/6.0 multiverse\"
\| tee /etc/apt/sources.list.d/mongodb-org-6.0.list && apt-get update &&
apt-get install -y mongodb-org

GLOSARIO

**DNS (Domain Name System)** Imagina que es como la libreta de teléfonos
de internet. Cuando tú quieres llamar a alguien, no memorizas su número
completo, memorizas su nombre. El DNS hace exactamente eso: convierte
nombres fáciles de recordar (como \"google.com\") en direcciones
numéricas que las computadoras entienden (como \"142.250.185.46\"). Sin
DNS, tendrías que memorizar números largos para cada sitio web.

**Network** Es simplemente una red de computadoras conectadas entre sí,
como una telaraña. Así como las personas en una ciudad se comunican
mediante teléfono, email o en persona, las computadoras en una red se
comunican compartiendo información. Pueden ser desde 2 computadoras
hasta millones en internet.

**Bridge** Es como un puente que conecta dos redes diferentes para que
se comuniquen. Imagina dos pueblos separados por un río: el puente
permite que la gente de un pueblo viaje al otro. Un bridge en networking
hace lo mismo: permite que dispositivos de una red se conecten y
compartan información con dispositivos de otra red, traduciendo entre
ellos si es necesario.
