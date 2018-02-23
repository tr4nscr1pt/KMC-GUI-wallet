**1. Clone wallet sources**

```
git clone https://github.com/tr4nscr1pt/KMC-GUI-wallet.git
```

**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../ cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/tr4nscr1pt/KMC-GUI-wallet.git cryptonote
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```
