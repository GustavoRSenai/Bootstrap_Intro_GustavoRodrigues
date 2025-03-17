# Exercício 8: Carossel com Bootstrap

**Objetivo:** Criar um carossel (slideshow) responsivo utilizando Bootstrap, demonstrando a implementação de um componente de apresentação de imagens com controles de navegação.

---
## Descrição:
Este exercício demonstra a criação de um carossel Bootstrap, que é um slideshow para apresentação de imagens em sequência. O carossel inclui controles de navegação e transições automáticas entre os slides.

---
## Passo 1: Configuração Inicial
1. **Dependências Bootstrap:**
   - Incluir CSS do Bootstrap via CDN
   - Adicionar JavaScript do Bootstrap no final do body
2. **Estrutura Base:**
   - Container principal com margem superior
   - Área definida para o carossel

---
## Passo 2: Estrutura do Carossel
1. **Container Principal:**
   - ID único para referência
   - Classes `carousel slide`
   - Atributo `data-bs-ride="carousel"`
2. **Inner Container:**
   - Classe `carousel-inner`
   - Contém todos os slides

---
## Passo 3: Slides
1. **Items do Carossel:**
   - Classe `carousel-item`
   - Primeiro item com classe `active`
2. **Imagens:**
   - Classes `d-block w-100`
   - Atributos alt para acessibilidade
   - Dimensões consistentes

---
## Passo 4: Controles de Navegação
1. **Botões de Navegação:**
   - Botão anterior com `carousel-control-prev`
   - Botão próximo com `carousel-control-next`
2. **Ícones dos Controles:**
   - Ícones com classes específicas
   - Posicionamento automático

---
## Conceitos Importantes:
1. **Classes Essenciais:**
   - `carousel`: Container principal
   - `carousel-inner`: Wrapper dos slides
   - `carousel-item`: Cada slide individual
   - `carousel-control-prev/next`: Controles de navegação

2. **Atributos de Dados:**
   - `data-bs-ride`: Controle de autoplay
   - `data-bs-target`: Referência ao caroussel
   - `data-bs-slide`: Direção da navegação

3. **Estrutura de Imagens:**
   - Uso de classes para responsividade
   - Dimensionamento apropriado
   - Alternativas para acessibilidade

---
## Explicação:
Este exercício demonstra a implementação de um caroussel Bootstrap, um componente popular para apresentação de conteúdo visual em sequência.

- **Funcionalidade Automática:** O caroussel inicia automaticamente a apresentação dos slides.
- **Controles Intuitivos:** Oferece navegação através de botões nas laterais.
- **Responsividade:** Adapta-se automaticamente ao tamanho da tela do dispositivo.
- **Performance:** Utiliza o sistema de carregamento otimizado do Bootstrap.
- **Flexibilidade:** Permite a inclusão de diferentes tipos de conteúdo além de imagens.