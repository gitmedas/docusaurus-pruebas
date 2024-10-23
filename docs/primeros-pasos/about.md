

## Estos son mis primeros pasos

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<!-- BARRA DE MENU  -->

<Tabs>
  <TabItem value="apple" label="Apple" default>
    This is an apple 🍎
  </TabItem>
  <TabItem value="orange" label="Orange and image">
    This is an orange 🍊
  </TabItem>
  <TabItem value="banana" label="Banana">
    This is a banana 🍌
  </TabItem>
</Tabs>

# Markdown page example

You don't need React to write simple standalone pages.

---

## Importar imagen local

![An image from the static](/img/docusaurus.png)

---

## Lista desordenada

- Peliculas
    - Acción
    - Comedia
    - Terror
- Caricaturas
- Series
- Anime

---

## Lista ordenada

1. **Verduras**
    1. Lechuga
    2. Chiles
    3. Tomates
    4. Jitomate
2. **Frutas**
    1. Sandia
    2. Melon
    3. Piña

---

## Tipos de advertencias

:::note -

Es una advertencia de tipo **note** 📝

:::

:::tip -

Es una advertencia de tipo **tip** ✨

:::

:::info -

Es una advertencia de tipo **info** ℹ

:::

:::warning -

Es una advertencia de tipo **warning** ⚠

:::

:::danger -

Es una advertencia de tipo **danger** ☣

:::

---

## Bloques de codigo

```jsx title="/src/components/HelloCodeTitle.js"
function HelloCodeTitle(props) {
  return <h1>Hello, {props.name}</h1>;
}
```


```php title="app/Http/Controller/PostController.php/"
$post = new Post();  // Inicializa el modelo Post para guardar el registro

// En el campo title = asignale lo que llego desde el formulario del campo title
$post->title = $request->title; 
$post->slug = $request->slug;
$post->category = $request->category; 
$post->content = $request->content;

$post->save();
```

---

## Lista de tareas

- [x] Tarea 1 
- [x] Tarea 2 
- [ ] Tarea 3 