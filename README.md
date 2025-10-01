# 🔐 Formulário de Login - Tailwind CSS

Projeto de estudo desenvolvido para praticar a criação de interfaces visuais utilizando **TailwindCSS**. Este formulário de login foi criado seguindo um guia de estilos específico, aplicando classes utilitárias para cores, espaçamento, bordas e tipografia.

![Preview do Formulário](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

## 📋 Sobre o Projeto

Este exercício tem como objetivo treinar a criação da **interface visual** de um formulário de login utilizando exclusivamente **TailwindCSS** para a estilização. O foco é aplicar corretamente as classes utilitárias seguindo um guia de estilos específico.

### ✨ Funcionalidades

O formulário contém:
- ✅ Campo para **nome de usuário ou e-mail**
- ✅ Campo para **senha**
- ✅ Botão de ação "Entrar"
- ✅ Checkbox "Lembrar de mim"
- ✅ Link "Esqueceu a senha?"
- ✅ Link para cadastro

## 🎨 Guia de Estilos

O projeto segue o seguinte guia de estilos:

| Elemento | Estilo | Valor |
|----------|--------|-------|
| Cor das bordas | `border-color` | `#6528D3` |
| Cor do botão | `background-color` | `#6528D3` |
| Cor de fundo dos inputs | `background-color` | `#130234` |
| Arredondamento das bordas | `border-radius` | `4px` |

## 🚀 Como Executar

### Pré-requisitos

- Node.js instalado na máquina
- NPM ou Yarn

### Instalação

1. Clone este repositório:
```bash
git clone https://github.com/DevAlex-full/formulario-login-tailwind.git
```

2. Acesse a pasta do projeto:
```bash
cd formulario-login-tailwind
```

3. Instale as dependências:
```bash
npm install
```

4. Compile o Tailwind CSS:
```bash
npx tailwindcss -i ./input.css -o ./output.css --watch
```

5. Abra o arquivo `index.html` no navegador ou utilize uma extensão como **Live Server** do VSCode.

## 📁 Estrutura do Projeto

```
formulario-login-tailwind/
├── index.html           # Estrutura HTML do formulário
├── input.css            # Arquivo CSS com estilos customizados
├── output.css           # Arquivo CSS gerado pelo Tailwind (não versionar)
├── tailwind.config.js   # Configuração do TailwindCSS
├── package.json         # Dependências do projeto
└── README.md            # Documentação do projeto
```

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **TailwindCSS** - Framework CSS utilitário para estilização
- **Node.js** - Ambiente de execução para compilar o Tailwind

## 📸 Preview

O formulário apresenta um design moderno com:
- Fundo escuro (`bg-gray-900`)
- Inputs com fundo roxo escuro (`#130234`)
- Bordas e botão em roxo vibrante (`#6528D3`)
- Layout responsivo e centralizado
- Efeitos de hover e foco nos elementos interativos

## 📝 Aprendizados

Durante este exercício, pratiquei:
- Utilização de classes utilitárias do Tailwind CSS
- Configuração local do Tailwind CSS
- Aplicação de estilos customizados com cores específicas
- Criação de layouts responsivos
- Estruturação semântica de formulários HTML

## 👨‍💻 Autor

**Alex**
- GitHub: [@DevAlex-full](https://github.com/DevAlex-full)

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais e está livre para uso.

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!
