
La regla en general en Platanus es que solo puede haber una fuente de la verdad para el estado de la aplicación, determinada por quién maneja la paginación.

* Si la paginación la maneja Rails, Rails debería manejar el estado de la aplicación, siendo Vue un suplemento para agregar elementos dinámicos.

* Si la paginación la maneja Vue (mediante un router, por ejemplo), el estado de la aplicación lo debería manejar Vue (con Vuex probablemente), usando Rails principalmente como API.

[Super tips vue](tips_vue/super_tips_vue.md)
