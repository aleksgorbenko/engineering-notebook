# 📝 Engineering Notebook
### 🏗️ Under construction

This is Obsidian vault that I use for work. When I join a new company, I clone this repo and can immediately start indexing internal knowledge into my notes.

See `/template` directory for all types of templates I regularly use.

### Import when joining the company

```
git clone git@github.com:aleksgorbenko/engineering-notebook.git ~/engbook/
```

### Usage

All work files related to the company are placed in `internal` directory. Everything that lives outside - generic notes that can be exported and integrated into your personal Obsidian.

```
root
    _media/
    _template/
    internal/
    internal_media/
```

#### Export when leaving the company

```
cd ~
zip -r engbook.zip engbook -x "README.md" "engbook/internal/*" "engbook/internal_media/*"
```

### About me 

- 👤 [Who am I and my past work experiences](https://github.com/aleksgorbenko/whoami) 
- 👨🏻‍💻 [How I work](https://github.com/aleksgorbenko/howiwork)

### Links
- 🧰 [LinkedIn](https://www.linkedin.com/in/aleks-gorbenko-software-engineer/)
- [My dotfiles](https://github.com/aleksgorbenko/dotfiles)