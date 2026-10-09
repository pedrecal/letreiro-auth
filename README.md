# letreiro-auth

Página de repasse do login do Spotify para o [letreiro](https://github.com/pedrecal/letreiro)
(firmware de ESP32). O Spotify só redireciona para HTTPS; esta página recebe o
redirect e manda o celular para o IP do aparelho na rede local, que vem no
parâmetro `state`. Não guarda nem envia nada para lugar nenhum.
