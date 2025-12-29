# 🛰️ Gerador de Relatórios - Yukaline Internet

Este é um sistema dinâmico e offline desenvolvido para a **Yukaline Internet**, focado na padronização e agilidade na criação de relatórios técnicos de derivações de fibras ópticas em Caixas de Emenda (CE).

## 🚀 Funcionalidades

- **Edição em Tempo Real:** Altere títulos, nomes de projetistas e dados de cabos com visualização instantânea.
- **Cálculo Automático de Portas:** O sistema identifica números de portas nas descrições e calcula o total por cabo e o total geral da CE.
- **Gestão Dinâmica de Cabos:** Adicione ou remova blocos de cabos conforme a necessidade do projeto.
- **Identidade Visual:** Totalmente personalizado com as cores (Azul e Amarelo) e logo da Yukaline.
- **Exportação para PDF:** Utiliza a função de impressão nativa do navegador para gerar arquivos PDF de alta qualidade, funcionando 100% offline.

## 🛠️ Como Utilizar

1. **Download:** Baixe o arquivo `index.html`.
2. **Abertura:** Abra o arquivo em qualquer navegador moderno (Chrome, Edge ou Firefox).
3. **Preenchimento:**
   - Insira o nome do **Projetista Responsável**.
   - Defina a **Identificação da CE**.
   - Adicione os cabos e descreva as fibras seguindo o padrão: `F1 -> Descrição - 16 portas`.
4. **Geração do PDF:**
   - Clique no botão **"GERAR RELATÓRIO PDF"**.
   - Na tela de impressão, em **Destino**, escolha **"Salvar como PDF"**.
   - **Importante:** Nas configurações de impressão, marque a opção **"Gráficos de segundo plano"** para manter as cores e estilos.

## 📊 Regra de Cálculo

O gerador possui um algoritmo que busca por padrões numéricos nas descrições. 
> **Exemplo:** Se você escrever `F1 -> Splitter 1/16 - 16 portas`, o sistema somará automaticamente **16** ao total do cabo.

## 📂 Estrutura do Arquivo

├── index.html        # Arquivo único contendo Estrutura, Estilo e Lógica.
└── imgs/             # (Opcional) Pasta local para armazenamento da logo.
