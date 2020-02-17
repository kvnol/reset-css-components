###### [← Voltar para a home](/)

<p align="center">
<img src="https://user-images.githubusercontent.com/3299130/61169083-921d8e80-a52e-11e9-8884-51b3e5653242.png" />
</p>

## Reset `<ul> | <ol>`

O componente **Reset Lists** permite uma maior flexibilidade para suas listas:

- Remove os bullets points da sua lista, seja ela ordenada(`<ol>`) ou não(`<ul>`);
- Remove a aparência padrão e bordas, permitindo maior controle sobre os itens da sua lista;
- Outline padrão do browser removido\*;
- Remove a decoração dos links no caso em que um ou mais itens da lista cotenham a tag `<a>` .


## Configurações

### Resetando tudo - `<ol> | <ul>`:

Use a classe `.reset-list-all`, quando quiser resetar todos os itens e níveis de uma lista, ordenada ou não:

```
<ol class="reset-list-all">
    <li>Item 1</li>
    <li>Item 2
        <ul>
            <li>Item 2.1</li>
            <li>Item 2.2</li>
        </ul>
    </li>
    <li>Item 3</li>
</ol>
```

### Resetando apenas o primeiro nível da lista - `<ol> | <ul>`:

Use a classe `.reset-list`, quando quiser resetar todos os itens de uma lista, ordenada ou não, ignorando sublistas:

```
<ul class="reset-list-all">
    <li>Item 1</li>
    <li>Item 2
        <ul>
            <li>Item 2.1</li>
            <li>Item 2.2</li>
        </ul>
    </li>
    <li>Item 3</li>
</ul>
```


## Arquivos

- [reset.sass](./reset.sass)

## Demonstração no Codepen

[Abrir a demonstração no Codepen]()
