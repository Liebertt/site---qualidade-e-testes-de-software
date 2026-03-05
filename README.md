# Planejamento do Projeto: Site Estático

## 📋 Fase 1: Definições Gerais e Setup

Nesta etapa, o grupo define a identidade visual para que as páginas não fiquem desproporcionais entre si.

* **Definição do Tema**: Ex: Loja de periféricos de informática.

* **Guia de Estilo**:

  * Cores primárias e secundárias (Hexadecimal).

  * Tipografia (Google Fonts).

  * Padrão de botões e espaçamentos (Padding/Margin).

* **Criação do Repositório**: 
  * Líder cria o repo no GitHub.

  * Adiciona os outros 3 membros como colaboradores.

  * Sobe o `index.html` básico e o `style.css` global.


## 🛠️ Fase 2: Divisão de Tarefas e Branches
Conforme sua ideia, cada membro terá uma branch específica.

| Membro | Branch Sugerida | Responsabilidade |
|--------|-----------------|------------------|
| **Membro 1** | `home-nome` | Header (menu), Banner principal e Destaques. |
| **Membro 2** | `produtos-nome` | Grade de produtos, cards com preços e imagens. |
| **Membro 3** | `sobre-nome` | Seção institucional, história e fotos da equipe. |
| **Membro 4** | `contato-nome` | Formulário, Rodapé e links de redes sociais. |

## 💻 Fase 3: Desenvolvimento Individual

Cada aluno trabalha isolado em sua branch para evitar conflitos imediatos.

1. `git checkout -b nome-da-branch`

2. Criação do conteúdo HTML semântico.

3. Estilização CSS seguindo o guia de estilo da Fase 1.

4. `git add .` -> `git commit -m "feat: estrutura da pagina X"`

5. `git push origin nome-da-branch`

## Fase 4: Integração (Merge) e Ajustes

O momento de unir as peças no ramo principal.

* **Pull Requests**: Abrir solicitações de mesclagem no GitHub.

* **Code Review**: Os membros revisam se o código do colega não quebra o layout.

* **Merge**: Unir as branches à branch main.

* **Resolução de Conflitos**: Ajustar seletores CSS que possam estar colidindo.

## 🚀 Fase 5: Deploy e Documentação

Finalização e entrega conforme os requisitos da imagem.

* **GitHub Pages**: Ativar o deploy nas configurações do repositório.

* **Teste Final**: Verificar se links de navegação entre as páginas estão funcionando.

* **Relatório** (Word):

  * Prints do gráfico de rede do GitHub (mostrando as ramificações).

  * Prints dos commits realizados.

  * Print do site no navegador.

  * Link final da URL do GitHub Pages.

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/105327109?v=4" width="100px;" alt="Lieberte "/><br>
        <sub>
          <b>Lieberte</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/141886542?v=4" width="100px;" alt="Foto do Mark Zuckerberg"/><br>
        <sub>
          <b>Thiago</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://miro.medium.com/max/360/0*1SkS3mSorArvY9kS.jpg" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Cristiano</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://miro.medium.com/max/360/0*1SkS3mSorArvY9kS.jpg" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Felipe</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
