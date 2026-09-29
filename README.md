# Automação de Cadastro com PyAutoGUI 🖥️🤖

Este projeto demonstra como automatizar tarefas repetitivas em sistemas web utilizando **Python** e a biblioteca **PyAutoGUI**.  
O código abre o navegador, acessa um sistema de login, realiza autenticação e pode cadastrar produtos automaticamente a partir de uma base de dados em CSV.

---

## 🚀 Funcionalidades
- Abrir o navegador e acessar o sistema da empresa.
- Realizar login automático com usuário e senha.
- Ler uma base de dados (`produtos.csv`) usando **Pandas**.
- Preencher formulários de cadastro de produtos de forma automatizada.
- Repetir o processo para todos os itens da base.

---

## 🛠️ Tecnologias Utilizadas
- [Python](https://www.python.org/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) – automação de teclado e mouse.
- [Pandas](https://pandas.pydata.org/) – manipulação de dados.
- [Time](https://docs.python.org/3/library/time.html) – controle de pausas e tempo de execução.
---
## 📂 Estrutura do Projeto
├── produtos.csv   # Base de dados com os produtos a serem cadastrados
├── main.py        # Script principal de automação
└── README.md      # Documentação do projeto

## ⚙️ Como Usar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/seurepositorio.git
2. Instale as dependências:
   ```bash
   pip install pyautogui pandas
3. Ajuste os valores de coordenadas (x, y) no código conforme a posição dos campos na sua tela.
4. Crie o arquivo produtos.csv com as colunas:

    codigo
    
    marca
    
    tipo
    
    categoria
    
    preco_unitario
    
    custo

    obs

5. xecute o script:
6. '''bash
   python main.py

⚠️ Observações Importantes
As coordenadas de clique (x, y) variam de acordo com a resolução e layout da sua tela. Ajuste conforme necessário.

O login e senha utilizados no exemplo são fictícios. Substitua pelos seus dados reais.

Este projeto é apenas para fins educacionais e demonstração de automação. Não utilize para automatizar acessos sem autorização.

📌 Próximos Passos
Implementar tratamento de erros (ex.: campos não encontrados).

Adicionar logs para monitorar o processo.

Criar interface gráfica para facilitar configuração.
👩‍💻 Autor
Projeto desenvolvido como exercício prático de automação em Python no curso da Hashtagtreinamentos
Sinta-se à vontade para contribuir ou sugerir melhorias! ✨



