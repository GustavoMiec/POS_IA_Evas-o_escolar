# Previsão de Evasão Acadêmica com Random Forest

## 📌 Sobre o Projeto
Este projeto utiliza um modelo de aprendizado de máquina para prever a evasão acadêmic. A base de dados analisada contém informações sobre estudantes e seu status de formação (Graduado ou Dropout). O objetivo é construir um classificador que ajude a identificar padrões que indicam risco de evasão.

## 🛠️ Tecnologias Utilizadas
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-Learn (sklearn)**

## 📊 Base de Dados
A base de dados utilizada está hospedada no GitHub:

```
https://raw.githubusercontent.com/pnferreira/fiap-ia-devs/main/dropout-inaugural.csv
```

Ela contém diversas variáveis sobre os alunos, incluindo informações acadêmicas e socioeconômicas.

## 🚀 Como Executar o Projeto
### 1️⃣ Instale as dependências necessárias
Caso ainda não tenha as bibliotecas, instale-as com:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 2️⃣ Execute o script Python
Salve o código em um arquivo `script.py` e execute:

```bash
python script.py
```

Isso irá:
- Carregar os dados
- Limpar e preprocessar as informações
- Criar um modelo RandomForestClassifier
- Avaliar o modelo com matriz de confusão e relatório de classificação

## 📌 Estrutura do Projeto

```
/
├── script.py  # Código principal
├── README.md  # Documentação do projeto
```

## 📈 Resultados e Análise
Após o treinamento, o modelo apresentou **100% de acurácia**. Alguns possíveis motivos incluem:
- **Desequilíbrio da base de dados**
- **Overfitting** (o modelo pode ter "decorado" os dados)
- **Fuga de dados (data leakage)**

### 📌 Possíveis Melhorias
Para melhorar o modelo, podem ser aplicadas técnicas como:
- Balanceamento da base de dados
- Redução da profundidade da Random Forest
- Validação cruzada

## 📢 Contribuição
Sugestões e melhorias são bem-vindas! Abra uma issue ou envie um pull request. 

## 📜 Licença
Este projeto é de livre uso para fins educacionais. 

---

Desenvolvido por **Gustavo Costa** 🚀
