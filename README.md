**1. Clone wallet sources**

```
git clone https://github.com/progof/aonecoinwallet.git
```

**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../aonecoin cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/progof/aonecoin.git cryptonote
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```
