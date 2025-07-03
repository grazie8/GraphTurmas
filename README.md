
# Graph Turmas

Graph Turmas é uma aplicação desenvolvida para automatizar e simplificar a criação de turmas educacionais no Microsoft Teams, otimizando o tempo e reduzindo o esforço manual dos administradores acadêmicos.

## Funcionalidades Principais

- **Autenticação de Usuário**  
  Tela de login segura para acesso restrito à aplicação.

- **Criação de Turmas em Lote**  
  Possibilita a criação automática de múltiplas turmas de uma só vez, facilitando o gerenciamento em larga escala.

- **Agrupamento por Tipo**  
  Permite classificar as turmas conforme o período acadêmico:
  - Anual
  - Semestral
  - Trimestral

- **Filtros Avançados**  
  - Filtro por Campus
  - Filtro por Nível de Ensino (ex: Médio, Superior, Pós-Graduação)

- **Tela de Log**  
  Exibe o registro detalhado das ações realizadas em cada etapa do processo, garantindo transparência e rastreabilidade.

---

## Pré-requisitos

Certifique-se de que os seguintes requisitos estejam atendidos antes de utilizar a aplicação:

- **Python 3.8 ou superior** (versão recomendada 3.11.0)
- **Microsoft Graph API**  
  Configuração de acesso e permissões apropriadas para manipulação de equipes no Teams.
- **Bibliotecas**
  - [`msal`](https://pypi.org/project/msal/) (Microsoft Authentication Library)
  - [`azure`](https://pypi.org/project/azure/) (SDKs Azure)
  - Outras dependências listadas em `requirements.txt`
- **Streamlit**  
  Utilizado para a criação da interface gráfica amigável e interativa.

---

## Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/GraphTurmas.git
cd GraphTurmas

# Instale as dependências
pip install -r requirements.txt
```

---

## Como Usar

1. **Configuração da API**
   - Configure as credenciais e permissões da Microsoft Graph API em um arquivo `.env` ou conforme instruções no repositório.

2. **Executando a Aplicação**
   ```bash
   streamlit run app.py
   ```

3. **Login**
   - Acesse a tela de login e autentique-se com suas credenciais autorizadas.

4. **Criação de Turmas**
   - Use os filtros para selecionar campus e nível de ensino.
   - Escolha o tipo de agrupamento (anual, semestral, trimestral).
   - Realize a criação das turmas em lote.
   - Acompanhe o progresso e eventuais erros na tela de log.

---

## Contribuição

Contribuições são bem-vindas! Por favor, envie um _pull request_ ou abra uma _issue_ para discutir melhorias ou correções.

---

## Licença




