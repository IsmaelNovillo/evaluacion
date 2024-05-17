

### **Estructura del Proyecto**

- **HomePage:** Página de botones.
- **LoginPage:** Página de inicio de sesión de usuarios.
- **RegisterPage:** Página de registro de nuevos usuarios.
- **Firebase:** Configuración de Firebase Authentication para gestionar la autenticación de usuarios.

### **Configuración de Firebase**

Para configurar Firebase, hemos utilizado el servicio Firebase Authentication. La configuración de Firebase se encuentra en el archivo **`environment.ts`**.

**Archivo `environment.ts`**

export const environment = {
production: false,
firebaseConfig: {
apiKey: '
authDomain: '
projectId: 
storageBucket: '
messagingSenderId: '
appId: '1
measurementId: '
},
};

### **Páginas**

### **HomePage**

La página de inicio que se muestra después de que el usuario ha iniciado sesión correctamente.

**Archivo `home.page.html`**

### **LoginPage**

La página de inicio de sesión donde los usuarios pueden ingresar con su correo electrónico y contraseña.

### **RegisterPage**

La página de registro donde los nuevos usuarios pueden crear una cuenta proporcionando su correo electrónico y contraseña.
