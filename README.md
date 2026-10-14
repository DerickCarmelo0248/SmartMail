# SmartMail

Workspace inicial para estudos de integração com Gmail, DevOps e DevSecOps.

Neste momento, o repositório contém apenas documentação e um arquivo de teste de leitura e escrita. O código da aplicação ainda não está presente neste diretório.

## Configuração local e segurança

Credenciais OAuth e tokens devem permanecer fora do Git, armazenados no gerenciador de credenciais local. Nunca cole credenciais reais em código ou documentação.

A pasta `gmail/`, exportações, dados locais, arquivos de ambiente, configurações privadas do agente e memória são ignorados. Arquivos `.env.example` e `.env.sample` podem conter apenas valores fictícios.

Antes de cada commit, confira `git status`, `git diff --cached` e a lista de arquivos preparados. O `.gitignore` não protege segredos inseridos em arquivos de código ou já rastreados.
