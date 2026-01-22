# Organograma da 2ª Cia Com Mec

Representação visual e estruturada da hierarquia e seções da 2ª Companhia de Comunicações Mecanizada.

## 📋 Descrição

Este projeto contém o organograma completo da 2ª Cia Com Mec, incluindo:
- Estrutura de comando
- Todas as seções e seus integrantes
- Hierarquia organizacional

## 🚀 Como Visualizar Localmente

### Opção 1: Visualização Interativa (Recomendado)

1. **Baixe o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/secoes.git
   cd secoes
   ```

2. **Abra o arquivo HTML no navegador:**
   - Navegue até a pasta do projeto
   - Dê duplo clique no arquivo `index.html`
   - OU abra seu navegador e pressione `Ctrl+O`, depois selecione `index.html`

3. **Recursos disponíveis:**
   - ✨ Zoom com botões `+` e `-`
   - 🖱️ Arraste o diagrama clicando e movendo
   - ⌨️ Zoom com `Ctrl + Scroll` do mouse
   - 🔄 Botão reset para voltar ao estado inicial
   - 📱 Compatível com dispositivos móveis

### Opção 2: Visualização no GitHub

Basta acessar este repositório no GitHub para ver o diagrama Mermaid renderizado automaticamente.

## 📁 Arquivos do Projeto

- `index.html` - Página interativa com zoom e navegação
- `README.md` - Este arquivo

## ✏️ Como Editar e Adicionar Militares

Para adicionar ou editar militares no organograma, siga estes passos:

### 1. Abra o arquivo `index.html` em um editor de texto

Você pode usar qualquer editor como:
- Notepad/Bloco de Notas
- VS Code
- Notepad++
- Sublime Text

### 2. Localize a seção do diagrama Mermaid

Procure pela tag `<div class="mermaid">` no arquivo. O diagrama está entre as linhas que começam com `graph TB`.

### 3. Adicionar um novo militar a uma seção existente

**Exemplo: Adicionar um militar à SEÇÃO S1**

Localize a última linha da SEÇÃO S1:
```
S1_5 --> S1_6[3º Sgt NASCIMENTO]
```

Adicione abaixo:
```
S1_6 --> S1_7[Posto NOME_DO_MILITAR]
```

### 4. Criar uma nova seção

**Exemplo: Adicionar SEÇÃO COMUNICAÇÕES**

1. Conecte a nova seção ao SCMT:
```
SCMT --> COMUNICACOES[SEÇÃO COMUNICAÇÕES]
```

2. Adicione os integrantes da seção:
```
COMUNICACOES --> COM_1[1º Sgt NOME_CHEFE]
COM_1 --> COM_2[3º Sgt NOME_INTEGRANTE]
```

### 5. Alterar cores (opcional)

No final do diagrama, antes de `</div>`, adicione:
```
style NOME_DA_SECAO fill:#cor_em_hexadecimal
```

Exemplos de cores:
- `#ff9999` - Vermelho claro
- `#ffcc99` - Laranja claro
- `#99ff99` - Verde claro
- `#99ccff` - Azul claro

### 6. Salve e teste

1. Salve o arquivo `index.html`
2. Abra-o no navegador para verificar as alterações
3. Se necessário, ajuste o código e recarregue a página (F5)

### Exemplo Completo

```mermaid
SCMT --> NOVA_SECAO[NOVA SEÇÃO]
NOVA_SECAO --> NS_1[Cap COMANDANTE]
NS_1 --> NS_2[1º Ten ADJUNTO]
NS_2 --> NS_3[3º Sgt OPERADOR]
style NOVA_SECAO fill:#ccffcc
```

## 🛠️ Tecnologias Utilizadas

- **Mermaid.js** - Geração de diagramas
- **HTML5/CSS3** - Interface visual
- **JavaScript** - Interatividade e controles de zoom

## 📝 Licença

© 2026 2ª Cia Com Mec - Todos os direitos reservados

---

**Atualizado em:** Janeiro de 2026