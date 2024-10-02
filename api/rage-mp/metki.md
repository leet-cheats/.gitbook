---
icon: map-location
description: >-
  В видеоиграх «Blip»/«Метка» — это сигнал или точка на радаре или мини-карте,
  указывающая на местоположение игрока, врагов, союзников или других важных
  объектов.
---

# Метки

### Создать

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

### Проверить существование

```typescript
mp.Blip.doesExist(): boolean
```

### Прозрачность

Прозрачность метки регулируется целым числом в диапазоне от 0 до 255.

<pre class="language-typescript"><code class="lang-typescript"><strong>mp.Blip.getAlpha(): number // Получить
</strong></code></pre>

```typescript
mp.Blip.setAlpha(alpha: number): void // Установить
```

### Позиция

Позиция метки в игровом трёхмерном мире. Координата Z может быть 0.

```typescript
mp.Blip.getCoords(): mp.Vector3 // Получить
```

```typescript
mp.Blip.setCoords(position: mp.Vector3): void // Установить
```

### Цвет

Цвет метки является игровым идентификатором GTA5 из [таблицы цветов](https://wiki.rage.mp/?title=Blips#Blip\_colors).

```typescript
mp.Blip.getColour(): number // Получить
```

```typescript
mp.Blip.setColour(colorId: number): void // Установить
```

### Неизвестно

mp.Blip.addTextComponentSubstringName

### Проверить существование метки

mp.Blip.doesExist

mp.Blip.endTextCommandSetName

mp.Blip.getAlpha mp.Blip.getColour

mp.Blip.getCoords mp.Blip.getFirstInfoId

mp.Blip.getInfoIdDisplay

mp.Blip.getInfoIdEntityIndex

