# una-blazor-lista12

# 🌍 EcoMonitor - Blazor Lista 12

## 👤 Identificação
- *Nome:* Lucas Henrique Miranda
- *Curso:* Análise e Desenvolvimento de Sistemas

---

## 💡 Descrição
Esta aplicação Blazor monitora ações sustentáveis, utilizando componentes reutilizáveis para calcular o impacto ambiental positivo. O projeto foca em interatividade e componentização avançada.

---

## 🧠 Heurísticas de Nielsen Aplicadas
1. *Visibilidade do Status do Sistema:* O usuário recebe feedback imediato através de um contador dinâmico, uma barra de progresso visual e mudanças de cores (Azul, Amarelo e Verde) que indicam o nível de impacto atingido.
2. *Reconhecimento em vez de Recordação:* A interface utiliza ícones (🌎, 🏆, 🌱) e cores semânticas para que o usuário identifique o status de cada atividade sem precisar memorizar regras de pontuação.

---

## 🛠️ Guia de Execução
Para rodar o projeto via terminal:

1. *Acesse a pasta:* cd una-blazor-lista12
2. *Execute o comando:* dotnet watch run
3. *Acesse no navegador:* https://localhost:5001 (ou a porta indicada no terminal).

---

## ⚙️ Explicação Técnica: [Parameter]
O atributo [Parameter] foi essencial para tornar o componente EcoStatus.razor reutilizável. Ele permite que a página Home.razor envie dados específicos para cada instância do componente:
- *Atividade:* Define o nome da ação (ex: Plantio de Árvores).
- *Peso:* Define o valor de pontos ganho por clique.
Isso permite usar o mesmo código visual para múltiplas funcionalidades.

---

## 📦 Funcionalidades e Desafios (Diferenciais)
- *Estado Dinâmico:* Soma de impacto individual e geral.
- *Barra de Progresso:* Feedback visual do avanço até a meta.
- *Mensagem de Conquista:* Alerta especial ao atingir 100 pontos: "Você é um Herói do Planeta!".
- *Estilização Adaptativa:* Alteração automática de cores conforme a pontuação.
