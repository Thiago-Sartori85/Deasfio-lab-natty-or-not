# Natural ou Fake Natty? Como Vencer na Era das IAs Generativas

# AI Text Summarizer

## Descrição
Este projeto utiliza inteligência artificial para resumir textos longos de forma automática. Usando a API da OpenAI, ele processa o conteúdo fornecido pelo usuário e retorna um resumo conciso.

### Funcionalidades
- Recebe um texto longo como entrada.
- Gera um resumo automatizado utilizando a API da OpenAI.
- Interface web simples para facilitar a interação.

## Tecnologias Utilizadas
- **Front-end**: HTML, CSS, JavaScript.
- **Back-end**: Python (Flask ou FastAPI).
- **API de IA**: OpenAI API.
- **Deploy**: Heroku, Vercel ou execução local.

## Instalação

### Pré-requisitos
- Python 3.x
- Conta na [OpenAI](https://beta.openai.com/signup/) para obter uma chave de API

### Passo a Passo

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/ai-text-summarizer.git
    ```

2. Entre no diretório do projeto:
    ```bash
    cd ai-text-summarizer
    ```

3. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    .\venv\Scripts\activate  # Windows
    ```

4. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

5. Configure a chave de API do OpenAI:
    - Crie um arquivo `.env` na raiz do projeto.
    - Adicione a seguinte linha:
      ```bash
      OPENAI_API_KEY=your-api-key
      ```

6. Execute a aplicação localmente:
    ```bash
    flask run  # Ou FastAPI, dependendo do framework escolhido
    ```

7. Acesse no navegador:
    ```
    http://localhost:5000
    ```

## Uso
1. Na página principal, insira o texto no campo indicado.
2. Clique no botão "Resumir".
3. O resumo gerado será exibido na tela.

## Contribuindo
Sinta-se à vontade para abrir *issues* e *pull requests*.

## Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE.md para detalhes.

### Exemplos e Insigths

- [E-BOOK](/exemplos/E-BOOK.md)
- [Podcast](/exemplos/PODCAST.md)
- [Vídeo (Avatar Virtual)](/exemplos/VIDEO.md)

## Links Interessantes

[Base10: If You’re Not First, You’re Last: How AI Becomes Mission Critical](https://base10.vc/post/generative-ai-mission-critical/)

![Base10's Trend Map Generative AI](https://github.com/digitalinnovationone/lab-natty-or-not/assets/730492/f4df26e8-f8f7-4419-8252-c69d73ea930c)
