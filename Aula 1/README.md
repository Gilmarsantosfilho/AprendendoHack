                            <h3><p align="center">Fake Bank:</p></h3> 


<h3><p align="center">Antes de entrar nas carreiras de segurança cibernética e o que é segurança ofensiva, vamos hackear (e sim, é  legal,  todos os exercícios são simulações falsas </p></h3>

Seu primeiro hack

Clique no botão "Iniciar máquina". Uma vez carregado no Split View no seu navegador, você terá acesso a uma máquina que usará para hackear um aplicativo bancário falso chamado FakeBank. Se você não vir a máquina aparecer, use o botão azul Mostrar visualização dividida no canto superior direito desta página.

Usaremos um aplicativo de linha de comando chamado "GoBuster" para forçar o site do FakeBank a encontrar diretórios e páginas ocultos. O GoBuster fará uma lista de possíveis nomes de páginas ou diretórios e tentará acessar um site com cada um deles; se a página existir, ela informa.

Etapa 1) Abra um terminal

Um terminal, também conhecido como linha de comando, nos permite interagir com um computador sem usar uma interface gráfica de usuário. Na máquina, abra o terminal usando o ícone Terminal:  

Etapa 2) Encontre páginas ocultas do site

A maioria das empresas terá uma página de portal de administração, dando à sua equipe acesso a controles administrativos básicos para operações do dia-a-dia. Para um banco, um funcionário pode precisar transferir dinheiro de e para contas de clientes. Muitas vezes, essas páginas não são privadas, permitindo que os invasores encontrem páginas ocultas que mostram ou dão acesso a controles administrativos ou dados confidenciais.

Digite o seguinte comando no terminal para encontrar páginas potencialmente ocultas no site do FakeBank usando o GoBuster (um aplicativo de segurança de linha de comando).
-------------------

Comando GoBuster para páginas de sites de força bruta
ubuntu@tryhackme:~/Desktop$ gobuster -u http://fakebank.com -w wordlist.txt dir  =====================================================
Gobuster v2.0.1
=====================================================
[+] Mode         : dir
[+] Url/Domain   : http://fakebank.com/
[+] Threads      : 10
[+] Wordlist     : wordlist.txt
[+] Status codes : 200,204,301,302,307,403
[+] Timeout      : 10s
=====================================================
2022/04/11 18:23:28 Starting gobuster
=====================================================
/images (Status: 301)
/DIRECTORY_NAME_OUTPUT (Status: 200)
=====================================================
2022/04/11 18:23:38 Finished
=====================================================

No comando acima, -ué usado para indicar o site que estamos verificando, -wleva uma lista de palavras para iterar para encontrar páginas ocultas.

Você verá que o GoBuster verifica o site com cada palavra da lista, encontrando as páginas que existem no site. O GoBuster terá informado as páginas encontradas na lista de nomes de páginas/diretórios (indicados por Status: 200).

----------------
Passo 3) Hackeie o banco

Você deve ter encontrado uma página secreta de transferência bancária que permite transferir dinheiro entre contas no banco (/bank-transfer). Digite a página oculta no site do FakeBank na máquina.
---------------------

Esta página permite que um invasor roube dinheiro de qualquer conta bancária, o que é um risco crítico para o banco. Como um hacker ético, você (com permissão) encontraria vulnerabilidades em seu aplicativo e as reportaria ao banco para corrigi-las antes que um hacker as explorasse.

Transfira $ 2000 da conta bancária 2276 para sua conta (conta número 8881).


                            <h3><p align="center">Agora é a reposta:</p></h3> 
   
 Responda as questões abaixo
 
After transferring money to your account, go back to your bank account page. What is the answer shown on your bank balance page?
Responsta: BANK-HACKED

-----------------------------------------------------------
Agora essa você tem que ler para depois "Submit" 

```
Agora Aula 2
```
