Realizando a tentativa de criar o servidor remoto;
A configuração do GIT foi:
echo "# servidorteste" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/FoxPereira/servidorteste.git
git push -u origin main

inicialmento utilizando o terminal do linux, mas com erro de compatibilidade ao realizar o push