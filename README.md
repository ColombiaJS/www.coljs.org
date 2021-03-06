# www.coljs.org

## Dependencias
Para poder trabajar en este proyecto usted necesita
instalar las siguientes dependencias:

* **Node.js**: http://nodejs.org/

* **Bower y Grunt**: ```$ sudo npm install -g bower grunt```

## Instalación
```
$ git clone git@github.com:c4milo/www.coljs.org.git
$ cd www.coljs.org
$ npm install
$ bower install
```

## Flujo de trabajo
### Administración de Contenido
1. Modifique contenido dentro del directorio ```./content```
2. Corra ```$ grunt deploy --force```
3. Abra su navegador y verifique sus cambios en ```http://www.coljs.org```

### Flujo de desarrollo
1. Corra ```grunt watch --force```
2. Modifique el diseño o estructura de cualquiera de los componentes dentro del directorio ```./lib```
3. En su navegador, abra el archivo ```./public/index.html```

## Despligue
La tarea grunt de despliegue corre ```compile``` y 
actualiza el branch ```gh-pages``` in Github, con el resultado. 

```
$ grunt deploy --force
```

## License
(The MIT License)

Copyright 2013 ColombiaJS Team. All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to
deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
sell copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
