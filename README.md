O que é:
Infraestrutura como código (IaC) é o gerenciamento e provisionamento da infraestrutura por meio de códigos, em vez de processos Manaus.
Com a IaC, são criados arquivos de configuração que incluem as especificações da sua infraestrutura, facilitando a edição e a distribuição de configurações.
Ela também assegura o provisionamento do mesmo ambiente todas as vezes.

Controle de versão:
O controle de versão é uma parte importante da IaC. Os arquivos de configuração devem pertencer à fonte como qualquer outro código-fonte de software. Ao implantar a infraestrutura como código, também é possível separá-la em módulos, que podem ser combinados de diferentes maneiras por meio da automação.

Principal beneficio:
Ao automatizar o provisionamento da infraestrutura com a IaC, os desenvolvedores não precisam provisionar e gerenciar manualmente servidores, sistemas operacionais, armazenamento e outros componentes de infraestrutura sempre que criam ou implantam uma aplicação.

Definições:
DIRETÓRIOS
GRUPOS
USUÁRIOS

Criação de um script:
nano ou vi iac.sh

Procedimento:
Deve ser aplicado e valido em ambiente de testes
Antes de aplicar em ambiente de testes deve fazer um backup ou snapshot da máquina ou máquina virtual

Permissões:
Antes de executar deve permitir a execução do arquivo com o comando abaixo.
chmod +x iac.sh

Conferindo os resultados:
cat /etc/passwd


