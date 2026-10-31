# MangaDesk

Leitor de mangá para **Windows e Linux**, com a experiência do Mihon no computador e compatível com as mesmas extensões.

Este repositório guarda apenas os instaladores e as atualizações do app.

## Baixar

Abra a [versão mais recente](https://github.com/MuriloWatanabe/mangadesk-releases/releases/latest) e, em **Assets**, baixe o arquivo do seu sistema:

| Sistema | Arquivo |
|---|---|
| Windows 10/11 (64 bits) | termina em `x64-setup.exe` |
| Ubuntu, Debian, Linux Mint e derivados | termina em `.deb` |
| Fedora, RHEL, openSUSE e derivados | termina em `.rpm` |

O Java e o Suwayomi-Server já vêm incluídos: não é preciso instalar mais nada.

Ignore os arquivos `.sig`, o `latest.json` e o "Source code". Eles são usados pelo atualizador ou gerados pelo GitHub, e não instalam o app.

## Instalar

**Windows:** feche o MangaDesk, se estiver aberto, e execute o `x64-setup.exe`. Se o Windows avisar que o app não é reconhecido, clique em **Mais informações → Executar assim mesmo**.

**Linux:** abra o pacote com a loja de aplicativos do sistema ou use o terminal na pasta do download:

```bash
sudo apt install ./MangaDesk_*_amd64.deb   # Ubuntu, Debian, Mint
sudo dnf install ./MangaDesk-*.x86_64.rpm  # Fedora, RHEL
```

## Primeiros passos

Na primeira abertura, o servidor pode levar até um minuto para iniciar. O app não vem com conteúdo: em **Navegar → Extensões → Repositórios**, adicione um repositório de extensões e instale as que quiser.

## Atualizar

O app procura versões novas ao abrir e mostra um aviso no topo quando houver uma. Em **Configurações → Atualização do app**, você pode atualizar manualmente ou ativar a instalação automática.

## Problemas e sugestões

Abra uma [issue](https://github.com/MuriloWatanabe/mangadesk-releases/issues) contando o que aconteceu, a versão do app e o seu sistema.

## Aviso legal

O MangaDesk não hospeda, fornece nem distribui mangás. Extensões e fontes são de terceiros e são adicionadas por quem usa o app, que é responsável pelo que acessa.

O MangaDesk é um projeto independente, sem vínculo com o Mihon ou o Suwayomi nem endosso deles.

## Créditos

- [Mihon](https://github.com/mihonapp/mihon) (Apache-2.0): inspiração para a experiência do app e o formato das extensões.
- [Suwayomi-Server](https://github.com/Suwayomi/Suwayomi-Server) (MPL-2.0): o motor que executa as extensões e cuida da biblioteca.
- [Eclipse Temurin](https://adoptium.net) (GPL-2.0 com Classpath Exception): o Java incluído nos instaladores.

## Licença

© 2026 Murilo Watanabe. Todos os direitos reservados. O MangaDesk é um software proprietário. Os termos completos e as licenças de terceiros estão na tela **Sobre** do app.
