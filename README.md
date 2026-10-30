# Tsuka Interface

[**Baixar Tsuka Interface para Windows**](https://github.com/tiagotsukahara/tsuka-interface/releases/latest/download/TsukaUpdater.exe)

## Instalar ou atualizar

1. Feche o Lineage 2.
2. Baixe `TsukaUpdater.exe` e coloque na raiz do seu cliente Interlude, ao lado da pasta `system` (fora dela).
3. Abra **Tsuka Interface**. Ele detecta a pasta onde esta e verifica os arquivos automaticamente.
4. Se quiser, escolha a animacao do soulshot (**Ativada/Desativada**) e a cor do toggle (**Roxo/Branco/Amarelo**).
5. Confira a lista de arquivos ausentes ou diferentes e o tamanho do download.
6. Clique em **Atualizar** quando quiser instalar. A verificacao inicial e a troca das opcoes nao baixam nem substituem os arquivos do jogo.

O programa baixa somente os arquivos ausentes ou diferentes. Nao precisa baixar
novamente toda a interface a cada atualizacao. Nao e necessario ter conta no
GitHub ou instalar o MEGA.

A cor do toggle vale para os indicadores de skills e soulshot. As opcoes ja
instaladas sao reconhecidas ao abrir. **Manter atual / padrao** preserva uma
variante personalizada e usa o padrao publicado apenas se o arquivo faltar.

As preferencias, conexao do servidor, macros e posicoes das janelas sao preservadas.
`Localization.ini` e `TTFontInfo.ini` sao atualizados junto com as fontes da interface;
os demais `.ini` existentes sao preservados. Um `.ini` ausente recebe o padrao.
Os arquivos substituidos ficam em `.tsuka-updater/<data-id>/backup`, dentro do
cliente, com os nomes e subpastas originais, como `system/Interface.u`.

O atualizador requer Windows com .NET Framework 4.8 (normalmente presente no
Windows 10/11). Se o proprio atualizador receber uma nova versao, baixe novamente
o EXE pelo mesmo link. As atualizacoes da interface sao verificadas dentro dele.

O executavel ainda nao tem assinatura digital de um editor validado. Por ser um
programa novo distribuido fora da Microsoft Store, pode apresentar o alerta de
reputacao do SmartScreen. Nao e necessario desativar a protecao do Windows.
O mesmo EXE e mantido nas publicacoes que alteram somente a interface do jogo.

[Ver versoes publicadas](https://github.com/tiagotsukahara/tsuka-interface/releases)
