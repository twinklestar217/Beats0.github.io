### Blog：[https://Beats0.github.io](https://Beats0.github.io)

Beats0's Jekyll theme blog on GitHub<br>

Original Jekyll theme by [Huxpro](https://github.com/Huxpro/huxpro.github.io).<br>

[Jekyll Docker Image](https://hub.docker.com/r/jekyll/jekyll/)

使用docker-compose

jekyll docker build

```bash
cd
vim docker-compose.yml
docker-compose up
```

使用bash

```bash
λ docker run --name jekyllserver -v D:/Sites/Beats0.github.io-master/Beats0.github.io:/srv/jekyll -p 4000:4000 -it jekyll/jekyll:builder bash
```
```
bash-5.0# jekyll serve
```

访问 http://localhost:4000 即可