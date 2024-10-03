---
icon: text-size
---

# Надписи
## Свойства
---
### Текст
```typescript
Label.text: string
```
### Цвет
```typescript
Label.color: Array<number>
```
### Тип шрифта
```typescript
Label.font: number
```
### Дальность отрисовки
```typescript
Label.drawDistance: number
```
### Показ через стены
```typescript
Label.los: boolean
```

## Функции
---
### Создать
```typescript
mp.labels.new(text: string, position: Vector3, 
    { 
        lineOfSight: boolean, 
        fontId: number, 
        drawDistance: number, 
        color: [number, number, number, number], 
        dimension: number
    }): Label
```

## Примеры
---
```typescript
// Создаём
const label = mp.labels.new("Welcome to Los Santos", new mp.Vector3(-431.88, 1146.86, 327),
    {
        los: false,
        font: 1,
        drawDistance: 100,
    });

// Устанавливаем показ через стены
label.los = true;

// Уничтожаем
label.destroy();
```
