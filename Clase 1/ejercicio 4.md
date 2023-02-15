
# Principales diferencias entre Subversion y Git

## Subversion:

1. VCS **centralizado**. Hay un server como repositorio central. No hay repositorios locales.
2. **Checkout** del repo central en una copia local, se modifica  y **checkin** devuelve los cambios al server incrementando la versión del repo.
3. Los cambios locales no son versionados
4. **Snapshots**: rastrea los datos de la versión en cada archivo individual

## Git:

1. VCS **Distribuido**.  no se realiza un **checkout** de un repo central. Hay repositorios locales ( copias completas de todo lo que hay en el repo remoto )
2. **Clone** y **pull** para tener actualizado el repo local. **Push** para subir los cambios al repo remoto.
3. **Operaciones locales**: Checkin / checkout / commit 
4. El repo local mantiene la versión de la historia.
3. **Snapshots**: mantiene "instantáneas" de todo el estado del proyecto, es redundante pero más rápido