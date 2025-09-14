## Tugas 1 ##
Bash 
> git config --global user.name "cecilchristabel"
> git config --global user.email "cecilia.cs0908@gmail.com"
> ssh-keygen -t ed25519 -C "cecilia.cs0908@gmail.com"
> SSH key tersimpan di C:\Users\<username>\.ssh\id_ed25519.pub

GitHub
> klik profile picture > settings
> SSH and GPG keys > New SSH key
> Paste semua isi file id_ed25519.pub ke bagian key > add SSH key

Check di bash
> ssh -T git@github.com
> Ketik yes

Workflow
> Buat repository di GitHub
> Clone reposiory : git clone git@github.com:cecilchristabel/Kapita-Selekta-Andat.git
> Pull : git pull origin main
> Buka folder repository di Visual Studio Code dan buat file baru
> Menambahkan file ke staging area : git add filename atau git add
> Commit : git commit -m  "message"
> Push : git push origin main
