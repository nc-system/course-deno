
### Instalacion

    Using Shell (macOS and Linux):
        $ curl -fsSL https://deno.land/x/install/install.sh | sh

    Using PowerShell (Windows):
        $ irm https://deno.land/install.ps1 | iex

    Using Scoop (Windows):
        $ scoop install deno

    Using Chocolatey (Windows):
        $ choco install deno

    Using Homebrew (macOS):
        $ brew install deno

    Using MacPorts (macOS):
        $ sudo port install deno

    Using Nix (macOS and Linux):
        nix-shell -p deno

    Using asdf (macOS and Linux):
        asdf plugin-add deno https://github.com/asdf-community/asdf-deno.git
        asdf install deno latest

        # To install globally
        asdf global deno latest

        # To install locally (current project only)
        asdf local deno latest


        # To install globally
        asdf global deno latest

        # To install locally (current project only)
        asdf local deno latest

    Build and install from source using Cargo:
        $ cargo install deno --locked


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