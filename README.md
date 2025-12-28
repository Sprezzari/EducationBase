# 🎓 **EducationBase** - Sistema de Gerenciamento de Formações Educacionais

Um sistema robusto e escalável para gerenciar uma vasta base de dados de formações educacionais, cursos e treinamentos profissionais. Conecta estruturas acadêmicas tradicionais com oportunidades de aprendizado contínuo.

---

## ✨ **Características**

- 📚 **Banco de Dados Abrangente**: 600+ cursos de bacharelado, técnico e tecnólogo
- 🔧 **Arquitetura Modular**: Separação clara de responsabilidades
- 🛡️ **Segurança**: Configuração YAML centralizada
- ⚡ **Escalabilidade**: Pronto para crescimento da base de dados
- 📊 **Structured Data**: JSON para fácil manutenção e importação

---

## 🏗️ **Arquitetura do Projeto**

```
EducationBase/
├── config.yml                 # Configurações do banco de dados
├── config_loader.py          # Carregador de configurações YAML
├── database_manager.py       # Gerenciador de conexões e schema MySQL
├── data_inserter.py         # Insertador de dados JSON
├── data_constants.json      # Base de dados em JSON (600+ registros)
├── main.py                  # Script principal de orquestração
├── requirements.txt         # Dependências Python
└── README.md               # Este arquivo
```

---

## 🚀 **Início Rápido**

### **Pré-requisitos**

- Python 3.8+
- MySQL Server 8.0+
- pip (Python package manager)

### **Instalação**

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/EducationBase.git
cd EducationBase
```

2. **Instale as dependências**
```bash
pip install -r requirements.txt
```

3. **Configure o banco de dados**
Edite `config.yml` com suas credenciais MySQL:
```yaml
database:
  host: localhost
  port: 3306
  user: root
  password: sua_senha
  database: peoplecore
```

4. **Execute o sistema**
```bash
python main.py
```

---
