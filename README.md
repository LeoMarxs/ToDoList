# 📝 Minhas Tarefas - Minimalist To-Do List

Uma aplicação web de gerenciamento de tarefas (To-Do List) focada em produtividade, com design minimalista, suporte a temas (claro/escuro) e integração com calendários.

---

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Hospedado-222222?style=for-the-badge&logo=github)](https://leomarxs.github.io/ToDoList/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)


## ✨ Funcionalidades

* **Gestão de Tarefas:** Adicione, conclua e exclua tarefas com uma interface intuitiva.
* **Priorização:** Classifique atividades por níveis (Alta, Média, Baixa) com indicadores visuais.
* **Categorização:** Organize seus afazeres por Trabalho, Pessoal, Estudos, Saúde ou Financeiro.
* **Gestão de Prazos:** * Visualização de data de vencimento.
    * Alertas visuais para tarefas **Atrasadas** ou que **Vencem hoje**.
* **Painel de Estatísticas:** Acompanhe o total de tarefas, itens concluídos e o progresso percentual do dia.
* **Filtros Inteligentes:** Alterne rapidamente entre:
    * Todas as tarefas.
    * Apenas pendentes ou concluídas.
    * Alta prioridade.
    * Prazos críticos (Hoje/Atrasadas).
* **Integração com Google Calendar:**
    * Botão direto para criar evento no Google Agenda por tarefa.
    * Exportação de todas as tarefas com prazo para arquivo `.ics` (iCalendar).
* **Persistência Local:** Utiliza `localStorage` para manter seus dados salvos mesmo após fechar o navegador.
* **Dark Mode Nativo:** Ajusta-se automaticamente às preferências de cores do seu sistema operacional.

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando o conceito de **Vanilla Web Development** (sem frameworks externos):

* **HTML5:** Estrutura semântica e acessível.
* **CSS3:** Design responsivo, CSS Variables, Flexbox e Grid.
* **JavaScript (ES6+):** Lógica de estado, manipulação de DOM e geração de arquivos Blob para exportação.
* **Google Fonts:** Tipografia moderna com as fontes *DM Sans* e *DM Mono*.

## 📦 Como Instalar e Rodar

Não é necessário configurar um servidor ou instalar dependências.

1.  Baixe o arquivo `index.html`.
2.  Abra o arquivo diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
3.  Pronto! Suas tarefas serão salvas localmente no seu dispositivo.

## 📅 Como exportar para o Calendário

Para sincronizar suas tarefas com o **Google Agenda**:
1.  Certifique-se de que a tarefa possui uma data de vencimento.
2.  Clique no ícone de calendário no topo da página.
3.  Clique em **Exportar .ics**.
4.  No Google Agenda, vá em `Configurações > Importar e Exportar` e faça o upload do arquivo baixado.

---

## 🛠️ Personalização

Você pode ajustar o visual do sistema editando as variáveis de CSS no topo do código:

```css
:root {
  --accent: #1a7a5e;    /* Cor principal do sistema */
  --radius: 10px;       /* Arredondamento dos elementos */
  --bg: #f5f4f0;        /* Cor de fundo do modo claro */
}
