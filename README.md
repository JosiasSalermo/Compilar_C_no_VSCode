# Compilar_C_no_VSCode
Aos amantes do  VSCode, que não querem larga-lo nem na hora de escrever seus códigos em C.

## Primeiramente é preciso instalar duas extensões no VSCode
<ol>
  <li>C/C++</li>
  
  ![c](https://user-images.githubusercontent.com/48113700/71306763-6fd44a80-23c3-11ea-95b2-60b56ffeaf22.jpg)
  <li>C/C++ Compile Run</li>

  ![copile run](https://user-images.githubusercontent.com/48113700/71306791-c6da1f80-23c3-11ea-9309-13dd65ae8945.jpg)
</ol>

<br>

## Agora vamos instalar o copilador mimgw no pc(Testei apenas no Windows)

https://pt.osdn.net/projects/mingw/downloads/68260/mingw-get-setup.exe/
<p>O link acima já leva para a página aonde irá baixar o arquivo (mingw-get-setup.exe: 93,184 bytes)</p>
<br>
<p>Instale normalmente</p>
<p>Lembrando que tem que ser instalado do C:</p>
<p>Depois vai no C: e irá ter a pasta MinGW </p>

![mingw](https://user-images.githubusercontent.com/48113700/71306853-c1c9a000-23c4-11ea-84ad-2ced3b59cdf4.jpg)

<p>Abra ela, e irá ter uma pasta bin </p>

![bin](https://user-images.githubusercontent.com/48113700/71306883-41f00580-23c5-11ea-94f8-e4bfbf5af472.jpg)
<p>Abra a pasta bin para pegar o endereço que fica na barra de nagevação </p>
<p>Clique na barra de nagegação e copie o endereço</p>
<p>C:\MinGW\bin</p>

![endereço](https://user-images.githubusercontent.com/48113700/71306893-63e98800-23c5-11ea-9b96-3f16b59596da.jpg)


## Agora vamos colocar  o endereço do bin no path do Windows
<p>Vai no Painel de controle </p>
<p>Vai em Sistemas</p>
<p>Configuração Avançado do Sistema</p>

![sistema](https://user-images.githubusercontent.com/48113700/71306954-4a950b80-23c6-11ea-8e5e-a5e5e57fd541.jpg)

<p>Na Aba Avançado, vai em Variáveis de Ambiente</p>

![avançado](https://user-images.githubusercontent.com/48113700/71306988-b4151a00-23c6-11ea-8024-e36ad72efb3e.jpg)

<p>Crie uma nova </p>

![novo](https://user-images.githubusercontent.com/48113700/71307038-7bc20b80-23c7-11ea-9533-429a710adf91.jpg)


<p>Coloque um nome e o endereço da bin</p>

![teste](https://user-images.githubusercontent.com/48113700/71307091-cd6a9600-23c7-11ea-97ab-ee6a66a7e84e.jpg)

<p>Pronto!</p>


## Compilando...

<p>Para Compilar basta depois de escrever o código em C, clicar a tecla F6 </p>

<p>Prontinho! </p>
