# 🧾 Painel SPED

Sistema visual para leitura, edição e exportação de arquivos SPED, feito com [Streamlit](https://streamlit.io).

---

## ⚙️ Funcionalidades

- 📂 Upload e visualização de arquivos SPED
- ✏️ Edição de campos específicos (com filtro por tipo de registro)
- 📊 Geração de resumos por CFOP e tipo de operação
- 📤 Exportação em Excel (.xlsx) ou CSV (.csv)

---


## 🚀 Executar Localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/PainelSpedApp.git
cd PainelSpedApp

# Crie o ambiente virtual (Windows)
python -m venv venv
venv\\Scripts\\activate

# Instale as dependências
pip install -r requirements.txt

# Rode o app
streamlit run main.py
