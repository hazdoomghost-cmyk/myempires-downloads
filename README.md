# MyEmpires — Downloads oficiais

Repositório público de distribuição do **MyEmpires**, uma adaptação para jogar Social Empires localmente e em dupla pela rede doméstica.

**Status:** canal público em configuração. Os arquivos aparecerão em **[Releases](https://github.com/hazdoomghost-cmyk/myempires-downloads/releases)** depois que a publicação automática for autorizada e a versão concluir os testes. Evite links de terceiros.

## O que estará disponível

| Arquivo | Para que serve |
| --- | --- |
| `MyEmpires-Instalador-vX.Y.Z.exe` | Instalação completa no computador anfitrião, sem buscar os recursos do jogo manualmente |
| `MyEmpires-Cliente.exe` | Cliente leve para o segundo computador, conectado à partida na rede local |
| `MyEmpires-Atualizacao-vX.Y.Z.zip` | Atualização incremental conferida por SHA-256 e instalada pelo próprio MyEmpires, com confirmação |
| `MyEmpires-Windows-Completo-vX.Y.Z.zip` | Edição portátil completa |
| `MyEmpires-Fonte-vX.Y.Z.zip` | Código-fonte correspondente às versões distribuídas (GPLv3) |

## Como jogar

No primeiro computador, instale o jogo completo e clique em **Jogar em dupla (hospedar)**. No segundo, execute **MyEmpires-Cliente.exe** e selecione a partida na mesma rede. Compare o código de confirmação de seis dígitos e aprove a conexão no anfitrião.

O jogo foi projetado para redes locais privadas. Não abra as portas 5050/5051 na internet. As sessões de jogo ainda usam HTTP na LAN, mesmo que o pareamento envie credenciais criptografadas.

## Privacidade e segurança

Este repositório **não** contém vilas salvas, códigos de acesso, segredos de autenticação ou backups. Os pacotes de atualização contêm apenas executáveis e templates permitidos, com integridade verificada antes da instalação. Os dados do jogo ficam nos computadores dos jogadores.

O repositório de desenvolvimento `myempires-importado` permanece privado. O código-fonte redistribuível correspondente aos executáveis é incluído em cada lançamento público para cumprir a licença GPLv3 do projeto de preservação [Social Emperors](https://github.com/AcidCaos/socialemperors).

Este é um projeto comunitário de preservação; não é um lançamento oficial da antiga Social Point. Novas funcionalidades multiplayer ainda requerem validação em dois computadores reais.

**Suporte:** utilize as [Issues deste repositório](https://github.com/hazdoomghost-cmyk/myempires-downloads/issues) sem anexar códigos, credenciais ou salvamentos privados.
