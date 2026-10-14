# super-vault: releases

Instaladores do **super-vault**, um cofre de senhas pessoal e offline com vários cofres cifrados, cada um com a sua senha mestra. Guarda logins de sites e apps, carteiras cripto e credenciais de hosts, e gera códigos de verificação. Sem conta, sem nuvem e sem telemetria.

Este repositório guarda só os binários publicados. O código-fonte é privado.

## Instalar (Windows)

```powershell
winget install fabbricio.super-vault
```

Ou baixe o `super-vault-<versão>-windows-x64-setup.exe` em [Releases](../../releases) e confira o SHA-256 publicado junto antes de executar:

```powershell
Get-FileHash .\super-vault-<versão>-windows-x64-setup.exe -Algorithm SHA256
```

A instalação é por usuário, sem pedir administrador. Instalar, atualizar ou desinstalar não mexe nos seus cofres. O instalador ainda não é assinado digitalmente, então o Windows SmartScreen avisa na primeira execução.

## Licença

MIT OR Apache-2.0, à sua escolha: [LICENSE-MIT](LICENSE-MIT) e [LICENSE-APACHE](LICENSE-APACHE).
