

# Esculápio: Sistema de Gerenciamento de Clínica Médica Online

O **Esculápio** é um sistema de gerenciamento de clínica online desenvolvido como parte do meu trabalho de conclusão de curso (TCC). Este projeto visa facilitar a administração e o atendimento de uma clínica de saúde de forma eficiente e simplificada.

## Recursos Principais:
- **Painel de Administração Intuitivo:** Uma interface de usuário amigável para gerenciar pacientes, médicos, consultas e outros aspectos essenciais da clínica.
- **Gestão de Pacientes e Médicos:** Cadastro, edição e visualização detalhada de informações de pacientes e médicos.
- **Agendamento de Consultas:** Funcionalidade para agendar consultas entre médicos e pacientes, com lembretes automáticos.
- **Autenticação de Usuários:** Sistema de login seguro para pacientes e médicos acessarem suas contas de forma segura.
- **Histórico de Consultas:** Registros detalhados de todas as consultas agendadas e realizadas, para referência futura.
- **Responsivo e Acessível:** Design responsivo que se adapta a diferentes dispositivos, garantindo uma experiência consistente em desktops, tablets e smartphones.

## Estrutura do Projeto:
- `src/`: Contém o código-fonte do sistema, incluindo pastas para administração, médicos e pacientes.
- `database/`: Arquivos relacionados ao banco de dados, como o esquema SQL e os arquivos de sementes.
- `includes/`: Arquivos PHP comuns incluídos em várias partes do sistema, como cabeçalhos e rodapés.
- `assets/`: Recursos estáticos como CSS, JavaScript e imagens.

Adicionar no GitHub:

1. **Clonar o Repositório:**
   ```
   git clone https://github.com/gabriellydsantos/tcc-esculapio.git
   ```

2. **Adicionar Arquivos Modificados:**
   ```
   git add .
   ```

   Substitua `.` pelos nomes dos arquivos específicos, se desejar.

3. **Fazer Commit das Alterações:**
   ```
   git commit -m "Mensagem do commit"
   ```

   Substitua `"Mensagem do commit"` por uma mensagem descritiva.

4. **Fazer Push das Alterações para o GitHub:**
   ```
   git push
   ```
      Existem várias formas de usar o comando `git push` no Git, Aqui estão alguns exemplos:
      
      1. **Push Simples:**
         ```bash
         git push
         ```
         Este comando simplesmente envia todas as suas alterações locais para o repositório remoto padrão.
      
      2. **Push para um Ramo Específico:**
         ```bash
         git push origin nome-do-ramo
         ```
         Isso envia as alterações do ramo específico para o repositório remoto.
      
      3. **Push de Todos os Ramos:**
         ```bash
         git push --all origin
         ```
         Isso envia todos os ramos locais para o repositório remoto.
      
      4. **Forçar o Push:**
         ```bash
         git push --force origin nome-do-ramo
         ```
         Às vezes, você pode precisar forçar o push se suas alterações locais forem diferentes das do repositório remoto. Tenha cuidado ao usar esse comando, pois ele pode substituir as alterações existentes no            repositório remoto.
      
      5. **Push com Tags:**
         ```bash
         git push --tags origin
         ```
         Isso envia todas as tags locais para o repositório remoto.
      
      6. **Push de um Ramo e Definir Como Padrão:**
         ```bash
         git push -u origin nome-do-ramo
         ```
         Isso não apenas envia o ramo para o repositório remoto, mas também define-o como o ramo padrão para push no futuro.

Lembre-se de substituir `origin` pelo nome do seu repositório remoto, se for diferente. Além disso, ajuste `nome-do-ramo` para corresponder ao nome do ramo que você deseja enviar ou receber.
Isso pressionará suas alterações para o ramo principal (`master`) do repositório no GitHub.

Certifique-se de executar esses comandos dentro do diretório do seu projeto local após ter feito as alterações necessárias.
