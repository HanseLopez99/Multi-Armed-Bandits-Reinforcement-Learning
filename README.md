# Laboratorio 2 - Multi-Armed Bandits 🎰  
**Curso:** Reinforcement Learning  
**Semestre:** II 2025  
**Integrantes:**  
- Hansel López (19026)  
---

## 📌 Descripción

Este laboratorio implementa y compara tres estrategias de acción en el problema del Multi-Armed Bandit:

- **Greedy**
- **Epsilon-Greedy (estático)** con valores de epsilon `[0.01, 0.05, 0.1]`
- **Epsilon-Greedy (con decaimiento)** con los mismos valores iniciales

El entorno simula 10 brazos con distintas probabilidades fijas de éxito. El agente toma decisiones y actualiza sus estimaciones de valor Q de forma incremental. Se ejecutan 5000 simulaciones, cada una de 1000 pasos.

---

## 📁 Repositorio

🔗 Repositorio oficial del proyecto:  
[https://github.com/HanseLopez99/Multi-Armed-Bandits-Reinforcement-Learning](https://github.com/HanseLopez99/Multi-Armed-Bandits-Reinforcement-Learning)

---

## 📄 Reporte del Laboratorio

📥 Puedes ver el reporte completo en formato PDF aquí:  
[👉 Ver `Multi_Armed_Bandit.pdf`](./Multi_Armed_Bandit.pdf)

---

## ⚙️ Requisitos

- Python 3.x  
- Numpy  
- Matplotlib

Instalación con entorno virtual:

```bash
python3 -m venv rl_lab_env
source rl_lab_env/bin/activate
pip install numpy matplotlib