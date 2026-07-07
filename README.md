# 🐾 Carteirinha Digital do Pet - PetUniverse

Este projeto contém uma interface móvel premium de altíssima fidelidade inspirada nas diretrizes de UX da Apple para a **Carteirinha Digital Pública do Pet** da startup **PetUniverse**. Quando a SmartTag da coleira do pet for escaneada, essa página será exibida.

---

## 📂 Conteúdo do Arquivo ZIP

- `index.html`: Código fonte completo (HTML, CSS e JavaScript unificados).
- `logo_oficial.jpg`: Arquivo de exemplo do Logotipo Institucional da PetUniverse.
- `logo_sistema_pu.png`: Arquivo de exemplo do Logotipo de Tecnologia (Sistema PU).
- `nike.jpg`: Arquivo de exemplo da foto do Pet (Nike).

---

## 🖼️ Como Substituir as Logos e a Foto do Pet

Para colocar as imagens reais da sua startup e do seu pet, basta substituir os arquivos de imagem na mesma pasta com os seguintes cuidados:

1. **Logotipo Institucional (PetUniverse)**:
   - Substitua o arquivo `logo_oficial.jpg` pelo seu logo oficial em formato `.jpg` ou `.png`.
   - Se o formato for diferente (ex: `.png`), abra o `index.html` e altere a tag `<img src="logo_oficial.jpg" ...>` para o novo nome do arquivo.

2. **Logotipo do Sistema PU**:
   - Substitua o arquivo `logo_sistema_pu.png` pelo ícone/logo do seu sistema. Recomenda-se imagem com fundo transparente.

3. **Foto do Pet**:
   - Substitua o arquivo `nike.jpg` pela foto do pet real.
   - O sistema de CSS aplica automaticamente o corte perfeitamente circular e sombras sofisticadas, então qualquer foto quadrada ou retangular centralizada funcionará perfeitamente!

---

## 🚀 Como Publicar no GitHub Pages (Em menos de 5 minutos)

O GitHub Pages é a melhor forma gratuita e profissional de colocar a carteirinha online para que qualquer QR Code possa acessá-la. Siga os passos abaixo:

### Passo 1: Criar o Repositório no GitHub
1. Acesse [github.com](https://github.com) e faça login (ou crie uma conta em 1 minuto).
2. Clique no botão **"New"** (Novo) no canto superior esquerdo ou vá em `github.com/new`.
3. Escolha um nome para o repositório (exemplo: `carteirinha-pet`).
4. **Importante:** Deixe o repositório marcado como **Public** (Público).
5. Clique em **"Create repository"** (Criar repositório).

### Passo 2: Fazer o Upload dos Arquivos
1. Na tela que se abrir, clique no link **"uploading an existing file"** (enviar um arquivo existente).
2. Arraste e solte todos os arquivos de dentro deste ZIP (`index.html`, `logo_oficial.jpg`, `logo_sistema_pu.png`, `nike.jpg`) para a área de upload do navegador.
3. Clique no botão verde **"Commit changes"** (Confirmar alterações) na parte inferior.

### Passo 3: Ativar o GitHub Pages
1. Na barra superior do seu repositório, clique na aba ⚙️ **Settings** (Configurações).
2. No menu lateral esquerdo, clique na opção **Pages** (dentro da seção *Code and automation*).
3. Em **"Build and deployment"** -> **"Source"**, certifique-se de que está marcado *"Deploy from a branch"*.
4. Logo abaixo, em **"Branch"**, mude de *None* para **`main`** (ou `master`) e clique em **Save** (Salvar).

### 🎉 Pronto!
Aguarde cerca de 30 segundos a 1 minuto. Atualize a página de configurações e um link no topo aparecerá, parecido com este:
👉 `https://seu-usuario.github.io/carteirinha-pet/`

Este é o link que você deve colocar no gerador de QR Code para gravar na SmartTag!
