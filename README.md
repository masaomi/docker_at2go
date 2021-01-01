# docker_at2go

Command log
```
docker load -i debian_at2go_20210101.tar.gz
docker run -it -p 3000:3000 --name debian_at2go debian:at2go
root@28c050ebdcba:/# cd
root@28c050ebdcba:~# source .bash_profile
root@28c050ebdcba:~# cd at2go
root@28c050ebdcba:~/at2go# bundle exec rails s -e production
=> Booting Puma
=> Rails 5.2.4.4 application starting in production
=> Run `rails server -h` for more startup options
Puma starting in single mode...
* Version 3.12.6 (ruby 2.6.6-p146), codename: Llamas in Pajamas
* Min threads: 5, max threads: 5
* Environment: production
* Listening on tcp://0.0.0.0:3000
Use Ctrl-C to stop
# Ctrl-P,Q
````

Access
* http://localhost:3000

Original git repository
* github.com/masaomi/at2go
