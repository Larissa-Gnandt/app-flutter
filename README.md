# Aplicativo Flutter - Layout Complexo

Aplicativo Flutter completo sobre o **Lago Oeschinen** que demonstra a construção de layouts complexos seguindo uma abordagem estruturada de desenvolvimento.

## ✅ Status do Projeto
- [x] Passo 1: Configuração do Ambiente
- [x] Passo 2: Estrutura Inicial
- [x] Passo 3: Divisão do Layout
- [x] Passo 4: Diagramação do Layout
- [x] Passo 5: Construção da Seção de Título
- [x] Passo 6: Construção da Seção de Botões
- [x] Passo 7: Definição da Seção de Texto
- [x] Passo 8: Adicionando uma Imagem
- [x] Passo 9: Organizando os Elementos em uma ListView

## 📱 Sobre o Projeto

**Objetivo:** Criar uma plataforma onde clientes possam compartilhar avaliações e comentários sobre suas experiências de viagem, utilizando widgets interativos do Flutter.

## 🚀 Como Executar

```bash
flutter pub get
flutter run -d chrome
```

## 🏗️ Implementação por Passos

### **Passo 1: Configuração do Ambiente**
- ✅ Flutter SDK instalado
- ✅ Novo aplicativo Flutter criado

### **Passo 2: Estrutura Inicial**
- ✅ MaterialApp como widget raiz
- ✅ Scaffold com AppBar e body
- ✅ Estrutura básica com "Hello World"

### **Passo 3: Divisão do Layout**
- ✅ Identificação de componentes principais
- ✅ Planejamento de estrutura hierárquica
- ✅ Definição de espaçamentos e alinhamentos

### **Passo 4: Diagramação do Layout**
- ✅ **4 elementos principais:** Imagem, Seção Título, Seção Button, Bloco de Texto
- ✅ **Seção Título:** Coluna de texto (Expanded) + Ícone estrela + Número
- ✅ **Seção Button:** 3 colunas (CALL, ROUTE, SHARE)
- ✅ **Abordagem de baixo para cima**
- ✅ **Organização do código** com variáveis e funções

### **Passo 5: Construção da Seção de Título**
- ✅ Container com padding de 32px
- ✅ Expanded para ocupar espaço disponível
- ✅ CrossAxisAlignment.start para alinhamento à esquerda
- ✅ Ícone de estrela vermelha com avaliação "41"

### **Passo 6: Construção da Seção de Botões**
- ✅ Método auxiliar `_buildButtonColumn()` reutilizável
- ✅ Cores do tema aplicadas automaticamente
- ✅ MainAxisAlignment.spaceEvenly para distribuição uniforme
- ✅ Três botões: CALL, ROUTE, SHARE

### **Passo 7: Definição da Seção de Texto**
- ✅ Container com padding de 32px
- ✅ softWrap: true para quebras de linha automáticas
- ✅ Texto descritivo completo sobre o lago

### **Passo 8: Adicionando uma Imagem**
- ✅ Diretório `images/` criado
- ✅ Imagem `lake.jpg` adicionada
- ✅ `pubspec.yaml` configurado com assets
- ✅ Image.asset com dimensões 600x240px e BoxFit.cover

### **Passo 9: Organizando os Elementos em uma ListView**
- ✅ Column substituída por ListView
- ✅ Suporte à rolagem vertical
- ✅ Experiência flexível em diferentes tamanhos de tela

## 📋 Funcionalidades

### **Interface:**
- **AppBar** com título "Demonstração de layout Flutter"
- **Imagem** do lago no topo
- **Seção de título** com nome, localização e avaliação ⭐ 41
- **Seção de botões** com três ações interativas
- **Texto descritivo** sobre o local
- **Rolagem** vertical quando necessário

### **Técnicas:**
- Design responsivo para diferentes dispositivos
- Assets configurados e funcionando
- Cores do tema aplicadas automaticamente
- Código organizado com comentários dos passos

## 🛠️ Tecnologias

- **Flutter 3.35.4**
- **Dart 3.9.2**
- **Material Design**
- **Assets (imagens)**
- **ListView para rolagem**

## 📁 Estrutura

```
lib/main.dart          # Código principal
images/lake.jpg        # Imagem do lago
pubspec.yaml          # Configuração de assets
```

## 🎯 Resultados ✨

Aplicativo completo com estrutura básica do Flutter, garantindo interfaces responsivas e acessíveis em dispositivos móveis, tablets e desktops.

Plataforma para clientes compartilharem avaliações e comentários sobre experiências de viagem, utilizando widgets interativos do Flutter para exibir avaliações e interagir com usuários de forma envolvente.

## 🔧 Comandos

```bash
flutter run -d chrome    # Executar no Chrome
flutter analyze          # Verificar erros
flutter pub get          # Atualizar dependências
```

---

Desenvolvido com ❤️ usando Flutter