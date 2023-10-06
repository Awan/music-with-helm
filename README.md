![image](https://github.com/Awan/music-with-helm/assets/42554663/ee7a40a3-d256-41a9-8af9-98148f304262)

# Simple Music App with helm

You have to set `env` for `music_host` at runtime.

```bash
helm install my-release my-music-app-0.1.0.tgz --set env.music_host=http://whmsonic.radio.gov.pk:8068
```
