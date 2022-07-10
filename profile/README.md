# Spotifiuby

Este sistema, inspirado en el actual Spotify, es parte del trabajo final y grupal realizado para la materia de Taller de Programación II dictada en la Facultad de Ingeniería de la Universidad de Buenos Aires (FIUBA).

El espíritu de esta plataforma es poder brindar una conexión entre los usuarios y los artistas de sus canciones favoritas. Para esto existen distintos tipos de suscripciones, tanto gratuitas como pagas. Donde al contar con una suscripción premium se podrá acceder a contenido exclusivo

## Integrantes
| Nombre                                                        | Padrón |
| ------------------------------------------------------------- | ------ |
| [AGUILAR LÓPEZ, Arturo](https://github.com/ArturoAguilar1)    | 99804 |
| [BIANCARDI, Julian](https://github.com/JulianBiancardi)       | 103945 |
| [FARFÁN, Nicolás](https://github.com/NicolasRFL)              | 97261 |
| [FLOURET, Agustín Miguel](https://github.com/aflouret)        | 102298 |
| [HETREA, Joaquín Emanuel](https://github.com/JoaquinHetrea)   | 103944 |


## Enunciado del proyecto
https://taller-de-programacion-2.github.io/works/statement/2022/1/enunciado/

## Bitácora del proyecto
https://docs.google.com/document/d/1JSt1Bey1gd4owlBRjPMO0AHgdXHp0fQtvkrmSFaHTXA/edit

## Arquitectura del proyecto
![Arquitectura](/profile/arquitectura.png)

### Servicios de backend
- Users: Servicio para resolver las operaciones CRUD y la autenticación de los usuarios y de los administradores.
- Songs: Servicio para resolver las operaciones CRUD sobre las canciones, álbumes y playlists. Para buscar, comentar, valorar y bloquear el contenido.
- Api Gateway: Servicio que actúa como interfaz entre el frontend y el backend. Redirige las requests al servicio correspondiente y valida los tokens de autorización.
- Payments: Servicio para resolver los pagos de suscripciones en un Smart Contract
- Api-Keys: Servicio que permite a los administradores dar de alta, visualizar y bloquear servicios. Cada servicio tiene asociada una API key que le permite autenticarse.

### Servicios de frontend
- App Mobile
- Backoffice


