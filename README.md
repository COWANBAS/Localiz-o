*Sobrescrevendo GetCurrentPosition*

Sobrescreve a função navigator.geolocation.getCurrentPosition. Normalmente, essa função é usada para obter a localização atual do usuário. No entanto, aqui estamos modificando seu comportamento para que ela sempre retorne um erro, impedindo o acesso à localização.

![image](https://github.com/user-attachments/assets/f06251db-585b-46f7-9469-094e64bade12)

*Sobrescrevendo WatchPosition e Fechando a Função Autoexecutável*

Sobrescreve a função navigator.geolocation.watchPosition. Esta função é usada para receber atualizações periódicas da localização do usuário. Mais uma vez, estamos modificando seu comportamento para que ela sempre retorne um erro.

![image](https://github.com/user-attachments/assets/91b9998e-8536-4739-aa43-064141d4ffdb)
