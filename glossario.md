# **GLOSSÁRIO**

<table>
  <tr>
   <td><strong>Termo</strong>
   </td>
   <td><strong>Descrição</strong>
   </td>
  </tr>
  <tr>
   <td><strong>cd</strong>
   </td>
   <td>Comando utilizado para mudar de diretório no sistema de arquivos. Por exemplo, cd /home leva você para o diretório especificado.
   </td>
  </tr>
  <tr>
   <td><strong>ls</strong>
   </td>
   <td>Lista arquivos e diretórios no local atual. Pode ser usado com opções, como ls -l para exibir detalhes ou ls -a para incluir arquivos ocultos.
   </td>
  </tr>
  <tr>
   <td><strong>pwd</strong>
   </td>
   <td>Exibe o caminho completo do diretório atual em que o usuário está.
   </td>
  </tr>
  <tr>
   <td><strong>clear</strong>
   </td>
   <td>Limpa a tela do terminal, facilitando a visualização de novos comandos.
   </td>
  </tr>
  <tr>
   <td><strong>cd /</strong>
   </td>
   <td>Leva diretamente ao diretório raiz do sistema Linux, o ponto mais alto da hierarquia de diretórios.
   </td>
  </tr>
  <tr>
   <td><strong>Kernel</strong>
   </td>
   <td>É o núcleo do sistema operacional. Responsável por gerenciar hardware, memória, processos e comunicação entre programas e o computador.
   </td>
  </tr>
  <tr>
   <td><strong>Linux</strong>
   </td>
   <td>Sistema operacional baseado no kernel Linux. É gratuito, open source e amplamente utilizado em servidores, desktops e dispositivos móveis.
   </td>
  </tr>
  <tr>
   <td><strong>Diretório /root</strong>
   </td>
   <td>Diretório pessoal do usuário root (administrador). Requer permissões elevadas para acesso.
   </td>
  </tr>
  <tr>
   <td><strong>Diretório /usr</strong>
   </td>
   <td>Armazena programas essenciais, bibliotecas e arquivos do sistema. É um dos diretórios mais importantes do Linux.
   </td>
  </tr>
  <tr>
   <td><strong>sudo</strong>
   </td>
   <td>Permite executar comandos com privilégios de administrador. Deve ser usado com cautela, pois permite acesso completo ao sistema.
   </td>
  </tr>
  <tr>
   <td><strong>Cuidados com o sudo</strong>
   </td>
   <td>Evitar usar em comandos perigosos ou sem saber a finalidade. Um erro com sudo pode remover ou alterar arquivos essenciais do sistema.
   </td>
  </tr>
  <tr>
   <td><strong>sudo ls /root</strong>
   </td>
   <td>Comando que permite listar o conteúdo do diretório /root usando permissões elevadas.
   </td>
  </tr>
  <tr>
   <td><strong>Por que “sudo cd /root” não funciona</strong>
   </td>
   <td>O comando cd é interno ao shell e não pode ser executado diretamente por sudo. Ele apenas altera o diretório dentro de um novo processo, não no shell atual.
   </td>
  </tr>
  <tr>
   <td><strong>sudo -i</strong>
   </td>
   <td>Abre um shell interativo com permissões de root, como se você estivesse logado como administrador.
   </td>
  </tr>
  <tr>
   <td><strong>Diretório /etc</strong>
   </td>
   <td>Contém arquivos de configuração do sistema, como permissões, rede, inicialização e serviços.
   </td>
  </tr>
  <tr>
   <td><strong>cat sudoers</strong>
   </td>
   <td>Exibe o conteúdo do arquivo que define quem pode usar o sudo e com quais permissões. Recomenda-se não editá-lo diretamente.
   </td>
  </tr>
  <tr>
   <td><strong>exit</strong>
   </td>
   <td>Encerra a sessão atual do terminal ou sai do modo root se estiver ativo.
   </td>
  </tr>
  <tr>
   <td><strong>touch</strong>
   </td>
   <td>Cria arquivos vazios ou atualiza a data de modificação de um arquivo existente.
   </td>
  </tr>
  <tr>
   <td><strong>Nano (editor de texto)</strong>
   </td>
   <td>Editor simples e fácil de usar diretamente no terminal. Recomendado para iniciantes.
   </td>
  </tr>
  <tr>
   <td><strong>Principais comandos do Nano</strong>
   </td>
   <td>CTRL + O salvar, CTRL + X sair, CTRL + K recortar linha, CTRL + U colar, CTRL + W buscar texto.
   </td>
  </tr>
  <tr>
   <td><strong>Vim (editor de texto)</strong>
   </td>
   <td>Editor avançado de terminal, poderoso e personalizável, mas com curva de aprendizado maior.
   </td>
  </tr>
  <tr>
   <td><strong>Setas do Teclado</strong>
   </td>
   <td>Permitem navegar pelo histórico de comandos já executados no terminal.
   </td>
  </tr>
  <tr>
   <td><strong>Distrowatch.com</strong>
   </td>
   <td>Site que lista, compara e acompanha a popularidade de distribuições Linux. Útil para explorar novas distros.
   </td>
  </tr>
  <tr>
   <td><strong>mv</strong>
   </td>
   <td>Move ou renomeia arquivos e diretórios. Ex.: renomear → mv antigo novo.
   </td>
  </tr>
  <tr>
   <td><strong>cp</strong>
   </td>
   <td>Copia arquivos e diretórios. Ex.: cp arquivo.txt backup.txt.
   </td>
  </tr>
  <tr>
   <td><strong>rm</strong>
   </td>
   <td>Remove arquivos permanentemente.
   </td>
  </tr>
  <tr>
   <td><strong>rmdir</strong>
   </td>
   <td>Remove diretórios vazios.
   </td>
  </tr>
  <tr>
   <td><strong>rm -r</strong>
   </td>
   <td>Remove diretórios e seus arquivos de forma recursiva.
   </td>
  </tr>
  <tr>
   <td><strong>rm -ri</strong>
   </td>
   <td>Remove recursivamente, perguntando antes de cada exclusão.
   </td>
  </tr>
  <tr>
   <td><strong>Aviso sobre rm e rmdir</strong>
   </td>
   <td>Remoções são permanentes – não vão para lixeira.
   </td>
  </tr>
  <tr>
   <td><strong>> (redirecionamento)</strong>
   </td>
   <td>Sobrescreve o conteúdo de um arquivo com a saída de um comando.
   </td>
  </tr>
  <tr>
   <td><strong>>> (redirecionamento)</strong>
   </td>
   <td>Adiciona a saída de um comando ao final de um arquivo, sem apagar o conteúdo anterior.
   </td>
  </tr>
  <tr>
   <td><strong>echo</strong>
   </td>
   <td>Exibe mensagens no terminal ou envia texto para arquivos.
   </td>
  </tr>
  <tr>
   <td><strong>Gerenciador de Pacotes</strong>
   </td>
   <td>Sistema que instala, atualiza e remove softwares no Linux. Ex.: APT no Ubuntu.
   </td>
  </tr>
  <tr>
   <td><strong>O que é um pacote</strong>
   </td>
   <td>Conjunto de arquivos que formam um programa, incluindo binários e dependências.
   </td>
  </tr>
  <tr>
   <td><strong>sudo apt update</strong>
   </td>
   <td>Atualiza a lista de pacotes disponíveis.
   </td>
  </tr>
  <tr>
   <td><strong>sudo apt upgrade</strong>
   </td>
   <td>Instala atualizações disponíveis dos programas já instalados.
   </td>
  </tr>
  <tr>
   <td><strong>sudo apt install</strong>
   </td>
   <td>Instala novos programas.
   </td>
  </tr>
  <tr>
   <td><strong>top</strong>
   </td>
   <td>Monitor de processos em tempo real que mostra uso de CPU, memória e atividades do sistema.
   </td>
  </tr>
  <tr>
   <td><strong>ps</strong>
   </td>
   <td>Lista processos em execução.
   </td>
  </tr>
  <tr>
   <td><strong>ps aux --sort=-%mem | head -n 11</strong>
   </td>
   <td>Lista os 10 processos que mais consomem memória.
   </td>
  </tr>
  <tr>
   <td><strong>ps aux | grep Firefox</strong>
   </td>
   <td>Busca processos específicos pelo nome.
   </td>
  </tr>
  <tr>
   <td><strong>ps aux --sort=-%cpu</strong>
   </td>
   <td>Exibe processos ordenados por uso de CPU.
   </td>
  </tr>
  <tr>
   <td><strong>kill</strong>
   </td>
   <td>Envia sinais para um processo. Geralmente usado para encerrar programas travados.
   </td>
  </tr>
  <tr>
   <td><strong>kill -9</strong>
   </td>
   <td>Força o encerramento imediato de um processo.
   </td>
  </tr>
  <tr>
   <td><strong>pkill</strong>
   </td>
   <td>Encerra processos pelo nome. Ex.: pkill firefox.
   </td>
  </tr>
  <tr>
   <td><strong>ssh -i</strong>
   </td>
   <td>Conecta via SSH usando uma chave privada.
   </td>
  </tr>
  <tr>
   <td><strong>chmod</strong>
   </td>
   <td>Altera permissões de arquivos e diretórios no sistema.
   </td>
  </tr>
</table>
