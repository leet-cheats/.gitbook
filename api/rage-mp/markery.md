---
icon: thumbtack
---

# Маркеры
## Свойства
---
### Размер маркера
```typescript
Marker.scale: number
```
### Направление маркера
```typescript
Marker.direction: Vector3
```
### Видимость маркера
```typescript
Marker.visible: boolean
```

## Функции
---
### Создать маркер
```typescript
mp.markers.new(type: number, position: mp.Vector3, scale: number,
    {
        direction: mp.Vector3,
        rotation: mp.Vector3,
        color: [number, number, number, number],
        visible: boolean,
        dimension: number
    }): Marker
```
### Показать маркер для
```typescript
Marker.showFor(UNKNOWN): void
```
### Скрыть маркер для
```typescript
Marker.hideFor(UNKNOWN): void
```
### Получить цвет маркера
```typescript
Marker.getColor(): Array<number> // Массив из 4-х целых чисел [R,G,B,A]
```
### Установить цвет маркера
```typescript
Marker.setColor(r: number, g: number, b: number, a: number): void
```

## Примеры
---
```typescript
// Создаём
const marker = mp.markers.new(29, new mp.Vector3(-431.88, 1146.86, 327), 1.0,
    {
        direction: new mp.Vector3(0, 0, 0),
        rotation: new mp.Vector3(0, 0, 0),
        color: [255, 0, 0, 255],
        visible: true,
        dimension: 0
    });

// Устанавливаем размер
marker.scale = 2.0;

// Уничтожаем
marker.destroy();
```
