# 🏋️ Sistema de Gestión para Gimnasio

Este proyecto es una solución web diseñada para automatizar los procesos operativos y administrativos de un gimnasio local. Permite gestionar membresías, controlar accesos, generar reportes y enviar notificaciones de manera eficiente, segura y escalable.

---

## 🚀 Tecnologías Utilizadas

- **Next.js** – Framework React para aplicaciones web modernas.
- **TailwindCSS** – Utilidad para estilos rápidos y personalizables.
- **Shadcn UI** – Componentes accesibles y bonitos para interfaces limpias.
- **Prisma ORM** – Acceso seguro y estructurado a la base de datos.
- **PostgreSQL** – Sistema de gestión de bases de datos relacional.
- **Zod** – Validación de datos para formularios y APIs.
- **Authjs** – Autenticación y gestión de sesiones (si aplica).

---

## ⚙️ Funcionalidades

- Registro y renovación de membresías (diaria/mensual).
- Validación de accesos mediante QR o RFID.
- Control de asistencia y registro de ingresos.
- Generación de reportes en tiempo real (PDF/Excel).
- Sistema de notificaciones automatizadas por vencimiento, renovación y morosidad.
- Panel de administración con métricas y dashboards.
- Soporte para mantenimiento y restauración de datos.

---

## 🧱 Estructura del Proyecto

```bash
.
├── app/                # Rutas y vistas (Next.js App Router)
├── components/         # Componentes reutilizables (UI)
├── prisma/             # Esquema de la base de datos
├── lib/                # Utilidades y validaciones (Zod, helpers)
├── public/             # Recursos estáticos
├── styles/             # Archivos de estilos
├── README.md
└── ...
```

---

## 🛠️ Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/gimnasio-tcc.git
cd gimnasio-tcc
```

2. Instala dependencias:

```bash
npm install
```

3. Configura la base de datos:

```bash
cp .env.example .env
# Edita las variables de entorno para la conexión PostgreSQL
```

4. Ejecuta las migraciones e inicia el servidor:

```bash
npx prisma migrate dev
npm run dev
```

---

## 📸 Capturas

> *(Agrega aquí imágenes o gifs del sistema funcionando)*

---

## 📄 Licencia

Este proyecto fue desarrollado como trabajo colaborativo contextualizado (TCC) para el programa de Ingeniería de Software de la Universidad de Cartagena. Uso académico.

---

## 👥 Autores

- Juan David Castro Zambrano  
- Edwin Jhosep Méndez Camacho  
- Over De Jesus Ramos Troconis  
- Harold David Rodelo Meléndez  
- Isaac David Solipá Bustamante  
