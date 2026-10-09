# Automatización con Selenium IDE – SauceDemo

Proyecto de práctica de **automatización de pruebas funcionales** con [Selenium IDE](https://www.selenium.dev/selenium-ide/) sobre [SauceDemo](https://www.saucedemo.com).

Automatiza algunos de los casos de prueba del proyecto [qa-manual-saucedemo](https://github.com/TU-USUARIO/qa-manual-saucedemo).

## 🧪 Tests incluidos

| Test | Caso manual relacionado | Qué verifica |
|------|-------------------------|--------------|
| TC-001 Login exitoso | TC-001 | Que tras ingresar credenciales válidas se muestre la página *Products* |
| TC-002 Login con contraseña incorrecta | TC-002 | Que aparezca el mensaje de error esperado |
| TC-007 Agregar producto al carrito | TC-007 | Que el contador del carrito muestre 1 |

Los tres tests están agrupados en la suite **Suite principal**.

## ▶️ Cómo ejecutarlos

1. Instalá la extensión **Selenium IDE** en Chrome o Firefox (buscala en la tienda de extensiones del navegador).
2. Abrí Selenium IDE y elegí **Open an existing project**.
3. Seleccioná el archivo [`saucedemo.side`](saucedemo.side) de este repositorio.
4. Para correr un test: seleccionalo y hacé clic en **Run current test**.
5. Para correr todos: elegí **Run all tests**.

## 📸 Resultados

Agregá en la carpeta `evidencias/` una captura de pantalla de la suite ejecutada con los tests en verde y mostrala acá:

```md
![Resultado de la suite](evidencias/resultado-suite.png)
```

## 🧠 Conceptos que practiqué

- Grabación y edición de comandos (`open`, `type`, `click`)
- Aserciones con `assertText` para validar resultados
- Localizadores por `id` y `css`
- Organización de tests en suites

## 🚀 Próximos pasos

- Agregar tests de checkout y logout
- Usar variables y `store text` para validar el total de la compra
- Dar el salto a Selenium WebDriver o Playwright
