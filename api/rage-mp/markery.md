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
