[YouTube Video](https://www.youtube.com/watch?v=gAkwW2tuIqE)

<details>
    <summary>Steps performed</summary>

- Docker Build Image

```
{
    PS C:\repos\first-docker-app> docker build -t first-docker-app:1.0 .         
[+] Building 71.5s (10/10) FINISHED                                                                           docker:desktop-linux
 => [internal] load build definition from Dockerfile                                                                          0.3s
 => => transferring dockerfile: 190B                                                                                          0.1s
 => [internal] load metadata for docker.io/library/node:12                                                                    3.3s
 => [internal] load .dockerignore                                                                                             0.1s
 => => transferring context: 52B                                                                                              0.0s
 => [1/5] FROM docker.io/library/node:12@sha256:01627afeb110b3054ba4a1405541ca095c8bfca1cb6f2be9479c767a2711879e             55.9s
 => => resolve docker.io/library/node:12@sha256:01627afeb110b3054ba4a1405541ca095c8bfca1cb6f2be9479c767a2711879e              0.1s
 => => sha256:3a69ea1270dbf4ef20477361be4b7a43400e559c6abdfaf69d73f7c755f434f5 2.21kB / 2.21kB                                0.0s
 => => sha256:01627afeb110b3054ba4a1405541ca095c8bfca1cb6f2be9479c767a2711879e 776B / 776B                                    0.0s
 => => sha256:6c8de432fc7f7d8c58899f61982d1662ec6b73fb3ef92f862ba170dcc5b64fa9 7.68kB / 7.68kB                                0.0s
 => => sha256:f5196cdf25181bc7e4411865a2e002932b7b6b0ffce787c04c1bdeaf1f204f20 45.43MB / 45.43MB                              8.8s
 => => sha256:9bed1e86f01ee95c76d2c8b4385a47ae336e6d293afade9368469d99daa9369f 11.30MB / 11.30MB                              2.5s
 => => sha256:f44e4bdb3a6c1325cc4d40e585ed7a759127c0c87b0388ec0236b1698827d70d 4.34MB / 4.34MB                                1.3s
 => => sha256:2f75d131f4060950dd6cc1f580e2fa5504ece8d692113a9cdb0a866637b397d7 49.77MB / 49.77MB                             10.8s
 => => sha256:07dff4ad21ebdb3ce3e329699663b2f81af70152453025f6624584a39a8e22b6 214.48MB / 214.48MB                           29.0s
 => => extracting sha256:f5196cdf25181bc7e4411865a2e002932b7b6b0ffce787c04c1bdeaf1f204f20                                    14.3s
 => => sha256:e0ac4f13b766d321acc3b650d3d23b82828995711f6f247ff591722c00d04cec 4.19kB / 4.19kB                                9.1s
 => => sha256:df2c3b2eb7cc63351bb32f26457bbe0402af8082548f26975f0c329bc7841881 23.70MB / 23.70MB                             15.3s
 => => sha256:efe636eac583776a8a114d50fef15bc65b648f3d2bb53326cf1f21cc5ef2b3ae 2.34MB / 2.34MB                               11.7s 
 => => sha256:fe17849545bb51455d3f7c8773ded2dbb1d6668a85bd00564573a4b88afd36f6 464B / 464B                                   12.0s 
 => => extracting sha256:9bed1e86f01ee95c76d2c8b4385a47ae336e6d293afade9368469d99daa9369f                                     2.4s 
 => => extracting sha256:f44e4bdb3a6c1325cc4d40e585ed7a759127c0c87b0388ec0236b1698827d70d                                     0.6s 
 => => extracting sha256:2f75d131f4060950dd6cc1f580e2fa5504ece8d692113a9cdb0a866637b397d7                                     8.8s 
 => => extracting sha256:07dff4ad21ebdb3ce3e329699663b2f81af70152453025f6624584a39a8e22b6                                    14.8s 
 => => extracting sha256:e0ac4f13b766d321acc3b650d3d23b82828995711f6f247ff591722c00d04cec                                     0.0s 
 => => extracting sha256:df2c3b2eb7cc63351bb32f26457bbe0402af8082548f26975f0c329bc7841881                                     2.8s 
 => => extracting sha256:efe636eac583776a8a114d50fef15bc65b648f3d2bb53326cf1f21cc5ef2b3ae                                     0.1s 
 => => extracting sha256:fe17849545bb51455d3f7c8773ded2dbb1d6668a85bd00564573a4b88afd36f6                                     0.0s 
 => [internal] load build context                                                                                             0.1s 
 => => transferring context: 26.45kB                                                                                          0.1s 
 => [2/5] WORKDIR C:\container                                                                                                5.5s 
 => [3/5] COPY package*.json ./                                                                                               0.2s 
 => [4/5] RUN npm install                                                                                                     5.4s 
 => [5/5] COPY . .                                                                                                            0.1s 
 => exporting to image                                                                                                        0.3s 
 => => exporting layers                                                                                                       0.2s 
 => => writing image sha256:6481a4455524409584e53fc29bc4effc15d393fbf054774dceac6c532837524a                                  0.0s 
 => => naming to docker.io/library/first-docker-app:1.0                                                                       0.0s

 1 warning found (use --debug to expand):
 - WorkdirRelativePath: Relative workdir "C:\\container" can have unexpected results if the base image changes (line 3)
}


</details>