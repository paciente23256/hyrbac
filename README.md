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
```
## Como Usar
1. Edite o ficheiro politica.json com os conteúdos desejados.
2. Executar o script
* No terminal ou prompt de comando:
```bash
python3 hyrbac.py
```
3. Abrir o ficheiro Word
* O script irá criar um ficheiro: Politica_IAM_AD_Hibrido.docx na mesma pasta.
