# Contra-Egum - Contexto do Projeto

## Descrição
Projeto de contador regressivo (countdown timer) para a retirada do contra-egum. Uma página web simples e visual que mostra quanto tempo falta até uma data específica.

## Tecnologias
- HTML5
- CSS3
- JavaScript (Vanilla)
- GitHub Pages (hospedagem)

## Estrutura do Projeto
```
contra-egum/
├── index.html      # Página principal
├── style.css       # Estilos
├── script.js       # Lógica do contador
├── README.md       # Documentação
└── CLAUDE.md       # Contexto do projeto
```

## Design Visual
O projeto passou por iterações de design, com a versão atual apresentando:

### Paleta de Cores
- **Fundo**: Gradiente verde (#4CAF50) → branco (#ffffff)
  - Enfoque maior no branco para um visual mais limpo
- **Texto principal**: Vermelho (#d32f2f)
  - Título
  - Números do contador
  - Labels (Dias, Horas, Minutos, Segundos)
- **Efeitos**: Sombra branca nos números para melhor visibilidade

### Estilo
- Design minimalista e clean
- **Sem bordas** nos boxes dos números
- Apenas números com sombra branca para destaque
- Layout responsivo para mobile

## Data Alvo
- **Data**: 24 de maio de 2026 às 18:00 (horário de Brasília)
- Definida em `script.js` na variável `targetDate`

## GitHub
- **Repositório**: https://github.com/greglixandrao/contra-egum
- **GitHub Pages**: https://greglixandrao.github.io/contra-egum/
- **Branch principal**: main

## Decisões de Design
1. Removidas as molduras/bordas dos boxes para visual mais limpo
2. Mudança do gradiente azul para verde→branco por preferência visual
3. Cores vermelhas para dar destaque e urgência ao contador
4. Sombra branca nos números para garantir legibilidade

## Como Desenvolver Localmente
```bash
# Clonar o repositório
git clone https://github.com/greglixandrao/contra-egum.git
cd contra-egum

# Iniciar servidor local
python3 -m http.server 8080

# Acessar no navegador
# http://localhost:8080
```

## Notas
- O projeto usa apenas tecnologias nativas (sem frameworks)
- GitHub Pages atualiza automaticamente após push para main
- Design otimizado para visualização em desktop e mobile
