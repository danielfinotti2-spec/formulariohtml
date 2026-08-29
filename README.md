# Portfólio pessoal

Modelo de portfólio responsivo feito com HTML e CSS. O projeto contém página inicial, apresentação, projetos e contato, além de um exemplo de código Python com destaque de sintaxe.

## Como executar

Não é necessário instalar dependências.

1. Baixe ou clone o projeto.
2. Abra a pasta do projeto.
3. Abra `index.html` no navegador.

Para desenvolver com atualização automática, você também pode usar a extensão Live Server do Visual Studio Code.

## Estrutura

```text
.
├── index.html       # Página inicial
├── sobre.html       # Apresentação
├── projetos.html    # Projetos
├── contato.html     # Formas de contato
├── css/
│   └── style.css    # Aparência e responsividade
└── img/             # Fotos, imagens e GIFs
```

## Personalização

Antes de publicar, pesquise e substitua os seguintes valores de exemplo:

| Dado | Valor de exemplo |
| --- | --- |
| Nome | `Daniel Finotti` |
| E-mail | `seuemail@example.com` |
| GitHub | `github.com/seu-usuario` |
| Instagram | `instagram.com/seu-usuario` |
| WhatsApp | `wa.me/5500000000000` |
| Localização | `Sua cidade` |

Troque também `img/logo.png` pela sua imagem. Se não quiser publicar uma foto pessoal, use um avatar, ilustração ou logotipo.

## Privacidade

O modelo não inclui telefone, e-mail, idade, bairro ou localização real. Evite publicar documentos, endereço residencial, data de nascimento completa ou qualquer informação que não queira tornar pública.

Antes de enviar o projeto ao GitHub, faça uma busca final:

```bash
rg -n "mailto:|wa.me|instagram.com|github.com|idade|endereço" .
```

## Tecnologias

- HTML5
- CSS3
- Font Awesome
- Google Fonts

As fontes e os ícones são carregados por CDN, portanto precisam de internet para aparecer na primeira visita.

## Responsividade

O layout possui ajustes para computadores, tablets e celulares. Os principais breakpoints estão em `css/style.css`.

## Licença

Consulte o arquivo `LICENSE` antes de reutilizar ou distribuir o projeto.
