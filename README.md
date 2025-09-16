# 🧪 Dosatron 9000 - Análise de Dados Científicos

## 📋 Descrição do Projeto

Sistema de análise de dados científicos desenvolvido em Python com interface gráfica interativa. Permite visualizar, selecionar e analisar dados em formato de planilha com cálculo automático de regressão linear. Ferramenta especializada para cálculo de Ácido Hexurônico em amostras de heparina.

## 🛠️ Funcionalidades

- ✅ **Interface de Planilha Interativa** - Visualização e edição de dados em formato tabular
- ✅ **Seleção de Dados** - Seleção flexível de células para análise
- ✅ **Plotagem de Gráficos** - Geração automática de gráficos de dispersão
- ✅ **Regressão Linear** - Cálculo automático de inclinação (slope) com numpy.linalg.lstsq
- ✅ **Suporte Bilíngue** - Interface em português e compatibilidade com dados em inglês
- ✅ **Cálculo de Ácido Hexurônico** - Especializado para análise de amostras de heparina

## ✨ Tecnologias Utilizadas

- **Python 3.x** - Linguagem de programação principal
- **Tkinter** - Framework para interface gráfica
- **tksheet** - Componente de planilha interativa
- **Matplotlib** - Visualização de gráficos e plots
- **NumPy** - Cálculos científicos e análise numérica

## 🚀 Como Executar o Projeto

### Pré-requisitos
- [Python 3.6 ou superior](https://www.python.org/downloads/)
- Gerenciador de pacotes pip
- Git (para clonar o repositório)

### Passos para Executar

1. **Clone o repositório:**
```bash
git clone https://github.com/seuusuario/dosatron-9000.git
cd dosatron-9000
```
2.**Instale as dependências:**
```bash
pip install -r requirements.txt
```
3. **Execute o programa:**
```bash
python origin_2.py
```

## Instalação manual das dependências

Caso não tenha um arquivo requirements.txt, instale as bibliotecas manualmente:
```bash
pip install tkinter tksheet matplotlib numpy
```

## 📊 Como Utilizar

1. Preencha os dados na planilha interativa:
	৹ A primeira linha contém as legendas das colunas.
	৹ A primeira coluna (coluna 0) é sempre usada como eixo X.
	৹ Os demais dados numéricos serão plotados no eixo Y.

2. Selecione as células que deseja analisar (incluindo legendas e dados).

3. Clique em "Plotar Selecionados" para gerar o gráfico com:
	৹ Pontos de dispersão para cada série de dados.
	৹ Linhas de regressão linear calculadas automaticamente.
	৹ Legenda com os nomes das séries e valores de inclinação (slope).

## 🧮 Cálculos Realizados

O programa utiliza o método dos mínimos quadrados (numpy.linalg.lstsq) para calcular:

   • Inclinação (slope) da reta de regressão linear.
   • Intercepto (não exibido no gráfico atual).
   • Valores preditos para a linha de tendência.

## 🎨 Personalização

O código permite personalizações como:

   • Alterar cores de fundo da tabela (table_bg).
   • Modificar dimensões da janela principal.
   • Adaptar estilos dos gráficos (cores, marcadores, etc.).

## 🤝 Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature ```git checkout -b feature/AmazingFeature```
3. Commit suas mudanças ```git commit -m 'Add some AmazingFeature'```
4. Push para a branch ```git push origin feature/AmazingFeature```
5. Abra um Pull Request.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/Marcos-Rob/Dosatron-9000?tab=MIT-1-ov-file) para mais detalhes.