# Downloads do Vigil Agent

[English](README.md) · **Português**

Downloads oficiais e públicos do [Vigil Trophies](https://vigiltrophies.com), rastreador de conquistas para ports de PC e emuladores.

**Beta atual:** [v0.1.0-beta.2](https://github.com/guutol/vigil-agent-releases/releases/tag/v0.1.0-beta.2). Não precisa de conta no GitHub para baixar.

- Aplicativo de bandeja Windows: `vigil-agent-tray.exe`.
- Linha de comando Windows: `vigil-agent-windows-amd64.exe`.
- Linha de comando Linux / Steam Deck: `vigil-agent-linux-amd64`.
- Linha de comando Linux ARM64: `vigil-agent-linux-arm64`.

Baixe também `SHA256SUMS.txt` e compare o SHA-256 antes de executar. PowerShell: `Get-FileHash .\vigil-agent-tray.exe -Algorithm SHA256`. Linux: `sha256sum --ignore-missing -c SHA256SUMS.txt`.

Crie sua conta em https://vigiltrophies.com. No Windows, abra o app de bandeja, escolha **Vincular este PC** e confirme o código no navegador. Escolha as pastas dos jogos que deseja acompanhar. O agent lê as conquistas e preserva a fila quando está sem conexão. Instruções: https://vigiltrophies.com/download.

Este repositório contém documentação de distribuição e arquivos de release; o código-fonte fica em um repositório separado e privado. Os binários têm licença MIT: [LICENSE](LICENSE).

A beta não tem assinatura de código nem atualização automática. O build original não possui atestado de proveniência do GitHub; publicar a cópia aqui não cria esse atestado. Os arquivos são cópias idênticas da release original compilada pelo GitHub Actions. As notas identificam o commit original e a conferência dos hashes.

Para atualizar, saia do agent pelo menu, substitua o executável e abra novamente. Mantenha o caminho se usa iniciar com Windows. Vínculo, fontes, preferências e conquistas na fila permanecem na pasta de configuração.
