<html lang="en">
    <style>

        body{
            font-family: Arial, Helvetica, sans-serif;
        }

        #searchInput {
          width: 100%;
          padding: 10px;
          box-sizing: border-box;
          margin-bottom: 20px;
          font-size: 16px;
        }
    
        ul {
          list-style-type: none;
          padding: 0;
          display: flex; /* Mostrar la lista como una fila */
          flex-wrap: wrap; /* Permitir que los elementos se envuelvan en múltiples filas */
        }
        
        li {
          margin-bottom: 10px;
          display: flex;
          align-items: center;
          margin-right: 20px; /* Agregar un espacio entre los elementos de la lista */
        }
        
        li img {
          margin-right: 5px;
          height: 20px;
        }
      </style>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Lenguajes de Programación</h1>

  <input type="text" id="searchInput" placeholder="Buscar lenguaje de programación...">

  <ul id="languageList">
    <li>
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="Logo de JavaScript">
      <a style="color: #bfbc04;" href="c/javascript.md">JavaScript</a>
    </li>
    <li>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1869px-Python-logo-notext.svg.png" alt="Logo de Python">
      <a href="https://www.example.com/python">Python</a>
    </li>
    <li>
      <img src="https://1000marcas.net/wp-content/uploads/2020/11/Java-logo.png" alt="Logo de Java">
      <a href="https://www.example.com/java">Java</a>
    </li>
    <li>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/ISO_C%2B%2B_Logo.svg/1822px-ISO_C%2B%2B_Logo.svg.png" alt="Logo de C++">
      <a href="https://www.example.com/cplusplus">C++</a>
    </li>
    <li>
      <img src="https://seeklogo.com/images/C/c-sharp-c-logo-02F17714BA-seeklogo.com.png" alt="Logo de C#">
      <a href="https://www.example.com/csharp">C#</a>
    </li>
    <li>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/Ruby_logo.svg/2048px-Ruby_logo.svg.png" alt="Logo de Ruby">
      <a href="https://www.example.com/ruby">Ruby</a>
    </li>
    <li>
      <img src="https://www.iebschool.com/blog/wp-content/uploads/2014/12/Apple_Swift_Logo.png" alt="Logo de Swift">
      <a href="https://www.example.com/swift">Swift</a>
    </li>
    <li>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Go_Logo_Blue.svg/1280px-Go_Logo_Blue.svg.png" alt="Logo de Go">
      <a href="https://www.example.com/go">Go</a>
    </li>
    <li>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/2560px-PHP-logo.svg.png" alt="Logo de PHP">
      <a href="https://www.example.com/php">PHP</a>
    </li>
    <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Rust_programming_language_black_logo.svg/1024px-Rust_programming_language_black_logo.svg.png" alt="Logo de Rust">
        <a href="https://www.example.com/rust">Rust</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/1200px-Typescript_logo_2020.svg.png" alt="Logo de TypeScript">
        <a href="https://www.example.com/typescript">TypeScript</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f0/Cebolla_Chulita.png" alt="Logo de Perl">
        <a href="https://www.example.com/perl">Perl</a>
      </li>
      <li>
        <img src="https://seeklogo.com/images/O/objective-c-logo-81746870EF-seeklogo.com.png" alt="Logo de Objective-C">
        <a href="https://www.example.com/objectivec">Objective-C</a>
      </li>
      <li>
        <img src="https://cdn-icons-png.flaticon.com/512/6132/6132220.png" alt="Logo de Scala">
        <a href="https://www.example.com/scala">Scala</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/74/Kotlin_Icon.png" alt="Logo de Kotlin">
        <a href="https://www.example.com/kotlin">Kotlin</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/2048px-HTML5_logo_and_wordmark.svg.png" alt="Logo de HTML">
        <a style="color: green;" href="c/html.md">HTML</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/1200px-CSS3_logo_and_wordmark.svg.png" alt="Logo de CSS">
        <a href="https://www.example.com/css">CSS</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Sql_database_shortcut_icon.png" alt="Logo de SQL">
        <a href="https://www.example.com/sql">SQL</a>
      </li>
      <li>
        <img src="logo-shell.png" alt="Logo de Shell">
        <a href="https://www.example.com/shell">Shell</a>
      </li>
      <li>
        <img src="data:image/png;base64,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" alt="Logo de Assembly">
        <a href="https://www.example.com/assembly">Assembly</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/VB.NET_Logo.svg/1024px-VB.NET_Logo.svg.png" alt="Logo de VB.NET">
        <a href="https://www.example.com/vbnet">VB.NET</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/Fortran_logo.svg" alt="Logo de Fortran">
        <a href="https://www.example.com/fortran">Fortran</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="Logo de MATLAB">
        <a href="https://www.example.com/matlab">MATLAB</a>
      </li>
      <li>
        <img src="https://www.oracle.com/a/ocom/img/pl-sql.svg" alt="Logo de PL/SQL">
        <a href="https://www.example.com/plsql">PL/SQL</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/Ada_horizon_green_logo_with_slogan.svg/1920px-Ada_horizon_green_logo_with_slogan.svg.png" alt="Logo de Ada">
        <a href="https://www.example.com/ada">Ada</a>
      </li>
      <li>
        <img src="https://cdn.icon-icons.com/icons2/2107/PNG/512/file_type_cobol_icon_130684.png" alt="Logo de COBOL">
        <a href="https://www.example.com/cobol">COBOL</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Lisp_logo.svg/1200px-Lisp_logo.svg.png" alt="Logo de Lisp">
        <a href="https://www.example.com/lisp">Lisp</a>
      </li>
      <li>
        <img src="https://avatars.githubusercontent.com/u/6884283?s=400&v=4" alt="Logo de Prolog">
        <a href="https://www.example.com/prolog">Prolog</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Haskell-Logo.svg/320px-Haskell-Logo.svg.png" alt="Logo de Haskell">
        <a href="https://www.example.com/haskell">Haskell</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Lua-Logo.svg/1200px-Lua-Logo.svg.png" alt="Logo de Lua">
        <a href="https://www.example.com/lua">Lua</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/Groovy-logo.svg/2560px-Groovy-logo.svg.png" alt="Logo de Groovy">
        <a href="https://www.example.com/groovy">Groovy</a>
      </li>
      <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Racket-logo.svg/1200px-Racket-logo.svg.png" alt="Logo de Racket">
        <a href="https://www.example.com/racket">Racket</a>
      </li>
  </ul>

  <script>
    function filterLanguages() {
      var input = document.getElementById('searchInput');
      var filter = input.value.toLowerCase();
      var ul = document.getElementById('languageList');
      var li = ul.getElementsByTagName('li');
      
      for (var i = 0; i < li.length; i++) {
        var a = li[i].getElementsByTagName('a')[0];
        var language = a.textContent || a.innerText;
        
        if (language.toLowerCase().indexOf(filter) > -1) {
          li[i].style.display = '';
        } else {
          li[i].style.display = 'none';
        }
      }
    }
    
    var searchInput = document.getElementById('searchInput');
    searchInput.addEventListener('input', filterLanguages);
  </script>


<p>Estamos tratando de optimizar la página, perdone si el tiempo de carga es excesivo</p>
<p>🟢 --> Facil de aprender</p>
<p>🟡</p>
<p>🟠</p>
<p>🔴 --> Dificil de aprender</p>
  

  
  

</body>
</html>