# install_haskell_docker
Simple instructions on how to use and setup a development environment for haskell language

<ol>
    <li>
        <h4>Install docker</h4>
        <p>PT: Fazer o download do docker</p>
        <p>EN: Install docker</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/docker.jpg" alt="">
        <a href="https://www.docker.com/">docker.com </a>
    </li>
    
 <li>
        <h4>Install WSL2</h4>
        <p>PT: Se o docker não requeriu o download do WSL2 durante a instalação então deverá instalar no link abaixo</p>
        <p>EN: If docker didnt required the download of WSL2 during the installation you should download in the link below</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/wsl2.png" alt="">
        <a href="https://docs.microsoft.com/pt-br/windows/wsl/install-win10#step-2---update-to-wsl-2">install-wsl-2 </a>
    </li>
    
   <li>
        <h4>Install VsCode</h4>
        <p>PT: Faça o download do vscode</p>
        <p>EN: Download vscode</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/vscode.png" alt="">
        <a href="https://code.visualstudio.com/">VsCode </a>
    </li>
    
   <li>
        <h4>Install Docker extension</h4>
        <p>PT: Vá no icone de cubinhos no lado esquerdo da tela e digite docker e instale a extensão mostrada na imagem</p>
        <p>EN: Go to the cube extension icon, search for docker and install the extension showed in the image</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/docker_extension.jpg" alt="">
    </li>
    
   <li>
        <h4>Install WSL extension</h4>
        <p>PT: Ainda no icone de cubinhos no lado esquerdo da tela e digite WSL e instale a extensão mostrada na imagem</p>
        <p>EN: Still on the cube extension icon, search for WSL and install the extension showed in the image</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/wsl_extension.jpg" alt="">
    </li>
    
   <li>
        <h4>Install Remote Containers extension</h4>
        <p>PT: Ainda no icone de cubinhos no lado esquerdo da tela e digite Remote Containers e instale a extensão mostrada na imagem</p>
        <p>EN: Still on the cube extension icon, search for Remote Containers and install the extension showed in the image</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/containers_extension.jpg" alt="">
    </li>
    
   <li>
        <h4>Install Haskelly extension</h4>
        <p>PT: Ainda no icone de cubinhos no lado esquerdo da tela e digite Haskelly e instale a extensão mostrada na imagem</p>
        <p>EN: Still on the cube extension icon, search for Haskelly and install the extension showed in the image</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/haskelly_extension.jpg" alt="">
    </li>
    
   <li>
        <h4>WSL workspaces</h4>
        <p>PT: Clicando no icone em destaque deverá aparecer a lista de todos os workspaces do wsl. Vá no topo clicque no dropdown e selecione containers</p>
        <p>EN: After clicked in the circled icon vscode should show list of all the wsl workspaces. Go on the top and click in the dropdown and select the containers option</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/containers_list.jpg" alt="">
    </li>
    
   <li>
        <h4>In containers list</h4>
        <p>PT: Na lista de containeres clique com o botão direito do mouse no container do haskell e clique em attach in new window ou em attach to container</p>
        <p>EN: In containers list click with mouse right button in the haskell container and after that click in attach in new window or em attach to container</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/open_container.jpg" alt="">
    </li>
    
   <li>
        <h4>Project open</h4>
        <p>PT: Quando conectado ao container clique em  open folder deixe o default root e clique em ok. Com o projeto aberto os seguintes arquivos em azul devem estar visiveis, após isso criei um arquivo hi.hs e compilei(destaques em laranja e vermelho escuro) depois cliquei na opção selecionada em verde e após aberta a aba cliquei no destaque em rosa para acessar o terminal e após isso em vermelho claro rodei o arquivo</p>
        <p>EN: When connected to container click in open folder select /root/ and click ok. With the project opened the following files and folders in blue should be visible, after that i created a hi.hs file and compiled it(orange and dark red colors), after it i clicked in the green square to open the tab and clicked in the pink option in the terminal i just have to run the file and see the output in red</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/projetoaberto.jpg" alt="">
    </li>
    
<li>
        <h4>Stopping Containers powershell</h4>
        <p>PT: Caso queira parar o container depois de usa-lo basta no powershell ou terminal basta apenas digitar o seguinte comando Docker stop + processId ou Docker stop + container name</p>
        <p>EN: If you want to stop the container after you used it, in powershell and terminal you just have do type the following commands Docker stop + processId or Docker stop + container name</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/list_stop.jpg" alt="">
    </li>
 <li>
        <h4>Stopping Containers vscode</h4>
        <p>PT: Caso queira parar o container via interface visual basta apenas clicar no icone do docker ir na aba containers clicar com o botão direito em cima do container do haskell e selecionar a opção stop</p>
        <p>EN: If you want to stop the container using the vscode UI you just have to click on the docker icon, select the haskell container in the containers and with the mouse right button click in stop</p>
        <img src="https://github.com/KevinDaSilvaS/install_haskell_docker/blob/master/images/parando_via_vscode.jpg" alt="">
    </li>
</ol>

<h3>Useful links:</h3>
<ul>
<li><a href="https://www.youtube.com/watch?v=yb2udL9GG2U">Basics of docker PT </a></li>
<li><a href="https://learndocker.online/">Docker course EN</a></li>
<li><a href="https://www.youtube.com/watch?v=a49gYcBwITc">Docker WSL2 PT</a></li>
<li><a href="https://www.youtube.com/watch?v=hM0-z6WL8XU&list=PLC3y8-rFHvwhleivq1QohBZN4d8IdzG3c">VSCODE basics playlist EN</a></li>
    </ul>
