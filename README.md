# Gravatar JavaScript

_Mediante esta libreria puede utilizar el servicio de Gravatar https://es.gravatar.com/ el cual crea una Un "avatar"(una imagen que lo representa en línea, una pequeña imagen que aparece junto a su nombre cuando interactúa con sitios web). Lo carga y crea su perfil solo una vez, y luego cuando participa en cualquier sitio habilitado para Gravatar, su imagen de Gravatar lo seguirá automáticamente allí._

_Gravatar es un servicio gratuito para propietarios de sitios, desarrolladores y usuarios. Se incluye automáticamente en cada cuenta de WordPress.com._

## Comenzando 🚀

_Esta libreria utiliza MD5 (es un algoritmo de reducción criptográfico de 128 bits ampliamente usado) para convertir el correo electronico en un valor unico que se envia a gravatar y envia una imagen unica (recuerda que si estas inscrito con ese correo electronico en gravatar o cualquier sitio que utilice este servicio el avatar asignado sera el mismo en todos los sitios_

Mira **Deployment** para conocer como desplegar el proyecto.


### Instalación 🔧

utiliza NPM para realizar la instalación con 

```
npm i @alejozepol/gravatar

```

### Implementación

Es importante tener en cuenta que para que la libreria funcione es necesario enviar el email para que sea convertido en un hash y se interpretado por gravatar

Para implementar la libreria dentro de tu proyecto puedes seguir el siguiente ejemplo:

```
import gravatar from '@alejozepol/gravatar';

//el objeto user corresponde a la informacion del usuario.

        <div className='header__menu--perfil'>
          <p>Perfil</p>
          {hasUser ? (
            <img
              className='menu__perfil--perfil'
              src={gravatar(user.email)}
              alt={user.email}
            />
          ) : (
            <img
              className='menu__perfil--perfil'
              src={userIcon}
              alt='Icono Perfil'
            />
          )}
        </div>

```

## Autores ✒️

_Libreria realizada en la esculea de javaScrip de @platzi en la ciudad de Bogotá_

* **Alejandro López Ramirez** - [alejozepol](https://github.com/alejozepol) mas informacion sobre mi en https://alejozepol.com 😊

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 a alguien del equipo. 
* Da las gracias públicamente 🤓.
* etc.

---
⌨️ con el ❤️ por [alejozepol](https://github.com/alejozepol) mas informacion sobre mi en https://alejozepol.com 😊