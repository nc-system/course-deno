
### Instalacion

    Shell (Mac, Linux):

    curl -fsSL https://deno.land/install.sh | sh

    PowerShell (Windows):
    iwr https://deno.land/install.ps1 -useb | iex

    Homebrew (Mac):
    brew install deno

    Chocolatey (Windows):
    choco install deno

    Scoop (Windows):
    scoop install 
    
    Build and install from source using Cargo:
    cargo install deno --locked


<br>

## Actualizacion

    - Actualizar a la ultima version
    
        $ deno upgrade

    - Actualizar a una version requerida

        $ deno upgrade --version 1.0.1


<br>

### Configurar el bash ( Debian )

    - Por consola abrir el archivo .bashrc
    
    $ sudo vim .bashrc

    - Agregar estas 2 lineas de texto

    Manually add the directory to your $HOME/.bash_profile (or similar)
        export DENO_INSTALL="/home/andres/.deno"
        export PATH="$DENO_INSTALL/bin:$PATH"


    - Reiniciar o Cerrar sesion

    - Comprobar la version de Deno

    deno --version


<br>