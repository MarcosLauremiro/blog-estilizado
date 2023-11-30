# Documentação - Blog da Kenzie

Este documento fornece uma visão geral do projeto "Blog da Kenzie". Aqui, você encontrará informações sobre a estrutura do HTML, o uso de estilos CSS e o propósito de cada seção.

## Estrutura do HTML

### Doctype e Declaração de Idioma
```html
<!DOCTYPE html>
<html lang="pt-br">
```

O doctype define a versão do HTML e o idioma do documento.

### Cabeçalho (Head)
```html
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog da Kenzie</title>
    <link rel="stylesheet" href="css/style.css">
</head>
```

O cabeçalho contém informações importantes sobre o documento, como o conjunto de caracteres, a compatibilidade com o navegador, a configuração da viewport e a inclusão de uma folha de estilo externa.

### Corpo (Body)
```html
<body>
    <header>
        <h1>Kenzie</h1>
    </header>
    <!-- ... -->
</body>
```

O corpo contém o conteúdo principal da página, incluindo o cabeçalho, o menu de navegação, e as seções principais.

### Seções Principais
```html
<main>
    <section class="artigos">
        <article id="do_zero">
            <!-- ... -->
        </article>
        <!-- Outros artigos -->
    </section>

    <section class="info">
        <!-- ... -->
    </section>
</main>
```

As seções principais incluem artigos e informações adicionais. Cada artigo tem um identificador único (`id`), e há uma seção dedicada para informações sobre o blog.

## Artigos
Cada artigo segue uma estrutura semelhante:
```html
<article id="do_zero">
    <h2>COMO APRENDER A PROGRAMAR DO ZERO: PASSO A PASSO</h2>
    <h3>Por que aprender programação é importante?</h3>
    <p class="conteudo_artigo"> <!-- Conteúdo do artigo --> </p>
    <p><a target="_blank" href="https://kenzie.com.br/blog/como-aprender-a-programar-2/">continue lendo...</a></p>
    <p class="autor">Por <cite>Daniel Kriger</cite></p>   
</article>
```

Cada artigo inclui um título, subtítulo, conteúdo, um link para continuar lendo, e informações sobre o autor.

## Seção de Inscrição
```html
<section class="info">
    <h2>Deseja receber nossas notícias em primeira mão?</h2>
    <p>Basta deixar seu <strong>e-mail</strong> e será notificado sempre que houver novas notícias.</p>
    <form action="">
        <label for="email">E-mail</label>
        <input type="email" name="email" id="email" placeholder="Deixe seu email aqui..." required>
        <button type="submit">Enviar</button>
    </form>
</section>
```

A seção de informações inclui um formulário simples para os visitantes se inscreverem para receber notícias por e-mail.

## Estilos CSS
```html
<link rel="stylesheet" href="css/style.css">
```

Os estilos CSS são mantidos em um arquivo separado (style.css) para melhor organização. Eles são vinculados ao HTML para estilizar o layout e a aparência da página.

Esse é um projeto básico, mas oferece uma estrutura sólida para um blog, permitindo fácil leitura e navegação.
