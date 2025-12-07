# Lightning

A WebGL-based lightning/electricity effect generator.

## Installs

No external dependencies.

## Usage

```jsx
import Lightning from './Lightning';

const Example = () => {
  return (
    <div style={{ height: '300px', width: '100%', backgroundColor: 'black' }}>
      <Lightning 
        hue={230} 
        intensity={1} 
      />
    </div>
  );
};

export default Example;
```

## Props

| Prop | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| `hue` | `number` | `230` | Hue of the lightning (0-360). |
| `xOffset` | `number` | `0` | Horizontal offset of the lightning center. |
| `speed` | `number` | `1` | Animation speed multiplier. |
| `intensity` | `number` | `1` | Brightness/alpha intensity. |
| `size` | `number` | `1` | Scale of the noise pattern. |
