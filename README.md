# G300 - Agenda do Grupo

Uma aplicação web moderna para gerenciar a agenda do grupo de homens G300 - Rede de Homens.

## 🚀 Características

- **Design Moderno**: Interface glassmorphism com tema dourado
- **Integração Google Sheets**: Sincronização automática com planilhas do Google
- **Responsivo**: Funciona perfeitamente em desktop e mobile
- **Tema Escuro/Claro**: Alternância entre temas
- **Dados Locais**: Armazenamento local para funcionalidade offline

## 📋 Como Usar

1. **Configurar o Logo**:
   - Salve sua imagem do logo G300 na pasta `images/` com o nome `g300-logo.jpg`
   - Formatos suportados: JPG, PNG, GIF
   - Tamanho recomendado: 400x400px ou superior (quadrado)

2. **Configurar Google Sheets**:
   - Abra sua planilha no Google Sheets
   - Clique em "Compartilhar" → "Alterar para qualquer pessoa com o link"
   - Defina como "Visualizador"
   - Clique em "🔄 Atualizar do Sheets" na aplicação

3. **Estrutura da Planilha**:
   ```
   Data          | Nome/Evento        | Status/Observações
   20/05/2025    | Carlos            | 
   10/06/2025    | Gerson            | Palavra: Junior G300
   17/06/2025    | Tonyglay          | Desmarcado (substituto: irmão Oziel)
   ```

## 📁 Estrutura do Projeto

```
G300-Agenda/
├── index.html          # Aplicação principal
├── images/             # Pasta para imagens
│   └── g300-logo.jpg   # Logo do G300 (você precisa adicionar)
└── README.md          # Este arquivo
```

## 🎨 Personalização

### Cores do Tema
As cores principais podem ser alteradas no CSS:
- **Dourado**: `#d4af37`, `#ffd700`, `#ffed4e`
- **Marrom Escuro**: `#2d1b14`
- **Gradientes**: Definidos nas variáveis CSS

### Logo
- Coloque sua imagem na pasta `images/` com o nome `g300-logo.jpg`
- Se a imagem não carregar, um logo de fallback será exibido
- O logo é automaticamente redimensionado para 120x120px

## 🔧 Funcionalidades

- ✅ Adicionar eventos à agenda
- ✅ Sincronizar com Google Sheets
- ✅ Visualizar agenda cronológica
- ✅ Modo escuro/claro
- ✅ Armazenamento local
- ✅ Design responsivo
- ✅ Indicadores visuais para datas (passado/presente/futuro)

## 📱 Compatibilidade

- ✅ Chrome/Edge (Recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile (iOS/Android)

## 🙏 Grupo G300

**Rede de Homens**  
📅 Toda Terça-feira às 19h30

---

Desenvolvido com ❤️ para o ministério masculino G300
