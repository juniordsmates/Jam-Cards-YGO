# Jam Cards - YGO!

App para buscar cartas de Yu-Gi-Oh!, montar decks, testar mãos e ver combos.

## Baixar

Os instaladores ficam em **[Releases](https://github.com/juniordsmates/Jam-Cards-YGO/releases/latest)**. A versão atual é a **1.0.1 Alpha**.

| Sistema | Arquivo |
| --- | --- |
| Windows 10/11 | `Jam.Cards.-.YGO._1.0.1_x64-setup.exe` |
| macOS (Apple Silicon e Intel) | `Jam.Cards.-.YGO._1.0.1_universal.dmg` |

No GitHub, os nomes dos arquivos trocam espaços e "!" por pontos; depois de instalado, o app se chama **Jam Cards - YGO!**.

### Primeira abertura

O app ainda não tem assinatura digital, então o sistema avisa na primeira vez:

- **Windows:** na tela azul "O Windows protegeu o computador", clique em **Mais informações** e depois em **Executar assim mesmo**.
- **macOS:** arraste o Jam Cards - YGO! para Aplicativos. Na primeira vez, clique com o botão direito no app e escolha **Abrir**. Se o macOS disser que o app "está danificado", rode no Terminal:

  ```sh
  xattr -cr '/Applications/Jam Cards - YGO!.app'
  ```

## Pasta `dados`

O arquivo [dados/camada.json](dados/camada.json) é baixado automaticamente pelo app. Ele traz tags, ajustes de leitura e combos calculados, mas **nenhum texto ou imagem de carta**. É gerado todos os dias: não edite à mão.

## Avisos

O Jam Cards - YGO! é um projeto independente e não tem ligação com a Konami. Yu-Gi-Oh! é marca registrada da Konami. Os dados das cartas vêm da [YGOPRODeck](https://ygoprodeck.com).
