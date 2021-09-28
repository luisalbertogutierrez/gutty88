fuente  'https://rubygems.org'
git_source ( : github )  { | repositorio | "https://github.com/ # { repo } .git"  }

rubí  '2.5.8'

# En su lugar, agrupe los rieles de borde: gem 'rieles', github: 'rieles / rieles', rama: 'principal'
gem  'rieles' ,  '~> 6.1.4' ,  '> = 6.1.4.1'
# Use sqlite3 como base de datos para Active Record
# gema 'sqlite3', '~> 1.4'
# Utilice Puma como servidor de aplicaciones
gema  'puma' ,  '~> 5.0'
# Use SCSS para hojas de estilo
gema  'sass-rails' ,  '> = 6'
# Transpile JavaScript similar a una aplicación. Leer más: https://github.com/rails/webpacker
gema  'webpacker' ,  '~> 5.0'
# Turbolinks agiliza la navegación por su aplicación web. Leer más: https://github.com/turbolinks/turbolinks
gema  'enlaces turbo' ,  '~> 5'
# Cree API JSON con facilidad. Leer más: https://github.com/rails/jbuilder
gema  'jbuilder' ,  '~> 2.7'
# Utilice el adaptador Redis para ejecutar Action Cable en producción
# gema 'redis', '~> 4.0'
# Usar modelo activo has_secure_password
# gema 'bcrypt', '~> 3.1.7'

# Utilice la variante de almacenamiento activo
# gem 'image_processing', '~> 1.2'

# Reduce los tiempos de arranque mediante el almacenamiento en caché; requerido en config / boot.rb
gem  'bootsnap' ,  '> = 1.4.4' ,  requiere : falso

grupo  : desarrollo ,  : Prueba de  tareas pendientes
  # Llame a 'byebug' en cualquier parte del código para detener la ejecución y obtener una consola de depuración
  joya  'byebug' ,  plataformas : [ : MRI ,  : MinGW ,  : x64_mingw ]
fin

grupo  : desarrollo  hacer
  # Acceda a una consola interactiva en las páginas de excepción o llamando a 'consola' en cualquier parte del código.
  gem  'consola web' ,  '> = 4.1.0'
  # Muestre información de rendimiento, como gráficos de llama y tiempo SQL para cada solicitud en su navegador.
  # También se puede configurar para que funcione en producción, consulte: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gema  'rack-mini-profiler' ,  '~> 2.0'
  gema  'escuchar' ,  '~> 3.3'
  # Spring acelera el desarrollo al mantener su aplicación ejecutándose en segundo plano. Leer más: https://github.com/rails/spring
  joya  'primavera'
fin

grupo  : prueba  hacer
  # Agrega soporte para las pruebas del sistema Capybara y el controlador de selenio
  gema  'carpincho' ,  '> = 3.26'
  joya  'selenium-webdriver'
  # Fácil instalación y uso de controladores web para ejecutar pruebas del sistema con navegadores
  gema  'webdrivers'
fin

grupo  : producción  hacer
  joya  "pg"
fin

# Windows no incluye archivos zoneinfo, así que empaquete la gema tzinfo-data
joya  'tzinfo-data' ,  plataformas : [ : MinGW ,  : mswin ,  : x64_mingw ,  : jruby ]
