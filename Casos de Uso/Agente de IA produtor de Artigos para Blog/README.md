# Roger - Agente Escritor de Blog com IA

Roger é um poderoso gerador de conteúdo para blogs baseado em IA que cria artigos otimizados para SEO com apenas algumas informações. Ele utiliza os modelos de linguagem da OpenAI e capacidades de busca na web para produzir posts de blog abrangentes e de alta qualidade, personalizados de acordo com suas necessidades específicas.

## 🌟 Funcionalidades

- **Geração Inteligente de Conteúdo**: Cria artigos profissionais com seções detalhadas baseadas no seu tópico
- **Otimização para SEO**: Incorpora palavras-chave naturalmente e analisa a densidade das palavras-chave
- **Integração com Busca na Web**: Usa a API Serper para enriquecer o conteúdo com informações atuais da internet
- **Análise de Conteúdo**: Fornece pontuação SEO, métricas de legibilidade e sugestões de melhoria
- **Múltiplas Opções de Exportação**: Salve artigos como Markdown, HTML ou texto simples
- **Suporte ao Google Colab**: Armazenamento seguro de chaves API e download fácil de arquivos

## 🚀 Começando

### Google Colab

A maneira mais fácil de usar o Roger é através do Google Colab:

1. Abra o notebook no Google Colab clicando no botão "Open in Colab" no topo do notebook
2. Insira suas API_KEYs na aba SECRETS:
   ```python
   OPENAI_API_KEY
   SERPER_API_KEY
   ```

### Instalação Local (se não quiser rodar no Google Colab)

Para usar o Roger localmente:

1. Clone este repositório
2. Instale as dependências necessárias:
   ```
   pip install openai==1.3.0 nltk tqdm pandas requests
   ```
3. Execute o script:
   ```
   python roger_blog_writer.py
   ```

## 🔑 Chaves API

O Roger requer as seguintes chaves API:

- **Chave API OpenAI**: Para acessar modelos de linguagem ([Obtenha a chave aqui](https://platform.openai.com/account/api-keys))
- **Chave API Serper** (opcional): Para funcionalidade de busca na web ([Obtenha a chave aqui](https://serper.dev/))

No Google Colab, as chaves são armazenadas com segurança como segredos para maior proteção.

## 💻 Uso

Quando você iniciar o gerador, será solicitado a fornecer:

1. Seu tópico de interesse
2. Palavras-chave para SEO (separadas por vírgula)
3. Tom de escrita preferido (informativo, persuasivo, conversacional, técnico ou inspirador)

O agente irá:
1. Criar um esboço abrangente do artigo
2. Gerar conteúdo detalhado para cada seção
3. Analisar o conteúdo para SEO e legibilidade
4. Fornecer opções de exportação para seu artigo completo

## 🛠️ Modelos Disponíveis

O Roger suporta vários modelos da OpenAI, incluindo:

- GPT-4.5 Preview
- GPT-4o
- GPT-3.5 Turbo
- Modelos da série "o" da Claude (o1, o1-mini, o1-pro, o3-mini)
- E mais

## 📊 Análise de Artigos

Após a geração, o Roger fornece métricas detalhadas:

- Contagem de palavras (mínimo de 2000 palavras)
- Pontuação SEO (de 0 a 100)
- Pontuação de legibilidade (de 0 a 100)
- Análise de densidade de palavras-chave
- Sugestões de melhoria

## 📝 Exemplo

```
===== 📝 GERADOR DE ARTIGOS DE BLOG OTIMIZADOS PARA SEO =====

Qual é o tópico principal do artigo? open source llm

Insira as palavras-chave para SEO (separadas por vírgula): 
openai, meta, google, hugging face, elon musk

Selecione o tom do artigo:
1. informativo
2. persuasivo
3. conversacional
4. técnico
5. inspirador
Escolha o número correspondente: 5
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues para melhorar o Roger.

## 📄 Licença

Este projeto é de código aberto e disponível sob a [Licença MIT](LICENSE).

## 🙏 Agradecimentos

- OpenAI por seus poderosos modelos de linguagem
- Serper pelas capacidades de busca na web
- A comunidade de código aberto pelas várias bibliotecas usadas neste projeto

---

Criado por [guifav](https://github.com/guifav) 
www.guilhermefavaron.com.br
