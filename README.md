### vimfile

create link

```
New-Item -ItemType SymbolicLink -Name vimfiles -Target $HOME\win\vimfiles
```

install minpac

```
cd $HOME
git clone https://github.com/k-takata/minpac.git vimfiles\pack\minpac\opt\minpac

# open vim and
call minpac#update()
```

