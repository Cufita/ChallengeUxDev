# UX Developer Jr. Challenge

## The Challenge

The client has requested that you build an Admin Dashboard view to track the latest transactions in sales and revenue. You can find the Figma file with the various views and flows [here](https://www.figma.com/design/8kNilrpajBQITsPd4kqObw/UX-Dev-Challenge-JR).

Please deliver a complete experience using React. If you are familiar with type-checking tools like TypeScript or PropTypes, feel free to use them. You may also use a CSS-in-JS library (such as Emotion or Styled Components), SASS, or plain CSS.

All views must be responsive and display correctly on Desktop, Tablet, and Mobile. You will only receive a desktop mockup. On mobile, the user should be able to see as much information as possible on the screen while maintaining design coherence.

### User Requirements

Your users should be able to:

- View the optimal layout based on their device's screen size
- See hover and focus states for all interactive elements on the page
- Access more information about a specific transaction through a drawer
- Access to the `SideBar` in the normal or collapsable view, also can access to the `Messages` section with the correct EmptyState
- View the `EmptyState` of the `Order` Tab and ability to switch between tabs

### Documentation and Delivery

Upon delivery, please provide clear explanations of your decision-making process regarding the responsive design. Make sure to document your code as thoroughly as possible.

## Where to Find Everything

On the `Platform` page, you will find the `Dashboard` with the `Drawer` interaction and the empty state of the Order Tab.

On the `Component` page, you will find the specific components, and in the `Foundation` section, you will see the color palette of the light and dark mode.

## Some Tips

1. Review the designs to start planning how to approach the project. This step is essential for organizing your CSS and components to enhance reusability.
2. You can include any additional elements you consider necessary to support your solution.
3. Pay close attention to detail.
4. Remember that while JavaScript logic is still important, our main focus for this exercise is on styles and components and not paying attention to the business logic and the router. You can hard-code the data provided in `content.txt` into your components.
5. Since we emphasize styles, please refrain from using Tailwind.
6. Include all necessary accessibility labels to ensure all users can access the platform.

## How to Run the Project Locally

To set up and run the project locally, follow these steps:

1. **Install dependencies**  
   Run the following command to install all required dependencies:

   ```bash
   npm install
   ```

2. **Start the development server**
   Once the dependencies are installed, run this command to start the application in development mode:

   ```bash
   npm run dev
   ```

## Deliverables

- Complete project files that work on Chrome, Safari, Firefox, and Edge, along with project documentation. Please deliver everything through a GitHub repository.

**Have fun building!**

En los últimos seis días, el trabajo se centró en desarrollar y optimizar componentes de una aplicación utilizando React y CSS. Este proceso incluyó:

**## Análisis inicial: Identificación de componentes necesarios y su lógica.**

1.Implementación incremental: Creación y ajuste de componentes clave.

2.Resolución de problemas: Enfoque en responsividad y diseño visual.

3.Metodología iterativa: Avances diarios basados en problemáticas específicas.

4.Detalle del Proceso Diario

**## Día 1: Análisis Inicial y Planificación**

1.Evalué los componentes existentes y detecté la necesidad de crear nuevos.

2.Definí la lógica y estructura de los componentes pendientes.

3.Establecí prioridades y una hoja de ruta para las tareas.

**Día 2: Implementación del Componente "Table"**

1.Desarrollé el componente básico con funcionalidades iniciales.

2.Implementé la renderización de datos y compatibilidad con estilos CSS existentes.

3.Preparé el componente para futuras expansiones.

**Día 3: Optimización de "Table" y Creación del Detalle de Transacciones**

1.Mejoras en "Table":

    Hice el diseño del componente "Table" más responsivo.

    Implementé clic en filas para mostrar detalles interactivos.

2.Creación del TransactionDetail:

    Diseñé un componente para mostrar información específica de cada transacción.

    Respeté al máximo el diseño de Figma.

3.Mejoras adicionales:

    Refiné los estilos del ToggleButton para mayor consistencia visual.

    Agregué detalles al estado (Status) dentro del detalle de transacciones.

**Día 4: Responsividad y Ajustes en CSS**

1.Solucioné problemas de visualización en dispositivos móviles y tabletas.

2.Ajusté el componente "Table" para mejorar la experiencia en pantallas pequeñas.

3.Diseñé la distribución responsiva inicial para el componente Card.

**Día 5: Desarrollo del Componente "Card" y Ajustes Responsivos**

4.Implementación del Componente "Card":

5.Creé un componente Card siguiendo las especificaciones de Figma.

6.Logré que las tarjetas se distribuyeran en dos filas con dos tarjetas por fila en pantallas ≤ 1200px.

7.Pruebas y Ajustes:

    Realicé pruebas para garantizar consistencia en navegadores y dispositivos.

**Día 6: Revisión General y Resolución de Problemas Pendientes**

1.Revisé la lógica y la usabilidad de los componentes.

2.Solucioné problemas relacionados con scroll y coherencia visual.

3.Documenté los cambios realizados y definí mejoras futuras.
