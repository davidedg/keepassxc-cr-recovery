
# Compile instructions on Windows:

Install GO if not already available:

- List available GO versions:

`winget show GoLang.Go --versions`

- Install a specific version:

`winget install GoLang.Go --version 1.20.11`

# Compile

    #set path=%PATH%;c:\go\bin\
    go build
