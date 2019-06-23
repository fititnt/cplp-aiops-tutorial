# CPLP AIOps: Hello World Tsuru, Plataforma Static

```sh
cd hello-world-tsuru/static

tsuru app-create hello-world-tsuru-static static
tsuru app-deploy -a hello-world-tsuru-static .

tsuru app-list
# +--------------------------+------------+------------------------------------------------+
# | Application              | Units      | Address                                         |
# +--------------------------+------------+-------------------------------------------------+
# | hello-world-tsuru-static | 1 starting | hello-world-tsuru-static.NNN.NNN.NNN.NNN.nip.io |
# +--------------------------+------------+---------------------------------------------=---+

# URL: hello-world-tsuru-static.NNN.NNN.NNN.NNN.nip.io

```

## Extra help

- https://github.com/tsuru/platforms/tree/master/static
- https://docs.tsuru.io/stable/using/app-deploy.html