# humanoadmin
Administrar humano

## Commands
Command                | Description                                      |
-----------------------|--------------------------------------------------|
`$ npm start`          | Start the development server
`$ npm test`           | Lint, validate deps & run tests
`$ npm run build`      | Compile all files into `dist/`
`$ npm run create`     | Generate a scaffold file
`$ npm run inspect`    | Inspect the bundle's dependencies


## Rutas

### Humanos

Ruta                   | Descripcion                                      |
-----------------------|--------------------------------------------------|
`/humanos/`            | Vista de todos los humanos con datos basicos
`/humanos/new`         | Formulario de carga de nuevos humanos
`/humanos/:id`         | Vista individual de un humano con todos sus datos
`/humanos/:id/edit`    | Formulario de edicion para modificar un humano en particular

### Productos

Ruta                   | Descripcion                                      |
-----------------------|--------------------------------------------------|
`/products/`           | Vista de todos los productos con datos basicos
`/products/new`        | Formulario de carga de nuevos productos 
`/products/:id`        | Vista individual de un producto con todos sus datos
`/products/:id/edit`   | Formulario de edicion para modificar un producto en particular

### Movimientos

Ruta                   | Descripcion                                      |
-----------------------|--------------------------------------------------|
### Configuracion

Ruta                   | Descripcion                                      |
-----------------------|--------------------------------------------------|
`/config/`             | Vista de configuracion actual
`/config/edit`         | Formulario de edicion de configuracion
