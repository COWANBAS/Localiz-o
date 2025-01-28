*Sobrescrevendo GetCurrentPosition*

Sobrescreve a função navigator.geolocation.getCurrentPosition. Normalmente, essa função é usada para obter a localização atual do usuário. No entanto, aqui estamos modificando seu comportamento para que ela sempre retorne um erro, impedindo o acesso à localização.

![image](https://github.com/user-attachments/assets/f06251db-585b-46f7-9469-094e64bade12)

*Sobrescrevendo WatchPosition e Fechando a Função Autoexecutável*

Sobrescreve a função navigator.geolocation.watchPosition. Esta função é usada para receber atualizações periódicas da localização do usuário. Mais uma vez, estamos modificando seu comportamento para que ela sempre retorne um erro.

![image](https://github.com/user-attachments/assets/91b9998e-8536-4739-aa43-064141d4ffdb)

O script de bloqueio de localização oferece uma vantagem significativa em termos de privacidade e segurança do usuário na internet. Ao sobrescrever as funções getCurrentPosition e watchPosition do objeto navigator.geolocation, ele impede que sites acessem a localização geográfica do usuário sem sua permissão explícita. Isso significa que suas informações de localização não serão compartilhadas inadvertidamente com sites que podem usá-las para rastreamento, publicidade direcionada ou outros fins potencialmente invasivos. Com esse script ativado, você tem maior controle sobre sua privacidade online, garantindo que sua localização permaneça protegida e fora do alcance de terceiros não autorizados.
