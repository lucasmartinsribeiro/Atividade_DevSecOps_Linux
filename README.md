# Atividade realizada durante o estágio na Compass - DevSecOps #

- Esse repositório tem como objetivo mostrar questões de Linux e Máquinas Virtuais.
- Desenvolvido por: Lucas Martins Ribeiro

# Instalação do linux #
  - Utilize a última versão estável disponibilizada do Oracle Linux: https://yum.oracle.com/oracle-linux-isos.html

#Vídeo do youtube que me ajudou na instalação
  - Link do vídeo: https://www.youtube.com/watch?v=mAijCMUY6CY&t=980s

# Idioma #
  - Escolha o idioma english como linguagem padrão do sistema.
  - Entre no campo Keyboard, retire o idioma english(us) e coloque portuguese(brazil).
  
# Configuração de rede #
  - Entre no campo "Network & Host name" para habilitar conexão de internet, clique no campo OFF, depois espere ele mudar para ON.

# Criando uma senha e Criando um novo usuário #
  - No menu principal de instalação do Linux, você notará  que tem dois campos Root Password e User Creation.
  - Para criar uma senha para o usuário root, clique em Root Password e digite a senha que escolher.
  - Para criar um usuário para acessar o terminal, acesse User Creation.
  
# Instalação e atualização de pacotes #
  - Importante sempre ao inicar a sessão rodar yum update e yum upgrade para começar a baixar outras ferramentas para evitar problemas futuros com atualizações!
  
# Mudar hostname #
  - Edite o arquivo /etc/hostname: vi /etc/hostname
  - Depois reinicie a máquina.
  
# Configurando ssh #
  - Instale o ssh: sudo yum install openssh-server
  - Para ativar o ssh: systemctl enable sshd
  - Para dar um restart no ssh: systemctl restart sshd

# Slide de Apresentação #
 - Link do slide: https://docs.google.com/presentation/d/1SPmTSgbefHYbRpJ9_Z5jiwKYWDLdFiFK/edit?usp=sharing&ouid=102601889449489509661&rtpof=true&sd=true
