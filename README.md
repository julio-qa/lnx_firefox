
# lnx_firefox

Script Bash para gerenciar a instalação, atualização e remoção do Firefox em sistemas Linux.

## Funcionalidades

- **Instalação**: Instale o Firefox com configuração de atalhos para o sistema.
- **Atualização**: Atualize para a versão mais recente do Firefox.
- **Remoção**: Remova completamente o Firefox do sistema.

## Requisitos

- Linux
- Bash
- `wget` e `tar`

## Uso

1. Clone este repositório:
   ```bash
   git clone https://github.com/<seu-usuario>/lnx_firefox.git
   cd lnx_firefox
   ```

2. Torne o script executável:
   ```bash
   chmod +x lnx_firefox
   ```

3. Execute o script com uma das opções:
   - **Instalar**:
     ```bash
     ./lnx_firefox --install
     ```
   - **Atualizar**:
     ```bash
     ./lnx_firefox --update
     ```
   - **Remover**:
     ```bash
     ./lnx_firefox --purge
     ```

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
