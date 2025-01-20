## **Níveis de Ensino**

### **1. Anos Iniciais (AI)**
- **Cobertura**: Do 1º ao 5º ano do Ensino Fundamental.
- **Bases disponíveis**:
  - **IDEB_AI**: Dados do IDEB por município.
  - **DADOS_AI**: Dados detalhados por escola e município.

### **2. Anos Finais (AF)**
- **Cobertura**: Do 6º ao 9º ano do Ensino Fundamental.
- **Bases disponíveis**:
  - **IDEB_AF**: Dados do IDEB por município.
  - **DADOS_AF**: Dados detalhados por escola e município.

### **3. Ensino Médio (ME)**
- **Cobertura**: Do 1º ao 3º ano do Ensino Médio.
- **Bases disponíveis**:
  - **IDEB_ME**: Dados do IDEB por município.
  - **DADOS_EM**: Dados detalhados por escola e município.

---

## **Bases de Dados**

### **IDEB_XX (AI, AF, ME)** - Dados por município
- **Nível de agregação**: Município.
- **Descrição geral**: Contém o Índice de Desenvolvimento da Educação Básica (IDEB) calculado por município.
- **Principais variáveis**:
  - `MESO`: Nome da mesorregião em que o município está localizado.
  - `COD_MUN`: Código único que identifica o município.
  - `MUN`: Nome do município.
  - `IDEB_XX`: Valor do IDEB para o respectivo nível de ensino.

### **DADOS_XX (AI, AF, ME)** - Dados por escola e município
- **Nível de agregação**: Escola e município.
- **Descrição geral**: Contém informações detalhadas sobre o desempenho educacional, incluindo notas do SAEB e indicadores de rendimento, tanto no nível de escola quanto no nível municipal.
- **Principais variáveis**:
  - `COD_MUN`: Código único que identifica o município.
  - `MUN`: Nome do município.
  - `COD_ESC`: Código único que identifica a escola (somente para dados no nível de escola).
  - `ESC`: Nome da escola (somente para dados no nível de escola).
  - `XX_P`: Indicador de rendimento (aprovação, reprovação e abandono) para o respectivo nível de ensino.
  - `XX_SAEB_MA`: Nota média em Matemática no SAEB para o respectivo nível de ensino.
  - `XX_SAEB_PT`: Nota média em Língua Portuguesa no SAEB para o respectivo nível de ensino.
  - `IDEB_XX`: Valor do IDEB para a escola ou município no respectivo nível de ensino.
