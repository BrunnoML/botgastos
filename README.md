<h1 align="center"> BotGastos </h1>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-objetivo">Objetivo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-estrutura">Usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-contribuir">Contribuir</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-notas">Notas Finais</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br>

<p align="center">
  <img alt="BotGastos" src="/images/preview.png" width="70%">
</p>


---

## 💻 Projeto

O **BotGastos** é um projeto que visa desenvolver um bot para WhatsApp que automatiza o controle de gastos de um grupo familiar. O bot será construído em Python e utilizará bibliotecas como pywhatkit para interagir com o WhatsApp e pandas para armazenar e analisar os dados de gastos.

## 📝 Objetivo

Criar um Bot para Controle de Gastos Familiares no WhatsApp.

---

## 📚 Funcionalidades do Projeto

### Cadastro de gastos
- Os membros do grupo familiar poderão cadastrar seus gastos informando valor, categoria e descrição.

### Visualização de gastos
- O bot fornecerá relatórios de gastos por período (semanal, mensal) e por categoria.

### Cálculo de totais e médias
- O bot calculará o total de gastos por membro, por categoria e a média de gastos do grupo.

### Alertas e lembretes
- O bot poderá enviar alertas sobre gastos excessivos ou lembretes de pagamentos.

---

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem de programação principal do projeto. Estamos utilizando a versão 3.9.
- **Pywhatkit**: Biblioteca para interagir com o WhatsApp.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Twilio**: Plataforma de comunicação para integrar o bot ao WhatsApp.
- **GitHub**: Para versionamento e colaboração.
- **Conda**: Gerenciador de ambientes virtuais.
- Novas tecnologias que sejam necessárias para dar continuidade ao projeto.


### Motivo de usar o Python 3.9 ao criar o ambiente virtual Conda por alguns motivos:

- **Compatibilidade**: A biblioteca twilio para Python, que usaremos para integrar o bot ao WhatsApp, suporta oficialmente o Python 3.9. Embora a biblioteca também suporte versões mais recentes do Python, como 3.10 e 3.11, o Python 3.9 oferece uma base sólida e estável para o nosso projeto.
- **Estabilidade**: O Python 3.9 é uma versão madura e estável, com um grande número de bibliotecas e pacotes compatíveis. Isso reduz o risco de encontrarmos problemas de compatibilidade ou bugs durante o desenvolvimento do bot.
- **Recursos**: O Python 3.9 possui todos os recursos necessários para construir o nosso bot, incluindo suporte para as bibliotecas pandas e twilio, além de oferecer um bom desempenho e ferramentas para desenvolvimento web, caso precisemos criar uma interface web para o bot no futuro.
- **Equilíbrio**: Escolher uma versão intermediária como o Python 3.9 oferece um bom equilíbrio entre compatibilidade, estabilidade e acesso aos recursos mais recentes. Evitamos usar uma versão muito antiga, que pode ter problemas de segurança ou falta de suporte, e também evitamos usar a versão mais recente, que pode ter menos bibliotecas compatíveis ou apresentar instabilidades.


---

## 📂 Como Usar

1. Clone este repositório:
```bash
 git clone https://github.com/BrunnoML/botgastos.git
```

2. Crie um ambiente virtual conda e ative-o.
```bash
 conda create -n botgastos python=3.9
```

3. Ativar o ambiente virtual conda:
```bash
conda activate botgastos
```

4. Instale as dependências: 
```bash
pip install -r requirements.txt
```

5. Criar uma conta no Twilio: Acesse o site do Twilio e crie uma conta.

6. Configurar o Twilio Sandbox para WhatsApp (opcional): Siga as instruções no site do Twilio para ativar o Sandbox e testar a API do WhatsApp.


7. Adicionar seu número Hushed ou outro (como do próprio Twilio) no Twilio: No painel do Twilio, adicione seu número em "Programmable SMS" > "WhatsApp" > "Senders".

8. Preencher o formulário de solicitação da API do WhatsApp: Preencha o formulário com as informações solicitadas.

9. Aguardar a aprovação do Twilio e do WhatsApp:

10. Execute o bot: 
```bash
python main.py
```

---

## 🤝 Como Contribuir

Sinta-se à vontade para contribuir com o projeto! Você pode ajudar de diversas maneiras:

* Reportando bugs: Encontrou algum erro ou problema no código? Abra uma issue no GitHub detalhando o problema e como reproduzi-lo.

* Sugerindo melhorias: Tem ideias para novas funcionalidades ou como melhorar o bot? Abra uma issue no GitHub descrevendo sua sugestão.

* Corrigindo bugs e implementando funcionalidades: Se você tem habilidades de programação, pode corrigir bugs ou implementar novas funcionalidades. Faça um fork do repositório, crie uma branch para sua contribuição, faça as alterações e envie um Pull Request.

* Melhorando a documentação: A documentação é fundamental para que outras pessoas possam entender e usar o projeto. Você pode ajudar melhorando o README.md ou criando tutoriais e exemplos de uso.

* Compartilhando o projeto: Divulgue o projeto para seus amigos e colegas que possam se interessar.

### Como enviar um Pull Request:

1. Faça um fork deste repositório.

2. Clone o seu fork:
   ```bash
   git clone https://github.com/BrunnoML/botgastos.git
   ```
3. Crie uma branch para a sua contribuição:
   ```bash
   git checkout -b minha-contribuicao
   ```
4. Faça as alterações necessárias e adicione os arquivos:
   ```bash
   git add .
   ```
5. Commit suas mudanças:
   ```bash
   git commit -m "Descrição das alterações"
   ```
6. Envie para o repositório remoto:
   ```bash
   git push origin minha-contribuicao
   ```
7. Abra um Pull Request!

### Dicas para contribuir:

- Siga as boas práticas de programação em Python.
- Escreva código limpo e legível.
- Adicione testes para as suas alterações.
- Documente o seu código.
- Comunique-se de forma clara e respeitosa.

A sua contribuição é muito bem-vinda! 😊

---

## 🗒️ Notas Finais

O BotGastos é um projeto em andamento e todas as contribuições são bem-vindas!

## 🪪 Licença

Esse projeto está sob a licença MIT.

---

Feito com ☕️  por [BrunnoML](https://www.brunnoml.com.br)