---
title: Navigator.cookieEnabled
slug: Web/API/Navigator/cookieEnabled
---
{{ ApiRef("HTML DOM") }}

`navigator.cookieEnabled` retorna um valor _Booleano_ que indica quando _cookies_ estão habilitados ou não. A propriedade é de apenas leitura.

## Sintaxe

```js
var cookieEnabled = navigator.cookieEnabled;
```

- `cookieEnabled` é um [Booleano](/pt-BR/docs/Glossario/Booleano): `true` ou `false`.

## Exemplo

```js
if (!navigator.cookieEnabled) {
  // The browser does not support or is blocking cookies from being set.
}
```

## Especificações

| Especificação                                                                                                                            | Status                           | Comentário         |
| ---------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- | ------------------ |
| {{SpecName("HTML WHATWG", "webappapis.html#dom-navigator-cookieenabled", "Navigator.cookieEnabled")}} | {{Spec2("HTML WHATWG")}} | Initial definition |

## Compatibilidade com navegadores

{{Compat("api.Navigator.cookieEnabled")}}
