# MangaDesk

Leitor de mangá para **Windows e Linux**, com a experiência do Mihon no computador e compatível com as mesmas extensões.

Este repositório guarda apenas os instaladores e as atualizações do app.

## Baixar

| Sistema | Download |
|---|---|
| Windows 10/11 (64 bits) | [**Baixar o instalador (.exe)**](https://github.com/MuriloWatanabe/mangadesk-releases/releases/latest/download/MangaDesk-windows-x64-setup.exe) |
| Ubuntu, Debian, Linux Mint e derivados | [**Baixar o pacote .deb**](https://github.com/MuriloWatanabe/mangadesk-releases/releases/latest/download/MangaDesk-linux-amd64.deb) |
| Fedora, RHEL, openSUSE e derivados | [**Baixar o pacote .rpm**](https://github.com/MuriloWatanabe/mangadesk-releases/releases/latest/download/MangaDesk-linux-x86_64.rpm) |

Outras versões estão na [página de versões](https://github.com/MuriloWatanabe/mangadesk-releases/releases).

O Java e o Suwayomi-Server já vêm incluídos: não é preciso instalar mais nada.

## Instalar

**Windows:** feche o MangaDesk, se estiver aberto, e execute o instalador baixado. Se o Windows avisar que o app não é reconhecido, clique em **Mais informações → Executar assim mesmo**.

**Linux:** abra o pacote com a loja de aplicativos do sistema ou use o terminal na pasta do download:

```bash
sudo apt install ./MangaDesk*.deb   # Ubuntu, Debian, Mint
sudo dnf install ./MangaDesk*.rpm   # Fedora, RHEL
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
