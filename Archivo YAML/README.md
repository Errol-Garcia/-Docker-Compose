
<h1>Archivo YAML </h1>

es un tipo de archivo ue se usa en todo tipo de proyecto y con todo tipo de lenguaje de programacion en donde permite crear son archivo de configuracion donde todo queda muy ordenado y bonito para la vista.

para tener un archivo yaml no es mas que crear un archivo con su editor favorito y que contenga como extencion yaml o yml; en mi caso yo tengo como editor predeterminado VS Code y cuando abra el archivo se abrira ahí.

<img src=img/img1.jpg width="100" height="100">

En este tipo de archivo tenemos dos partes: las claves o llaves y los valores; los valores pueden ser de distintos tipos:

* <h3>Escalares</h3>
    la llave se comprente como si fuera la variable y estas tendrian sus valores.
    
        numero: 10
        textos: 'Hola Mundo'
        
        texto2: |-
            Hola mundo 2.
        
        listas: ['a','b']
        listas2:
            - 'Hola'
            - 'adios'
        
        enlista: [[]]

        objetos:
            numero: 10
            texto: 'texto'
            objetos2:
                array:
                    - 12
                    - 13
                    - -13

Se debe tener en cuenta la identacion que es el margen de donde pertenece cada valor.

basicamente yaml nos sirve para hacer una configuracion instantanea con varias configuraciones, en este caso, la utilizaremos para configurar una aplicacion cliente servidor.