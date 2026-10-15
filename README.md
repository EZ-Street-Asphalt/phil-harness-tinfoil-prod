# phil-harness-tinfoil-prod

Tinfoil Containers configuration for PHIL's **production** agent harness
(the DeepSeek Harness, `dsh`). Configuration only: the image is the generic
bootstrap published from
[phil-harness-tinfoil](https://github.com/EZ-Street-Asphalt/phil-harness-tinfoil)
(public software only — `dsh` from npm, Caddy, git, and a boot script that
fetches PHIL's own plugins from a private repository over a read-only deploy
key held in Tinfoil's secrets vault). Nothing proprietary lives here.
