# Criação de um repositório



Para criar um repositório no Github com arquivos criados através de sua máquina utilizando o GIT, é preciso seguir alguns passos:



- Executar o programa no local onde será criada a pasta, clicando com o botão direito do mouse e selecionando **Git Bash Here**:
  
  ![](C:\Users\dougl\AppData\Roaming\marktext\images\2022-01-06-17-08-25-image.png)

- Com o terminal Git aberto, iremos criar uma pasta utilizando o comando **mkdir** e em seguida o nome da pasta;
  
  > **IMPORTANTE:** O nome não deve contér nenhuma acentuação



- Após criar a pasta, usamos o comando **touch README.md** para criarmos o arquivo que será a "capa" do repositório;
  
  > O comando echo também é valido no lugar de touch
  
  

- Iremos usar o comando **git init** para criar o repositório git;



- Precisamos agora adicionar o arquivo README.md ao estágio **staged**, ou seja, prepara-lo para upload no diretório GITHUB. Para isso, usamos o comando **git add**  seguido pelo nome do arquivo, neste caso **git add README.md**;

> O mesmo comando pode ser utilizado como git add * para que todos os arquivos que estejam nesta pasta sejam preparados.



- O arquivo está pronto para ser adicionado ao repositório no GITHUB, para isso é preciso que antes seja adicionado informações parao envio, utilizando o comando **git commit -m " Informações sobre o arquivo"**;

> É necessário o uso das aspas quando iremos digitar algum texto. Exemplo para o caso: git commit -m "Envio do arquivo readme"



- Neste ponto, em sua conta no GitHub acesse "seus diretorios" e crie um novo diretório para upload dos arquivos. Com o diretório criado, copie o caminho do diretório e o adicione no terminar após o comando **git remote add origin** 

> Exemplo: **git remote add origin git@github.com:DouglasCanto/notes.git**



- Após isso usamos o comando **git push -u origin main** para que os arquivos sejam encaminhados ao diretório. Será necessário confirmar o envio e informar sua senha criada.



O arquivo readme aparecerá no seu diretório no Github contendo todas as informações que possuir nele como a capa.


