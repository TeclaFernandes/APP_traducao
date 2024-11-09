# Google Translate - Python Application

Este é um aplicativo simples de tradução usando a biblioteca `googletrans` para traduzir textos entre diferentes idiomas com uma interface gráfica feita com `Tkinter`. O aplicativo permite detectar o idioma de entrada e traduzir o texto para o idioma selecionado.

## Funcionalidades

- Detecta automaticamente o idioma do texto inserido.
- Tradução de textos de um idioma para outro.
- Interface gráfica amigável com suporte para múltiplos idiomas.
- Exibe o nome do idioma detectado.
- Personalização com cores e fontes configuráveis.

## Tecnologias Usadas

- **Python**: Linguagem de programação usada.
- **Tkinter**: Biblioteca para a interface gráfica.
- **googletrans**: API do Google Translate para tradução de textos.
- **Pillow**: Para manipulação e exibição de imagens (logo do Google Translate).

## Como Usar

1. Clone este repositório ou baixe os arquivos.
2. Instale as dependências:
    ```bash
    pip install googletrans==4.0.0-rc1 pillow
    ```
3. Abra o arquivo `main.py` e execute-o:
    ```bash
    python main.py
    ```

4. A interface gráfica será aberta, permitindo que você insira o texto a ser traduzido e selecione o idioma de destino.
5. O idioma do texto inserido será detectado automaticamente e a tradução será exibida na caixa de texto de saída.

## Como Funciona

1. O aplicativo possui uma janela principal onde o usuário pode digitar o texto a ser traduzido.
2. O idioma de origem é detectado automaticamente com a API do `googletrans`.
3. O usuário seleciona o idioma de destino a partir de uma lista suspensa de idiomas.
4. O texto traduzido é exibido em uma caixa de texto abaixo.

## Arquivos do Projeto

- `main.py`: O código principal da aplicação com a interface gráfica.
- `custom.py`: Contém opções de cores e fontes personalizáveis para a interface.
- `data.py`: Contém os dados de mapeamento de idiomas para uso na tradução e na interface.

## Exemplo de Interface

![Imagem do Google Translate App](GoogleTranslate.png)

## Sobre

Este projeto foi desenvolvido como parte de um estudo de como construir um tradutor simples utilizando APIs externas e interfaces gráficas no Python.

## Contribuições

Se você quiser contribuir para o projeto, fique à vontade para fazer um fork e enviar pull requests. Qualquer contribuição é bem-vinda!

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
