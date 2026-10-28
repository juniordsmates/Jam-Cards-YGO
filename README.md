# Cartas

App para buscar cartas de Yu-Gi-Oh!, montar decks, testar mãos e ver combos.

## Baixar

Os instaladores ficam em **[Releases](https://github.com/juniordsmates/Cartas/releases/latest)**. A versão atual é a **1.0.0 Alpha**.

| Sistema | Arquivo |
| --- | --- |
| Windows 10/11 | `Cartas_1.0.0_x64-setup.exe` |
| macOS (Apple Silicon e Intel) | `Cartas_1.0.0_universal.dmg` |

### Primeira abertura

O app ainda não tem assinatura digital, então o sistema avisa na primeira vez:

- **Windows:** na tela azul "O Windows protegeu o computador", clique em **Mais informações** e depois em **Executar assim mesmo**.
- **macOS:** arraste o Cartas para Aplicativos. Na primeira vez, clique com o botão direito no app e escolha **Abrir**. Se o macOS disser que o app "está danificado", rode no Terminal:

  ```sh
  xattr -cr /Applications/Cartas.app
  ```

## Pasta `dados`

O arquivo [dados/camada.json](dados/camada.json) é baixado automaticamente pelo app. Ele traz tags, ajustes de leitura e combos calculados, mas **nenhum texto ou imagem de carta**. É gerado todos os dias: não edite à mão.

## Avisos

O Cartas é um projeto independente e não tem ligação com a Konami. Yu-Gi-Oh! é marca registrada da Konami. Os dados das cartas vêm da [YGOPRODeck](https://ygoprodeck.com).
