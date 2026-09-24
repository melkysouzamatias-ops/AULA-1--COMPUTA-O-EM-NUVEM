# AULA-1--COMPUTA-O-EM-NUVEM

Aula 01: Introdução ao Ambiente Linux e Playgrounds em Nuvem (KillerCoda & Ubuntu)
Seja bem-vindo ao repositório da primeira aula da disciplina de Computação em Nuvem!

Neste encontro inicial, exploramos como provisioning, terminal remoto e ambientes de sandbox em nuvem nos permitem praticar comandos e configurações em sistemas Linux sem a necessidade de instalação local ou consumo de recursos da própria máquina. Utilizávamos a plataforma KillerCoda para provisionar instâncias sob demanda do Ubuntu Linux.

📌 Conteúdos Abordados
1. O que é o KillerCoda?
Definição: Uma plataforma interativa de aprendizado baseada no navegador que fornece ambientes Linux e Kubernetes reais provisionados temporariamente na nuvem.

Vantagens na Nuvem:

Acesso Instantâneo: Sem necessidade de virtualização local (como VirtualBox/VMware).

Isolamento e Segurança: Ambientes ephemeral (descartáveis), permitindo testes sem risco de danificar o sistema operacional hospedeiro.

Padronização: Todos os alunos trabalham com a mesma imagem de SO e permissões de acesso (root).

2. Navegação e Comandos Essenciais no Ubuntu Linux
Durante a prática no terminal do Ubuntu, repassamos comandos fundamentais para gestão de arquivos, diretórios, permissões e rede:

Navegação e Sistema de Arquivos:

pwd: Exibe o diretório atual (Print Working Directory).

ls -la: Lista arquivos e diretórios, incluindo ocultos e permissões detalhadas.

cd <diretorio>: Navega entre os diretórios.

mkdir <nome>: Cria novos diretórios.

Gerenciamento de Arquivos e Permissões:

touch <arquivo>: Cria um arquivo vazio.

cat, less, nano: Visualização e edição rápida de arquivos no terminal.

chmod e chown: Alteração de permissões e proprietários de arquivos/diretórios.

Gerenciamento de Pacotes (apt):

sudo apt update: Atualiza o índice de pacotes disponíveis nos repositórios.

sudo apt upgrade: Atualiza os pacotes instalados para as versões mais recentes.

sudo apt install <pacote>: Instala novas ferramentas (ex: curl, net-tools, nginx).

🛠️ Roteiro Prático Realizado na Aula
Passo 1: Acesso ao Ambiente no KillerCoda
Acesso à plataforma KillerCoda.

Seleção do cenário Ubuntu Playground.

Inicialização do ambiente interativo com acesso ao terminal remoto via SSH no navegador.
