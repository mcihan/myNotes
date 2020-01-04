# Bir Repository'i Fork Etmek Yerine Yeni Repository'e Push'lama

# 1. Yöntem
```
$ git clone <exist_repository_url>
$ git push <new_repository_url> master:master
```
# 2. Yöntem
```
$ git clone <exist_repository_url>
$ git remote rename origin upstream   
$ git remote add origin <new_repository_url> > test
$ git pull upstream master && git push origin master
```
# 3. Yöntem
```
$ git clone <exist_repository_url>
$ git remote set-url --push origin <new_repository_url>
$ git remote -v
> origin <exist_repository_url> (fetch)                                                          
> origin <new_repository_url> (push)
$ git push
```
