# 🧠 Machine Learning - Entorno de Desarrollo

## 🚀 Configuración del entorno

### 1. Crear entorno virtual
python3 -m venv .prueba1

### 2. Activar entorno virtual
# Linux / Mac
source .prueba1/bin/activate

# Windows
.prueba1\Scripts\activate

### 3. Instalar dependencias principales
pip install pandas numpy matplotlib scikit-learn jupyter ipykernel

### 4. Configurar kernel para Jupyter
python -m ipykernel install --user --name=prueba1 --display-name "Python (prueba1)"

---

## 📦 Gestión de dependencias

### Guardar dependencias actuales
pip freeze > requirements.txt

### Instalar dependencias en otro entorno
pip install -r requirements.txt

---

## ✅ Notas
- Activar el entorno virtual antes de trabajar.
- Seleccionar el kernel **Python (prueba1)** en Jupyter o VS Code.