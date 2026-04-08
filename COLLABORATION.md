## Procedura wysyłania zmian (push)
1. git checkout -b feature/nazwa
2. Wprowadź zmiany
3. git add . && git commit -m "opis"
4. git push origin feature/nazwa

## Procedura pobrania zmian (pull, fetch)
- git fetch origin – pobiera zmiany bez merge
- git pull origin master – pobiera i merguje

## Jak tworzyć PR/MR
1. Push brancha na GitHub
2. Otwórz Pull Request: base=master, compare=feature/nazwa
3. Dodaj opis, poproś o review
4. Po akceptacji – Merge

## Best practices dla zespołu
- Jeden branch = jedna funkcja/fix
- Commituj często, małe zmiany
- Opisowe nazwy commitów i branchy
- Code review przed mergem
