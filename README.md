# administra-omdmintune
## **Administração de dispositivos MacOS e Windows via intune.**

Este projeto tem como objetivo trazer scripts e manual de como administrar dispositivos MacOS e Windows atraves do Microsoft Intune. 

Durante minha experiencia como administrador de ambiente de computadores com esses dois sistemas operacionais, enfrentei alguns desafios com solicitações que vinham de outras áreas e meus superiores que não tinham de forma clara e objetiva nos foruns e outros githubs. 

Então resolvi abrir este projeto para centralizar estas informações e disponibilizar de maneira simples e com casos de uso de aplicação de cada situação. 

### **Alguns topicos que iremos ver.**

#### **Windows**

    - Aplicação de patch de atualização atraves do intune, porém buscando as atualizações e reportando os status para um WSUS.

    - Efetuar uma busca dos usuários que compoem o grupo administrador das maquinas locais e guarda esta informação em um txt. E fazer o tratamento destas informações. 

    - Remover usuários de dominio que estão no grupo administrador local dos dispositivos, e sempre validar e remover (caso tenha sido incluido novamente) a cada checkin que o dispositivo fizer.

    - Criar usuários locais nos dispositivos e definir a senha, e resetar a senha deles a cada X dias. 

#### **MacOS**

    - Aplicar wallpaper na área de trabalho. 

    - Aplicar wallpaper na tela de bloqueio (screensaver)


Quanto ao Linux ainda esta muito limitado a questão de administração via Microsoft Intune, mas irei abrir um outro repositorio com algumas instruções de como instalar o Microsoft Defender e configurar para que ele tenha resposta a incidentes e reporte para a console do Defender. Atualmente via intune conseguimos somente ingressar e impor algumas politicas de conformidade. 


