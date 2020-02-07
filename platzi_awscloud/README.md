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

### []()
