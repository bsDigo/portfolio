# Portfólio — Rodrigo Benato

Site estático em português, responsivo, com quatro páginas e sem dependências de instalação. Abra `index.html` para visualizar no computador.

## Publicar

Envie o conteúdo desta pasta a um repositório GitHub e importe o repositório na Vercel. Selecione o preset **Other**, deixe o comando de build vazio e use a raiz do projeto como diretório de saída. O projeto também funciona em qualquer hospedagem de arquivos estáticos. Depois de publicar, adicione a URL no Linktree.

## Editar

- `index.html`: apresentação, formação, experiência e contato.
- `projetos.html`: sete projetos, descrições e tecnologias.
- `habilidades.html`: habilidades e idiomas.
- `certificados.html`: página preparada; aguarda nome, instituição, data e arquivo do certificado.
- `style.css`: aparência e regras de adaptação para celular.
- `script.js`: menu mobile e ano do rodapé.
- `assets/`: foto e cartão originais. O monograma é mostrado por recorte visual em CSS para preservar o desenho fornecido. O favicon usa as iniciais RB.

As imagens ficam locais e não dependem de serviços externos. Não há formulário, coleta de dados, chaves de API ou backend. Os projetos restritos são apresentados por descrição, sem links de acesso. O ganho de tempo do gerador é identificado como estimativa pessoal; não é garantia de desempenho ou conformidade jurídica. Atualize períodos acadêmicos e descrições quando necessário.

## Adicionar um certificado

Coloque o PDF em `assets/certificados/`, remova o bloco `certificate-empty` de `certificados.html` e insira um artigo com título do curso, instituição, data, carga horária real e um link para o arquivo. Não publique informações pessoais desnecessárias do documento.

## Atualização visual

Versão revisada: apresentação pelo nome, textos em primeira pessoa, projetos em lista e aparência predominantemente preta e branca. Para atualizar um repositório existente, substitua os arquivos do site preservando a pasta `.git`, depois faça commit e push. Os prints poderão ser adicionados aos artigos em `projetos.html`.
