---
description: >-
  В видеоиграх «Blip»/«Метка» — это сигнал или точка на радаре или мини-карте,
  указывающая на местоположение игрока, врагов, союзников или других важных
  объектов.
icon: map-location
---

# Метки

### Создать метку

```typescript
mp.blips.new(spriteId: number, position: mp.Vector3,
    {
        name: string, // Название
        scale: number, // Размер на мини-карте
        colorId: number, // Цвет
        alpha: number, // Прозрачность (0 — 255)
        drawDistance: number, // Расстояние отрисовки
        shortRange: boolean, // Метка скрыта, пока игрок не подойдёт близко
        directionAngle: number, // Угол направления на мини-карте
        dimensionId: number, // Измерение
        radius: number // Радиус закругления
    })
```

### Цвета меток

Вы сможете найти эту информацию в официальной документации RAGE:MP — [https://wiki.rage.mp/?title=Blips#Blip\_colors](https://wiki.rage.mp/?title=Blips#Blip\_colors)
