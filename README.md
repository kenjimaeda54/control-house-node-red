## Control_House
Este software e um backend para ser consumido no mobile Control House

## End Points
- [Referencia](https://nodered.org/docs/getting-started/raspberrypi)
- hostname:porta/timer_on_off


```text
// parametros no body em json

{ 

 "status": numero entre 0 e 1, em 0 led apagado 1 led acesso
 "time": tempo em segundos ficara acesso ou apagado o led

}


```

##
- hostname:porta/toggle

```text
// parametros no body em json

{ 

 "status": numero entre 0 e 1, em 0 led apagado 1 led acesso
 

}


```
