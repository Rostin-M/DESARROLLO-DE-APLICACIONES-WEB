# instapic-app

# AGREGADO

### 1. Espaciado entre el icono y el texto
```css
header ul li {
    display: flex;
    align-items: center;
    gap: 12px;
}
```
- Usa `display: flex` para organizar los elementos en fila.
- `align-items: center;` centra verticalmente los elementos dentro del `li`.
- `gap: 12px;` agrega un espacio de 12 píxeles entre el icono y el texto.

---

### 2. Se añadieron inconos y se les puso un efecto de crecimiento al pasar el cursor por estos

![image](https://github.com/user-attachments/assets/3d4246e4-0d6a-4ef8-bac8-c4f80ef91773)

```css
header ul li i {
    font-size: 22px;
    transition: transform 0.s ease-in-out;
}
```
- Define un tamaño de fuente de `22px` para los iconos.
- Aplica una transición en la propiedad `transform` (aunque `0.s` es incorrecto y debería corregirse a un valor como `0.3s`).

#### **Efecto al pasar el mouse**
```css
header ul li:hover i {
    transform: scale(1.4);
}
```
- Aumenta el tamaño del icono a 1.4 veces su tamaño original cuando el usuario pasa el cursor sobre él.

---

### 3. Diseño del contenedor principal
```css
main {
    display: flex;
    flex: 1;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 20px;
    padding: 10px 20px;
    width: 100%;
}
```
- `display: flex;` permite organizar el contenido en una estructura flexible.
- `flex: 1;` hace que el `main` ocupe todo el espacio disponible.
- `flex-direction: column;` organiza los elementos en columna.
- `align-items: center;` centra los elementos horizontalmente.
- `justify-content: center;` centra los elementos verticalmente.
- `gap: 20px;` establece un espaciado uniforme entre los elementos.
- `padding: 10px 20px;` agrega un espaciado interno.
- `width: 100%;` ocupa todo el ancho disponible.

---

### 4. Estilo para las secciones
```css
section {
    background: #ffffff;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    font-size: 18px;
    font-weight: 500;
    text-align: center;
    width: 300px;
}
```
- `background: #ffffff;` establece un fondo blanco.
- `padding: 20px;` agrega un espacio interno uniforme.
- `border-radius: 12px;` redondea los bordes del contenedor.
- `box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);` aplica una sombra ligera para resaltar la sección.
- `font-size: 18px;` define el tamaño de la fuente.
- `font-weight: 500;` establece un peso de fuente medio.
- `text-align: center;` centra el texto dentro de la sección.
- `width: 300px;` limita el ancho de la sección para mantener un diseño compacto.

