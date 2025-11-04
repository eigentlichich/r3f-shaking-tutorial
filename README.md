# R3F Shaking Playground Tutorial

Willkommen zum R3F Shaking Playground Tutorial! In diesem Repository werden wir gemeinsam einen interaktiven Playground mit React Three Fiber (R3F) bauen, der verschiedene Shake/Wobble-Effekte für 3D-Objekte demonstriert.

## Projektbeschreibung

Dieses Tutorial zeigt, wie man mit React Three Fiber realistische Shake- und Wobble-Animationen erstellt. Wir werden verschiedene Ansätze implementieren, von einfachen Spring-Animationen bis hin zu komplexeren physikbasierten Effekten.

## Beispiel-Setup

```jsx
import { Canvas } from '@react-three/fiber'
import { OrbitControls } from '@react-three/drei'
import { ShakingBox } from './components/ShakingBox'

function App() {
  return (
    <Canvas camera={{ position: [0, 0, 5] }}>
      <ambientLight intensity={0.5} />
      <directionalLight position={[10, 10, 5]} intensity={1} />
      <ShakingBox />
      <OrbitControls />
    </Canvas>
  )
}

export default App
```

## Wichtige Ressourcen

### Dokumentation
- [React Three Fiber Dokumentation](https://docs.pmnd.rs/react-three-fiber)
- [Three.js Dokumentation](https://threejs.org/docs/)
- [React Spring Dokumentation](https://www.react-spring.dev/)
- [Drei Helpers](https://github.com/pmndrs/drei)

### Tutorials & Guides
- [R3F Getting Started](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)
- [React Spring with R3F](https://docs.pmnd.rs/react-three-fiber/tutorials/using-with-react-spring)
- [Physics in R3F](https://github.com/pmndrs/use-cannon)

### Inspiration
- [PMND Studio](https://pmnd.rs/)
- [R3F Examples](https://docs.pmnd.rs/react-three-fiber/getting-started/examples)

## Installation

```bash
npm install three @react-three/fiber @react-three/drei
npm install @react-spring/three
```

## Roadmap

- [ ] Basic Setup mit R3F Canvas
- [ ] Einfache Shake-Animation mit React Spring
- [ ] Wobble-Effekt implementieren
- [ ] Physics-basierte Shake-Effekte
- [ ] UI Controls für Parameter-Anpassung
- [ ] Verschiedene Objekt-Geometrien
- [ ] Export/Share Funktionalität

## Mitmachen

Dieses Tutorial wird gemeinsam entwickelt! Fühle dich frei, Issues zu öffnen, Pull Requests zu erstellen oder Verbesserungsvorschläge zu machen.

## Lizenz

MIT
