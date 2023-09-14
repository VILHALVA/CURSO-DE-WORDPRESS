# FAZENDO MIGRAÇÃO DE UM SITE
Migrar um site WordPress de um servidor ou domínio para outro é uma tarefa importante e sensível que requer cuidado para evitar a perda de dados ou problemas de funcionamento. Aqui estão as etapas gerais para realizar a migração de um site WordPress:

**1. Faça Backup do Site Atual:**
- Antes de iniciar qualquer migração, faça backup de todos os arquivos do seu site e do banco de dados. Você pode usar plugins de backup como o UpdraftPlus ou fazer backups manualmente pelo painel de controle do seu provedor de hospedagem.

**2. Configuração do Novo Ambiente:**
- Configure o novo servidor ou hospedagem onde você deseja migrar o site. Isso pode incluir a criação de um banco de dados vazio e a configuração do servidor web.

**3. Exporte o Banco de Dados:**
- Acesse o phpMyAdmin no seu painel de controle de hospedagem ou use uma ferramenta de gerenciamento de banco de dados para exportar o banco de dados do site atual. Salve o arquivo SQL em seu computador.

**4. Transfira os Arquivos do Site:**
- Use um cliente FTP (como FileZilla) para transferir todos os arquivos do seu site (pasta wp-content, arquivos principais do WordPress, temas, plugins, uploads, etc.) para o novo servidor ou hospedagem.

**5. Importe o Banco de Dados:**
- No novo ambiente, importe o arquivo SQL que você exportou anteriormente. Isso pode ser feito usando o phpMyAdmin ou uma ferramenta semelhante.

**6. Atualize o arquivo wp-config.php:**
- No novo ambiente, verifique se o arquivo `wp-config.php` está configurado corretamente para se conectar ao novo banco de dados.

**7. Corrija URLs e Caminhos:**
- É importante atualizar as URLs e caminhos no banco de dados para refletir o novo domínio ou caminho, caso tenha mudado. Você pode usar um plugin como o "Better Search Replace" para fazer isso de maneira eficiente.

**8. Atualize as Permissões de Arquivos:**
- Certifique-se de que as permissões de arquivos no novo servidor estejam corretamente configuradas para garantir que o WordPress possa escrever e ler os arquivos e diretórios necessários.

**9. Teste o Novo Site:**
- Antes de direcionar o domínio ao novo ambiente, teste o site para garantir que tudo funcione corretamente. Isso inclui navegar pelas páginas, testar formulários e verificar a funcionalidade geral.

**10. Aponte o Domínio:**
- Atualize as configurações de DNS ou aponte o domínio para o novo servidor/hospedagem. Isso pode levar um tempo para propagar, então seja paciente.

**11. Realize Testes Finais:**
- Após a propagação do DNS, teste novamente o site para garantir que ele funcione perfeitamente no novo ambiente.

**12. Monitore e Corrija Problemas:**
- Monitore o site nos dias seguintes à migração para garantir que não ocorram problemas inesperados. Esteja preparado para corrigir qualquer problema que surja.

Lembre-se de que a migração de um site WordPress pode ser complexa, especialmente se você não estiver familiarizado com a configuração de servidores e bancos de dados. Se você não se sente confortável fazendo isso sozinho, considere a contratação de um profissional ou serviço especializado em migração de sites WordPress para garantir um processo tranquilo e sem problemas.