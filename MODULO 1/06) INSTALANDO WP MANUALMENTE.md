# INSTALANDO O WORDPRESS MANUALMENTE
Instalar o WordPress manualmente envolve alguns passos adicionais em comparação com a instalação usando pacotes como XAMPP ou WAMPP. A seguir, estão as etapas para instalar o WordPress manualmente em um servidor web:

**Pré-requisitos**:

- Um servidor web configurado (como Apache ou Nginx).
- Um banco de dados MySQL configurado.
- Acesso FTP ou SSH ao servidor (para transferir arquivos).

## Passos para instalar o WordPress manualmente:
1. **Baixe o WordPress**:

   - Acesse o site oficial do WordPress em [https://wordpress.org/download/](https://wordpress.org/download/).
   - Clique no botão "Download" para obter a versão mais recente do WordPress.

2. **Extraia os Arquivos do WordPress**:

   - Após o download, extraia o arquivo ZIP do WordPress no seu computador.

3. **Crie um Banco de Dados MySQL**:

   - Acesse o painel de controle do seu servidor de hospedagem ou use um cliente MySQL para criar um banco de dados vazio.
   - Anote as informações de conexão do banco de dados, incluindo o nome do banco de dados, o nome de usuário e a senha.

4. **Configure o arquivo wp-config.php**:

   - Renomeie o arquivo `wp-config-sample.php` na pasta raiz do WordPress para `wp-config.php`.
   - Abra o arquivo `wp-config.php` em um editor de texto e insira as informações do banco de dados que você anotou anteriormente nos campos apropriados.

5. **Faça o Upload dos Arquivos para o Servidor**:

   - Use FTP, SSH ou o gerenciador de arquivos do seu servidor para enviar todos os arquivos do WordPress para o diretório raiz do seu site no servidor.

6. **Conclua a Instalação pelo Navegador**:

   - Acesse seu site no navegador (por exemplo, [http://seusite.com](http://seusite.com)).
   - Você será direcionado para a página de configuração do WordPress.
   - Escolha o idioma e siga as instruções para criar um usuário administrador e configurar as informações do site.

7. **Conclua a Instalação**:

   - Após configurar o WordPress, você terá acesso ao painel de administração.
   - Agora você pode começar a personalizar seu site, instalar temas e plugins e criar conteúdo.

Lembre-se de que a instalação manual do WordPress pode ser mais demorada e requer conhecimentos técnicos, mas oferece mais controle sobre o processo. Certifique-se de seguir as instruções cuidadosamente e manter seu WordPress e plugins atualizados para garantir a segurança do seu site.