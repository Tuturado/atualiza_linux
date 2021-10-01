## Script Simples criado para atualizar o Linux :computer:
Criado para atualização do linux de maneira mais rápida, pode ser adicionado ao iniciar o sistema.


## Modo de uso :hammer_and_wrench:
Antes de usar efetivamente é necessário forneceer permissão para o arquvio ser executado, vá até o diretório onde ele se ecnontra e execute o comando: "chmod 777 atualiza.sh";
Dessa maneira ele vai ter a permissão necessária para executar as atualizações.
Para usar basta ir até o local onde se encontra o scipt e executar o seguinte comando: "./atualiza.sh"

## Colocando para Inicializar junto ao sistema
Para iniciar junto ao sistema é necessário mover o arquivo para o diretório "/etc/init.d."

Primeiro vá até o diretório onde se encontra o script de atualização, depois mova para o diretório necessário com o seguinte comando: "mv atualiza.sh /etc/init.d"

Após o arquivo estar no diretório é necessário executar o seguinte comando: update-rc.d atualiza.sh defaults

Pronto, agora todas as vezes que seu sistema linux iniciar ele automáticamente executará as atualizações necessárias. :heavy_check_mark:

### Autor
---

<a href="https://blog.rocketseat.com.br/author/thiago/">
 <img style="border-radius: 50%;" src="https://media-exp1.licdn.com/dms/image/C5603AQHQhVF1DcK4BQ/profile-displayphoto-shrink_800_800/0/1626360406690?e=1638403200&v=beta&t=iiWyAVEA37996CkECQNCHu5EkMAqNUS0yDqSoe9mZDA" width="100px;" alt=""/>
 <br />
 <sub><b>Alef de Paula</b></sub></a> <a href="https://www.linkedin.com/in/alef-paula-aa98041ba/ title="LinkedIn">:desktop_computer:</a>
