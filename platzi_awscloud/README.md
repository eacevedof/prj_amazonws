### [¿Cómo puedo empezar a usar AWS?](https://platzi.com/clases/1323-aws-cloud/12574-como-puedo-empezar-a-usar-aws/)
- ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/7aff613ae8b5ec4e8822b2fa4fc96f5b/image.png)
- ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/0a7c6bec382cecf271eddf91e7f83c86/image.png)
  - *NOTA* En este punto ya debes de tener un link de activación en la cuenta de email con lo que puedes utilizar los servicios de amazon sin necesidad de poner una CC.
- ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/b65848664cf702390ffd5d871fa254d5/image.png)
- Beca. https://aws.amazon.com/grants
- Con este plan (si justifcas que eres estudiante) amazon te da 30$ para que puedas probar los nuevos servicios que van saliendo.
- La beca dura un año
- ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/c880ec1c27249a264c7f6c7ebd05f24a/image.png)
- ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/433093fc3a9db525631c66ebdb0d5a3a/image.png)
- ![https://passwordsgenerator.net/](passwordsgenerator.net.)

### [Introducción a la oferta de servicios de AWS y sus aplicaciones](https://platzi.com/clases/1323-aws-cloud/12575-introduccion-a-la-oferta-de-servicios-de-aws-y-sus/)
- Computo
- Storage
- Database
- Migration
- Networking & content
- Developer Tools
  - X-Ray ayuda a ver que es lo que está pasando en la app mientras está funcionando
- Management tools
  - Cloudwatch Recursos de la maquina
  - CloudTrait Logs de eventos de todas las maquinas
- Media services
  - Elastic transcode Sirve para hacer streaming
- Machine Learning
  - Rekognition interpreta lo que estas viendo
- Analytics
  - cuanta ram esta usando cada visitante, etc.
- Security, Identity & Compliance
  - IAM gestor de cuentas por roles
  - Guardduty  Recuento de accesos de red que han habido. Sirve para detectar ataques
- Mobile services
  - Crear servicios moviles de manera más sencilla
- AR & VR
  - Realidad virtual
- Application integration
  - Automatizacion de rutinas, enviar emails.
- Customer engagement
  - mas para empresas, cuentas de correo
- Business productivity
- Desktop & App streaming
  - Maquinas virtuales customizadas de recursos limitadas asociadas a n usuarios
- Internet of things
  - Puede proveer de hardware 
- Game development
  - Crear juegos

### [Ejemplo de arquitectura con Elastic Beanstalk](https://platzi.com/clases/1323-aws-cloud/12576-ejemplo-de-arquitectura-con-elastick-beanstalk/)
- ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/7b138c276e40bb3fe177b5d7accae870/image.png)
- Elastic load balancer permite configurar https con el certificado que decidas
- En amazon puedes crear un servicio por ssl sin necesidad de comprar un certificado, ya que el certificado que creas en amazon va a ser compatible con la mayoria de navegadores y móviles.
- El cliente se conecta a una IP PUBLICA que es la de ELB (elastic load balancer)
- Pasando el ELB podria ir a una instancia concreta que esta en distintas regiones del mundo
- Las instancias son servidores de aplicaciones
- ELB se conecta con CLOUD WATCH (el chivato de la salud de tus instancias)
- ELB provee una API que permite hacer modificaciones sobre Beanstalk esto mismo se puede llevar a cabo usando AWS Management console.
- Amazon tiene su propio DNS, permite hacer cambios de IT de manera muy sencilla
- Sistema de alta disponibilidad

### [¿Qué es EC2?](https://platzi.com/clases/1323-aws-cloud/12577-que-es-ec2/)
- EC2 son maquinas virtuales en linea 
- Instancias:
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/f2e8a990ff040aca145df18ee853e208/image.png)
  - Se pueden crear distintas llasves 
- El espacio:
  - Es económico, para desarrollo con 8 GB de hdd es suficiente. Se puede ampliar a posteriori
- ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/951e4c7e27f337bf811d4b92ccebfea9/image.png)
- Redundancia:
  - El datacenter lo puedes tener en distintas regiones
  - Se hace snapshot de una maquina y se mueve a otra region
- Firewall:
  - Se puede configurar el firewall para que una maquina este donde esté se pueda conectar siempre
  - Se puede configurar distintas reglas
- IPS ESTATICAS:
  - Cada instancia tiene una IP Publica y Privada (para dentro de amazon)
  - Por más que se tenga una IP dinamica en una instancia siempre que la instancia exista conservara la misma IP
- ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/85164e76fb9d085cb65f78dec04990c8/image.png)
- Migracion y snapshot:
  - Los respaldos se pueden hacer como snapshots para puntos de retorno
  - Se pueden mover de regiones para backups
- Se puede cambiar en caliente el tamaño de la RAM

### [Creando una instancia de EC2](https://platzi.com/clases/1323-aws-cloud/12578-creando-una-instancia-de-ec2/)
- ![](https://trello-attachments.s3.amazonaws.com/5e3de4638099128d5381b037/1002x524/5cb9545ce9449e55ea22bbd6f2df2892/image.png)
- ![](https://trello-attachments.s3.amazonaws.com/5e3de4638099128d5381b037/1122x534/34bd8a1fe7e7f0603b8e3d5ea2d3d95e/image.png)
  - Hay que activar la cuenta (revisar email)
  - Hay que aplicar el código enviado 
  - Se necesita tarjeta de credito o debito, seleccionar el plan gratuito
- ![](https://trello-attachments.s3.amazonaws.com/5e3de4638099128d5381b037/1006x626/78639ed16b711200bd3236d862f0a4db/image.png)
  - EC2 dashboard
  - Crear instancia
  - Activar "Free tier only"
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/5a031b783f8a51599eb1f5e2a59e7591/image.png)
  - La version gratuita cuenta con menos ofertas pero aun así tiene una variedad considerable de sistemas.
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/30eb50680923ca118d2cd1a81f7ab15e/image.png)
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/f9e777614e3c011e2d62aa91f6239df7/image.png)
    - Aqui nos indica cual es la gratuita
- Ahora toca configurar algunas cosas:
  - En esta pantalla no se hace realmente nada, todo está bien por defecto
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/0ca95257496b0d8012ec48b72e17ee49/image.png)
- Storage:
  - Se muestra un DD de 8 GB que es el plan gratuito, no hay que cambiarlo
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/a14e11daec4904b883bfea9d93786931/image.png)
- Tag:
  - Insertamos una etiqueta descriptiva que nos permita reconocer facilmente la instancia y/o sus caracteristicas
  - Son varios items de clave=>valor
  - Ejemplo: Name: PlatziLab
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/896e310b447247c888e5e5261888414e/image.png)
- Security Group:
  - Aqui podemos controlar el acceso a la máquina
  - En el ejemplo, el grupo: "platzi-solo-ssh" solo va a tener activado SSH con conexion desde cualquier ip
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/3bea3af75ca6e8619073587c59e7039b/image.png)
- Review:
  - Muestra un resumen de lo configurado previamente 
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/8172ac4c1b970d9e6324f82153005ce8/image.png)  
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/da44170cb5918384c5c88203d7f1fd9c/image.png)
  - La gratuita solo tiene un CPU y 1 GB de RAM
- Posteriormente modificaremos la conf para que de servicios
- Definimos una clave de conexión
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/5785cee2caa8224362a32ff9436717fa/image.png)
  - Descargamos el fichero **.pem**
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/7a5232c4ef26db4dc0f086cc4388e703/image.png)
- Lanzamos la instancia:
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/3510c1a5727f94bdae35ca949947abfa/image.png)
  - Vemos el número de identificación, si hacemos click vamos a la consola:
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/626c3376fb880640030e78ae008cd873/image.png)
- Nos indica que la instancia está corriendo pero todavia no está lsita
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/dfc273cb992beabebf6520d054536c60/image.png)
- **Elastic IP**:
  - IP fija, puedes rentar una IP que la puedes asignar a tu instancia u otras. Si tienes un DNS que no está en amazon puedes asignar en tu DNS esta IP. Posteriormente, en Amazon, puedes ir cambiando de maquina sin que se vea afectado tu DNS y sin que se vean afectaados los usuarios que están accediendo a esa maquina a traves de un dominio
  - ![](https://trello-attachments.s3.amazonaws.com/5b014dcaf4507eacfc1b4540/5e3de4638099128d5381b037/42fce76173b0977b6caa93bb77076c44/image.png)
- Despues de que acabe la inicialización de la maquina, veremos como instalar el SO, instalar algún lenguaje de programación, un editor de textos, etc.
### [Conectándonos a nuestra instancia desde Windows](https://platzi.com/clases/1323-aws-cloud/12579-conectandonos-a-nuestra-instancia-desde-windows/)





