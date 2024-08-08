<div align="center" style="padding: 10px; border: 1px solid #ccc; background-color: #f9f9f9; border-radius: 10px; margin-bottom: 20px;">
    <h2 style="margin: 0; font-size: 24px; color: #333;">Integração Langflow com Streamlit</h2>
    <p style="margin: 5px 0 0 0; font-size: 16px; color: #666;">Integre perfeitamente os componentes do Streamlit no Langflow</p>
</div>


<p align="center"><strong>
    Integre o Streamlit para aplicações web interativas com o Langflow
</strong></p>
<p align="center" style="font-size: 12px;">
    Integração open-source, alimentada por Python, totalmente personalizável para uma experiência de usuário perfeita
</p>


<p align="center">
    <a href="https://github.com/yaitec/Langflow-Streamlit">
        <img src="https://img.shields.io/github/stars/yaitec/Langflow-Streamlit">
    </a>
</p>



# 📝 Conteúdo

- [Executando Langflow a partir de um Repositório Clonado](#executando-langflow-com-integração-streamlit-a-partir-de-um-repositório-clonado)
- [Como obter os Fluxos do Streamlit da loja](#como-obter-os-fluxos-do-streamlit-da-loja)
- [Usando Componentes do Streamlit no Langflow](#usando-componentes-do-streamlit-no-langflow)
- [Componentes do Streamlit](#componentes-do-streamlit)
- [👋 Contribua](#-contribua)
- [🌟 Contribuidores](#-contribuidores)
- [📄 Licença](#-licença)

# Executando Langflow com integração Streamlit a partir de um repositório clonado

Se você prefere executar o Langflow a partir de um repositório clonado em vez de instalá-lo via pip, siga estas etapas:

1. **Clone o Repositório**

Primeiro, clone o repositório Langflow do GitHub:

```shell
git clone https://github.com/yaitec/Langflow-Streamlit.git
```

Navegue para o diretório clonado:

```shell
cd Langflow-Streamlit
```

2. **Instale Dependências e execute**

Para instalar as dependências do frontend e backend e executar ambos, use o seguinte comando:

```shell
make start
```

**Por padrão, o Streamlit começará a ser executado na porta 5001**, mas isso pode ser alterado configurando um arquivo .env onde você pode alterar o comportamento padrão do Streamlit:

```
LANGFLOW_STREAMLIT_PORT = 5001
```

# Início Rápido usando Fluxos do Streamlit

O gif abaixo mostra como obter e executar o fluxo do Streamlit:
<p align="center">
  <img src="./docs/static/img/streamlit/streamlit_how_to_get_flows.gif" alt="Seu GIF" style="border: 3px solid #211C43;">
</p>

# Usando Componentes do Streamlit no Langflow
O gif abaixo mostra como usar os componentes `Listen` e `Send`:
<p align="center">
  <img src="./docs/static/img/streamlit/streamlit_how_to_connect_components.gif" alt="Seu GIF" style="border: 3px solid #211C43;">
</p>

# Componentes do Streamlit

Langflow fornece os seguintes componentes do Streamlit:

- **[Send](./send.md)**: Envie mensagens para uma sessão de chat do Streamlit.
- **[Listen](./listen.md)**: Ouça mensagens recebidas em um chat do Streamlit, alterando o layout da aplicação Streamlit.

# 👋 Contribua

Aceitamos contribuições de desenvolvedores de todos os níveis para nosso projeto open-source no GitHub. Se você deseja contribuir, por favor, verifique nossas [diretrizes de contribuição](./CONTRIBUTING.md) e ajude a tornar o Langflow mais acessível.

---

[![Star History Chart](https://api.star-history.com/svg?repos=yaitec/Langflow-Streamlit&type=Timeline)](https://star-history.com/#yaitec/Langflow-Streamlit&Date)

# 🌟 Contribuidores

[![langflow streamlit contributors](https://contrib.rocks/image?repo=yaitec/Langflow-Streamlit)](https://github.com/yaitec/Langflow-Streamlit/graphs/contribuidores)

# 📄 Licença

Langflow é lançado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
