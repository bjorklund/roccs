
Ansible för att automatisera för att skydda ett nätverk.

| Fil                               | Beskrivning                      |
| --------------------------------- | -------------------------------- |
| inventory.yml                     |  Lista med servrar i nätverket   |
| check_ports_and_add_iptables.yml  |  Leta upp portar på varje server och skapa brandväggsregler. Obs, den tar ALLA portar som är öppna, även om det finns skadlig programvara. Men den skapar filerna i /root/ sedan får man finjustera dessa när man vet exakt vad som behövs. Låser även all utgående trafik.    |
| more to come....                  | |
