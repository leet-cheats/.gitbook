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

```typescript
mp.Blip.addTextComponentSubstringName
```
### Проверить существование
```typescript
mp.Blip.doesExist
```
### 
```typescript
mp.Blip.endTextCommandSetName
```
### Получить прозрачность
```typescript
mp.Blip.getAlpha
```
### Получить цвет
```typescript
mp.Blip.getColour
```
### Получить позицию
```typescript
mp.Blip.getCoords
```
### 
```typescript
mp.Blip.getFirstInfoId
```
### 
```typescript
mp.Blip.getInfoIdDisplay
```
### 
```typescript
mp.Blip.getInfoIdEntityIndex
```
### 
```typescript
mp.Blip.getInfoIdPickupIndex
```
### 
```typescript
mp.Blip.getInfoIdType
```
###
```typescript
mp.Blip.getHudColour
```
### 
```typescript
mp.Blip.getNextInfoId
```
### Получить спрайт
```typescript
mp.Blip.getSprite
```
### Мигает ли метка
```typescript
mp.Blip.isFlashing
```
### 
```typescript
mp.Blip.isMissionCreator
```
### Видна ли метка на мини-карте
```typescript
mp.Blip.isOnMinimap
```
### Показывается ли лишь вблизи
```typescript
mp.Blip.isShortRange
```
### 
```typescript
mp.Blip.hideNumberOn
```
### 
```typescript
mp.Blip.pulse
```
### Установить прозрачность
```typescript
mp.Blip.setAlpha
```
### Установить дружелюбие
```typescript
mp.Blip.setAsFriendly
```
### 
```typescript
mp.Blip.setAsMissionCreator
```
### Установить показ лишь вблизи
```typescript
mp.Blip.setAsShortRange
```
### 
```typescript
mp.Blip.setBright
```
### Установить категорию
```typescript
mp.Blip.setCategory
```
### Установить цвет
```typescript
mp.Blip.setColour
```
### Установить поизицию
```typescript
mp.Blip.setCoords(position: mp.Vector3): void
```
### 
```typescript
mp.Blip.setDisplay
```
### 
```typescript
mp.Blip.setFade(opacity: number, duration: number): void
```
### Включить мигание
```typescript
mp.Blip.setFlashes(toggle: boolean): void
```
### 
```typescript
mp.Blip.setFlashesAlternate(toggle: boolean): void
```
### 
```typescript
mp.Blip.setFlashInterval
```
### 
```typescript
mp.Blip.setFlashTimer(duration: number): void
```
### 
```typescript
mp.Blip.setHighDetail
```
### 
```typescript
mp.Blip.setNameFromTextFile
```
### 
```typescript
mp.Blip.setNameToPlayerName
```
### Установить порядок в легенде
```typescript
mp.Blip.setPriority(priority: boolean): void
```
### Установить угол направления
```typescript
mp.Blip.setRotation(directionAngle: number): void
```
### Включить показ маршрута
```typescript
mp.Blip.setRoute(enabled: boolean): void
```
### Установить цвет маршрута
```typescript
mp.Blip.setRouteColour(color: number): void
```
### Установить размер
```typescript
mp.Blip.setScale(scale: number): void
```
### Установить вторичный цвет
```typescript
mp.Blip.setSecondaryColour(r: number, g: number, b: number): void
```
### 
```typescript
mp.Blip.setShowCone(toggle: boolean): void
```
### Включить индикатор направления
Индикатор направления используется в GTA:O для игроков отображаемых на мини-карте.
```typescript
mp.Blip.setShowHeadingIndicator(toggle: boolean): void
```
### Установить спрайт
```typescript
mp.Blip.setSprite(spriteId: number): void
```
### 
```typescript
mp.Blip.showNumberOn
```
