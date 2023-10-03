# INSTALANDO O WORDPRESS NO PC
Para instalar o WordPress em um ambiente de desenvolvimento local no seu PC, você pode seguir os passos básicos abaixo. Neste exemplo, usaremos o XAMPP, que é um pacote que inclui Apache, MySQL e PHP. Certifique-se de ter o XAMPP instalado antes de prosseguir:

## Passos para instalar o WordPress no seu PC com XAMPP:

1. **Baixe o WordPress**:

   - Acesse o site oficial do WordPress em [https://wordpress.org/download/](https://wordpress.org/download/).
   - Clique no botão "Download" para obter a versão mais recente do WordPress.

2. **Extraia os Arquivos do WordPress**:

   - Após o download, extraia o arquivo ZIP do WordPress para a pasta "htdocs" no diretório de instalação do XAMPP (geralmente em "C:\xampp\htdocs\"). Você pode criar uma subpasta para o seu site WordPress, se desejar.

3. **Crie um Banco de Dados MySQL**:

   - Abra seu navegador web e acesse [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
   - Clique na guia "Databases" (Bancos de Dados).
   - Insira um nome para o seu banco de dados (por exemplo, "wordpress") e clique em "Create" (Criar).

4. **Configure o WordPress**:

   - Abra seu navegador e acesse [http://localhost/sua-pasta-wordpress](http://localhost/sua-pasta-wordpress), onde "sua-pasta-wordpress" é o nome da pasta onde você extraiu os arquivos do WordPress.
   - Siga as instruções de configuração do WordPress para escolher um idioma, configurar informações de conexão com o banco de dados (use o nome do banco de dados, "root" como usuário e deixe a senha em branco) e criar um usuário administrador.

5. **Instale o WordPress**:

   - Após a configuração, clique em "Install WordPress" (Instalar o WordPress) para concluir a instalação.
   - Faça login com as credenciais do usuário administrador que você criou.

Agora, o WordPress está instalado e funcionando em seu ambiente de desenvolvimento local. Você pode começar a criar e personalizar seu site, instalar temas e plugins e realizar testes sem a necessidade de uma conexão à internet. Lembre-se de que este ambiente é apenas para desenvolvimento e teste, e você deve fazer o upload do seu site para um servidor de hospedagem quando estiver pronto para ir ao ar. Certifique-se também de manter seu ambiente local atualizado e fazer backups regularmente.