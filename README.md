Projeto da DIOS envolvendo ataque de brute force no DVWA para fins educacionais

Este projeto registra a atividade prática que realizei utilizando o DVWA (Damn Vulnerable Web Application) para demonstrar uma vulnerabilidade de Brute Force. Eu utilizei a máquina Metasploitable 2 rodando no IP 192.168.56.101 e fiz todos os testes a partir do Kali Linux.

Primeiro, acessei o DVWA pelo navegador usando o endereço http://192.168.56.101/dvwa
. Em seguida, fiz login na aplicação com as credenciais padrão do DVWA, usando o usuário “admin” e a senha “password”. Depois disso, entrei no módulo “Brute Force” dentro da própria interface do DVWA.

Para testar a vulnerabilidade, tentei realizar um brute force usando ferramentas do Kali. Inicialmente tentei usar o Medusa, mas o módulo http-form não funcionou corretamente. Então continuei os testes validando manualmente as combinações de usuário e senha. A combinação “admin” / “password” funcionou, confirmando que o DVWA estava vulnerável ao ataque de força bruta. Registrei todas as saídas e salvei as evidências dentro da pasta evidence do projeto.

Depois de finalizar os testes, configurei o Git no Kali, iniciei o repositório e fiz o push para o GitHub usando um token de acesso pessoal. Assim, todo o conteúdo do projeto — incluindo os arquivos e as evidências geradas — ficou armazenado no repositório remoto.
