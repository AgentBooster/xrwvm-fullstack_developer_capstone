# Migracion al repo requerido

El evaluador AI exige que la URL publica use este nombre exacto:

`xrwvm-fullstack_developer_capstone`

## Pasos

1. Crea un repositorio publico nuevo en GitHub con ese nombre exacto.
2. En esta copia local ejecuta:

```bash
git remote rename origin old-origin
git remote add origin https://github.com/<tu_usuario>/xrwvm-fullstack_developer_capstone.git
git add .
git commit -m "Complete final capstone submission artifacts"
git push -u origin main
```

3. Verifica estas URLs publicas:

- `https://github.com/<tu_usuario>/xrwvm-fullstack_developer_capstone/blob/main/README.md`
- `https://github.com/<tu_usuario>/xrwvm-fullstack_developer_capstone/blob/main/server/frontend/static/About.html`
- `https://github.com/<tu_usuario>/xrwvm-fullstack_developer_capstone/blob/main/server/frontend/static/Contact.html`
- `https://github.com/<tu_usuario>/xrwvm-fullstack_developer_capstone/blob/main/server/frontend/src/components/Register/Register.jsx`

4. Actualiza cualquier documento de entrega reemplazando `AgentBooster/django-dealer-review-app` por tu nuevo repo.
