# hyrbac
# Modelo de Política de Gestão de Identidades e Acessos (IAM) Ambiente Híbrido Microsoft AD

# README – Gerar Política IAM em Word

## Objetivo
Este script gera automaticamente um **documento Word (.docx)** com a **Política de Gestão de Identidades e Acessos (IAM)** para um ambiente híbrido Microsoft AD. O documento inclui:  
- Capa com título e informação básica  
- Objetivos da política  
- Princípios de IAM  
- Matriz de Funções RBAC  
- Matriz de Segregação de Funções (SoD)  
- Salvaguardas adicionais  

---

## Requisitos
- **Python 3.x**  
- Biblioteca **python-docx**  
```bash
pip install python-docx
