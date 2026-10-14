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

## Doações

O super-vault é gratuito, sem anúncios e sem telemetria. Se ele for útil para você, considere uma doação em cripto:

| Moeda | Rede | Endereço |
|---|---|---|
| BTC | Bitcoin | `bc1ql2eqx4samvnws8u33sf3sxue29mgx8hjptd2dr` |
| ETH e USDC | Ethereum (ERC-20) | `0x26163ef9c4b07Fa7cEe5ecb68c2D61973289FF81` |
| SOL | Solana | `46rrstUk6AKGPkU6LKRwMxUtMeUie7xcPwSq2zSzMN36` |
| XLM | Stellar | `GDFE3CH63OUZU3URRFNRYBFCTMNSBQZ4C4XHPCTQWALBRVTV2QNJ2JCO` |

Envie USDC só pela rede Ethereum. Depois de colar o endereço na carteira, confira os primeiros e os últimos caracteres: malware de área de transferência pode trocar o endereço copiado. Os mesmos endereços aparecem na tela inicial do app e em [fabbricio/super-vault-releases](https://github.com/fabbricio/super-vault-releases).

## Licença

MIT OR Apache-2.0, à sua escolha: [LICENSE-MIT](LICENSE-MIT) e [LICENSE-APACHE](LICENSE-APACHE).
