# Project-framewors

la base de datos a utilizar es el documento db.sqlite3
----------------------------------------------------------------
BASICOS
- para correr el archivo se necesita el comando en consola 
python manage.py runserver
- los cambios se haran dentro de la carpeta myapp y dentro de templates
- en url dentro de la carpeta my app se encuentran las urls que estan disponibles donde se crearan los HTMLS
- en views es donde se ve el esquema de urls con los documentos correspondientes, ejem: 
      def home (request):
      return render(request,'home.html')
  lo demas en views son simples ejemplos de lo que hara esa pagina que viene en un h1     
