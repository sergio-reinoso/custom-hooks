# React Custom Hooks Repository

Este repositorio contiene una colección de custom hooks personalizados para utilizar en proyectos de React. Los custom hooks son funciones de React que encapsulan lógica comúnmente utilizada, permitiendo reutilizar código y mejorar la modularidad de tus aplicaciones.

## ¿Cómo usar los custom hooks?

Cada hook en este repositorio está ubicado en su propio directorio, y cada directorio contiene un archivo `README.md` específico que explica cómo usar y qué funcionalidades ofrece el hook correspondiente.

A continuación, se presenta una lista de los custom hooks disponibles junto con una breve descripción:

## Custom Hooks

### 1. useCounter

**Descripción:** Este hook proporciona funcionalidad para gestionar un contador en tus componentes.

**Uso:**
```jsx
import { useCounter } from 'react-custom-hooks';

// Utilizar el hook en tu componente
const MyComponent = () => {
  const { count, increment, decrement, reset } = useCounter(0);

  return (
    <div>
      <p>Contador: {count}</p>
      <button onClick={increment}>Incrementar</button>
      <button onClick={decrement}>Decrementar</button>
      <button onClick={reset}>Resetear</button>
    </div>
  );
};

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes un custom hook que consideras útil y quieres compartirlo con la comunidad, por favor sigue estos pasos:

1. Realiza un fork del repositorio.
2. Crea una rama nueva para tu feature: `git checkout -b feature/nuevo-hook`.
3. Desarrolla y prueba tu custom hook.
4. Asegúrate de que tu código cumple con las guías de estilo.
5. Crea un pull request describiendo tu contribución.

## Problemas y sugerencias

Si encuentras algún problema con alguno de los custom hooks o tienes sugerencias para mejorarlos, no dudes en abrir un issue en este repositorio.
