# Atajos de teclado para un desarrollo eficaz

### [VSCode](https://github.com/MrRedu/atajos-teclado#atajos-vscode-editores-en-general) + [Emmet](https://github.com/MrRedu/atajos-teclado#atajos-emmet)

Pequeña colección de atajos que utilizo frecuentemente.

Todos estos atajos están dirigidos al sistema operativo de Windows, junto al teclado latinoaméricano. <br>
Algunos podrían ser bastante similares o idénticos en otros idiomas/teclados/sistemas operativos.

## Atajos VSCode (editores en general)
|        Acción                                                 |       Atajo                       |
| ------                                                        |    ---                            |
| Ir al principio o final de una línea                          |     [`Inicio`](https://github.com/MrRedu/atajos-teclado/blob/main/images/inicio-fin.png) o [`Fin`](https://github.com/MrRedu/atajos-teclado/blob/main/images/inicio-fin.png)|
| Seleccionar línea completa                                    |      `Shift` + `Inicio` o `Fin`   |
| Ir al principio o final de una archivo                        |      `Ctrl` + `Inicio` o `Fin`    |
| | | 
| Ir al principio o final de una palabra                        |      `Ctrl` + `➡` o `⬅`          |
| Seleccionar palabra (o el restante desde el punto activo)     |   `Shift` + `Ctrl` + `➡` o `⬅`   |
| Borrar (cortar) línea activa                                  |        `Ctrl` + `X`               |
| Mover código seleccionado (en su defecto, la línea activa)    |        `Alt` + `⬆` o `⬇`          |
| Duplicar línea activa                                         |    `Alt` + `Shift` + `⬆` o `⬇`    |
| Identar el código                                             |       `Alt` + `Shift` + `F`       |
| Comentar código seleccionado (en su defecto, la línea activa) |          `Ctrl` + `}`             |
| Deshacer el último cambio                                     |          `Ctrl` + `Z`             |
| Rehacer el último cambio (el antagonista al atajo anterior)   |          `Ctrl` + `Y`             |
| | |
| Cambiar entre pestañas abiertas                               |        `Alt` + `➡` o `⬅`         |
| Buscar archivos de la carpeta                                 |        `Ctrl` + `P`               |

<br>

## Atajos Emmet

En esta práctica/ejemplo aprenderemos lo más rápido posible, cómo se traducirá el siguiente texto a HTML con el plugin de Emmet *(dicho plugin, ya viene por defecto en VSCode, asi que no te preocupes en descargarlo)*

```html
nav.navBar#navBar>ul.list-items>li*5.item>a[href='#' role='button' id='button-$']{Text $}
```

- El punto `.` se utiliza para ponerle clase al elemento que le antecede. En caso que no exista dicho elemento, se interpretará como un `<div>`

  ![div](https://github.com/MrRedu/atajos-teclado/assets/73679190/9c77ab41-27ab-447f-8e14-79b2ff08006b)
  ![nav navBar](https://github.com/MrRedu/atajos-teclado/assets/73679190/9c1b43b2-83aa-4a57-97bd-f8af1012256b)

- El numeral/almohadilla/gato `#` se utiliza para añadir un ID (identificador único) al elemento que le antecede.

  ![nav navBar#navBar](https://github.com/MrRedu/atajos-teclado/assets/73679190/137a4ae9-1c00-4621-b208-3bb502c7e298)
  
- El símbolo de mayor que `>` se utiliza para anidar elementos. *Incorporarles hijos*

  ![nav navBar#navBar-ul](https://github.com/MrRedu/atajos-teclado/assets/73679190/d190a3fc-92ab-4d9e-bc40-d0e9f1e921ab)
  
- El símbolo de la multiplicación `*` se utiliza para multiplicar por la cantidad que se indique, el elemento que le antecede.

  ![nav navBar#navBar-ul-li5](https://github.com/MrRedu/atajos-teclado/assets/73679190/c87ce811-482e-441a-a50e-f4017c29a2c5)

- Los corchetes `[ ]` se utilizan para añadir atributos con valores a un elemento.

  ![nav navBar#navBar-ul-li5-a](https://github.com/MrRedu/atajos-teclado/assets/73679190/0d5f6147-9db4-4024-b974-d7abb27d6d06)
  
- El símbolo de dólar/peso `$` se utiliza para enumerar valores que se hayan repetido.

  ![nav navBar#navBar-ul-li5-a -$](https://github.com/MrRedu/atajos-teclado/assets/73679190/5c67fcc5-cbcc-4ae4-a527-04a77a483d3d)

- Las llaves `{ }` se utilizan para ingresarle texto al elemento que le antecede.

  ![nav navBar#navBar-ul-li5-a -$-{}](https://github.com/MrRedu/atajos-teclado/assets/73679190/3bdfea9a-a277-4e8e-9f8d-eb902aa6aea9)

<br>

De esta manera, es como podemos construir componentes de HTML en una sola línea de código. <br>
Este fue un muy pequeño ejemplo de lo que se puede llegar a hacer con el plugin de Emmet.
También existen atajos para CSS, si te interesa seguir aprendiendo más atajos, te invito a que visites la [CheatSheet *(hoja de trucos)* de Emmet](https://docs.emmet.io/cheat-sheet/).
