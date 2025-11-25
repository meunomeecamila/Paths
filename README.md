# 🖼️ Organizador Automático de Imagens em Python

Este projeto é um script em **Python** desenvolvido para **organizar automaticamente arquivos de imagem** de um diretório para outro.  
O programa identifica extensões específicas (como `.png`, `.jpg`, `.jpeg`, `.gif`, etc.) e move esses arquivos para uma pasta separada, criando-a caso ela ainda não exista.

---

## 📌 Objetivo

Facilitar a organização de imagens em um diretório, separando-as automaticamente em uma pasta própria.  
É especialmente útil para quem possui pastas com muitos arquivos misturados.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3+**
- Módulos:
  - `os` — manipulação de diretórios e caminhos
  - `shutil` — movimentação de arquivos

---

## 📂 Funcionalidade

O script:

1. Acessa uma pasta de origem (`from_dir`)
2. Lista todos os arquivos presentes
3. Verifica a extensão de cada arquivo
4. Se o arquivo for uma imagem, ele:
   - Cria a pasta de destino caso não exista
   - Move o arquivo para a pasta correta

As extensões suportadas são:
.gif, .png, .jpg, .jpeg, .jfif

---


---

## ▶️ Como Executar

1. Certifique-se de ter Python instalado:

```bash
python --version
```

2. Ajuste os caminhos no código para sua máquina:
```bash
from_dir = "C:/caminho/da/pasta/origem"
to_dir = "C:/caminho/da/pasta/destino"
```

4. Execute o script:
python organize_images.py

## 🔮 Possíveis Melhorias

- Separar arquivos por categorias adicionais (documentos, vídeos, áudio)  
- Criar interface gráfica simples (Tkinter)  
- Implementar logs de movimentação  
- Transformar em script executável `.exe`  
- Permitir que o usuário escolha os diretórios dinamicamente  

---

## 👩‍💻 Autoria

Projeto desenvolvido por **Camila Cardoso de Menezes**, como parte dos estudos de **automação com Python**.


