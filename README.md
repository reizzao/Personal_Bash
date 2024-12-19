# BASH PERSONALIZADO RZ

---

1. Crie na raiz o arquivo .bash_aliases - ele já esta sendo chamado no bash original
2. Cole nele essas instruções

`
# ALIASES > CHAMA O _INIT

# VARIAVEIS MASTERS
export MY_BASH_DIR="$HOME/_myRZJ/myBASH"
export MY_BASH_INIT="$MY_BASH_DIR/._init"
export MY_BASH_DIR_SCRIPTS="$MY_BASH_DIR/scripts"


# CHAMAR O INIT PARA ESTE ARQUIVO
if [ -f $MY_BASH_INIT ]; then
    . $MY_BASH_INIT
fi

`

---

3. Crie a pas na raiz : _myRZJ - depois faça o clone no MyBASH para dentro dela.

---
