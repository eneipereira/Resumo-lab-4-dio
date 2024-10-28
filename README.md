# Resumo-lab-4-dio

## Passo a Passo para Criar um Grupo de Recursos no Azure:

### 1. Acessar o Portal do Azure:

Acesse o portal do Azure.

### 2. Criar um Grupo de Recursos:

No painel esquerdo, clique em Grupos de Recursos.

Clique em Criar no topo da tela.

### 3. Configurar o Grupo de Recursos:

Assinatura: Selecione a assinatura do Azure que será usada.

Nome: Dê um nome descritivo ao grupo de recursos, como RG-ProjetoWebApp.

Região: Selecione uma região para o grupo. Esse é o local onde os metadados do grupo serão armazenados (não afeta a localização dos recursos dentro do grupo).

### 4. Revisar e Criar:

Após preencher os campos, clique em Revisar + Criar.

Clique em Criar novamente para finalizar a criação do grupo de recursos.

### 5. Adicionar Recursos ao Grupo:

Agora você pode adicionar novos recursos (máquinas virtuais, bancos de dados, etc.) ao grupo de recursos ou mover recursos existentes para ele.

## Gerenciamento de Grupos de Recursos:

Permissões: Atribua funções e permissões aos usuários no grupo de recursos usando o Azure RBAC (Role-Based Access Control).

Deleção: Excluindo o grupo de recursos, você apaga todos os recursos nele contidos, o que facilita a limpeza de ambientes temporários ou de teste.

Monitoramento: Utilize o Azure Monitor para ver o desempenho e a utilização de todos os recursos dentro do grupo.

4. Criar um Grupo de Recursos

No Portal do Azure, crie um Grupo de Recursos. Um grupo de recursos é uma unidade lógica para agrupar todos os recursos relacionados a um projeto. Exemplo: Servidores, bancos de dados, redes, armazenamento.


## Configurar a Rede Virtual (VNet)

Uma rede virtual (VNet) define o espaço de rede no qual seus recursos se comunicarão de forma privada.

Vá para Redes Virtuais e clique em Criar.

Defina o nome, espaço de endereço IP (por exemplo, 10.0.0.0/16), e a região.

Adicione Sub-redes para segmentar suas aplicações. Por exemplo:

Sub-rede 1: Servidores de aplicação.

Sub-rede 2: Banco de dados.

Configure as regras de segurança (NSG - Network Security Groups) para controlar o tráfego.
